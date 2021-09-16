## 1. Versionamento
|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|14/09|Criação do documento|João Pedro e Thiago|
|1.1|16/09|Adição dos viewpoint|João Pedro e Thiago|

## 2. Introdução
<p style="text-align: justify; text-indent: 20px">Messaoudi define informalmente a técnica de <i>viewpoint</i> como a análise dos "diferentes pontos de vista de um domínio que pode ser observado" [1]. Ou seja, a metologia se baseia na ideia de que os diversos requisitos podem ser elicitados de diferentes pontos de vista, onde a validação das diferenças pode ser utilizada como uma forma de validação inicial dos requisitos.</p>

## 3. Metodologia
<p style="text-align: justify; text-indent: 20px">A metologia para a execução dessa validação, utilizando a ideia de <i>viewpoints</i>, foi proposta por Julio Cesar Sampaio do Prado Leite e Peter A. Freeman [2], e estará validando apenas o domínio dos artefatos produzido pela equipe. Dentro da abordagem proposta, apenas 2 <i>viewpoint</i> dentre os 3 possíveis será utilizado, sendo ele o de processo, onde a perspectiva A mostrará o ponto de vista da equipe em relação ao universo do discurso, enquanto a perspectiva B envolverá a visão de um usuário que participou na <a href="../../elicitacao/analiseProtocolo#4-verbalizacao-do-usuario">Análise de Protocolo</a>.</p>

### 3.1 Universo do discurso
<p style="text-align: justify; text-indent: 20px">Para entender melhor os requisitos, foi definido um universo do discurso que guiou as produções dos <i>viewpoints</i>. Esse universo se encontra a seguir: </p>
```
“Comprar um ingresso. Essa compra é restrita ao usuário. Existem três tipos 
de usuários; São eles o Cliente, o próprio Ingresso.com e o Cinema. As seguintes
restrições devem ser atendidas: 1) Todos ingressos selecionados devem estar
disponíveis para compra; 2) Nenhum ingresso pode estar disponível para compra e
ocupado ao mesmo tempo; 3) O tipo do ingresso selecionado deve estar contido
entre as classes disponíveis; 4) O método de pagamento selecionado deve estar
contido entre os tipos possíveis. 5) O usuário pode comprar sem a necessidade
de um cadastro."
``` 

## 4. Perspectivas
### 4.1 <i>Viewpoint</i> A

<pre style="overflow-x:scroll;">
Perspectiva do processo:    
    (((<a href="../../modelagem/lexicos#usuario">usuario</a> =usuario-id =cpf =email)    
    (<a href="../../modelagem/lexicos#ingresso">ingresso</a> =ingresso-id =preço =assento =tipo =forma-de-pagamento =quantidade)    
    (<a href="../../modelagem/lexicos#filme">filme</a> =filme-id =nome =indicação =duração =avaliação =cinema-id)    
    (<a href="../../modelagem/lexicos#sessao">sessão</a> =sessão-id =horário =dia =sala =tipo =filme-id)    
    (<a href="../../modelagem/lexicos#cinema">cinema</a> =cinema-id =nome =localização =filmes-disponíveis)    
    (<a href="../../modelagem/lexicos#assento">assento</a> =assento-id =localização =quantidade =sessão-id)    
    (checa-assento-disponível =assento-id =assento-disponível)    
    (<a href="../../modelagem/lexicos#acompanhamento">acompanhamento</a> =acompanhamento-id =alimentos =preço)    
    (<a href="../../modelagem/lexicos#carrinho">compra</a> =compra-id =quantidade-ingressos =preço =assento-id =acompanhamento-id))    
    (($delete-from wm (<a href="../../modelagem/lexicos#assento-disponivel">assento-disponível</a> =assento-id =cinema-id =filme-id =sessão-id))    
    ($add-to wm (<a href="../../modelagem/lexicos#assento-indisponivel">assento-indisponível</a> =assento-id =cinema-id =filme-id =sessão-id))))    
</pre>
<pre style="overflow-x:scroll;">
Hierarquia:
    (é-um 
        (agente (usuário cinema ingresso.com))    
	    (objeto (ingresso filme assento acompanhamento)))    
    (parte-de 
        (objeto (sessão sessão-id horário dia sala tipo filme-id)    
            (filme filme-id nome indicação duração avaliação cinema-id))    
        (objeto (filme filme-id nome indicação duração avaliação cinema-id)    
	        (cinema cinema-id nome localização filmes-disponíveis))    
        (objeto (acompanhamento acompanhamento-id alimentos preço)    
	        (sessão sessão-id horário dia sala tipo filme-id))    
        (objeto (assento assento-id localização quantidade sessão-id)    
	        (sessão sessão-id horário dia sala tipo filme-id))    
        (objeto (compra compra-id quantidade-ingressos preço assento-id acompanhamento-id)    
            (usuario usuario-id cpf)))    
