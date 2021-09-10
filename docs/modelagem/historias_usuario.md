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
| E02 - Perfil | Engloba toda a parte de informações de usuário e configurações da aplicação. | -> Perfil <br/> -> Atendimento <br/> -> Sobre o App <br/> | 
| E03 - Cinemas | Engloba toda parte de cinemas | -> Localização <br/> -> Cinemas <br/> -> Sessões <br/> |
| E04 - Filmes | Engloba toda parte de filmes | -> Filmes <br/> |
| E05 - Compra | Engloba toda a parte de compra de ingressos | -> Ingresso <br/> -> Acompanhamentos <br/> -> Pagamento <br/> -> Carrinho <br/>|
| E06 - Engajamento | Engloba toda a parte de manter o usuário engajado.  | -> Noticia <br/> -> Destaques <br/> |
| E07 - Lucro | Engloba uma parte do lucro do aplicativo. | -> Anúncios. <br/>|

## 5. Features

<b>Legenda:</b>

- US: Histórias de Usuário.

### Feature 01 - Cadastro

| ID | US01  |
|-----|--------|
| Nome | Criar conta. |
| Descrição | Eu, como usuário, desejo criar uma conta para eu ter acesso as funcionalidades completas do aplicativo. |
| Critérios de Aceitação | O formulário de cadastramento deve conter os seguintes campos: <br/> -> Nome <br/> -> E-mail <br/> -> Senha <br/> -> Data de Aniversário <br/> -> Gênero <br/> -> Cpf <br/> -> DDD e telefone <br/> -> Endereço composto |

| ID | US02 |
|-----|--------|
| Nome | Validação do formulário de cadastramento. |
| Descrição | Eu, como sistema, desejo realizar a validadação dos dados preenchidos no formulário de cadastramento para garantir que são reais. |
| Critérios de Aceitação | Deve conter as seguintes opções: <br/> <b> Nome </b> <br/> -> Apenas caracteres do alfabeto.<br/> <b> E-mail </b> <br/>-> Ser email válido. <br/> <b> Senha </b> <br/>-> Possuir ao menos 8 digitos. <br/>  <b> Data de Aniversário </b><br/> -> Possuir dia entre 1 e 31  <br/> ->  Possuir mês entre 01 e 12<br/> <b> Cpf </b> <br/>-> Cpf válido <br/>  <b> DDD e telefone </b> <br/>-> telefone válido <br/> <b> Endereço composto </b> <br/> -> Endereço existente <br/>|

### Feature 02 - Login

| ID | US03 |
|-----|--------|
| Nome | Fazer login |
| Descrição | Eu, como usuário, desejo fazer login para entrar na minha conta e aproveitar das funcionalidades do ingresso.com |
| Critérios de Aceitação | -> Input de email e senha <br/> -> Opção para logar com Facebook <br/> -> Opção para logar com Google <br/> -> Opção para escolher se quer receber novidades e mensagens por email.|

| ID | US04 |
|-----|--------|
| Nome | Validação do formulário de login. |
| Descrição | Eu, como sistema, desejo realizar a validadação dos dados preenchidos no formulário de login para que possa autenticá-lo. |
| Critérios de Aceitação | Deve conter as seguintes opções: <br/> <b> E-mail </b> <br/>-> Ser email válido. <br/> <b> Senha </b> <br/>-> Possuir ao menos 8 digitos. <br/> |

| ID | US05 |
|-----|--------|
| Nome | Esqueceu senha. |
| Descrição | Eu, como usuário, desejo redefinir a senha da minha conta que esqueci para fazer login. |
| Critérios de Aceitação | -> Opção "esqueci a senha" <br/> -> Campo input para que o usuário insira email. <br/> |

| ID | US06 |
|-----|--------|
| Nome | Enviar email esqueceu senha. |
| Descrição | Eu, como sistema, desejo enviar email para que o usuário redefina a senha. |
| Critérios de Aceitação | -> Mensagem com informação de email enviado. <br/> |

### Feature 03 - Logout

| ID | US07  |
|-----|--------|
| Nome | Fazer logout. |
| Descrição | Eu, como usuário, desejo realizar logout do aplicativo para que minha conta não esteja mais vinculada com o app. |
| Critérios de Aceitação | -> Existir opção para sair da conta no app.|

### Feature 04 - Perfil

