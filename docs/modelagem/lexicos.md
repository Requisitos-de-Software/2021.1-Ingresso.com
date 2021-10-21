## 1. Versionamento

| Versão | Data  | Descrição                               | Autor(es)                        |
| ------ | ----- | :---------------------------------------: | :--------------------------------: |
| 1.0    | 24/08 | Abertura do documento | Rafael e Thiago|
| 1.1    | 24/08 | Adição dos léxicos | Rafael e Thiago|
| 1.2	 | 28/09 | Linkagem dos léxicos | João Pedro|
| 1.3	 | 17/10 | Correções levantadas na verificação| Rafael|

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

<div id="usuario"/>
|LO01|**Usuário**|
|---|------------------|
|**Sinônimos**|Cliente|
|**Noção**|A pessoa interessada em comprar <a href=.#ingresso>ingresso</a> para algum evento|
|**Impacto**|O usuário pode <a href=.#comprar-ingresso>comprar ingresso</a>, <a href=.#escolher-assento>escolher assento</a>, <a href=.#pesquisar>pesquisar</a> um evento e <a href=.#visualizar-prevencoes>visualizar prevenções</a>|

<div id="filme"/>
|LO02|**Filme**|
|---|------------------|
|**Sinônimos**|Evento, Espetáculo|
|**Noção**|Filmes para o <a href=.#usuario>usuário</a> ver|
|**Impacto**|O <a href=.#usuario>usuário</a> escolhe um filme desejado<br>O <a href=.#usuario>usuário</a> visualiza os <a href=.#local>locais</a> e <a href=.#sessao>horários</a> em que o filme vai passar|

<div id="acompanhamento"/>
|LO03|**Acompanhamento**|
|---|------------------|
|**Sinônimos**|Bebida, comida e pipoca|
|**Noção**|Conjunto de comidas e bebidas que acompanham o <a href=.#usuario>usuário</a> durante a <a href=.#sessao>sessão</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode comprar acompanhamentos<br>O <a href=.#usuario>usuário</a> retira o acompanhamento no evento|

<div id="ingresso"/>
|LO04|**Ingresso**|
|---|------------------|
|**Sinônimos**|Bilhete, Entrada, Convite|
|**Noção**|Um <a href=.#ingresso>ingresso</a> representa a entrada para uma <a href=.#sessao>sessão</a> de <a href=.#filme>filme</a> em determinado <a href=.#cinema>cinema</a>|
|**Impacto**|Um <a href=.#ingresso>ingresso</a> é utilizado para assistir um filme|

<div id="cinema"/>
|LO05|**Cinema**|
|---|------------------|
|**Sinônimos**|Estabelecimento|
|**Noção**|<a href=.#local>Local</a> onde é possível assistir um <a href=.#filme>filme</a> desejado|
|**Impacto**|Os <a href=.#filme>filmes</a> que estão em <a href=.#filme-em-cartaz>cartaz</a> só podem ser transmitidos em algum cinema|

<div id="assento"/>
|LO06|**Assento**|
|---|------------------|
|<b>Sinônimos</b>|Poltrona|
|**Noção**|A cadeira que o <a href=.#usuario>usuário</a> irá sentar durante o evento|
|**Impacto**|O <a href=.#usuario>usuário</a> pode escolher o assento|

<div id="sessao"/>
|LO07|**Sessão**|
|---|------------------|
|**Sinônimos**|Horário|
|**Noção**|Sessão refere-se a um determinado <a href=.#cinema>cinema</a> e horário onde vai passar o filme|
|**Impacto**|Um <a href=.#ingresso>ingresso</a> só pode ser <a href=.#comprar-ingresso>comprado</a> quando referido a uma sessão|

<div id="carrinho"/>
|LO08|**Carrinho**|
|---|------------------|
|**Sinônimos**|Carrinho de compras|
|**Noção**|Conjunto de <a href=.#ingresso>ingressos</a> e <a href=.#acompanhamento>acompanhamentos</a> que o <a href=.#usuario>usuário</a> pretende comprar|
|**Impacto**|O <a href=.#usuario>usuário</a> pode comprar vários itens|

