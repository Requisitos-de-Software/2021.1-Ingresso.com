## 1. Versionamento

| Versão | Data  | Descrição             | Autor(es)       |
| ------ | ----- | --------------------- | --------------- |
| 1.0    | 06/09 | Abertura do documento | Carlos |
| 1.1    | 07/09 | Adição das features   | Carlos e Victor Lima |


## 2. Introdução

<p style="text-align: justify; text-indent: 20px">
Uma história do usuário é um cenário de uso de um produto por um tipo específico de usuário. Uma história deveria ser compreendida pelos clientes, testável pelo desenvolvedor, de valor para o cliente e pequena o suficiente para que os programadores possam construir uma meia dúzia delas em uma iteração. [1]
</p>

## 3. Metodologia

<p style="text-align: justify; text-indent: 20px">
De forma a manter um formato padronizado, a estrutura das histórias de usuário seguirá um padrão conhecido como "expressão da história do usuário" ou "voz do
usuário" ou "cartão (card)". [2]
</p>

| ID | USYY  |
|-----|--------|
| Nome | Nome da história. |
| Descrição | Descrição da História de Usuário. |
| Critérios de Aceitação | Critérios complementares que ajudam a esclarecer como será validada a história.|

## 4. Épicos

<b>Legenda:</b>

- E: Épico.

