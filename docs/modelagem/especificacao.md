## 1. Versionamento

| Versão | Data  | Descrição             | Autor(es)       |
| ------ | ----- | --------------------- | --------------- |
| 1.0    | 26/08 | Abertura do documento | Rafael e Thiago |
| 1.0    | 27/08 | Adição da tabela FURPS+ | Rafael e Thiago |
|1.2|01/10|Linkagem dos léxicos|João Pedro|

## 2. Introdução

<p style="text-align: justify; text-indent: 20px">A especificação suplementar é um documento em linguagem natural, na qual são descritos os requisitos não funcionais [1]. Segundo Vazquez e Simões (2016), o requisito não funcional é o resultado de uma construção de escolhas para uma solução particular dentre várias possiveis. Por exemplo, quais normas seguir para garantir a segurança no armazenamento dos dados do <a href=../../modelagem/lexicos/#usuario>usuário</a> ? Assim, para sistematizar a identificação, validadação e desenvolvimento dos requisitos não funcionais, a metodologia utilizada foi a FURPS+, apresentada na proxima seção. Os requisitos não funcionais, utilizados nesta modelagem, foram derivados da lista de requisitos levantados e da Políticas de Privacidade e Segurança do Ingresso.com [3].</p>

## 3. METODOLOGIA FURPS+

### 3.1 Funcionalidade

<p align=”justify”>As funcionalidades se encontram na <a href="https://docs.google.com/spreadsheets/d/1jnQp4QDh6lcEGvI0FulFJ9UemWUIfF5fezK66ocX0iw/edit?usp=sharing" target="_blank">lista de requisitos</a> e nos casos de usos do projeto.</p>
<hr>

### 3.2 Usabilidade
	
- <b>O <a href=../../modelagem/lexicos/#usuario>usuário</a> deve poder navegar pelo aplicativo sem precisar de um cadastro</b>
<p align=”justify”>&emsp;&emsp;	Não ter necessidade de autenticação para navegar no app é necessário, pois o <a href=../../modelagem/lexicos/#usuario>usuário</a> quer ter acesso à informações antes de fazer qualquer tipo de compra. Logo, o aplicativo Ingresso.com não possui restrição de acesso às informações de <a href=../../modelagem/lexicos/#filme>filmes</a> e <a href=../../modelagem/lexicos/#cinema>cinemas</a>, apenas ao pagamento.</p>
Rastro [AP16](../elicitacao/analiseProtocolo.md) e [I09](../elicitacao/introspeccao.md).

- <b>O pagamento de <a href=../../modelagem/lexicos/#ingresso>ingressos</a> deve ser fácil e rápido</b>
<p align=”justify”>&emsp;&emsp;Por ser um app que dispensa filas físicas, o Ingresso.com torna mais rápido o pagamento de <a href=../../modelagem/lexicos/#ingresso>ingressos</a> e possui algumas técnicas para melhorar ainda mais a experiência do <a href=../../modelagem/lexicos/#usuario>usuário</a>, como a possibilidade de selecionar algum cartão já utilizado, bem como várias outras possibilidades de pagamento.</p>
Rastro [E06](../elicitacao/entrevistas.md), [E07](../elicitacao/entrevistas.md) e [ST10](../elicitacao/storytelling.md).


- <b>A seleção de cadeiras deve ser intuitiva e prover uma forma de visualização eficiente  para se entender onde a cadeira se localiza no <a href=../../modelagem/lexicos/#cinema>cinema</a></b>
<p align=”justify”>&emsp;&emsp;A aplicação do Ingresso.com estabelece uma visualização simples em 2D para selecionar as cadeiras disponíveis em determinada <a href=../../modelagem/lexicos/#sessao>sessão</a>. Assim, é possível selecionar a(s) cadeira(s) desejadas com apenas um clique. Talvez aderir um modelo de visualização 3D traria mais eficiência para entender onde a cadeira se localiza no <a href=../../modelagem/lexicos/#cinema>cinema</a>.</p>
Rastro [E08](../elicitacao/entrevistas.md) e [E09](../elicitacao/entrevistas.md).


- <b>O aplicativo deve ser fácil de ser utilizado</b>
<p align=”justify”>&emsp;&emsp; O aplicativo deve prover uma interface gráfica intuitiva e de fácil utilização. O app do Ingresso.com promove uma fácil utilização por meio do menu inferior contendo diferentes seções como “Destaques”, “<a href=../../modelagem/lexicos/#filme>Filmes</a>”, “<a href=../../modelagem/lexicos/#cinema>Cinemas</a>”, “<a href=../../modelagem/lexicos/#noticia>Notícias</a>” e “Prevenções”, ou seja, o <a href=../../modelagem/lexicos/#usuario>usuário</a> pode se mover entre as funcionalidades do app de maneira intuitiva, quando quiser ver um <a href=../../modelagem/lexicos/#filme>Filme</a> vai para <a href=../../modelagem/lexicos/#filme>filme</a>, quando tiver em dúvida do que assistir pode ir nos destaque, e assim por diante. Já no painel superior, há as informações sobre a região e conta do <a href=../../modelagem/lexicos/#usuario>usuário</a>, onde é importante ter a seleção de região de maneira chamativa pois ela determina as informações do app.</p>
Rastro [ST01](../elicitacao/storytelling.md)
, [ST07](../elicitacao/storytelling.md)
 e [AP18](../elicitacao/analiseProtocolo.md).
