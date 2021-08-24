## 1. Versionamento

|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|23/08|Criação do documento|João Pedro e Victor Lima|
|1.1|23/08|Adição da introdução e do Diagrama de Casos de Uso|João Pedro e Victor Lima|
|1.2|24/08|Adição das tabelas 6 a 10 de especialização|João Pedro|

## 2. Introdução
<p style="text-align: justify; text-indent: 20px"> Difersas são as formas de se modelar os requisitos elicitados de um sistema. Entre essas diversas maneiras se encontra a técnica de <b>Casos de Uso</b>, utilizada especificamente para os requisitos funcionais do software. Nesse diagrama, segundo Andrey	(2007, pág. 15)[1], são representados um conjunto de ações que um usuário pode realizar em um sistema, bem como, relacionamentos entre ator e caso de uso, e entre caso de uso e caso de uso.</p>
<p style="text-align: justify; text-indent: 20px"> Entretanto, apenas a utilização do diagrama pode deixar pontos em aberto, por isso, em conjunto com essa metodologia, se faz a utilização da <b>Especialização dos Casos de Uso</b>. Nessa especialização, ainda conforme Andrey [1], o diagrama de casos de uso será complementado buscando descrever os comportamentos dos casos de uso.</p>

## 3. Diagrama de Casos de Uso
![UseCases](../assets/modelagem/use_case.png)
<h6 align = "center">Figura 1: Casos de Uso do aplicativo Ingresso.com.</h6>
<h6 align = "center">Fonte: Autores</h6>