<div id="noticia"/>
|LO09|**Notícia**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|Uma <a href=.#noticia>notícia</a> sobre algum <a href=.#filme>filme</a>, evento ou anúncio|
|**Impacto**|O <a href=.#usuario>usuário</a> pode visualizar as <a href=.#noticia>notícias</a> e compartilhá-la|

<div id="local"/>
|LO10|**Local**|
|---|------------------|
|**Sinônimos**|Localidade|
|**Noção**|Localização do <a href=.#cinema>cinema</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode pesquisar os <a href=.#cinema>cinemas</a> pela localidade|

<div id="classificacao-etaria"/>
|LO11|**Classificação etária**|
|---|------------------|
|**Sinônimos**|Classificação indicativa|
|**Noção**|Idade mínima recomendada para assistir o filme|
|**Impacto**|O <a href=.#usuario>usuário</a> pode filtrar os <a href=.#filme>filmes</a> que a classificação etária atende a sua idade|

<div id="genero"/>
|LO12|**Gênero**|
|---|------------------|
|**Sinônimos**|Classificação|
|**Noção**|Conjunto de <a href=.#filme>filmes</a> com a mesma origem ou tema relacionados|
|**Impacto**|O <a href=.#usuario>usuário</a> pode filtrar por gênero do filme|

<div id="avaliacao"/>
|LO13|**Avaliação**|
|---|------------------|
|**Sinônimos**|Avaliação de <a href=.#usuario>usuários</a>|
|**Noção**|Feedback dos <a href=.#usuario>usuários</a> sobre um filme|
|**Impacto**|O <a href=.#usuario>usuário</a> pode <a href=.#visualizar-avaliacao>visualizar avaliações</a> de um filme|

<div id="pedido"/>
|LO14|**Pedido**|
|---|------------------|
|**Sinônimos**|Pedido de compra|
|**Noção**|Conjunto de produtos, quantidades, preços e condições que o <a href=.#usuario>usuário</a> está comprando ou comprou|
|**Impacto**|O <a href=.#usuario>usuário</a> pode pedir reembolso|

<hr>

### 4.2 Verbos

<div id="comprar-ingresso"/>
|LV01|**Comprar Ingresso**|
|---|------------------|
|**Sinônimos**|Adquirir/Obter <a href=.#ingresso>ingresso</a>|
|**Noção**|O <a href=.#usuario>usuário</a> irá, através do pagamento, obter um <a href=.#ingresso>ingresso</a> para uma <a href=.#sessao>sessão</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> receberá o <a href=.#ingresso>ingresso</a> para o <a href=.#filme>filme</a> comprado|

<div id="escolher-assento"/>
|LV02|**Escolher Assento**|
|---|------------------|
|**Sinônimos**|Selecionar <a href=.#assento>assento</a>|
|**Noção**|O <a href=.#usuario>usuário</a> tem a opção de escolher um ou mais <a href=.#assento>assentos</a> para determinada <a href=.#sessao>sessão</a>|
|**Impacto**|Os <a href=.#assento>assentos</a> foram escolhidos<br><a href=.#assento>Assentos</a> próximos são bloqueados por medidas de segurança|

<div id="cadastrar-usuario"/>
|LV03|**Cadastrar usuário**|
|---|------------------|
|**Sinônimos**|Registrar <a href=.#usuario>usuário</a>|
|**Noção**|O <a href=.#usuario>usuário</a> poderá se cadastrar no app e receber alguns benefícios|
|**Impacto**|O <a href=.#usuario>usuário</a> cadastrado tem direito a algumas funcionalidades a mais|

<div id="logar-no-sistema"/>
|LV04|**Logar no sistema**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O <a href=.#usuario>usuário</a> já cadastrado poderá logar no sistema|
|**Impacto**|Após logado, o <a href=.#usuario>usuário</a> poderá ter acesso às informações sobre sua conta, bem como os benefícios de um <a href=.#usuario>usuário</a> cadastrado|