<hr>

### 3.3 Confiabilidade

- <b>O aplicativo deve garantir a segurança no armazenamento de dados</b>
<p align=”justify”>&emsp;&emsp;
Uma vez que o Ingresso.com armazena dados sensiveis do <a href=../../modelagem/lexicos/#usuario>usuário</a>, os serviços providos pelo aplicativo são regidos e operados em conformidade com as leis do Brasil. 
</p>
Rastro [AP19](../elicitacao/analiseProtocolo.md).

- <b>O aplicativo deve estar sempre com os horários das <a href=../../modelagem/lexicos/#sessao>sessões</a> e <a href=../../modelagem/lexicos/#noticia>notícias</a> atualizadas</b>
<p align=”justify”>&emsp;&emsp;
	É imprescindível a atualização constante das <a href=../../modelagem/lexicos/#sessao>sessões</a> e <a href=../../modelagem/lexicos/#noticia>notícias</a> por parte do app do Ingresso.com. A maneira que eles encontraram de possibilitar essa atualização é disponibilizando <a href=../../modelagem/lexicos/#sessao>sessões</a> de até 2 dias posteriores referentes a data de uso do <a href=../../modelagem/lexicos/#usuario>usuário</a>, pois o <a href=../../modelagem/lexicos/#usuario>usuário</a> precisa ter a confiança nas informações que estão sendo mostradas.
</p>
Rastro [ST03](../elicitacao/storytelling.md), [ST05](../elicitacao/storytelling.md)

- <b>O  aplicativo deve estar sempre disponível para o <a href=../../modelagem/lexicos/#usuario>usuário</a></b>
<p align=”justify”>&emsp;&emsp;
Para atender as necessidades e expectativas dos <a href=../../modelagem/lexicos/#usuario>usuários</a>, o aplicativo tenta estar sempre em operação, uma vez que a indisponibilidade pode frustrar o <a href=../../modelagem/lexicos/#usuario>usuário</a> e, consequentemente, desistir da utilização da aplicação. 
</p>
Sem rastro.


- <b>O aplicativo deve sempre tratar as exceções e erros que podem acontecer durante a utilização</b>
<p align=”justify”>&emsp;&emsp;
	Para passar uma maior confiança para o <a href=../../modelagem/lexicos/#usuario>usuário</a>, é de extrema importância tratar os possíveis erros e sempre informar de maneira fácil e intuitiva o <a href=../../modelagem/lexicos/#usuario>usuário</a> sobre o que está acontecendo. Sem esse tratamento, a experiência do <a href=../../modelagem/lexicos/#usuario>usuário</a> e sua expectativa sobre a qualidade da aplicação é impactada negativamente.
</p>
Sem rastro.


<hr>

### 3.4 Desempenho

- <b>O aplicativo deve ser eficiente</b>
<p align=”justify”>&emsp;&emsp;
	É imprescindível que o aplicativo seja leve e otimizado para que possa incluir o maior grupo de <a href=../../modelagem/lexicos/#usuario>usuário</a> possível e passar uma experiência agradável para o <a href=../../modelagem/lexicos/#usuario>usuário</a>.
</p>
Rastro [E10](../elicitacao/entrevistas.md).
<hr>

### 3.5 Suportabilidade

- <b>O sistema do Ingresso.com está disponível para as principais plataformas Web e Mobile do mercado</b>
<p align=”justify”>&emsp;&emsp;
O site <a href="https://www.ingresso.com/" target="_blank">Web</a> pode ser acessado através de um desktop, notebook, smartphone ou tablet apenas havendo conexão com internet.
Referente às plataformas Mobile tem-se para <a href="https://play.google.com/store/apps/details?id=com.<a href=../../modelagem/lexicos/#ingresso>ingresso</a>.<a href=../../modelagem/lexicos/#cinema>cinemas</a>&hl=pt_BR&gl=US)" target="_blank">Android</a> que pode ser instalada através do Google Play funcionando nas versões  5.0 ou superior ou <a href="https://apps.apple.com/br/app/<a href=../../modelagem/lexicos/#ingresso>ingresso</a>-com-<a href=../../modelagem/lexicos/#filme>filmes</a>-<a href=../../modelagem/lexicos/#cinema>cinemas</a>/id1165054492" target="_blank">IOS</a> que pode ser instalada através da App Store funcionando nas versões 13.0 ou superior.
</p>

<hr>

## 4. Referência

<p style="text-align: justify; text-indent: 20px">[1] SERRANO, Milene; SERRANO, Maurício. <b>Requisitos - Aula 13</b>. 2019. 40 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>
<p style="text-align: justify; text-indent: 20px">[2] VAZQUEZ, C; SIMÕES, G. <b>Engenharia de Requisitos, software orientado a negocios</b>. Brasport. 2016. p. 167-175.</p>
<p style="text-align: justify; text-indent: 20px">[3] INGRESSO.COM. <b>Políticas de Privacidade e Segurança</b>. Acesso em 26 de agosto de 2021. Disponível em: <a href=”https://atendimento.ingresso.com/hc/pt-br/sections/360000077411-Pol%C3%ADticas-de-Privacidade-e-Seguran%C3%A7a%7C”> Politicas de Privacidade e Segurança</a>.</p>

