## 1. Versionamento

|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|26/08|Abertura do documento de Cenários|Carlos Eduardo e Vitor Lamego|
|1.1|26/08|Criação dos Cenários|Carlos Eduardo e Vitor Lamego|



## 2. Introdução
<p style="text-align: justify; text-indent: 20px">Dentro da Engenharia de Requisitos existe uma etapa fundamental designada para a Modelagem dos requisitos. Dentre as várias técnicas existentes, este documento irá abordar e aplicar uma técnica em específico: Cenários.</p>

<p style="text-align: justify; text-indent: 20px">A técnica de modelagem citada anteriormente consiste basicamente na descrição narrativa informal e concreta a respeito da interação entre um usuário e um sistema.[1] Sendo assim, nesse documento foram elaboras algumas descrições relacionadas a interação dos usuários do aplicativo Ingresso.com com o sistema em questão.</p>


## 3. Cenários:
<p style="text-align: justify; text-indent: 20px">Para a aplicação da técnica, o grupo optou pela criação do primeiro(C01) cenário como uma dinâmica geral do aplicativo, que aborda as funcionalidades e ações gerais, mas que ao longo do documento foram especificadas para extrair qualquer tipo de interação existente. A partir do segundo cenário (C02) foram descritas as interações mais específicas do software. Vejamos a seguir os resultados:</p>

### C01: Dinâmica do Ingresso.com

<center>

|Cenário 001||
|:----:|:----------|
|<b>Objetivo</b>| Descrever as regras do Ingresso.com | 
|<b>Contexto</b>| Abertura do aplicativo |
|<b>Atores</b>| Comprador/Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet |
|<b>Episódios</b>| 1. Usuário abre o aplicativo </br>2. Usuário ESCOLHE REGIÃO DO CINEMA</br>3. Usuário ESCOLHE CINEMA.</br>4. Usuário FAVORTIA CINEMA</br>5. Usuário CONSULTA FILMES EM CARTAZ</br>6. Usuário CONSULTA FILMES EM BREVE</br>7. Usuário ESCOLHE SESSÃO DO FILME</br>8. Usuário ESCOLHE ASSENTOS DA SESSÃO</br>9. Usuário ESCOLHE TIPO DE INGRESSO</br>10. Usuário CRIA CONTA</br>11. Usuário FAZ LOGIN</br>12. Usuário ESCOLHE FORMA DE PAGAMENTO</br>13. Usuário COMPRA INGRESSO</br>14. Usuário OLHA NOTÍCIAS</br>15. Usuário CONSULTA MEDIDAS DE PREVENÇÃO DO CINEMA|

</center>
<h6 align = "center">Tabela 1: Descrição das características do Cenário 01</h6>

### C02: Escolher região do cinema

<center>

|Cenário 002||
|:----:|:----------|
|<b>Objetivo</b>| Filtrar os cinemas pela região que o usuário se encontra, a fim de ter um serviço mais focado na sua área | 
|<b>Contexto</b>| Pré-condição: Aplicativo aberto, acesso à internet e smatphone com gps<br>Pós-condição: O usuário possui um serviço direcionado para onde ele se encontra |
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não libera o uso da localização pelo aplicativo Ingresso |
|<b>Episódios</b>| 1.Usuário acessa o aplicativo<br>2.Usuário clica no ícone de localização<br>3.Usuário escolhe a sua cidade ou atualiza a sua localização|

</center>
<h6 align = "center">Tabela 2: Descrição das características do Cenário 02</h6>

### C03: Escolher cinema

<center>

|Cenário 003||
|:----:|:----------|
|<b>Objetivo</b>| Visualizar informações específicas de um cinema desejado | 
|<b>Contexto</b>| Pré-condição: Região do cinema escolhida<br>Pós-condição: O usuário verifica as informações de um cinema em específico |
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Não existem cinemas disponíveis na região desejada |
|<b>Episódios</b>| 1. Usuário navega até a lista de cinemas<br>2. Usuário escolhe um cinema desejado|

</center>
<h6 align = "center">Tabela 3: Descrição das características do Cenário 03</h6>

### C04: Favoritar cinema

<center>

|Cenário 004||
|:----:|:----------|
|<b>Objetivo</b>| Criar uma lista de cinemas favoritos para os usuários que possuem conta | 
|<b>Contexto</b>| Pré-condição: Aplicativo aberto, acesso à internet e ter uma conta no aplicativo<br>Pós-condição: O usuário adiciona o cinema a sua lista de favoritos |
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não possui conta |
|<b>Episódios</b>| 1. Usuário navega até a lista de cinemas<br>2. Usuário escolhe um cinema desejado<br>3. Usuário clica no ícone de coração<br>4. Usuário faz login, caso não tenha feito anteriormente.<br>5. Cinema é adiciona à lista de favoritos|

