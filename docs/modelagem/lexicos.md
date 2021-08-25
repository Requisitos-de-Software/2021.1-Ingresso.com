
## 1. Versionamento

| Versão | Data  | Descrição                               | Autor(es)                        |
| ------ | ----- | :---------------------------------------: | :--------------------------------: |
| 1.0    | 24/08 | Abertura do documento | Rafael e Thiago|
| 1.1    | 24/08 | Adição dos léxicos | Rafael e Thiago|

<hr>

## 2. Introdução

<p style="text-align: justify; text-indent: 20px">O Léxico é uma técnica de modelagem que permite a descrição dos símbolos de uma linguagem, ele funciona como um dicionário que auxilia na identificação de palavras ou frases peculiares relativas ao meio social da aplicação que está sob estudo [1].</p>

<p style="text-align: justify; text-indent: 20px">Os símbolos da linguagem são descritos com noção e impacto, onde noção traz a tona o significado do símbolo (denotação) e impacto, como o nome já diz, descreve o efeito do símbolo na aplicação ou o efeito de algo na aplicação sobre o símbolo. É importante estar atento a algumas regras gerais, por exemplo, um símbolo pode ter ou não sinônimos, e um símbolo pode ter uma ou mais noções, bem como um ou mais impactos [1].</p>

<hr>

## 3. Metodologia
<p style="text-align: justify;">Para representar os léxicos, foram definidas tabelas contendo o seguinte formato:</p>

|LCXX|**Nome do léxico**|
|:----:|:--------------------:|
|**Sinônimos**|Sinônimos do léxico|
|**Noção**|Explicação ou noção do léxico|
|**Impacto**|Ocorrência ou impacto do léxico na aplicação|

|Legenda||
|:----:|:--------------------:|
|**L**|Léxico|
|**C**|Classificação (estado, verbo ou objeto)|
|**XX**|Numeração|

<hr>

## 4. Léxicos

### 4.1 Objetos

|LO01|**Usuário**|
|---|------------------|
|**Sinônimos**|Cliente|
|**Noção**|A pessoa interessada em comprar ingresso para algum evento|
|**Impacto**|O usuário pode comprar ingresso, escolher assento, pesquisar um evento e visualizar prevenções|

|LO02|**Filme**|
|---|------------------|
|**Sinônimos**|Evento, Espetáculo|
|**Noção**|Filmes para o usuário ver |
|**Impacto**|O usuário escolhe um filme desejado<br>O usuário visualiza os locais e horários em que o filme vai passar|

|LO03|**Acompanhamento**|
|---|------------------|
|**Sinônimos**|Bebida, comida e pipoca|
|**Noção**|Conjunto de comidas e bebidas que acompanham o usuário durante a sessão|
|**Impacto**|O usuário pode comprar acompanhamentos<br>O usuário retira o acompanhamento no evento|

|LO04|**Ingresso**|
|---|------------------|
|**Sinônimos**|Bilhete, Entrada, Convite|
|**Noção**|Um ingresso representa a entrada para uma sessão de filme em determinado cinema|
|**Impacto**|Um ingresso é utilizado para assistir um filme|

|LO05|**Cinema**|
|---|------------------|
|**Sinônimos**|Estabelecimento|
|**Noção**|Local onde é possível assistir um filme desejado|
|**Impacto**|Os filmes que estão em cartaz só podem ser transmitidos em algum cinema|

|LO06|**Assento**|
|---|------------------|
|<b>Sinônimos</b>|Poltrona|
|**Noção**|A cadeira que o usuário irá sentar durante o evento|
|**Impacto**|O usuário pode escolher o assento|

|LO07|**Sessão**|
|---|------------------|
|**Sinônimos**|Horário|
|**Noção**|Sessão refere-se a um determinado cinema e horário onde vai passar o filme|
|**Impacto**|Um ingresso só pode ser comprado quando referido a uma sessão|

|LO08|**Carrinho**|
|---|------------------|
|**Sinônimos**|Carrinho de compras|
|**Noção**|Conjunto de ingressos e acompanhamentos que o usuário pretende comprar|
|**Impacto**|O usuário pode comprar vários itens|

|LO09|**Notícia**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|Uma notícia sobre algum filme, evento ou anúncio|
|**Impacto**|O usuário pode visualizar as notícias e compartilhá-la|