| Épico | Descrição | Features |
| ------| --------- | -------- |
| E01 - Cadastro e Autenticação | Engloba toda parte de cadastramento, login e logout | -> Cadastro <br/> -> Login <br/> -> Logout |
| E02 - Perfil | Engloba toda a parte de informações de [usuário](../../modelagem/lexicos/#usuario) e configurações da aplicação. | -> Perfil <br/> -> Atendimento <br/> -> Sobre o App <br/> | 
| E03 - [Cinemas](../../modelagem/lexicos/#cinema) | Engloba toda parte de [cinemas](../../modelagem/lexicos/#cinema) | -> Localização <br/> -> [Cinemas](../../modelagem/lexicos/#cinema) <br/> -> [Sessões](../../modelagem/lexicos/#sessao) <br/> |
| E04 - [Filmes](../../modelagem/lexicos/#filme) | Engloba toda parte de [filmes](../../modelagem/lexicos/#filme) | -> [Filmes](../../modelagem/lexicos/#filme) <br/> |
| E05 - [Compra](../../modelagem/lexicos/#compra-ingresso) | Engloba toda a parte de [compra](../../modelagem/lexicos/#compra-ingresso) de [ingressos](../../modelagem/lexicos/#ingresso) | -> [Ingresso](../../modelagem/lexicos/#ingresso) <br/> -> [Acompanhamentos](../../modelagem/lexicos/#acompanhamento) <br/> -> Pagamento <br/> -> [Carrinho](../../modelagem/lexicos/#carrinho) <br/>|
| E06 - Engajamento | Engloba toda a parte de manter o [usuário](../../modelagem/lexicos/#usuario) engajado.  | -> [Notícia](../../modelagem/lexicos/#noticia) <br/> -> Destaques <br/> |
| E07 - Lucro | Engloba uma parte do lucro do aplicativo. | -> Anúncios. <br/>|

## 5. Features

<b>Legenda:</b>

- US: Histórias de Usuário.

### Feature 01 - Cadastro

| ID | US01  |
|-----|--------|
| Nome | Criar conta. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo criar uma conta para ter acesso às funcionalidades completas do aplicativo. |
| Critérios de Aceitação | O formulário de cadastramento deve conter os seguintes campos: <br/> -> Nome <br/> -> E-mail <br/> -> Senha <br/> -> Data de Aniversário <br/> -> Gênero <br/> -> Cpf <br/> -> DDD e telefone <br/> -> Endereço composto |

| ID | US02 |
|-----|--------|
| Nome | Validação do formulário de cadastramento. |
| Descrição | Eu, como sistema, desejo realizar a validadação dos dados preenchidos no formulário de cadastramento para garantir que são reais. |
| Critérios de Aceitação | Deve conter as seguintes opções: <br/> <b> Nome </b> <br/> -> Apenas caracteres do alfabeto.<br/> <b> E-mail </b> <br/>-> Ser email válido. <br/> <b> Senha </b> <br/>-> Possuir ao menos 8 dígitos. <br/>  <b> Data de Aniversário </b><br/> -> Possuir dia entre 1 e 31  <br/> ->  Possuir mês entre 01 e 12<br/> <b> Cpf </b> <br/>-> Cpf válido <br/>  <b> DDD e telefone </b> <br/>-> Telefone válido <br/> <b> Endereço composto </b> <br/> -> Endereço existente <br/>|

### Feature 02 - Login

| ID | US03 |
|-----|--------|
| Nome | Fazer login |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo fazer login para entrar na minha conta e aproveitar as funcionalidades do Ingresso.com |
| Critérios de Aceitação | -> Input de email e senha <br/> -> Opção para logar com Facebook <br/> -> Opção para logar com Google <br/> -> Opção para escolher se quer receber novidades e mensagens por email.|

| ID | US04 |
|-----|--------|
| Nome | Validação do formulário de login. |
| Descrição | Eu, como sistema, desejo realizar a validadação dos dados preenchidos no formulário de login para que possa autenticá-lo. |
| Critérios de Aceitação | Deve conter as seguintes opções: <br/> <b> E-mail </b> <br/>-> Ser email válido. <br/> <b> Senha </b> <br/>-> Possuir ao menos 8 dígitos. <br/> |

| ID | US05 |
|-----|--------|
| Nome | Esqueceu senha. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo redefinir a senha da minha conta que esqueci para fazer login. |
| Critérios de Aceitação | -> Opção "esqueci a senha" <br/> -> Campo input para que o [usuário](../../modelagem/lexicos/#usuario) insira email. <br/> |

| ID | US06 |
|-----|--------|
| Nome | Enviar email esqueceu senha. |
| Descrição | Eu, como sistema, desejo enviar email para que o [usuário](../../modelagem/lexicos/#usuario) redefina a senha. |
| Critérios de Aceitação | -> Mensagem com informação de email enviado. <br/> |

### Feature 03 - Logout

| ID | US07  |
|-----|--------|
| Nome | Fazer logout. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo realizar logout do aplicativo para que minha conta não esteja mais vinculada com o app. |
| Critérios de Aceitação | -> Existir opção para sair da conta no app.|

### Feature 04 - Perfil

| ID | US08  |
|-----|--------|
| Nome | Alterar senha. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo alterar a senha da minha conta para uma de minha preferência. |
| Critérios de Aceitação | -> Campo input de senha atual <br/> -> Campo input de nova senha <br/> -> Validar senha com ao menos 8 caracteres <br/> -> Campo para confirmar senha <br/>|

| ID | US09  |
|-----|--------|
| Nome | Alterar dados pessoais. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo alterar os dados pessoais da minha conta caso algum dado tenha mudado. |
| Critérios de Aceitação | Deve conter os seguintes campos: <br/> -> Nome <br/> -> Senha <br/> -> Data de Aniversário <br/> -> Gênero <br/> -> DDD e telefone <br/> -> Endereço composto <br/> Dados válidados de acordo com a [**US02**](#feature-01-cadastro)|

| ID | US10 |
|-----|--------|
| Nome | Visualizar cartões salvos. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar cartões salvos para que eu possa excluir algum ou alterá-lo. |
| Critérios de Aceitação | -> Todos cartões salvos. <br/> -> Opção para alterar. <br/> -> Opção para excluir cartão salvo. <br/>|

| ID | US11  |
|-----|--------|
| Nome | Visualizar pedidos. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar meu pedidos realizados para que possa acompanhar quais [ingressos](../../modelagem/lexicos/#ingresso) e [sessões](../../modelagem/lexicos/#usuario) já assisti.|
| Critérios de Aceitação | -> Apresentar pedidos ordenados pelo mais recente. <br/>|

### Feature 05 - Atendimento

| ID | US12  |
|-----|--------|
| Nome | Solicitar atendimento. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo esclarecer dúvidas e/ou enviar solicitações de atendimento para o Ingresso.com para compreender melhor o aplicativo. |
| Critérios de Aceitação | -> Opção de atendimento. <br/> -> Campo para pesquisar dúvida. <br/> -> Campo de seleção para opção de contato. <br/> -> Formulário com input para email, assunto, descrição, motivo do contato, cpf e celular. <br/> -> Opção de anexar arquivos. <br/>|

### Feature 06 - Sobre o App

| ID | US13  |
|-----|--------|
| Nome | Informações do app. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar informações sobre o aplicativo para saber qual a versão que está instalada em meu smartphone. |
| Critérios de Aceitação | -> Informalções sobre o smartphone. <br/> -> Informação sobre a versão do app. <br/>|

### Feature 07 - Localização

| ID | US14  |
|-----|--------|
| Nome | Adicionar localização. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo adicionar minha localização ou escolher a cidade para que eu possa ver os [cinemas](../../modelagem/lexicos/#cinema) da minha região.  |
| Critérios de Aceitação | -> Opção para atualizar localização. <br/> -> Opção para buscar cidade. <br/> -> Lista de cidades mais acessadas. <br/> -> Lista de cidades ordenadas por estado. <br/>|

| ID | US15  |
|-----|--------|
| Nome | Alterar localização. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo alterar a localização ou cidade para que eu possa ver os [cinemas](../../modelagem/lexicos/#cinema) da cidade em que estou.|
| Critérios de Aceitação | -> Critérios da [**US14**](#feature-07-localizaçao)|

### Feature 08 - [Cinemas](../../modelagem/lexicos/#cinema)

| ID | US16  |
|-----|--------|
| Nome | Visualizar [cinemas](../../modelagem/lexicos/#cinema). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar [cinemas](../../modelagem/lexicos/#cinema) da minha cidade para que eu possa escolher algum para ir. |
| Critérios de Aceitação | -> Opção para ordenar por nome. <br/> -> Opção para ordenar por proximidade. <br/> -> Opção para visualizar [cinemas](../../modelagem/lexicos/#cinema) fechados. <br/> -> Opção para visualizar [cinemas](../../modelagem/lexicos/#cinema) abertos. <br/> -> Listar [cinemas](../../modelagem/lexicos/#cinema) favoritos. <br/> |

| ID | US17  |
|-----|--------|
| Nome | Pesquisar [cinemas](../../modelagem/lexicos/#cinema). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo pesquisar [cinemas](../../modelagem/lexicos/#cinema) para ver se está aberto ou se vende [ingressos](../../modelagem/lexicos/#ingresso) pelo app. |
| Critérios de Aceitação | -> Campo input para busca. <br/> |

| ID | US18  |
|-----|--------|
| Nome | Sobre o [cinema](../../modelagem/lexicos/#cinema). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar informações sobre o [cinema](../../modelagem/lexicos/#cinema) para que eu possa saber como chegar nele e entrar em contato. |
| Critérios de Aceitação | -> Informação sobre contato. <br/> -> Localização do [cinema](../../modelagem/lexicos/#cinema). <br/> -> Tipo de retirada de [ingresso](../../modelagem/lexicos/#ingresso). <br/> |

| ID | US19  |
|-----|--------|
| Nome | Prevenções do [cinema](../../modelagem/lexicos/#cinema). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar as medidas preventivas adotadas pelo [cinema](../../modelagem/lexicos/#cinema) para que eu possa me previnir melhor. |
| Critérios de Aceitação | -> Informações sobre as prevenções. <br/> |

| ID | US20  |
|-----|--------|
| Nome | Compartilhar [cinema](../../modelagem/lexicos/#cinema). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo compartilhar um [cinema](../../modelagem/lexicos/#cinema) para meus amigos e/ou familiares para mostrar que tenho interesse nesse [cinema](../../modelagem/lexicos/#cinema). |
| Critérios de Aceitação | -> Opção para compartilhar. <br/> -> Plataformas em que pode ser compartilhado o [cinema](../../modelagem/lexicos/#cinema). <br/>|

| ID | US21  |
|-----|--------|
| Nome | Favoritar [cinema](../../modelagem/lexicos/#cinema). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo favoritar um [cinema](../../modelagem/lexicos/#cinema) para adicioná-lo a minha lista de [cinemas](../../modelagem/lexicos/#cinema) favoritos e ter acesso mais fácil a ele.| 
| Critérios de Aceitação | -> Opção de favoritar [cinema](../../modelagem/lexicos/#cinema). <br/> |

### Feature 09 - [Sessões](../../modelagem/lexicos/#usuario)

| ID | US22  |
|-----|--------|
| Nome | [Sessões](../../modelagem/lexicos/#usuario) do [cinema](../../modelagem/lexicos/#cinema). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar as [sessões](../../modelagem/lexicos/#usuario) do [cinema](../../modelagem/lexicos/#cinema) escolhido para escolher qual [filme](../../modelagem/lexicos/#filme) assistir. |
| Critérios de Aceitação | -> Opção para filtrar [sessão](../../modelagem/lexicos/#usuario) por tipo de exibição. <br/> -> Opção para filtrar [sessões](../../modelagem/lexicos/#usuario) por dia da semana. <br/> |

| ID | US23  |
|-----|--------|
| Nome | [Sessões](../../modelagem/lexicos/#usuario) do [filme](../../modelagem/lexicos/#filme). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar as [sessões](../../modelagem/lexicos/#usuario) disponíveis do [filme](../../modelagem/lexicos/#filme) escolhido para que eu possa escolher quando e onde assistir. |
| Critérios de Aceitação | -> [Cinema](../../modelagem/lexicos/#cinema) e [sessões](../../modelagem/lexicos/#usuario) disponíveis nesse [cinema](../../modelagem/lexicos/#cinema). <br/> -> Opção para filtrar por tipo de exibição. <br/>-> Opção para filtrar por nome do [cinema](../../modelagem/lexicos/#cinema). <br/> -> Opção para filtrar por proximidade do [cinema](../../modelagem/lexicos/#cinema). <br/> |

| ID | US24  |
|-----|--------|
| Nome | Assentos da [sessão](../../modelagem/lexicos/#usuario). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar os assentos disponíveis na [sessão](../../modelagem/lexicos/#usuario) para que eu possa escolher onde sentar. |
| Critérios de Aceitação | -> Mapa de assentos. <br/> -> Assentos disponíveis. <br/> -> Assentos ocupados. <br/> -> Legenda. <br/>|

### Feature 10 - [Filmes](../../modelagem/lexicos/#filme)

| ID | US25  |
|-----|--------|
| Nome | Visualizar [filmes](../../modelagem/lexicos/#filme) em cartaz. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar [filmes](../../modelagem/lexicos/#filme) que estão em cartaz para que eu possa escolher algum [filme](../../modelagem/lexicos/#filme) para assistir. |
| Critérios de Aceitação | -> Listar todos os [filmes](../../modelagem/lexicos/#filme) em cartaz da cidade. <br/> |

| ID | US26  |
|-----|--------|
| Nome | Visualizar [filmes](../../modelagem/lexicos/#filme) em breve. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar [filmes](../../modelagem/lexicos/#filme) que em breve estarão nos [cinemas](../../modelagem/lexicos/#cinema) para que eu possa me programar para assistir a ele. |
| Critérios de Aceitação | -> Listar todos os [filmes](../../modelagem/lexicos/#filme) em breve da cidade. <br/> -> Data que os [filmes](../../modelagem/lexicos/#filme) entrarão em cartaz. <br/>|

| ID | US27  |
|-----|--------|
| Nome | Detalhes do [filme](../../modelagem/lexicos/#filme). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar as informações sobre o [filme](../../modelagem/lexicos/#filme) para decidir se quero assistir a ele ou não. |
| Critérios de Aceitação | -> Avaliação crítica do Roten Tomatoes. <br/> ->  Avaliação dos [usuários](../../modelagem/lexicos/#usuario) do Roten Tomatoes. <br/> -> Classificação indicativa. <br/> -> Duração do [filme](../../modelagem/lexicos/#filme). <br/> -> Data de estreia. <br/> -> Gênero do [filme](../../modelagem/lexicos/#filme). <br/> -> Nome original do [filme](../../modelagem/lexicos/#filme). <br/> -> Elenco. <br/> -> Sinopse. <br/> -> Direção. <br/> -> Distribuidor. <br/> -> País de origem. <br/>|

| ID | US28  |
|-----|--------|
| Nome | Ver trailer do [filme](../../modelagem/lexicos/#filme). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar o trailer do [filme](../../modelagem/lexicos/#filme) para descobrir do que se trata o [filme](../../modelagem/lexicos/#filme). |
| Critérios de Aceitação | -> Opção de reproduzir trailer. <br/>|

| ID | US29  |
|-----|--------|
| Nome | Disponibilizar trailer. |
| Descrição | Eu, como sistema, desejo disponibilizar trailer do [filme](../../modelagem/lexicos/#filme) do youtube para o aplicativo para que o [usuário](../../modelagem/lexicos/#usuario) consiga assistir a ele. |
| Critérios de Aceitação | -> Reproduzir trailer do [filme](../../modelagem/lexicos/#filme) vindo do youtube. <br/>|

### Feature 11 - [Ingresso](../../modelagem/lexicos/#ingresso)

| ID | US30  |
|-----|--------|
| Nome | Tipos de [ingressos](../../modelagem/lexicos/#ingresso) da [sessão](../../modelagem/lexicos/#usuario). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo escolher os tipos de [ingressos](../../modelagem/lexicos/#ingresso) da [sessão](../../modelagem/lexicos/#usuario) escolhida para comprá-los. |
| Critérios de Aceitação | -> Tipos de [ingressos](../../modelagem/lexicos/#ingresso) disponíveis. <br/> -> Campo input com informações de identificação de acordo com o tipo de [ingresso](../../modelagem/lexicos/#ingresso) escolhido. <br/>|

### Feature 12 - [Acompanhamentos](../../modelagem/lexicos/#acompanhamento)

| ID | US31  |
|-----|--------|
| Nome | Escolher [acompanhamentos](../../modelagem/lexicos/#acompanhamento). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo escolher [acompanhamentos](../../modelagem/lexicos/#acompanhamento) para que eu não precise enfrentar filas no [cinema](../../modelagem/lexicos/#cinema). |
| Critérios de Aceitação | -> [Acompanhamentos](../../modelagem/lexicos/#acompanhamento) disponíveis. <br/>|


### Feature 13 - Pagamento

| ID | US32  |
|-----|--------|
| Nome | Pagar os [ingressos](../../modelagem/lexicos/#ingresso). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo escolher forma de pagamento disponível para pagar os [ingressos](../../modelagem/lexicos/#ingresso) que quero comprar. |
| Critérios de Aceitação | -> Formas de pagamento disponíveis. <br/> -> Opção para aplicar código de desconto. <br/> -> Formulário com input para dados da forma de pagamento. <br/> -> Cartões salvos. <br/>|

| ID | US33  |
|-----|--------|
| Nome | Enviar mensagem sobre pagamento. |
| Descrição | Eu, como sistema, desejo enviar uma mensagem para o email do [usuário](../../modelagem/lexicos/#usuario) para informar que a compra de [ingresso](../../modelagem/lexicos/#ingresso) foi realizada.|
| Critérios de Aceitação | -> Sistema enviar mensagem via email do [usuário](../../modelagem/lexicos/#usuario). <br/> |

### Feature 14 - [Carrinho](../../modelagem/lexicos/#carrinho)

| ID | US34  |
|-----|--------|
| Nome | [Carrinho](../../modelagem/lexicos/#carrinho) com [ingresso](../../modelagem/lexicos/#ingresso)(s). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo ver quais [sessões](../../modelagem/lexicos/#usuario) coloquei no [carrinho](../../modelagem/lexicos/#carrinho) para que eu possa remover alguma, mudar os assentos, tipo de [ingresso](../../modelagem/lexicos/#ingresso), [acompanhamentos](../../modelagem/lexicos/#acompanhamento) e forma de pagamento. |
| Critérios de Aceitação | -> Opção para mudar assentos. <br/> -> Opção para remover [sessão](../../modelagem/lexicos/#usuario). <br/> -> Opção para mudar tipo de [ingresso](../../modelagem/lexicos/#ingresso). <br/> -> Opção para forma de pagamento. <br/> -> Opção para [acompanhamentos](../../modelagem/lexicos/#acompanhamento). <br/> -> Informação sobre retirada disponível de [ingresso](../../modelagem/lexicos/#ingresso). <br/> |


### Feature 15 - Noticia

| ID | US35  |
|-----|--------|
| Nome | Visualizar [[notícias](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar [[notícias](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia) sobre o mundo do [cinema](../../modelagem/lexicos/#cinema) para que eu possa ficar por dentro das novidades. |
| Critérios de Aceitação | -> Cards de [[notícias](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia). <br/>|

| ID | US36  |
|-----|--------|
| Nome | Ler [[notícia](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo ler a [[notícia](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia) para que eu possa entendê-la por completo. |
| Critérios de Aceitação | -> Contéudo da [[notícia](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia). <br/>|

| ID | US37  |
|-----|--------|
| Nome | Compartilhar [[notícia](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia). |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo compartilhar uma [[notícia](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia) para que eu possa enviá-la para meus amigos e/ou parentes. |
| Critérios de Aceitação | -> Opção de compartilhar [[notícia](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia). <br/> -> Plataformas em que pode ser compartilhada a [[notícia](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia). <br/>|


### Feature 16 - Destaques

| ID | US38  |
|-----|--------|
| Nome | Visualizar destaques. |
| Descrição | Eu, como [usuário](../../modelagem/lexicos/#usuario), desejo visualizar os destaques do aplicativo para que possa acompanhar a tendência do mundo do [cinema](../../modelagem/lexicos/#cinema). |
| Critérios de Aceitação | -> [[Notícias](../../modelagem/lexicos/#noticia)](../../modelagem/lexicos/#noticia) em alta. <br/> -> [Filmes](../../modelagem/lexicos/#filme) em alta. <br/> -> [Cinemas](../../modelagem/lexicos/#cinema) favoritos abertos. <br/> -> [Filmes](../../modelagem/lexicos/#filme) em breve. <br/> |


### Feature 17 - Anúncio

| ID | US39  |
|-----|--------|
| Nome | Anúncios. |
| Descrição | Eu, como sistema, desejo apresentar ao [usuário](../../modelagem/lexicos/#usuario) propagandas para que seja gerada receita e lucro para minha empresa. |
| Critérios de Aceitação | -> Anúncios localizados em pontos estratégicos. <br/>|



## 6. Referência

<p style="text-align: justify; text-indent: 20px">[1] Reinehr, S. <b>Engenharia de Requisitos</b>. Grupo A, 2020. 9786556900674. Disponível em: https://integrada.minhabiblioteca.com.br/#/books/9786556900674/. Acesso em: 2021 set. 06.</p>