| ID | US08  |
|-----|--------|
| Nome | Alterar senha. |
| Descrição | Eu, como usuário, desejo alterar a senha da minha conta para uma de minha preferência. |
| Critérios de Aceitação | -> Campo input de senha atual <br/> -> Campo input de nova senha <br/> -> Validar senha com ao menos 8 caracteres <br/> -> Campo para confirmar senha <br/>|

| ID | US09  |
|-----|--------|
| Nome | Alterar dados pessoais. |
| Descrição | Eu, como usuário, desejo alterar os dados pessoais da minha conta caso algum dado tenha mudado. |
| Critérios de Aceitação | Deve conter os seguintes campos: <br/> -> Nome <br/> -> Senha <br/> -> Data de Aniversário <br/> -> Gênero <br/> -> DDD e telefone <br/> -> Endereço composto <br/> Dados válidados de acordo com a [**US02**](#feature-01-cadastro)|

| ID | US10 |
|-----|--------|
| Nome | Vizualizar cartões salvos. |
| Descrição | Eu, como usuário, desejo visualizar cartões salvos para que eu possa excluir algum ou alterá-lo. |
| Critérios de Aceitação | -> Todos cartões salvos. <br/> -> Opção para alterar. <br/> -> Opção para excluir cartão salvo. <br/>|

| ID | US11  |
|-----|--------|
| Nome | Visualizar pedidos. |
| Descrição | Eu, como usuário, desejo visualizar meu pedidos realizados para que possa acompanhar quais ingressos e sessões já assisti.|
| Critérios de Aceitação | -> Apresentar pedidos ordenados pelo mais recente. <br/>|

### Feature 05 - Atendimento

| ID | US12  |
|-----|--------|
| Nome | Solicitar atendimento. |
| Descrição | Eu, como usuário, desejo esclarecer dúvidas e/ou enviar solicitações de atendimento para o ingresso.com para compreender melhor o aplicativo. |
| Critérios de Aceitação | -> Opção de atendimento. <br/> -> Campo para pesquisar dúvida. <br/> -> Campo de seleção para opção de contato. <br/> -> Formulário com input para email, assunto, descrição, motivo do contato, cpf e celular. <br/> -> Opção de anexar arquivos. <br/>|

### Feature 06 - Sobre o App

| ID | US13  |
|-----|--------|
| Nome | Informações do app. |
| Descrição | Eu, como usuário, desejo visualizar informações sobre o aplicativo para saber qual a versão que está instalada em meu smartphone. |
| Critérios de Aceitação | -> Informalções sobre o smartphone. <br/> -> Informação sobre a versão do app. <br/>|

### Feature 07 - Localização

| ID | US14  |
|-----|--------|
| Nome | Adicionar localização. |
| Descrição | Eu, como usuário, desejo adicionar minha localização ou escolher a cidade para que eu possa ver os cinemas da minha região.  |
| Critérios de Aceitação | -> Opção para atualizar localização. <br/> -> Opção para buscar cidade. <br/> -> Lista de cidades mais acessadas. <br/> -> Lista de cidades ordenadas por estado. <br/>|

| ID | US15  |
|-----|--------|
| Nome | Alterar localização. |
| Descrição | Eu, como usuário, desejo alterar a localização ou cidade para que eu possa ver os cinemas da cidade em que estou.|
| Critérios de Aceitação | -> Critérios da [**US14**](#feature-07-localizaçao)|

### Feature 08 - Cinemas

| ID | US16  |
|-----|--------|
| Nome | Visualizar cinemas. |
| Descrição | Eu, como usuário, desejo visualizar cinemas da minha cidade para que eu possa escolher algum para ir. |
| Critérios de Aceitação | -> Opção para ordenar por nome. <br/> -> Opção para ordenar por proximidade. <br/> -> Opção para visualizar cinemas fechados. <br/> -> Opção para visualizar cinemas abertos. <br/> -> Listar cinemas favoritos. <br/> |

| ID | US17  |
|-----|--------|
| Nome | Pesquisar cinemas. |
| Descrição | Eu, como usuário, desejo pesquisar cinemas para ver se está aberto ou se vende ingressos pelo app. |
| Critérios de Aceitação | -> Campo input para busca. <br/> |

| ID | US18  |
|-----|--------|
| Nome | Sobre o cinema. |
| Descrição | Eu, como usuário, desejo visualizar informações sobre o cinema para que eu possa saber como chegar nele e entrar em contato. |
| Critérios de Aceitação | -> Informação sobre contato. <br/> -> Localização do cinema. <br/> -> Tipo de retirada de ingresso. <br/> |

| ID | US19  |
|-----|--------|
| Nome | Prevenções do cinema. |
| Descrição | Eu, como usuário, desejo visualizar as medidas preventivas adotadas pelo cinema para que eu possa me previnir melhor. |
| Critérios de Aceitação | -> Informações sobre as prevenções. <br/> |

| ID | US20  |
|-----|--------|
| Nome | Compartilhar cinema. |
| Descrição | Eu, como usuário, desejo compartilhar um cinema para meus amigos e/ou familiares para mostrar que tenho interesse nesse cinema. |
| Critérios de Aceitação | -> Opção para compartilhar. <br/> -> Plataformas em que pode ser compartilhado o cinema. <br/>|

| ID | US21  |
|-----|--------|
| Nome | Favoritar cinema. |
| Descrição | Eu, como usuário, desejo favoritar um cinema para adicioná-lo a minha lista de cinemas favoritos e ter acesso mais fácil a ele.| 
| Critérios de Aceitação | -> Opção de favoritar cinema. <br/> |

### Feature 09 - Sessões

| ID | US22  |
|-----|--------|
| Nome | Sessões do cinema. |
| Descrição | Eu, como usuário, desejo visualizar as sessões do cinema escolhido para escolher qual filme assistir. |
| Critérios de Aceitação | -> Opção para filtrar sessão por tipo de exibição. <br/> -> Opção para filtrar sessões por dia da semana. <br/> |

| ID | US23  |
|-----|--------|
| Nome | Sessões do filme. |
| Descrição | Eu, como usuário, desejo visualizar as sessões disponíveis do filme escolhido para que eu possa escolher quando e onde assistir. |
| Critérios de Aceitação | -> Cinema e sessões disponíveis nesse cinema. <br/> -> Opção para filtrar por tipo de exibição. <br/>-> Opção para filtrar por nome do cinema. <br/> -> Opção para filtrar por proximidade do cinema. <br/> |

| ID | US24  |
|-----|--------|
| Nome | Assentos da sessão. |
| Descrição | Eu, como usuário, desejo visualizar os assentos disponíveis na sessão para que eu possa escolher onde sentar. |
| Critérios de Aceitação | -> Mapa de assentos. <br/> -> Assentos disponíveis. <br/> -> Assentos ocupados. <br/> -> Legenda. <br/>|

### Feature 10 - Filmes

| ID | US25  |
|-----|--------|
| Nome | Visualizar filmes em cartaz. |
| Descrição | Eu, como usuário, desejo visualizar filmes que estão em cartaz para que eu possa escolher algum filme para assistir. |
| Critérios de Aceitação | -> Listar todos os filmes em cartaz da cidade. <br/> |

| ID | US26  |
|-----|--------|
| Nome | Visualizar filmes em breve. |
| Descrição | Eu, como usuário, desejo visualizar filmes que em breve estarão nos cinemas para que eu possa me programar para assistir a ele. |
| Critérios de Aceitação | -> Listar todos os filmes em breve da cidade. <br/> -> Data que os filmes entrarão em cartaz. <br/>|

| ID | US27  |
|-----|--------|
| Nome | Detalhes do filme. |
| Descrição | Eu, como usuário, desejo visualizar as informações sobre o filme para decidir se quero assistir a ele ou não. |
| Critérios de Aceitação | -> Avaliação crítica do Roten Tomatoes. <br/> ->  Avaliação dos usuários do Roten Tomatoes. <br/> -> Classificação indicativa. <br/> -> Duração do filme. <br/> -> Data de estreia. <br/> -> Gênero do filme. <br/> -> Nome original do filme. <br/> -> Elenco. <br/> -> Sinopse. <br/> -> Direção. <br/> -> Distribuidor. <br/> -> País de origem. <br/>|

| ID | US28  |
|-----|--------|
| Nome | Ver trailer do filme. |
| Descrição | Eu, como usuário, desejo visualizar o trailer do filme para descobrir do que se trata o filme. |
| Critérios de Aceitação | -> Opção de reproduzir trailer. <br/>|

| ID | US29  |
|-----|--------|
| Nome | Disponibilizar trailer. |
| Descrição | Eu, como sistema, desejo disponibilizar trailer do filme do youtube para o aplicativo para que o usuário consiga assistir a ele. |
| Critérios de Aceitação | -> Reproduzir trailer do filme vindo do youtube. <br/>|

### Feature 11 - Ingresso

| ID | US30  |
|-----|--------|
| Nome | Tipos de ingressos da sessão. |
| Descrição | Eu, como usuário, desejo escolher os tipos de ingressos da sessão escolhida para comprá-los. |
| Critérios de Aceitação | -> Tipos de ingressos disponíveis. <br/> -> Campo input com informações de identificação de acordo com o tipo de ingresso escolhido. <br/>|

### Feature 12 - Acompanhamentos

| ID | US31  |
|-----|--------|
| Nome | Escolher acompanhamentos. |
| Descrição | Eu, como usuário, desejo escolher acompanhamentos para que eu não precise enfrentar filas no cinema. |
| Critérios de Aceitação | -> Acompanhamentos disponíveis. <br/>|


### Feature 13 - Pagamento

| ID | US32  |
|-----|--------|
| Nome | Pagar os ingressos. |
| Descrição | Eu, como usuário, desejo escolher forma de pagamento disponível para pagar os ingressos que quero comprar. |
| Critérios de Aceitação | -> Formas de pagamento disponíveis. <br/> -> Opção para aplicar código de desconto. <br/> -> Formulário com input para dados da forma de pagamento. <br/> -> Cartões salvos. <br/>|

| ID | US33  |
|-----|--------|
| Nome | Enviar mensagem sobre pagamento. |
| Descrição | Eu, como sistema, desejo enviar uma mensagem para o email do usuário para informar que a compra de ingresso foi realizada.|
| Critérios de Aceitação | -> Sistema enviar mensagem via email do usuário. <br/> |

### Feature 14 - Carrinho

| ID | US34  |
|-----|--------|
| Nome | Carrinho com ingresso(s). |
| Descrição | Eu, como usuário, desejo ver quais sessões coloquei no carrinho para que eu possa remover alguma, mudar os assentos, tipo de ingresso, acompanhamentos e forma de pagamento. |
| Critérios de Aceitação | -> Opção para mudar assentos. <br/> -> Opção para remover sessão. <br/> -> Opção para mudar tipo de ingresso. <br/> -> Opção para forma de pagamento. <br/> -> Opção para acompanhamentos. <br/> -> Informação sobre retirada disponível de ingresso. <br/> |


### Feature 15 - Noticia

| ID | US35  |
|-----|--------|
| Nome | Visualizar notícias. |
| Descrição | Eu, como usuário, desejo visualizar notícias sobre o mundo do cinema para que eu possa ficar por dentro das novidades. |
| Critérios de Aceitação | -> Cards de notícias. <br/>|

| ID | US36  |
|-----|--------|
| Nome | Ler notícia. |
| Descrição | Eu, como usuário, desejo ler a notícia para que eu possa entendê-la por completo. |
| Critérios de Aceitação | -> Contéudo da notícia. <br/>|

| ID | US37  |
|-----|--------|
| Nome | Compartilhar notícia. |
| Descrição | Eu, como usuário, desejo compartilhar uma notícia para que eu possa enviá-la para meus amigos e/ou parentes. |
| Critérios de Aceitação | -> Opção de compartilhar notícia. <br/> -> Plataformas em que pode ser compartilhada a notícia. <br/>|


### Feature 16 - Destaques

| ID | US38  |
|-----|--------|
| Nome | Visualizar destaques. |
| Descrição | Eu, como usuário, desejo visualizar os destaques do aplicativo para que possa acompanhar a tendência do mundo do cinema. |
| Critérios de Aceitação | -> Notícias em alta. <br/> -> Filmes em alta. <br/> -> Cinemas favoritos abertos. <br/> -> Filmes em breve. <br/> |


### Feature 17 - Anúncio

| ID | US39  |
|-----|--------|
| Nome | Anúncios. |
| Descrição | Eu, como sistema, desejo apresentar ao usuário propagandas para que seja gerada receita e lucro para minha empresa. |
| Critérios de Aceitação | -> Anúncios localizados em pontos estratégicos. <br/>|



## 6. Referência

<p style="text-align: justify; text-indent: 20px">[1] Reinehr, S. <b>Engenharia de Requisitos</b>. Grupo A, 2020. 9786556900674. Disponível em: https://integrada.minhabiblioteca.com.br/#/books/9786556900674/. Acesso em: 2021 set. 06.</p>