<div id="pesquisar"/>
|LV05|**Pesquisar**|
|---|------------------|
|**Sinônimos**|Buscar, Encontrar, Filtrar|
|**Noção**|O <a href=.#usuario>usuário</a> pode pesquisar sobre um <a href=.#filme>filme</a> ou <a href=.#cinema>cinema</a>|
|**Impacto**|Após pesquisado, o <a href=.#usuario>usuário</a> pode acessar informações específicas sobre os <a href=.#filme>filmes</a> ou <a href=.#cinema>cinemas</a> encontrados|

<div id="visualizar-prevencoes"/>
|LV06|**Visualizar prevenções**|
|---|------------------|
|**Sinônimos**|Ler prevenções|
|**Noção**|O <a href=.#usuario>usuário</a> pode visualizar as prevenções referentes ao <a href=.#cinema>cinema</a> determinado|
|**Impacto**|O <a href=.#usuario>usuário</a> tem acesso as prevenções referentes a <a href=.#cinema>cinemas</a> próximos<br>Sabendo as prevenções ele pode se preparar para evitar imprevistos|

<div id="visualizar-avaliacao"/>
|LV07|**Visualizar avaliação**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O <a href=.#usuario>usuário</a> pode ver as avaliações feitas pelos <a href=.#usuario>usuários</a> do Rotten Tomatoes|
|**Impacto**|O <a href=.#usuario>usuário</a> pode perder ou ganhar interesse a partir das avaliações|

<div id="visualizar-filme"/>
|LV08|**Visualizar filme**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O <a href=.#usuario>usuário</a> pode ver as informações sobre o <a href=.#filme>filme</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode perder ou ganhar interesse a partir das informações<br>O <a href=.#usuario>usuário</a> pode <a href=.#comprar-ingresso>comprar ingressos</a> para o <a href=.#filme>filme</a>|

<div id="ler-noticia"/>
|LV09|**Ler notícia**|
|---|------------------|
|**Sinônimos**|Visualizar <a href=.#noticia>notícia</a>|
|**Noção**|O <a href=.#usuario>usuário</a> pode ler as <a href=.#noticia>notícias</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode se interessar por um <a href=.#filme>filme</a>|

<div id="compartilhar"/>
|LV10|**Compartilhar**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O <a href=.#usuario>usuário</a> pode compartilhar um <a href=.#filme>filme</a> ou uma <a href=.#noticia>notícia</a> com alguém|
|**Impacto**|O <a href=.#usuario>usuário</a> compartilha a página do filme, ou <a href=.#noticia>notícia</a>, por uma rede social|

<div id="pedir-reembolso"/>
|LV11|**Pedir reembolso**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O <a href=.#usuario>usuário</a> pode pedir reembolso de um pedido|
|**Impacto**|O <a href=.#usuario>usuário</a> terá seu dinheiro estornado<br>Os <a href=.#assento-esta-selecionado>assentos selecionados</a> se tornam <a href=.#assento-disponivel>disponíveis</a>|

<div id="selecionar-cinema"/>
|LV12|**Selecionar cinema**|
|---|------------------|
|**Sinônimos**|Selecionar <a href=.#local>local</a>|
|**Noção**|O <a href=.#usuario>usuário</a> pode escolher o <a href=.#cinema>cinema</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode escolher a <a href=.#sessao>sessão</a>|

<div id="selecionar-sessao"/>
|LV13|**Selecionar sessão**|
|---|------------------|
|**Sinônimos**|-|
|**Noção**|O <a href=.#usuario>usuário</a> pode escolher a <a href=.#sessao>sessão</a> do <a href=.#cinema>cinema</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode <a href=.#comprar-ingresso>comprar o ingresso</a><br>|

<hr>

### 4.3 Estados

<div id="ingresso-esta-no-carrinho"/>
|LE01|**Ingresso está no carrinho**|
|---|------------------|
|**Sinônimos**|<a href=.#ingresso>Ingresso</a> está sendo comprado|
|**Noção**|O <a href=.#usuario>usuário</a> pretende <a href=.#comprar-ingresso>comprar um ingresso</a>, então esse <a href=.#ingresso>ingresso</a> é salvo no <a href=.#carrinho>carrinho</a> para ele poder tanto fazer o pagamento quanto realizar modificações|
|**Impacto**|O <a href=.#usuario>usuário</a> pode comprar os itens do <a href=.#carrinho>carrinho</a><br>Se o <a href=.#usuario>usuário</a> não se interessar mais pelo <a href=.#ingresso>ingresso</a>, ele pode retirá-lo do <a href=.#carrinho>carrinho</a>|

