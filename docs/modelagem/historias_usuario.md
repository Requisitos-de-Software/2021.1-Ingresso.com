## 1. Versionamento

| Versão | Data  | Descrição             | Autor(es)       |
| ------ | ----- | --------------------- | --------------- |
| 1.0    | 06/09 | Abertura do documento | Carlos |


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

#### Legenda:
- E: Épico.

| Épico | Descrição | Features |
| ------| --------- | -------- |
| E01 - Cadastro e Autenticação | Engloba toda parte de cadastramento, login e logout | -> Cadastro <br/> -> Login <br/> -> Logout |
| E02 - Perfil | Engloba toda a parte de informações de usuário e configurações da aplicação. | -> Perfil <br/> -> Cartões Salvos <br/> -> Atendimento <br/> -> Sobre o App | 
| E03 - Cinemas | Engloba toda parte de cinemas | -> Localização <br/> -> Cinemas <br/> -> Sessões <br/> |
| E04 - Filmes | Engloba toda parte de filmes | -> Filmes <br/> |
| E05 - Noticias | Engloba toda parte de notícias | -> Noticia <br/>  |
| E06 - Compra | Engloba toda a parte de compra de ingressos | -> Ingresso <br/> -> Pagamento <br/> |

## 5. Features

#### Legenda:
- US: Histórias de Usuário.

### Feature 01 - Cadastro

| ID | US01  |
|-----|--------|
| Nome | Formulário para cadastramento. |
| Descrição | Eu, como desenvolvedor, desejo elaborar um formulário para que o usuário preencha com suas informações pessoais para que seja possível efetuar o cadastro dele na base de dados. |
| Critérios de Aceitação | Deve conter os seguintes campos: <br/> -> Nome <br/> -> E-mail <br/> -> Senha <br/> -> Data de Aniversário <br/> -> Gênero <br/> -> Cpf <br/> -> DDD e telefone <br/> -> Endereço composto |

| ID | US02 |
|-----|--------|
| Nome | Validação do formulário de cadastramento. |
| Descrição | Eu, como desenvolvedor, desejo realizar a validadação dos dados preenchidos no formulário de cadastramento para garantir que são reais. |
| Critérios de Aceitação | Deve conter as seguintes opções: <br/> <b> Nome </b> <br/> -> Apenas caracteres do alfabeto.<br/> <b> E-mail </b> <br/>-> Ser email válido. <br/> <b> Senha </b> <br/>-> Possuir ao menos 8 digitos. <br/>  <b> Data de Aniversário </b><br/> -> Possuir dia entre 1 e 31  <br/> ->  Possuir mês entre 01 e 12<br/> <b> Cpf </b> <br/>-> Cpf válido <br/>  <b> DDD e telefone </b> <br/>-> telefone válido <br/> <b> Endereço composto </b> <br/> -> Endereço existente <br/>|

## 5. Referência

<p style="text-align: justify; text-indent: 20px">[1] Reinehr, S. <b>Engenharia de Requisitos</b>. Grupo A, 2020. 9786556900674. Disponível em: https://integrada.minhabiblioteca.com.br/#/books/9786556900674/. Acesso em: 2021 set. 06.</p>