|LO10|**Local**|
|---|------------------|
|**Sinônimos**|Localidade|
|**Noção**|Localização do cinema|
|**Impacto**|O usuário pode pesquisar os cinemas pela localidade|

|LO11|**Classificação etária**|
|---|------------------|
|**Sinônimos**|Classificação indicativa|
|**Noção**|Idade mínima recomendada para assistir o filme|
|**Impacto**|O usuário pode filtrar os filmes que a classificação etária atende a sua idade|

|LO12|**Gênero**|
|---|------------------|
|**Sinônimos**|Classificação|
|**Noção**|Conjunto de filmes com a mesma origem ou tema relacionados|
|**Impacto**|O usuário pode filtrar por gênero do filme|

|LO13|**Avaliação**|
|---|------------------|
|**Sinônimos**|Avaliação de usuários|
|**Noção**|Feedback dos usuários sobre um filme|
|**Impacto**|O usuário pode visualizar avaliações de um filme|

<hr>

### 4.2 Verbos

|LV01|**Comprar Ingresso**|
|---|------------------|
|**Sinônimos**|Adquirir/Obter ingresso|
|**Noção**|O usuário irá, através do pagamento, obter um ingresso para uma sessão|
|**Impacto**|O usuário receberá o ingresso para o filme comprado|

|LV02|**Escolher Assento**|
|---|------------------|
|**Sinônimos**|Selecionar assento|
|**Noção**|O usuário tem a opção de escolher um ou mais assentos para determinada sessão|
|**Impacto**|Os assentos foram escolhidos<br>Assentos próximos são bloqueados por medidas de segurança|

|LV03|**Cadastrar usuário**|
|---|------------------|
|**Sinônimos**|Registrar usuário|
|**Noção**|O usuário poderá se cadastrar no app e receber alguns benefícios|
|**Impacto**|O usuário cadastrado tem direito a algumas funcionalidades a mais|

|LV04|**Logar no sistema**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O usuário já cadastrado poderá logar no sistema|
|**Impacto**|Após logado, o usuário poderá ter acesso às informações sobre sua conta, bem como os benefícios de um usuário cadastrado|

|LV05|**Pesquisar**|
|---|------------------|
|**Sinônimos**|Buscar, Encontrar, Filtrar|
|**Noção**|O usuário pode pesquisar sobre um filme ou cinema|
|**Impacto**|Após pesquisado, o usuário pode acessar informações específicas sobre os filmes ou cinemas encontrados|

|LV06|**Visualizar prevenções**|
|---|------------------|
|**Sinônimos**|Ler prevenções|
|**Noção**|O usuário pode visualizar as prevenções referentes ao cinema determinado|
|**Impacto**|O usuário tem acesso as prevenções referentes a cinemas próximos<br>Sabendo as prevenções ele pode se preparar para evitar imprevistos|

|LV07|**Visualizar avaliação**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O usuário pode ver as avaliações feitas pelos usuários do Rotten Tomatoes|
|**Impacto**|O usuário pode perder ou ganhar interesse a partir das avaliações|

|LV08|**Visualizar filme**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O usuário pode ver as informações sobre o filme|
|**Impacto**|O usuário pode perder ou ganhar interesse a partir das informações<br>O usuário pode comprar ingressos para o filme|

|LV09|**Visualizar notícia**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O usuário pode ler as notícias|
|**Impacto**|O usuário pode se interessar por um filme|

|LV10|**Compartilhar filme**|
|---|------------------|
|**Sinônimos**|Compartilhar notícia|
|**Noção**|O usuário pode compartilhar um filme ou uma notícia com alguém|
|**Impacto**|O usuário compartilha a página do filme, ou notícia, por uma rede social|

<hr>

### 4.3 Estados

|LE01|**Ingresso está no carrinho**|
|---|------------------|
|**Sinônimos**|Ingresso está sendo comprado|
|**Noção**|O usuário pretende comprar um ingresso, então esse ingresso é salvo no carrinho para ele poder tanto fazer o pagamento quanto realizar modificações|
|**Impacto**|O usuário pode comprar os itens do carrinho<br>Se o usuário não se interessar mais pelo ingresso, ele pode retirá-lo do carrinho|

