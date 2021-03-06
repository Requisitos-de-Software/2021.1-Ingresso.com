## 1. Versionamento

|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|11/08|<center>Adição do documento de entrevistas</center>|<center>João Pedro</center>|
|1.1|15/08|<center>Adição das entrevistas e dos requisitos levantados</center>|<center>João Pedro</center>|
|1.2|03/10|<center>Linkagem dos léxicos</center>|<center>Thiago</center>|

## 2. Introdução
<p style="text-align: justify; text-indent: 20px">Entre uma das muitas técnicas citadas por Wiegers <i>et al.</i> (2013, pág. 121-128) [1], aquela que é destacada como a forma mais óbvia de obtenção de informações é a metodologia de <b>entrevistas</b>. Através de um diálogo, formal ou informal, entre o entrevistador e o entrevistado serão feitas diversas perguntas previamente planejadas, a fim de obter informações sobre a aplicação em questionamento [2]. Essa técnica, portanto, é extremamente flexivel visando aproximar o engenheiro com seus <a href="../../modelagem/lexicos/#usuario">usuários</a> sendo muito utilizada para levantar requisitos.</p>

## 3. Resultados
### 3.1 Roteiro
1. Você já utilizou alguma plataforma de compra de [ingressos](../../modelagem/lexicos/#ingresso)? Se sim, qual ou quais?
2. Quais vantagens você vê na compra de [ingressos](../../modelagem/lexicos/#ingresso) online em comparação as compras presenciais? E quais desvantagens?
3. Você já utilizou o Ingresso.com? Se o fez, por quais motivos? Se não, o que está te impedindo?
4. Quais funcionalidades do aplicativo você mais utiliza?
5. Você acredita que o aplicativo tem facilitado sua vida de alguma forma? Por quê?
6. Quais são os maiores defeitos do aplicativo em sua opinião?
7. Quais são as maiores qualidades do aplicativo em sua opinião?
8. Quais funcionalidades, em sua opinião, seriam interessantes para serem adicionadas no aplicativo?

### 3.2 Entrevistas
#### 3.1.1 Entrevista 1: Matheus Santana Cândido
|Questão|Resposta
|--|--|
|1|Sim, ingresse, ingresso.com e futebolcard.com|
|2|Facilidade em [comprar](../../modelagem/lexicos/#comprar-ingresso) estando em qualquer lugar. Taxas abusivas são cobradas ao comprar pela internet|
|3|Sim, comprar [ingresso](../../modelagem/lexicos/#ingresso) para [filme](../../modelagem/lexicos/#filme) no Taguatinga shopping|
|4|[Compra](../../modelagem/lexicos/#comprar-ingresso) sem sair de casa|
|5|Não utilizo mais o aplicativo por causa da pandemia|
|6|Preços abusivos de taxas|
|7|Comodidade|
|8|Colocar cadeiras em 3D, para ter a melhor dimensão de onde ficar na sala de [cinema](../../modelagem/lexicos/#cinema)|
<h6 align = "center">Tabela 1: Entrevista com o Matheus</h6>
<h6 align = "center">Fonte: Autor</h6>

#### 3.1.2 Entrevista 2: Josimar Kallebe Lima
|Questão|Resposta
|--|--|
|1|Sim, Ingresso.com, Cinemark|
|2|Evitar filas, pagamento facilitado, escolha de lugares e horários|
|3|Sim, [compra de ingressos](../../modelagem/lexicos/#comprar-ingresso) de [cinema](../../modelagem/lexicos/#cinema)|
|4|Compra de ticket de [cinema](../../modelagem/lexicos/#cinema)|
|5|Sim, facilidade de compra|
|6|Demora para selecionar os lugares|
|7|Rapidez para comprar os tickets|
|8|Plataforma mais rápida|
<h6 align = "center">Tabela 2: Entrevista com o Kallebe</h6>
<h6 align = "center">Fonte: Autor</h6>

## 4. Requisitos
|ID|Descrição|Tipo de Requisito
|--|--|--|
|E01|O [usuário](../../modelagem/lexicos/#usuario) deve ser capaz de [comprar](../../modelagem/lexicos/#comprar-ingresso) tickets para o [filme](../../modelagem/lexicos/#filme)|Requisito Funcional
|E02|O [usuário](../../modelagem/lexicos/#usuario) deve ser capaz de [selecionar os lugares](../../modelagem/lexicos/#escolher-assento) para a [sessão](../../modelagem/lexicos/#sessao)|Requisito Funcional
|E03|O [usuário](../../modelagem/lexicos/#usuario) deve ser capaz de ver os horários dos [filmes](../../modelagem/lexicos/#filme)|Requisito Funcional
|E04|A plataforma deve evitar o [usuário](../../modelagem/lexicos/#usuario) esperar em longas filas|Requisito Não Funcional
|E05|O aplicativo deve oferecer comodidade ao [usuário](../../modelagem/lexicos/#usuario)|Requisito Não Funcional
|E06|O pagamento de [ingressos](../../modelagem/lexicos/#ingresso) deve ser fácil|Requisito Não Funcional
|E07|O pagamento de [ingressos](../../modelagem/lexicos/#ingresso) deve ser rápido|Requisito Não Funcional
|E08|A [seleção de cadeiras](../../modelagem/lexicos/#escolher-assento) deve ser rápida|Requisito Não Funcional
|E09|A [seleção de cadeiras](../../modelagem/lexicos/#escolher-assento) deve prover uma forma de visualização eficiente, para se entender onde a cadeira se [localiza](../../modelagem/lexicos/#local) no [cinema](../../modelagem/lexicos/#cinema)|Requisito Não Funcional
|E10|A plataforma deve ser rápida|Requisito Não Funcional
<h6 align = "center">Tabela 3: Tabela contendo os requisitos levantados pelas entrevistas</h6>
<h6 align = "center">Fonte: Autor</h6>

## 5. Referências
<p style="text-align: justify; text-indent: 20px">[1] Wiegers, K.. Beatty J. <b>Software Requirements</b>. Third Edition. 2013</p>

<p style="text-align: justify; text-indent: 20px">[2] Vazquez, C.; Simões, G.; <b>Engenharia de Requisitos: Cap. 7 - Elicitação de Requisitos</b>. Brasport. 2016.</p>
