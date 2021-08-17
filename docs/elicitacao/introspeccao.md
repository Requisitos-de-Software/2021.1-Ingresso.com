## 1. Versionamento

|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|13/08|Abertura do documento de Introspecção|Thiago|
|1.1|13/08|Adição das introspecções|Thiago|
|1.1|15/08|Adicao da introducão e referências|Thiago|
|1.2|16/08|Adição dos requisitos elicitados|Thiago|

## 1. Introdução
<p style="text-align: justify; text-indent: 20px">
A introspecção consiste no ato de tentar entender as propriedades que um sistema deve ter para que seja bem sucedido. Baseia-se em imaginar o que você gostaria que o sistema tivesse para realizar uma determinada tarefa. Essa técnica pode sofrer com o viés do Engenheiro de Requisitos que está imaginando, uma vez que as escolhas dele podem não refletir as necessidades da maioria dos usuários do sistema [1]. Sendo assim, a seção 2 apresenta uma introspecção que está sendo aplicada sobre um fluxo de entrar no aplicativo até o recebimento do ingresso.
</p>

## 2. Introspecções Desenvolvidas
### Ao acessar o aplicativo

- Deve apresentar os filmes mais populares em cartaz.
- Deve apresentar os filmes que serão lançados.
- Deve mostrar os cinemas abertos próximos ao usuário.
- Deve ter uma maneira de pesquisar e filtrar.
- Deve ter uma área para notícias.
- Deve ter uma área de autenticação.
- Deve ter uma área informando as medidas de prevenção durante a pandemia.
- Deve ter uma área para selecionar a cidade que deseja.
- Não há necessidade de autenticação para navegar entre os filmes e notícias.

### Ao escolher um filme

- Deve apresentar informações sobre o filme.
- Deve mostrar os cinemas mais próximos em que o filme está em cartaz.
- Os cinemas devem apresentar os horários das sessões do filme nos próximos dois dias.
- Deve ter como seguir o filme para acompanhar notícias e lançamentos.
- Deve recomendar outros filmes.
- Pode compartilhar o filme.

### Ao escolher o cinema

- Deve apresentar as informações do cinema.
- Deve apresentar as sessões com os horários e dias com vagas.

### Ao escolher uma sessão

- Deve apresentar informações da sessão.
- Deve mostrar os assentos disponíveis.

### Ao escolher o assento

- Deve apresentar os tipos de ingressos.
- Deve oferecer acompanhamentos, como bebidas, pipocas e lanches.

### A identificação

- Pode comprar com uma conta criada no domínio.
- Pode comprar com uma conta do Google ou Facebook.
- Pode comprar sem o cadastro.

### O pagamento

- Deve mostrar um resumo da compra.
- Deve mostrar o total e informações do pagamento.
- Deve ter como escolher o método de pagamento.
- O usuário deve ser notificado.
- O resumo do pedido deve ser enviado por e-mail.

### Após a confirmação de pagamento.

- Deve ter uma área para os pedidos.
- Deve notificar a confirmação do pagamento.
- Deve apresentar informações do ingresso.
- Deve enviar o ingresso por e-mail;
- Deve notificar quando a sessão tiver chegando.

## 3. Requisitos Elicitados

|ID|Descrição|Tipo|
|---|----|-----|
I01|Apresentar os filmes mais populares em cartaz|Funcional|
I02|Apresentar os filmes que serão lançados|Funcional|
I03|Mostrar os cinemas abertos próximos ao usuário|Funcional|
I04|Pesquisar um filme|Funcional|
I05|Ter uma área para notícias|Funcional|
I06|Ter uma área de autenticação|Funcional|
I07|Ter uma área informando as medidas de prevenção durante a pandemia|Funcional|
I08|Ter uma área para selecionar a cidade que deseja|Funcional|
I09|Não há necessidade de autenticação para navegar entre os filmes e notícias|Não funcional|
I10|Apresentar informações sobre o filme|Funcional|
I11|Mostrar os cinemas mais próximos em que o filme está em cartaz|Funcional|
I12|Os cinemas devem apresentar os horários das sessões do filme nos próximos dois dias|Funcional|
I13|Ter como seguir o filme para acompanhar notícias e lançamentos|Funcional|
I14|Recomendar outros filmes|Funcional|
I15|Compartilhar o filme|Funcional|
I16|Apresentar as informações do cinema|Funcional|
I17|Apresentar as sessões com os horários e dias com vagas|Funcional|
I18|Apresentar informações da sessão|Funcional|
I19|Mostrar os assentos disponíveis|Funcional|
I20|Apresentar os tipos de ingressos|Funcional|
I21|Oferecer acompanhamentos|Funcional|
I22|Comprar com uma conta criada no domínio|Funcional|
I23|Comprar com uma conta do Google ou Facebook|Funcional|
I24|Comprar sem o cadastro|Funcional|
I25|Mostrar um resumo da compra|Funcional|
I26|Mostrar o total e informações do pagamento|Funcional|
I27|Ter como escolher o método de pagamento|Funcional|
I28|O usuário deve ser notificado|Funcional|
I29|O resumo do pedido deve ser enviado por e-mail|Funcional|
I30|Ter uma área para os pedidos|Funcional|
I31|Notificar a confirmação do pagamento|Funcional|
I32|Apresentar informações do ingresso|Funcional|
I33|Enviar o ingresso por e-mail|Funcional|
I34|Notificar quando a sessão tiver chegando|Funcional|

<p align="center">Tabela 1: Requisitos elicitados a partir da introspecção</p>
<p align="center">Fonte: Autores</p>


## 3. Referências

- [1] Goguen, J. e Linde, C. <b>Techniques for Requirements Elicitation</b>. IEE Computer Society. 1993.