</center>
<h6 align = "center">Tabela 4: Descrição das características do Cenário 04</h6>

### C05: Consultar filmes em cartaz

<center>

|Cenário 005||
|:----:|:----------|
|<b>Objetivo</b>| Usuário ter conhecimento do que está passando nos cinemas, para então saber se quer assistir ou não | 
|<b>Contexto</b>| Pré-condição: Aplicativo aberto, acesso à internet e região escolhida|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet |
|<b>Episódios</b>| 1. Usuário abre o aplicativo<br>2. Usuário clica na aba "Filmes" do menu de navegação<br> 3. Usuário seleciona filme do seu interesse|

</center>
<h6 align = "center">Tabela 5: Descrição das características do Cenário 05</h6>

### C06: Consultar filmes em breve

<center>

|Cenário 006||
|:----:|:----------|
|<b>Objetivo</b>| Usuário ter conhecimento de quais filmes chegarão em breve nos cinemas. | 
|<b>Contexto</b>| Pré-condição: Aplicativo aberto, acesso à internet e região escolhida|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Não ter filmes em breve |
|<b>Episódios</b>| 1. Usuário abre o aplicativo<br>2. Usuário clica na aba "Filmes" do menu de navegação<br> 3. Usuário seleciona a opção "Em Breve"<br>4. Usuário escolhe e consulta filme que deseja|

</center>
<h6 align = "center">Tabela 6: Descrição das características do Cenário 06</h6>

### C07: Escolher sessão do filme

<center>

|Cenário 007||
|:----:|:----------|
|<b>Objetivo</b>| Usuário escolher qual o filme ele quer assistir, assim como o cinema e o horário. | 
|<b>Contexto</b>| Pré-condição: Cinema escolhido<br>Pós-condição: Usuário é direcionado para a escolha dos assentos|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Não ter mais sessões disponíveis |
|<b>Episódios</b>| 1. Usuário abre o aplicativo<br>2. Usuário seleciona o filme ou cinema que deseja<br>3. Usuário escolhe o horário (sessão) que deseja|

</center>
<h6 align = "center">Tabela 7: Descrição das características do Cenário 07</h6>

### C08: Escolher assentos da sessão

<center>

|Cenário 008||
|:----:|:----------|
|<b>Objetivo</b>| Usuário escolher onde irá sentar para assistir o filme. | 
|<b>Contexto</b>| Pré-condição: Sessão escolhida<br>Pós-condição: Usuário é direcionado para a seleção do tipo de ingresso|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Não ter mais assento disponível |
|<b>Episódios</b>| 1.Sistema apresenta os assentos disponíveis<br>2. Usuário escolhe o(s) seu(s) assento(s) de acordo com o seu número de ingressos|

</center>
<h6 align = "center">Tabela 8: Descrição das características do Cenário 08</h6>

### C09: Escolher o tipo de ingresso

<center>

|Cenário 009||
|:----:|:----------|
|<b>Objetivo</b>| Usuário escolher qual o tipo de ingresso ele vai comprar, podendo utilizar benefícios de meia-entrada se assim ele puder. | 
|<b>Contexto</b>| Pré-condição: Assentos escolhidos<br>Pós-condição: Usuário é direcionado para a compra de comidas e snacks no cinema|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet|
|<b>Episódios</b>| 1. Sistema apresenta os tipos de ingresso disponíveis e seus respectivos valores<br>2. Usuário escolhe o(s) seu(s) tipo(s) de ingresso(s)<br>3. Se usuário escoher tipo meia, sistema pede mais informações para comprovação<br>4. Usuário preeenche suas informações para utilizar a meia entrada|

</center>
<h6 align = "center">Tabela 9: Descrição das características do Cenário 09</h6>

### C10: Escolher o que vai comer na sessão

<center>

|Cenário 010||
|:----:|:----------|
|<b>Objetivo</b>| Permitir que o usuário já compre a sua comida do cinema junto aos ingressos, evitando que ele enfrente mais filas | 
|<b>Contexto</b>| Pré-condição: Tipo de ingresso escolhido<br>Pós-condição: Usuário é direcionado para o pagamento do que foi escolhido|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não deseja comprar a comida do cinema|
|<b>Episódios</b>| 1. Sistema apresenta as opções disponíveis<br>2. Se o usuário desejar, escolhe a quantidade de cada opção que deseja<br>3. Se o usuário não desejar, pula para a próxima etapa|