## 4. Especificação dos Casos de Uso
### 4.1 UC01 Login
|UC01|Informações|
|--|--|
|Descrição|
|Ator|
|Pré-condições|
|Ação|
|Fluxo Principal|
|Fluxo Alternativo|
|Pós-condições|
<h6 align = "center">Tabela 1: Tabela de especialização do login.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.2 UC02 Cadastro 
|UC02|Informações|
|--|--|
|Descrição|
|Ator|
|Pré-condições|
|Ação|
|Fluxo Principal|
|Fluxo Alternativo|
|Pós-condições|
<h6 align = "center">Tabela 2: Tabela de especialização do cadastro.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.3 UC03 Editar Conta 
|UC03|Informações|
|--|--|
|Descrição|
|Ator|
|Pré-condições|
|Ação|
|Fluxo Principal|
|Fluxo Alternativo|
|Pós-condições|
<h6 align = "center">Tabela 3: Tabela de especialização de editar a conta.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.4 UC04 Selecionar Região 
|UC04|Informações|
|--|--|
|Descrição|
|Ator|
|Pré-condições|
|Ação|
|Fluxo Principal|
|Fluxo Alternativo|
|Pós-condições|
<h6 align = "center">Tabela 4: Tabela de especialização de selecionar a região.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.5 UC05 Ver Notícias
|UC05|Informações|
|--|--|
|Descrição|
|Ator|
|Pré-condições|
|Ação|
|Fluxo Principal|
|Fluxo Alternativo|
|Pós-condições|
<h6 align = "center">Tabela 5: Tabela de especialização da visualização de notícias.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.6 UC06 Ver Filmes em Cartaz
|UC06|Informações|
|--|--|
|Descrição|O usuário deve visualizar os filmes em cartaz|
|Ator|Usuário|
|Pré-condições|Acesso à internet|
|Ação|O usuário ver os filmes em cartaz|
|Fluxo Principal|<b>FP01</b>: Fluxo de acessar filmes em cartaz pelo menu inferior<br/>1. O ator entra no aplicativo<br/>2. O sistema exibe 5 funcionalidades pricipais de acesso<br/>3. O ator clica em "Filmes"<br/>4. O sistema mostra a opção "Em Cartaz" ou "Em Breve"<br/>5. O ator seleciona a opção "Em Cartaz"|
|Fluxo Alternativo|<b>FA01</b>: Fluxo de acessar filmes em alta no menu principal<br/>1. O ator entra no aplicativo<br/>2. O sistema exibe no menu principal os filmes em alta<br/>3. O ator seleciona essa opção<br/>4. O ator é redirecionado para a aba de filmes em cartaz|
|Pós-condições|O ator poderá visualizar todos os filmes em cartaz em sua região|
<h6 align = "center">Tabela 6: Tabela de especialização da visualização dos filmes em cartaz.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.7 UC07 Ver cinemas
|UC07|Informações|
|--|--|
|Descrição|O usuário deve visualizar os cinemas em sua região|
|Ator|Usuário|
|Pré-condições|Acesso à internet e acesso à localização|
|Ação|O usuário ver os cinemas|
|Fluxo Principal|<b>FP01</b>: Fluxo de acessar cinemas pelo menu inferior<br/>1. O ator entra no aplicativo<br/>2. O sistema exibe 5 funcionalidades pricipais de acesso<br/>3. O ator clica em "Cinemas"<br/>4. O ator seleciona o cinema de sua escolha|
|Fluxo Alternativo|<b>FA01</b>: Fluxo de acessar um cinema pelo filme em cartaz<br/>1. O ator entra no aplicativo<br/>2. O ator acessa a funcionalidade "Filmes"<br/>3. O ator escolhe a opção "Em Cartaz"<br/>4. O ator seleciona um filme de sua escolha<br/>5. O sistema exibe informações de sessões em diversos cinemas<br/>6. O ator seleciona um cinema de sua escolha<br/><br/><b>FA02</b>: Fluxo de acessar um cinema pelo menu principal<br/>1. o ator entra no aplicativo<br/>2. O sistema exibe em seu menu principal a opção "Cinemas Abertos Próximos de Você"<br/>3. O usuário seleciona essa opção<br/>4. O sistema redireciona para a aba "Cinemas"|
|Pós-condições|O ator poderá visualizar informações do cinema, bem como, cinemas em sua região|
<h6 align = "center">Tabela 7: Tabela de especialização da visualização dos cinemas.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.8 UC08 Ver Horários
|UC08|Informações|
|--|--|
|Descrição|O usuário deve visualizar os horários de uma sessão|
|Ator|Usuário|
|Pré-condições|Acesso à internet|
|Ação|O usuário ver os horários das sessões|
|Fluxo Principal|<b>FP01</b>: Fluxo de acessar os horários pelo filme escolhido<br/>1. O ator entra no aplicativo<br/>2. O ator acessa a funcionalidade "Filmes"<br/>3. O ator escolhe a opção "Em Cartaz"<br/>4. O ator seleciona um filme de sua escolha<br/>5. O sistema mostra todas as sessões dos cinemas com seus horários|
|Fluxo Alternativo|<b>FA01</b>: Fluxo de acessar os horários pelas sessões de um cinema<br/> O ator entra no aplicativo<br/>2. O ator acessa a funcionalidade "Cinemas"<br/>3. O ator escolhe um cinema<br/>4. O sistema mostra os filmes em cartaz daquele sistema<br/>5. O usuário seleciona um filme de sua escolha<br/>6. O aplicativo retorna os horários das sessões para aquele filme e cinema selecionados|
|Pós-condições|O ator poderá ver os horários das sessões do filme em um cinema escolhido|
<h6 align = "center">Tabela 8: Tabela de especialização da visualização dos horários.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.9 UC09 Ver Filmes em Breve
|UC09|Informações|
|--|--|
|Descrição|O usuário deve visualizar os filmes em breve|
|Ator|Usuário|
|Pré-condições|Acesso à internet|
|Ação|O usuário ver os filmes em breve|
|Fluxo Principal|<b>FP01</b>: Fluxo de acessar filmes em breve pelo menu inferior<br/>1. O ator entra no aplicativo<br/>2. O sistema exibe 5 funcionalidades pricipais de acesso<br/>3. O ator clica em "Filmes"<br/>4. O sistema mostra a opção "Em Cartaz" ou "Em Breve"<br/>5. O ator seleciona a opção "Em Breve"|
|Fluxo Alternativo|<b>FA01</b>: Fluxo de acessar filmes em breve no menu principal<br/>1. O ator entra no aplicativo<br/>2. O sistema exibe no menu principal os filmes em breve<br/>3. O ator seleciona essa opção<br/>4. O ator é redirecionado para a aba de filmes em breve|
|Pós-condições|O ator poderá visualizar todos os filmes em breve, com suas datas de lançamento|
<h6 align = "center">Tabela 9: Tabela de especialização da visualização dos filmes em breve.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4.10 UC10 Comprar Ingresso
|UC10|Informações|
|--|--|
|Descrição|O usuário deve conseguir realizar a compra de um ou mais ingressos|
|Ator|Usuário|
|Pré-condições|Acesso à internet|
|Ação|O usuário comprar os ingressos|
|Fluxo Principal|<b>FP01</b>: Fluxo de comprar ingressos selecionando o horário do filme<br/>1. O ator entra no aplicativo<br/>2. O ator acessa a funcionalidade "Filmes"<br/>3. O ator seleciona a opção "Em Cartaz"<br/>4. O ator seleciona um filme de sua escolha<br/>5. O ator seleciona o cinema de sua escolha<br/>6. O ator seleciona o horário de sua escolha<br/>7. O ator seleciona seus assentos da sessão<br/>8. O ator seleciona o tipo de ingresso<br/>9. O ator seleciona a forma de pagamento|
|Pós-condições|O ator terá acesso aos seus ingressos comprados|
<h6 align = "center">Tabela 10: Tabela de especialização da compra de ingressos.</h6>
<h6 align = "center">Fonte: Autores</h6>

## 5. Referências
<p style="text-align: justify; text-indent: 20px">[1] Andrey, R. P. <b>Projeto de Software Usando a UML</b>. 2007.</p>
