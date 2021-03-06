## 1. Versionamento

|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|20/08|Abertura do documento de MoSCoW|Victor Lima e Vitor Lamego|
|1.1|20/08|Adição da Priorização e Legenda|Victor Lima e Vitor Lamego|
|1.2|20/08|Adição da Introdução|Victor Lima|
|1.3|01/10|Linkagem dos léxicos|João Pedro|

## 2. Introdução
<p style="text-align: justify; text-indent: 20px">MoSCoW é um técnica de priorização de requisitos que serve para definir quais são os requisitos elicitados mais importantes para serem tratados de forma mais urgente. Eles são divididos em grupos de acordo com o anagrama, M significa "must" que seriam os requisitos que o sistema deve ter obrigatoriamente, S significa "should" que são os requisitos que são importantes mas não são vitais para o projeto, C significa "could" que são os requisitos desejáveis mas não são necessários para a entrega e satisfação do cliente e o W significa "would" que são os requisitos menos críticos que não serão feitos pois terão baixo retorno no produto final, ou podem apenas serem deixados para o final do projeto. Temos na seção seguinte a priorização MoSCoW que fizemos relativas ao aplicativo <a href="../../modelagem/lexicos/#ingresso">Ingresso</a>.</p>


## 3. Priorização:

|ID|Descrição|Tipo de Requisito|Priorização| 
|:--:|:--:|:-----:|: -----:| 
|AP01| O aplicativo deve permitir selecionar a [região](../../modelagem/lexicos/#local) desejada | RF | <b>MUST</b> | 
|AP02| O [usuário](../../modelagem/lexicos/#usuario) deve conseguir ver os [filmes em cartaz](../../modelagem/lexicos/#filme-em-cartaz) na [região](../../modelagem/lexicos/#local) desejada | RF | <b>MUST</b> | 
|AP03| O [usuário](../../modelagem/lexicos/#usuario) deve conseguir pesquisar os [filmes em cartaz](../../modelagem/lexicos/#filme-em-cartaz) na [região](../../modelagem/lexicos/#local) desejada | RF | <b>SHOULD</b> | 
|AP04| O [usuário](../../modelagem/lexicos/#usuario) deve conseguir ver os [cinemas](../../modelagem/lexicos/#cinema) na [região](../../modelagem/lexicos/#local) desejada | RF | <b>MUST</b> | 
|AP05| O [usuário](../../modelagem/lexicos/#usuario) deve conseguir pesquisar os [cinemas](../../modelagem/lexicos/#cinema) na [região](../../modelagem/lexicos/#local) desejada | RF |<b>SHOULD</b>  | 
|AP06| O aplicativo deve recomendar os [filmes em alta (destaques)](../../modelagem/lexicos/#filme-em-alta) | RF |<b>COULD</b>  | 
|AP07| O aplicativo deve recomendar [notícias](../../modelagem/lexicos/#noticia) em alta (destaques) | RF |<b>COULD</b>  | 
|AP08| O aplicativo deve exibir as prevenções adotadas pelos [cinemas](../../modelagem/lexicos/#cinema) referentes a pandemia do covid-19 | RF | <b>MUST</b> | 
|AP09| O aplicativo deve deixar claro o que cada medida de prevenção significa | RF | <b>SHOULD</b> | 
|AP10| O [usuário](../../modelagem/lexicos/#usuario) deve se cadastrar utilizando redes sociais ou não | RF | <b>MUST</b> 
|AP11| O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher o(s) seu(s) [assento(s)](../../modelagem/lexicos/#assento)| RF | <b>MUST</b> | 
|AP12| O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher qual tipo de [ingresso](../../modelagem/lexicos/#ingresso) vai querer | RF |<b>MUST</b>  | 
|AP13| O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher o [alimento(combo)](../../modelagem/lexicos/#acompanhamento) que irá consumir na [sessão](../../modelagem/lexicos/#sessao) | RF |<b>SHOULD</b>  | 
|AP14| O [usuário](../../modelagem/lexicos/#usuario) deve conseguir efetuar o pagamento de diferentes formas | RF |<b>MUST</b>  | 
|AP15| O aplicativo deve identificar o [usuário](../../modelagem/lexicos/#usuario) no pagamento | RF |<b>MUST</b>  | 
|E01| O [usuário](../../modelagem/lexicos/#usuario) deve ser capaz de comprar tickets para o [filme](../../modelagem/lexicos/#filme) | RF |<b>MUST</b>  | 
|E03| O [usuário](../../modelagem/lexicos/#usuario) deve ser capaz de ver os horários dos [filmes](../../modelagem/lexicos/#filme) | RF |<b>MUST</b> | 
|I02| Apresentar os [filmes](../../modelagem/lexicos/#filme) que serão lançados | RF |<b>SHOULD</b> | 
|I04| Pesquisar um [filme](../../modelagem/lexicos/#filme) | RF |<b>COULD</b>  |
|I05| Ter uma área para [notícias](../../modelagem/lexicos/#noticia) | RF|<b>COULD</b>| 
|I10| Apresentar informações sobre o [filme](../../modelagem/lexicos/#filme) | RF |<b>SHOULD</b>  | 
|I12| Os [cinemas](../../modelagem/lexicos/#cinema) devem apresentar os horários das [sessões](../../modelagem/lexicos/#sessao) do [filme](../../modelagem/lexicos/#filme) nos próximos dois dias | RF |<b>MUST</b>| 
|I13| Ter como seguir o [filme](../../modelagem/lexicos/#filme) para acompanhar [notícias](../../modelagem/lexicos/#noticia) e lançamentos | RF |<b>COULD</b>| 
|I14| Recomendar outros [filmes](../../modelagem/lexicos/#filme) | RF |<b>COULD</b> | 
|I15| Compartilhar o [filme](../../modelagem/lexicos/#filme) | RF |<b>WOULD</b>  | 
|I16| Apresentar as informações do [cinema](../../modelagem/lexicos/#cinema) | RF |<b>COULD</b>  | 
|I17| Apresentar as [sessões](../../modelagem/lexicos/#sessao) com os horários e dias com vagas | RF |<b>MUST</b>  | 
|I18| Apresentar informações da [sessão](../../modelagem/lexicos/#sessao) | RF |<b>MUST</b>  | 
|I19| Mostrar os [assentos](../../modelagem/lexicos/#assento) disponíveis | RF |<b>MUST</b>  
|I20| Apresentar os tipos de [ingressos](../../modelagem/lexicos/#ingresso) | RF |<b>MUST</b>  | 
|I21| Oferecer [acompanhamentos](../../modelagem/lexicos/#acompanhamento) | RF |<b>SHOULD</b>  | 
|I22| Comprar com uma conta criada no domínio | RF |<b>MUST</b>  | 
|I23| Comprar com uma conta do Google ou Facebook | RF |<b>COULD</b>  | 
|I24| Comprar sem o cadastro | RF |<b>MUST</b>  | 
|I25| Mostrar um resumo da compra | RF |<b>MUST</b>  |
|I26| Mostrar o total e informações do pagamento | RF |<b>MUST</b>   |
|I29| O resumo do pedido deve ser enviado por e-mail | RF | <b>MUST</b>  | 
|I30| Ter uma área para os pedidos | RF |<b>SHOULD</b>  |
|I31| Notificar a confirmação do pagamento | RF |<b>MUST</b>   |
|I32| Apresentar informações do [ingresso](../../modelagem/lexicos/#ingresso) | RF |<b>MUST</b>  | 
|I33| Enviar o [ingresso](../../modelagem/lexicos/#ingresso) por e-mail | RF |<b>MUST</b>  | 
|I34| Notificar quando a [sessão](../../modelagem/lexicos/#sessao) tiver chegando | RF |<b>WOULD</b>  | 
|OP03| O [usuário](../../modelagem/lexicos/#usuario) deve poder visualizar senha digitada | RF |<b>SHOULD</b>  | 
|OP04| O [usuário](../../modelagem/lexicos/#usuario) deve poder recuperar senha | RF |<b>MUST</b>  | 
|OP05| O sistema deve enviar um email de recuperação de senha | RF |<b>MUST</b>  | 
|OP06| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver seus dados pessoais | RF |<b>MUST</b>  | 
|OP07| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver seus Pedidos | RF |<b>SHOULD</b>  
|OP08| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver seus Cartões Salvos| RF |<b>MUST</b>  | 
|OP09| O [usuário](../../modelagem/lexicos/#usuario) deve poder sair da conta logada | RF |<b>MUST</b>  | 
|OP12| O [usuário](../../modelagem/lexicos/#usuario) deve poder enviar uma solicitação de atendimento | RF |<b>MUST</b>  | 
|OP19| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [filmes](../../modelagem/lexicos/#filme) que vão estar nos [cinemas](../../modelagem/lexicos/#cinema) em breve | RF |<b>SHOULD</b>  | 
|OP20| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver título, categoria, classificação indicativa, avaliação, duração, elenco, sinopse, direção, distribuidor e país de origem do [filme](../../modelagem/lexicos/#filme) selecionado | RF |<b>MUST</b>  | 
|OP22| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver as [sessões](../../modelagem/lexicos/#sessao) do [filme](../../modelagem/lexicos/#filme) selecionado por dia da semana | RF |<b>SHOULD</b>  | 
|OP23| O [usuário](../../modelagem/lexicos/#usuario) deve poder filtrar [sessões](../../modelagem/lexicos/#sessao) do [filme](../../modelagem/lexicos/#filme) selecionado por Tipos de Exibição | RF |<b>SHOULD</b>  | 
|OP24| O [usuário](../../modelagem/lexicos/#usuario) deve poder limpar filtros selecionados | RF |<b>SHOULD</b>  | 
|OP26| O [usuário](../../modelagem/lexicos/#usuario) deve poder assistir trailer do [filme](../../modelagem/lexicos/#filme) | RF |<b>COULD</b>  | 
|OP27| O [usuário](../../modelagem/lexicos/#usuario) deve poder ordenar [cinemas](../../modelagem/lexicos/#cinema) por nome ou proximidade | RF |<b>COULD</b>  | 
|OP28| O [usuário](../../modelagem/lexicos/#usuario) deve poder favoritar [cinemas](../../modelagem/lexicos/#cinema) | RF |<b>WOULD</b>  
|OP29| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver nome, logo e endereço do [cinema](../../modelagem/lexicos/#cinema) | RF |<b>MUST</b>  | 
|OP36| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver a Legenda da Escolha de [Assentos](../../modelagem/lexicos/#assento) | RF |<b>MUST</b>  | 
|OP37| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver os números dos [assentos](../../modelagem/lexicos/#assento) | RF |<b>MUST</b>  | 
|OP42| O [usuário](../../modelagem/lexicos/#usuario) deve poder aplicar código de desconto no pagamento | RF |<b>COULD</b>  | 
|OP43| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [Carrinho](../../modelagem/lexicos/#carrinho) com as [sessões](../../modelagem/lexicos/#sessao) selecionadas | RF |<b>MUST</b>  | 
|OP45| O [usuário](../../modelagem/lexicos/#usuario) deve poder remover [sessões](../../modelagem/lexicos/#sessao) do [Carrinho](../../modelagem/lexicos/#carrinho) | RF |<b>MUST</b>  |
|OP47| O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [cinemas](../../modelagem/lexicos/#cinema) favoritados | RF |<b>WOULD</b>  | 
|BS10| O [usuário](../../modelagem/lexicos/#usuario) deve poder comprar os [acompanhamentos](../../modelagem/lexicos/#acompanhamento) junto dos [ingressos](../../modelagem/lexicos/#ingresso) | RF |<b>COULD</b>  | 
|BS11| O aplicativo deve permitir o cancelamento/reembolso da compra | RF |<b>MUST</b>  | 
|BS12| O aplicativo deve informar o histórico de compra dos [usuários](../../modelagem/lexicos/#usuario) logados | RF| <b>SHOULD</b>  | 
|BS16| O aplicativo deve fornecer informações sobre eventos próximos a [região](../../modelagem/lexicos/#local) escolhida | RF |<b>WOULD</b>  | 
|AP16| O [usuário](../../modelagem/lexicos/#usuario) deve poder navegar pelo aplicativo sem precisar de um cadastro| RNF |<b>MUST</b>  | 
|AP18| O aplicativo deve ser de fácil instalação | RNF |<b>MUST</b>  | 
|AP19| O aplicativo deve ser seguro por lidar com dados sensíveis | RNF |<b>MUST</b>  | 
|AP20| O aplicativo deve ser monetizado através de publicidade | RNF |<b>SHOULD</b>  | 
|E05| O aplicativo deve oferecer comodidade ao [usuário](../../modelagem/lexicos/#usuario) | RNF |<b>SHOULD</b>  | 
|E06| O pagamento de [ingressos](../../modelagem/lexicos/#ingresso) deve ser fácil | RNF |<b>MUST</b>  | 
|E07| O pagamento de [ingresso](../../modelagem/lexicos/#ingresso) deve ser rápido | RNF |<b>MUST</b>  | 
|E09| A seleção de [cadeiras](../../modelagem/lexicos/#assento) deve prover uma forma de visualização eficiente, para se entender onde a [cadeira](../../modelagem/lexicos/#assento) se localiza no [cinema](../../modelagem/lexicos/#cinema) | RNF |<b>MUST</b>  | 
|E10| A plataforma deve ser rápida| RNF |<b>SHOULD</b>  | 
|I09| Não há necessidade de autenticação para navegar entre os [filmes](../../modelagem/lexicos/#filme) e [notícias](../../modelagem/lexicos/#noticia)| RNF |<b>MUST</b> | 
|ST01| O aplicativo deve ser fácil de ser utilizado | RNF |<b>SHOULD</b>  | 
|ST03| O aplicativo deve estar sempre com os horários das [sessões](../../modelagem/lexicos/#sessao) atualizados | RNF |<b>MUST</b>  | 
|ST05| O aplicativo deve estar sempre com as [notícias](../../modelagem/lexicos/#noticia) atualizadas | RNF |<b>MUST</b>  | 
|ST07| A lista de [filmes](../../modelagem/lexicos/#filme) e [notícias](../../modelagem/lexicos/#noticia) devem ser claras e legíveis | RNF |<b>MUST</b>  | 
|ST10| O aplicativo deve prover conforto e menos tempos em filas para compra de [ingressos](../../modelagem/lexicos/#ingresso) | RNF |<b>MUST</b>  | 
|BS19| O aplicativo deve funcionar em todas as plataformas virtuais | RNF |<b>MUST</b>  | 
|BS20| O aplicativo deve funcionar em dispositivos de tamanhos diferentes | RNF |<b>SHOULD</b>  | 
|BS21| O sistema e o evento deve ter uma interface de comunicação prática | RNF |<b>SHOULD</b>  | 

<h6 align="center">Tabela 1: Requisitos priorizados utilizando MoSCoW</h6>
<h6 align="center">Fonte: Autores</h6>

### 3.1 Legenda
<center>

|Legenda|Significado| 
|:--:|:--:|
|RF|Requisito Funcional|
|RNF|Requisito Não Funcional|
|AP|Avaliação Participativa|
|E|Entrevista|
|I|Introspecção|
|OP|Observação Participativa|
|BS|Brainstorming|
|ST|Storytelling|

</center>

<h6 align="center">Tabela 2: Legenda referente à Tabela 1</h6>
<h6 align="center">Fonte: Autores</h6>


## 4. Conclusões

<p style="text-align: justify; text-indent: 20px">Após feita a priorização, os resultados obtidos referente à quantidade de requisitos em cada nível de prioridade foi:</p>

<center>

|Prioridade|Quantidade| 
|:--:|:--:|
|MUST|49|
|SHOULD|21|
|COULD|12|
|WOULD|5|


</center>


## 5. Referências
<p style="text-align: justify;">[1] <b>Aprenda como o método MoSCoW poderá ajudá-lo a priorizar tarefas da sua empresa</b>. Disponível em: <a href="https://www.voitto.com.br/blog/artigo/metodo-moscow" target="_blanck">https://www.voitto.com.br/blog/artigo/metodo-moscow</a>. Acesso em: 20 de ago. de 2021.</p>