</pre>

### 4.2 <i>Viewpoint</i> B

<pre style="overflow-x:scroll;">
Perspectiva do autor:
    (((usuário =usuario-id =cpf =email)
    (filme =filme-id =titulo =imagem)
    (cinema =cinema-id =nome =localização =filme-id)
    (sessão =sessão-id =sala =horário =data =tipo =filme-id)
    (assento =assento-id =posição =sessão-id)
    (checa-assento-disponível =assento-id =assento-disponível)
    (ingresso =ingresso-id =tipo =quantidade =preço =assento)
    (checa-tipo-ingresso =ingresso-id =tipos)
    (acompanhamento =acompanhamento-id =preço =quantidade =taxa)
    (compra =usuario-id =cinema-id =sessão-id =assento-id =ingresso-id =acompanhamento-id =total =forma-pagamento =desconto))
    (($delete-from wm (assento-disponível =assento-id =sessão-id =cinema-id =filme-id))) )
</pre>
<pre style="overflow-x:scroll;">
Hierarquia:
    (é-um 
        (agente (usuário cinema Ingresso.com)
        (objeto (filme sessão assento checar-assento-disponível ingresso checar-tipo-ingresso acompanhamento compra)))

    (parte de 
        (agente (usuário usuário-id cpf email senha)
            (cinema cinema-id nome localidade))
	    (objeto (filme filme-id titulo imagem) 
            (cinema-id))
	    (objeto (sessão sessão-id sala horário data tipo)
            (filme-id cinema-id))
        (objeto (assento assento-id posição) 
            (sessão-id cinema-id filme-id checar-assento-disponível))
	    (objeto (ingresso ingresso-id tipo quantidade preço assento)
            (cinema-id checar-tipo-ingresso))
	    (objeto (acompanhamento acompanhamento-id preço quantidade taxa)
            (cinema-id))
        (objeto (compra usuario-id cinema-id sessão-id assento-id ingresso-id acompanhamento-id total forma-pagamento desconto)
            (usuario-id cinema-id sessão-id assento-id ingresso-id acompanhamento-id)))
</pre>

## 5. Identificação e Classificação
<p style="text-align: justify; text-indent: 20px">Após a realização e definição das perspectivas A e B, foi realizada a comparação entre ambos e as inconsistências e discrepâncias estão listadas abaixo.</p>

### 5.1 Inconsistências
- <b>Fatos em A</b></br>Não há inconsistências em A.
- <b>Fatos em B</b></br>Não há inconsistências em B.

### 5.2 Fatos Faltantes
- <b>Fatos em A</b></br>- Checa-tipo-ingresso (Objeto).</br>- Atributo taxa de acompanhamento.
- <b>Fatos em B</b></br>- Assento-indisponível (Ação).</br>- Atributos avaliação, indicação e duração do filme.

### 5.3 Fatos Errados
- <b>Fatos em A</b></br>Não há inconsistências em A.
- <b>Fatos em B</b></br>Não há inconsistências em B.

### 5.4 Avaliação
- <b>Solução alternativa para A</b></br>Adicionar o atributo de taxa ao acompanhamento.
- <b>Solução alternativa para B</b></br>Adicionar objeto assento-indisponível, atributos de avaliação, indicação e duração ao filme e correção do objeto checa-tipo-ingresso.

## 6. Integração
<p style="text-align: justify; text-indent: 20px">Feita a identificação dos fatos inconsistentes, faltantes e errados, bem como, a avaliação indicando possíveis soluções alternativas para ambos <i>viewpoints</i>, propõe-se uma solução conciliada baseada em ambos pontos de vista, de forma que os fatos faltantes e errados em um sejam corrigidos no outro.</p>

## 7. Referências
<p style="text-align: justify; text-indent: 20px">[1] Messaoudi M. <b>Requirements Engineering Through Viewpoints</b>. Faculty of Sciences, Imam University, Riyadh, Saudi Arabia. 2013.
<p style="text-align: justify; text-indent: 20px">[2] Leite, J. C. S. P.; Freeman, P. A. <b>Requirements Validation Through Viewpoint Resolution</b>. IEEE TRANSACTIONS ON SOFTWARE ENGINEERING. vol. 17, no. 12, dezembro 1991. </p>