<div id="filme-em-cartaz"/>
|LE02|**Filme em cartaz**|
|---|------------------|
|**Sinônimos**|<a href=.#filme>Filme</a> disponível para venda|
|**Noção**|O a filme estando em cartaz significa que ele está disponível para ser assistido em determinados <a href=.#cinema>cinemas</a> possuindo uma ou várias <a href=sessao>sessões</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode decidir assistir o <a href=.#filme>filme</a> em cartaz comprando um <a href=.#ingresso>ingresso</a> para determinada <a href=.#sessao>sessão</a><br>Quando não há mais <a href=.#cinema>cinemas</a> transmitindo esse filme, ele fica <a href=.#filme-fora-de-cartaz>fora de cartaz</a><br>Quando não houver mais <a href=.#ingresso>ingressos</a> a venda, o <a href=.#filme-esgotado>filme está egotado</a>|

<div id="filme-fora-de-cartaz"/>
|LE03|**Filme fora de cartaz**|
|---|------------------|
|**Sinônimos**|Filme não disponível|
|**Noção**|Um <a href=.#filme>filme</a> que não tem mais <a href=.#sessao>sessões</a> disponíveis|
|**Impacto**|O <a href=.#usuario>usuário</a> não pode <a href=.#comprar-ingresso>comprar ingressos</a> para esse <a href=.#filme>filme</a><br>Quando houver <a href=.#sessao>sessões</a>, o <a href=.#filme-em-cartaz>filme entra em cartaz</a>|

<div id="filme-em-breve"/>
|LE04|**Filme em breve**|
|---|------------------|
|**Sinônimos**|<a href=.#filme>Filme</a> chegará em breve, <a href=.#filme>Filme</a> está para ser lançado|
|**Noção**|Um <a href=.#filme>filme</a> que está para ser lançado significa que ele estará disponível para ser assistido em breve|
|**Impacto**|O <a href=.#usuario>usuário</a> pode ver mais detalhes sobre o <a href=.#filme>filme</a> que está para ser lançado (trailer, descrição)<br>Quando o <a href=.#filme>filme</a> for lançado, ele sairá dos filmes em breve|

<div id="filme-em-lancamento"/>
|LE05|**Filme em lançamento**|
|---|------------------|
|**Sinônimos**|Filme recém-lançado|
|**Noção**|Um <a href=.#filme>filme</a> que está em lançamento significa que está disponível para ser assistido há pouco tempo|
|**Impacto**|O <a href=.#usuario>usuário</a> pode comprar <a href=.#ingresso>ingresso</a> para o <a href=.#filme>filme</a><br>Quando passa algumas semanas depois que o <a href=.#filme>filme</a> foi lançado, ele se torna um <a href=.#filme-em-cartaz>filme em cartaz</a>|

<div id="filme-em-alta"/>
|LE06|**Filme em alta**|
|---|------------------|
|**Sinônimos**|Filmes populares|
|**Noção**|Um <a href=.#filme>filme</a> em alta é um <a href=.#filme>filme</a> popular, que é de interesse de várias pessoas|
|**Impacto**|O <a href=.#usuario>usuário</a> pode decidir assistir o <a href=.#filme>filme</a> em alta comprando um <a href=.#ingresso>ingresso</a> para determinada <a href=.#sessao>sessão</a>. Quando o <a href=.#filme>filme</a> não está mais em alta e a quantidade de sessões diminuiu, ele se torna apenas um <a href=.#filme-em-cartaz>filme em cartaz</a>|

