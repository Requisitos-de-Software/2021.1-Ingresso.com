## 1. Versionamento

|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|13/08|Abertura do documento de Introspecção|Thiago|
|1.1|13/08|Adição das introspecções|Thiago|
|1.1|15/08|Adicao da introducão e referências|Thiago|
|1.2|16/08|Adição dos requisitos elicitados|Thiago|
|1.3|03/10|Linkagem dos léxicos|Thiago|

## 1. Introdução
<p style="text-align: justify; text-indent: 20px">
A introspecção consiste no ato de tentar entender as propriedades que um sistema deve ter para que seja bem sucedido. Baseia-se em imaginar o que você gostaria que o sistema tivesse para realizar uma determinada tarefa. Essa técnica pode sofrer com o viés do Engenheiro de Requisitos que está imaginando, uma vez que as escolhas dele podem não refletir as necessidades da maioria dos <a href="../../modelagem/lexicos/#usuario">usuários</a> do sistema [1]. Sendo assim, a seção 2 apresenta uma introspecção que está sendo aplicada sobre um fluxo de entrar no aplicativo até o recebimento do <a href="../../modelagem/lexicos/#ingresso">ingresso</a>.
</p>

## 2. Introspecções Desenvolvidas
### Ao acessar o aplicativo

- Deve apresentar os [filmes](../../modelagem/lexicos/#filme) mais populares em [cartaz](../../modelagem/lexicos/#filme-em-cartaz).
- Deve apresentar os [filmes](../../modelagem/lexicos/#filme) que serão [lançados](../../modelagem/lexicos/#filme-em-lancamento).
- Deve mostrar os [cinemas](../../modelagem/lexicos/#cinema) abertos próximos ao [usuário](../../modelagem/lexicos/#usuario).
- Deve ter uma maneira de [pesquisar e filtrar](../../modelagem/lexicos/#pesquisar).
- Deve ter uma área para [notícias](../../modelagem/lexicos/#noticia).
- Deve ter uma área de [autenticação](../../modelagem/lexicos/#logar-no-sistema).
- Deve ter uma área informando as medidas de [prevenção](../../modelagem/lexicos/#visualizar-prevencoes) durante a pandemia.
- Deve ter uma área para selecionar a [cidade](../../modelagem/lexicos/#local) que deseja.
- Não há necessidade de autenticação para navegar entre os [filmes](../../modelagem/lexicos/#filme) e [notícias](../../modelagem/lexicos/#noticia).

### Ao escolher um [filme](../../modelagem/lexicos/#filme)

- Deve apresentar informações sobre o [filme](../../modelagem/lexicos/#filme).
- Deve mostrar os [cinemas](../../modelagem/lexicos/#cinema) mais próximos em que o [filme](../../modelagem/lexicos/#filme) está em cartaz.
- Os [cinemas](../../modelagem/lexicos/#cinema) devem apresentar os horários das [sessões](../../modelagem/lexicos/#sessao) do [filme](../../modelagem/lexicos/#filme) nos próximos dois dias.
- Deve ter como seguir o [filme](../../modelagem/lexicos/#filme) para acompanhar [notícias](../../modelagem/lexicos/#noticia) e [lançamentos](../../modelagem/lexicos/#filme-em-lancamento).
- Deve recomendar outros [filmes](../../modelagem/lexicos/#filme).
- Pode compartilhar o [filme](../../modelagem/lexicos/#filme).

### Ao escolher o [cinema](../../modelagem/lexicos/#cinema)

- Deve apresentar as informações do [cinema](../../modelagem/lexicos/#cinema).
- Deve apresentar as [sessões](../../modelagem/lexicos/#sessao) com os horários e dias com vagas.

### Ao escolher uma [sessão](../../modelagem/lexicos/#sessao)

- Deve apresentar informações da [sessão](../../modelagem/lexicos/#sessao).
- Deve mostrar os [assentos](../../modelagem/lexicos/#assento) disponíveis.

### Ao [escolher o assento](../../modelagem/lexicos/#escolher-assento)

- Deve apresentar os tipos de [ingressos](../../modelagem/lexicos/#ingresso).
- Deve oferecer [acompanhamentos](../../modelagem/lexicos/#acompanhamento), como bebidas, pipocas e lanches.

### A identificação

- Pode comprar com uma conta criada no domínio.
- Pode comprar com uma conta do Google ou Facebook.
- Pode comprar sem o cadastro.

### O pagamento

- Deve mostrar um resumo da [compra](../../modelagem/lexicos/#comprar-ingresso).
- Deve mostrar o total e informações do pagamento.
- Deve ter como escolher o método de pagamento.
- O [usuário](../../modelagem/lexicos/#usuario) deve ser notificado.
- O resumo do [pedido](../../modelagem/lexicos/#pedido) deve ser enviado por e-mail.

### Após a confirmação de pagamento.

- Deve ter uma área para os [pedidos](../../modelagem/lexicos/#pedido).
- Deve notificar a confirmação do pagamento.
- Deve apresentar informações do [ingresso](../../modelagem/lexicos/#ingresso).
- Deve enviar o [ingresso](../../modelagem/lexicos/#ingresso) por e-mail;
- Deve notificar quando a [sessão](../../modelagem/lexicos/#sessao) tiver chegando.

## 3. Requisitos Elicitados

|ID|Descrição|Tipo de Requisito|
|---|----|-----|
I01|Apresentar os [filmes](../../modelagem/lexicos/#filme) mais [populares](../../modelagem/lexicos/#filme-em-alta) [em cartaz](../../modelagem/lexicos/#filme-em-cartaz)|Requisito Funcional|
I02|Apresentar os [filmes](../../modelagem/lexicos/#filme) que serão [lançados](../../modelagem/lexicos/#filme-em-lancamento)|Requisito Funcional|
I03|Mostrar os [cinemas](../../modelagem/lexicos/#cinema) abertos próximos ao [usuário](../../modelagem/lexicos/#usuario)|Requisito Funcional|
I04|[Pesquisar](../../modelagem/lexicos/#pesquisar) um [filme](../../modelagem/lexicos/#filme)|Requisito Funcional|
I05|Ter uma área para [notícias](../../modelagem/lexicos/#noticia)|Requisito Funcional|
I06|Ter uma área de autenticação|Requisito Funcional|
I07|Ter uma área informando as medidas de [prevenção](../../modelagem/lexicos/#visualizar-prevencoes) durante a pandemia|Requisito Funcional|
I08|Ter uma área para selecionar a cidade que deseja|Requisito Funcional|
I09|Não há necessidade de autenticação para navegar entre os [filmes](../../modelagem/lexicos/#filme) e [notícias](../../modelagem/lexicos/#noticia)|Requisito Não Funcional|
I10|Apresentar informações sobre o [filme](../../modelagem/lexicos/#filme)|Requisito Funcional|
I11|Mostrar os [cinemas](../../modelagem/lexicos/#cinemas) mais próximos em que o [filme](../../modelagem/lexicos/#filme) está em cartaz|Requisito Funcional|
I12|Os [cinemas](../../modelagem/lexicos/#cinema) devem apresentar os horários das [sessões](../../modelagem/lexicos/#sessao) do [filme](../../modelagem/lexicos/#filme) nos próximos dois dias|Requisito Funcional|
I13|Ter como seguir o [filme](../../modelagem/lexicos/#filme) para acompanhar [notícias](../../modelagem/lexicos/#noticia) e lançamentos|Requisito Funcional|
I14|Recomendar outros [filmes](../../modelagem/lexicos/#filme)|Requisito Funcional|
I15|Compartilhar o [filme](../../modelagem/lexicos/#filme)|Requisito Funcional|
I16|Apresentar as informações do [cinema](../../modelagem/lexicos/#cinema)|Requisito Funcional|
I17|Apresentar as [sessões](../../modelagem/lexicos/#sessao) com os horários e dias com vagas|Requisito Funcional|
I18|Apresentar informações da [sessão](../../modelagem/lexicos/#sessao)|Requisito Funcional|
I19|Mostrar os [assentos disponíveis](../../modelagem/lexicos/#assento-disponivel)|Requisito Funcional|
I20|Apresentar os tipos de [ingressos](../../modelagem/lexicos/#ingresso)|Requisito Funcional|
I21|Oferecer [acompanhamentos](../../modelagem/lexicos/#acompanhamento)|Requisito Funcional|
I22|Comprar com uma conta criada no domínio|Requisito Funcional|
I23|Comprar com uma conta do Google ou Facebook|Requisito Funcional|
I24|Comprar sem o cadastro|Requisito Funcional|
I25|Mostrar um resumo da [compra](../../modelagem/lexicos/#pedido)|Requisito Funcional|
I26|Mostrar o total e informações do pagamento|Requisito Funcional|
I27|Ter como escolher o método de pagamento|Requisito Funcional|
I28|O [usuário](../../modelagem/lexicos/#usuario) deve ser notificado|Requisito Funcional|
I29|O resumo do [pedido](../../modelagem/lexicos/#pedido) deve ser enviado por e-mail|Requisito Funcional|
I30|Ter uma área para os [pedidos](../../modelagem/lexicos/#pedido)|Requisito Funcional|
I31|Notificar a confirmação do pagamento|Requisito Funcional|
I32|Apresentar informações do [ingresso](../../modelagem/lexicos/#ingresso)|Requisito Funcional|
I33|Enviar o [ingresso](../../modelagem/lexicos/#ingresso) por e-mail|Requisito Funcional|
I34|Notificar quando a [sessão](../../modelagem/lexicos/#sessao) tiver chegando|Requisito Funcional|

<p align="center">Tabela 1: Requisitos elicitados a partir da introspecção</p>
<p align="center">Fonte: Autores</p>


## 4. Referências

- [1] Goguen, J. e Linde, C. <b>Techniques for Requirements Elicitation</b>. IEE Computer Society. 1993.