|LE02|**Filme está em cartaz**|
|---|------------------|
|**Sinônimos**|Filme disponível para venda|
|**Noção**|O filme estando em cartaz significa que ele está disponível para ser assistido em determinados cinemas possuindo uma ou várias sessões|
|**Impacto**|O usuário pode decidir assistir o filme em cartaz comprando um ingresso para determinada sessão<br>Quando não há mais cinemas transmitindo esse filme, ele fica fora de cartaz<br>Quando não houver mais ingressos a venda, o filme está egotado|

|LE03|**Filme fora de cartaz**|
|---|------------------|
|**Sinônimos**|Filme não disponível|
|**Noção**|Um filme que não tem mais sessões disponíveis|
|**Impacto**|O usuário não pode comprar ingressos para esse filme<br>Quando houver sessões, o filme entra em cartaz|

|LE04|**Filme está para ser lançado**|
|---|------------------|
|**Sinônimos**|Filme chegará em breve|
|**Noção**|Um filme que está para ser lançado significa que ele estará disponível para ser assistido em breve|
|**Impacto**|O usuário pode ver mais detalhes sobre o filme que está para ser lançado (trailer, descrição)<br>Quando o filme for lançado, ele sairá dos filmes em breve|

|LE05|**Filme está em lançamento**|
|---|------------------|
|**Sinônimos**|Filme recém-lançado|
|**Noção**|Um filme que está em lançamento significa que está disponível para ser assistido há pouco tempo|
|**Impacto**|O usuário pode comprar ingresso para o filme<br>Quando passa algumas semanas depois que o filme foi lançado, ele se torna um filme em cartaz|

|LE06|**Filme está em alta**|
|---|------------------|
|**Sinônimos**|Filmes populares|
|**Noção**|Um filme em alta é um filme popular, que é de interesse de várias pessoas|
|**Impacto**|O usuário pode decidir assistir o filme em alta comprando um ingresso para determinada sessão. Quando o filme não está mais em alta e a quantidade de sessões diminuiu, ele se torna apenas um filme em cartaz|

|LE07|**Filme esgotado**|
|---|------------------|
|**Sinônimos**|Ingressos esgotados|
|**Noção**|Um filme que está em cartaz, mas não tem ingressos disponíveis para a venda|
|**Impacto**|O usuário não pode comprar ingressos para esse filme<br>Quando houver sessões com ingressos disponíveis, então ele se torna um filme em cartaz|

|LE08|**Assento disponível**|
|---|------------------|
|**Sinônimos**|Assento livre|
|**Noção**|Um assento que pode ser selecionado pelo usuário para uma determinada sessão|
|**Impacto**|O usuário pode escolher um assento disponível<br>Quando alguém já escolheu esse assento, ele não está mais disponível|

|LE09|**Assento indisponível**|
|---|------------------|
|**Sinônimos**|Assento ocupado|
|**Noção**|Um assento que ter sido selecionado por outro usuário ou está bloqueado devido a medidas de prevenção contra o COVID|
|**Impacto**|O usuário não pode escolher um assento indisponível<br>Quando o usuário desiste da compra do ingresso, o assento desse usuário se torna disponível|

|LE10|**Assento está selecionado**|
|---|------------------|
|**Sinônimos**|Assento está escolhido|
|**Noção**|Um ou mais assentos foram selecionados pelo usuário para determinada sessão|
|**Impacto**|O usuário visualiza os assentos disponíveis para a sessão<br>O usuário escolhe um assento disponível<br>Os assentos ao redor são bloqueados por motivos de prevenção|

|LE11|**Cinema está favoritado**|
|---|------------------|
|**Sinônimos**|Cinema está como preferido, predileto|
|**Noção**|Um usuário logado pode favoritar um cinema, facilitando o futuro acesso a esses cinemas por uma aba especial "Favoritos"|
|**Impacto**|O usuário clica no símbolo de coração e favorita o cinema<br>O cinema favoritado aparece em “Favoritos”<br>Caso o usuário clique no coração novamente, este cinema deixa de ser favorito.|

|LE12|**Cinema aberto**|
|---|------------------|
|**Sinônimos**|Cinema em funcionamento|
|**Noção**|Um cinema que tem sessões disponíveis para filmes|
|**Impacto**|O usuário pode visualizar os filmes e sessões disponíveis<br>Quando não há sessões disponíveis, ele está fechado|

<hr>

## 5. Referências

<p style="text-align: justify; text-indent: 20px">[1] SERRANO, Milene; SERRANO, Maurício. <b>Requisitos - Aula 10</b>. 2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>