<div id="filme-esgotado"/>
|LE07|**Filme esgotado**|
|---|------------------|
|**Sinônimos**|<a href=.#ingresso>Ingressos</a> esgotados|
|**Noção**|Um <a href=.#filme>filme</a> que está em cartaz, mas não tem <a href=.#ingresso>ingressos</a> disponíveis para a venda|
|**Impacto**|O <a href=.#usuario>usuário</a> não pode comprar <a href=.#ingresso>ingressos</a> para esse <a href=.#filme>filme</a><br>Quando houver <a href=.#sessao>sessões</a> com <a href=.#ingresso>ingressos</a> disponíveis, então ele se torna um <a href=.#filme-em-cartaz>filme em cartaz</a>|

<div id="assento-disponivel"/>
|LE08|**Assento disponível**|
|---|------------------|
|**Sinônimos**|<a href=.#assento>Assento</a> livre|
|**Noção**|Um <a href=.#assento>assento</a> que pode ser selecionado pelo <a href=.#usuario>usuário</a> para uma determinada <a href=.#sessao>sessão</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode escolher um <a href=.#assento>assento</a> disponível<br>Quando alguém já escolheu esse <a href=.#assento>assento</a>, ele não está mais disponível|

<div id="assento-indisponivel"/>
|LE09|**Assento indisponível**|
|---|------------------|
|**Sinônimos**|<a href=.#assento>Assento</a> ocupado|
|**Noção**|Um <a href=.#assento>assento</a> que ter sido selecionado por outro <a href=.#usuario>usuário</a> ou está bloqueado devido a medidas de prevenção contra o COVID|
|**Impacto**|O <a href=.#usuario>usuário</a> não pode escolher um <a href=.#assento>assento</a> indisponível<br>Quando o <a href=.#usuario>usuário</a> desiste da compra do <a href=.#ingresso>ingresso</a>, o <a href=.#assento>assento</a> desse <a href=.#usuario>usuário</a> se torna disponível|

<div id="assento-esta-selecionado"/>
|LE10|**Assento está selecionado**|
|---|------------------|
|**Sinônimos**|<a href=.#assento>Assento</a> está escolhido|
|**Noção**|Um ou mais <a href=.#assento>assentos</a> foram selecionados pelo <a href=.#usuario>usuário</a> para determinada <a href=.#sessao>sessão</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> visualiza os <a href=.#assento-disponivel>assentos disponíveis</a> para a <a href=.#sessao>sessão</a><br>O <a href=.#usuario>usuário</a> escolhe um <a href=.#assento-disponivel>assento disponível</a><br>Os <a href=.#assento>assentos</a> ao redor são bloqueados por motivos de prevenção|

<div id="cinema-esta-favoritado"/>
|LE11|**Cinema está favoritado**|
|---|------------------|
|**Sinônimos**|<a href=.#cinema>Cinema</a> está como preferido, predileto|
|**Noção**|Um <a href=.#usuario>usuário</a> <a href=.#logar-no-sistema>logado</a> pode favoritar um <a href=.#cinema>cinema</a>, facilitando o futuro acesso a esses <a href=.#cinema>cinemas</a> por uma aba especial "Favoritos"|
|**Impacto**|O <a href=.#usuario>usuário</a> clica no símbolo de coração e favorita o <a href=.#cinema>cinema</a><br>O <a href=.#cinema>cinema</a> favoritado aparece em “Favoritos”<br>Caso o <a href=.#usuario>usuário</a> clique no coração novamente, este <a href=.#cinema>cinema</a> deixa de ser favorito.|

<div id="cinema-aberto"/>
|LE12|**Cinema aberto**|
|---|------------------|
|**Sinônimos**|<a href=.#cinema>Cinema</a> em funcionamento|
|**Noção**|Um <a href=.#cinema>cinema</a> que tem <a href=.#sessao>sessões</a> disponíveis para <a href=.#filme>filmes</a>|
|**Impacto**|O <a href=.#usuario>usuário</a> pode visualizar os filmes e sessões disponíveis<br>Quando não há sessões disponíveis, ele está fechado|

<hr>

## 5. Referências

<p style="text-align: justify; text-indent: 20px">[1] SERRANO, Milene; SERRANO, Maurício. <b>Requisitos - Aula 10</b>. 2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>
