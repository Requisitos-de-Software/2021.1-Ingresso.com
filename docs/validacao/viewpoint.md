## 1. Versionamento
|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|14/09|Criação do documento|João Pedro e Thiago|

## 2. Introdução
<p style="text-align: justify; text-indent: 20px">Messaoudi, define informalmente a técnica de <i>viewpoint</i> como a análise dos "diferentes diferentes pontos de vista de um domínio que pode ser observado" [1]. Ou seja, a metologia se baseia na ideia de que os diversos requisitos podem ser elicitados de diferentes pontos de vista, onde a validação das diferenças pode ser utilizada como uma forma de validação inicial dos requisitos.</p>

## 3. Metodologia
<p style="text-align: justify; text-indent: 20px">A metologia para a execução dessa validação, utilizando a ideia de <i>viewpoints</i>, foi proposta por Julio Cesar Sampaio do Prado Leite e Peter A. Freeman [2], e estará validando apenas o domínio dos artefatos produzido pela equipe. Dentro da abordagem proposta, apenas 1 <i>viewpoint</i> dentre os 3 possíveis será utilizado, sendo ele o de processo, onde a perspectiva A mostrará o ponto de vista da equipe em relação ao universo do discurso, enquanto a perspectiva B envolverá a visão de um usuário que participou na <a href=../../elicitacao/analiseProtocolo#4-verbalizacao-do-usuario>Análise de Protocolo</a>.</p>

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
de um cadastro.”
``` 

## 4. Perspectivas
### 4.1 <i>Viewpoint</i> A

### 4.2 <i>Viewpoint</i> B

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