</center>
<h6 align = "center">Tabela 10: Descrição das características do Cenário 10</h6>

### C11: Realizar pagamento como cliente do Ingresso.com

<center>

|Cenário 011||
|:----:|:----------|
|<b>Objetivo</b>| Permitir que o usuário escolha alguma forma de pagamento já salva em sua conta, ou que fique salvo o histórico de compra, pelo menos. | 
|<b>Contexto</b>| Pré-condição: Tipo de ingresso e comida para a sessão escolhidos e ter uma conta no aplicativo<br>Pós-condição: Aprovar o pagamento do ingresso|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não possui cartão válido e não possui conta PayPal|
|<b>Episódios</b>| 1. Se não estiver logado ainda, usuário insere suas informações de login<br>2. Usuário escolhe qual a forma de pagamento deseja utilizar<br>3. Se os dados da forma de pagamento não estão salvas, usuário insere os dados<br>4. Se o usuário possuir, insere código de desconto para a compra<br>5. Usuário prossegue para a verificação do pagamento<br>6. Se aprovado, usuário recebe os ingressos no endereço de email cadastrado|

</center>
<h6 align = "center">Tabela 11: Descrição das características do Cenário 11</h6>

### C12: Realizar pagamento sem ser cliente do Ingresso.com

<center>

|Cenário 012||
|:----:|:----------|
|<b>Objetivo</b>| Permitir que usuários que não possuem conta no aplicativo também comprem ingressos | 
|<b>Contexto</b>| Pré-condição: Tipo de ingresso e comida para a sessão escolhidos e ter um email e CPF válido para a compra<br>Pós-condição: Aprovar o pagamento do ingresso|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não possui cartão válido e não possui conta PayPal|
|<b>Episódios</b>| 1. Usuário informa o seu email<br>2. Usuário confirma o email inserido<br>3. Usuário informa o seu CPF<br>4. Usuário informa as informações de pagamento<br>5. Usuário prossegue para a verificação do pagamento<br>6. Se aprovado, usuário recebe os ingressos no endereço de email informado.|

</center>
<h6 align = "center">Tabela 12: Descrição das características do Cenário 12</h6>

### C13: Criar conta sem integração com outro aplicativo

<center>

|Cenário 013||
|:----:|:----------|
|<b>Objetivo</b>| Permitir que o usuário crie uma conta para salvar as suas compras e formas de pagamento, evitando de ficar inserindo em todas as compras | 
|<b>Contexto</b>| Pré-condição: Possuir um email válido e o aplicativo<br>Pós-condição: Usuário é logado no aplicativo|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não confirma o email|
|<b>Episódios</b>| 1. Usuário clica no ícone de perfil na tela incial<br>2. Usuário clica em "Entrar"<br>3. Usuário clica em "CRIAR CONTA"<br>4. Usuário informa o seu email ou CPF<br>5. Usuário cria uma senha<br>6. Usuário clica em "ENTRAR" |

</center>
<h6 align = "center">Tabela 13: Descrição das características do Cenário 13</h6>

### C14: Criar conta a partir do Facebook

<center>

|Cenário 014||
|:----:|:----------|
|<b>Objetivo</b>| Permitir que usuários que possuam conta no Facebook façam login no aplicativo a partir dessa mesma conta | 
|<b>Contexto</b>| Pré-condição: Possuir uma conta válida no Facebook<br>Pós-condição: Usuário é logado no aplicativo|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não possui conta válida no Facebook|
|<b>Episódios</b>| 1. Usuário clica no ícone de perfil na tela incial<br>2. Usuário clica em "Entrar"<br>3. Usuário clica em "CRIAR CONTA"<br>4. Usuário clica em "Entrar com o Facebook"<br>5. Usuário insere o seu email cadastrado no Facebook<br>6. Usuário informa a sua senha cadastrada no Facebook |

</center>
<h6 align = "center">Tabela 14: Descrição das características do Cenário 14</h6>

### C15: Criar conta a partir do Google

<center>

|Cenário 015||
|:----:|:----------|
|<b>Objetivo</b>| Permitir que usuários que possuam conta na Google façam login no aplicativo a partir dessa mesma conta | 
|<b>Contexto</b>| Pré-condição: Possuir uma conta Google válida<br>Pós-condição: Usuário é logado no aplicativo|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não possui conta válida na Google|
|<b>Episódios</b>| 1. Usuário clica no ícone de perfil na tela incial<br>2. Usuário clica em "Entrar"<br>3. Usuário clica em "CRIAR CONTA"<br>4. Usuário clica em "Entrar com Google"<br>5. Usuário insere o seu email cadastrado na Google<br>6. Usuário informa a sua senha cadastrada na Google |

</center>
<h6 align = "center">Tabela 15: Descrição das características do Cenário 15</h6>

### C16: Fazer Login

<center>

|Cenário 016||
|:----:|:----------|
|<b>Objetivo</b>| Permitir que o usuário esteja logado na aplicação | 
|<b>Contexto</b>| Pré-condição: Possuir uma conta no aplicativo<br>Pós-condição: Usuário é logado no aplicativo|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não possui mais uma conta válida|
|<b>Episódios</b>| 1. Usuário clica no ícone de perfil na página principal<br>2. Usuário clica em "Entrar"<br>3. Usuário insere o seu CPF ou e-mail cadastrado<br>4. Usuário informa a sua senha cadastrada<br>5. Usuário clica no botão "ENTRAR"|

</center>
<h6 align = "center">Tabela 16: Descrição das características do Cenário 16</h6>

### C17: Ver Notícias

<center>

|Cenário 017||
|:----:|:----------|
|<b>Objetivo</b>| Usuário poder ler as notícias mais recentes disponibilizadas pelo aplicativo | 
|<b>Contexto</b>| Pré-condição: Aplicativo aberto e acesso à internet|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet|
|<b>Episódios</b>| 1. Usuário clica na aba "Notícias" no menu de navegação<br>2. Usuário seleciona a notícia que deseja ler|

</center>
<h6 align = "center">Tabela 17: Descrição das características do Cenário 17</h6>

### C18: Ver Prevenções

<center>

|Cenário 018||
|:----:|:----------|
|<b>Objetivo</b>| Usuário poder se informar sobre quais medidas de seguranças estão sendo realizadas por cada cinema da região devido à pandemia ocasionada pelo vírus Sars-CoV-2 | 
|<b>Contexto</b>| Pré-condição: Aplicativo aberto e acesso à internet|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet|
|<b>Episódios</b>| 1. Usuário clica na aba "Prevenções" no menu de navegação<br>2. Usuário pesquisa por cinema desejado<br>3. Usuário seleciona o cinema desejado apresentado na lista|

</center>
<h6 align = "center">Tabela 18: Descrição das características do Cenário 18</h6>

### C19: Ver Ingressos comprados

<center>

|Cenário 019||
|:----:|:----------|
|<b>Objetivo</b>| Usuário visualiza os seus ingressos comprados | 
|<b>Contexto</b>| Pré-condição: Aplicativo aberto, acesso à internet e conta no aplicativo Ingresso|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br>3. Usuário não possuir conta no app|
|<b>Episódios</b>| 1. Usuário clica no ícone de ingresso na tela principal<br>2. Usuário, se já não estiver logado, insere o seu CPF e a sua senha<br>3. Usuário visualiza os seus ingressos disponíveis|

</center>
<h6 align = "center">Tabela 19: Descrição das características do Cenário 19</h6>

### C20: Visualizar detalhes de um filme

<center>

|Cenário 020||
|:----:|:----------|
|<b>Objetivo</b>| Usuário poder visualizar detalhes como, duração, sinopse, diretor, país de origem, e algumas outras informações de algum filme em específico. | 
|<b>Contexto</b>| Pré-condição: Aplicativo aberto, acesso à internet|
|<b>Atores</b>| Usuário | 
|<b>Recursos</b>| Smartphone, internet e o aplicativo | 
|<b>Exceção</b>| 1. Smartphone para de funcionar</br>2. Sem acesso à internet<br> 3. Distribuidor não oferecer os detalhes do filme|
|<b>Episódios</b>| 1. Usuário escolhe o filme desejado<br>2. Usuário clica na aba "Detalhes"|

</center>
<h6 align = "center">Tabela 20: Descrição das características do Cenário 20</h6>

## 4. Referências
<p style="text-align: justify;">[1] DevMedia. <b>Artigo Engenharia de Software 16 - Cenários e Casos de Uso: Fundamentos e Conceitos</b>. 2009. Disponível em: <a href="https://www.devmedia.com.br/artigo-engenharia-de-software-16-cenarios-e-casos-de-uso-fundamentos-e-conceitos/14186" target="_blank">DevMedia</a>. Acesso em: 26 de agosto de 2021</p>
