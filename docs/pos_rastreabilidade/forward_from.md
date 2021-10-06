## 1. Versionamento
|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|05/10|Adição da Matriz de Rastreabilidade|Thiago|
|1.1|05/10|Adição da introdução e metodologia|Rafael|
|1.2|05/10|Adição das telas|Carlos, Rafael e Thiago|
|1.3|05/10|Adição do resumo|Carlos, Rafael e Thiago|

## 2. Introdução
<p style="text-align: justify; text-indent: 20px"> A intenção do documento de Forward-From é conectar  os requisitos elicitados durante o desenvolvimento do projeto com seus respectivos artefatos. Para isso, foi utilizada uma matriz de rastreabilidade, onde é possível ver os artefatos derivados dos requisitos, bem como o estado atual desse requisitos, se foi implementado ou não.</p>

## 3. Metodologia

<p style="text-align: justify; text-indent: 20px">Será feita a avaliação da implementação dos requisitos elicitados durante o desenvolvimento do projeto (considerando o cumprimento dos critérios de aceitação referente a US do requisito). Como o Ingresso.com não é um projeto open source, encontrar o código referente a cada requisito é uma tarefa inviável, logo a avaliação será feita com o que já tem implementado e será apresentada as telas para comprovar a veracidade da implementação.</p>

<b>Legenda:</b>

|Símbolo|Descrição|
|:--:|:--:|
|✔|Totalmente implementado|
|ρ|Parcialmente implementado|
|✖|Não implementado|

## 4. Matriz de Rastreabilidade

|ID|Descrição|Artefatos|Foi implementado?|Tela|
|:--:|:--:|:--:|:--:|:--:|
|RF01| O aplicativo deve permitir selecionar a região desejada|<a href=../../modelagem/cenarios/#c02-escolher-regiao-do-cinema>C02</a><br><a href=../../modelagem/use_case/#uc04-selecionar-regiao>UC04</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-07-localizacao>US14</a>|✔|[Tela RF01](../telas/#RF01)|
|RF02| O usuário deve conseguir ver os filmes em cartaz na região desejada|<a href=../../modelagem/cenarios/#c05-consultar-filmes-em-cartaz>C05</a><br><a href=../../modelagem/use_case/#uc06-ver-filmes-em-cartaz>UC06</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-10-filmes>US25</a>|✔|[Tela RF02](../telas/#RF02)|
|RF03| O usuário deve conseguir pesquisar os filmes em cartaz na região desejada|<a href=../../modelagem/cenarios/#c05-consultar-filmes-em-cartaz>C05</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a>|✔|[Tela RF03](../telas/#RF03)|
|RF04| O usuário deve conseguir ver os cinemas na região desejada|<a href=../../modelagem/cenarios/#c03-escolher-cinema>C03</a><br><a href=../../modelagem/use_case/#uc07-ver-cinemas>UC07</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-08-cinemas>US16</a>|✔|[Tela RF04](../telas/#RF04)|
|RF05| O usuário deve conseguir pesquisar os cinemas na região desejada|<a href=../../modelagem/cenarios/#c03-escolher-cinema>C03</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-08-cinemas>US17</a>|✔|[Tela RF05](../telas/#RF05)|
|RF06| O aplicativo deve recomendar os filmes em alta (destaques)|<a href=../../modelagem/historias_usuario/#feature-16-destaques>US38</a>|✔|[Tela RF06](../telas/#RF06)|
|RF07| O aplicativo deve recomendar notícias em alta (destaques)|<a href=../../modelagem/istar/#32-noticia>Notícia</a><br><a href=../../modelagem/historias_usuario/#feature-16-destaques>US38</a>|✔|[Tela RF07](../telas/#RF07)|
|RF08| O aplicativo deve exibir as prevenções adotadas pelos cinemas referentes a pandemia do covid-19|<a href=../../modelagem/cenarios/#c18-ver-prevencoes>C18</a><br><a href=../../modelagem/historias_usuario/#feature-08-cinemas>US19</a>|✔|[Tela RF08](../telas/#RF08)|
|RF09| O aplicativo deve deixar claro o que cada medida de prevenção significa|-|✔|[Tela RF09](../telas/#RF09)|
|RF10| O usuário deve se cadastrar utilizando redes sociais ou não|<a href=../../modelagem/cenarios/#c13-criar-conta-sem-integracao-com-outro-aplicativo>C13</a><br><a href=../../modelagem/cenarios/#c14-criar-conta-sem-integracao-com-outro-aplicativo>C14</a><br><a href=../../modelagem/cenarios/#c15-criar-conta-sem-integracao-com-outro-aplicativo>C15</a><br><a href=../../modelagem/use_case/#uc02-cadastro>UC02</a><br><a href=../../modelagem/istar/#33-conta>Conta</a><br><a href=../../modelagem/historias_usuario/#feature-01-cadastro>US01</a>|✔|[Tela RF10](../telas/#RF10)|
|RF11| O usuário deve poder escolher o(s) seu(s) assento(s)|<a href=../../modelagem/cenarios/#c08-escolher-assentos-da-sessao>C08</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-08-cinemas>US24</a>|✔|[Tela RF11](../telas/#RF11)|
|RF12| O usuário deve poder escolher qual tipo de ingresso vai querer|<a href=../../modelagem/cenarios/#c09-escolher-o-tipo-de-ingresso>C09</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-11-ingresso>US30</a>|✔|[Tela RF12](../telas/#RF12)|
|RF13| O usuário deve poder escolher o alimento(combo) que irá consumir na sessão|<a href=../../modelagem/cenarios/#c10-escolher-o-que-vai-comer-na-sessao>C10</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-12-acompanhamentos>US31</a>|✔|[Tela RF13](../telas/#RF13)|
|RF14| O usuário deve conseguir efetuar o pagamento de diferentes formas|<a href=../../modelagem/cenarios/#c11-realizar-pagamento-como-cliente-do-ingressocom>C11</a><br><a href=../../modelagem/cenarios/#c12-realizar-pagamento-como-cliente-do-ingressocom>C12</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-13-pagamento>US32</a>|✔|[Tela RF14](../telas/#RF14)|
|RF15| O aplicativo deve identificar o usuário no pagamento|-|✔|[Tela RF15](../telas/#RF15)|
|RF16| O usuário deve ser capaz de comprar ingressos para o filme|<a href=../../modelagem/cenarios/#c11-realizar-pagamento-como-cliente-do-ingressocom>C11</a><br><a href=../../modelagem/cenarios/#c12-realizar-pagamento-como-cliente-do-ingressocom>C12</a><br><a href=../../modelagem/use_case/#uc10-comprar-ingresso>UC10</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-13-pagamento>US32</a>|✔|[Tela RF16](../telas/#RF16)|
|RF17| O usuário deve ser capaz de ver os horários dos filmes|<a href=../../modelagem/cenarios/#c20-visualizar-detalhes-de-um-filme>C20</a><br><a href=../../modelagem/use_case/#uc08-ver-horarios>UC08</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US23</a>|✔|[Tela RF17](../telas/#RF17)|
|RF18| Apresentar os filmes que serão lançados|<a href=../../modelagem/cenarios/#c06-consultar-filmes-em-breve>C06</a><br><a href=../../modelagem/use_case/#uc09-ver-filmes-em-breve>UC09</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-10-filmes>US26</a>|✔|[Tela RF18](../telas/#RF18)|
|RF19| Pesquisar um filme|<a href=../../modelagem/cenarios/#c05-consultar-filmes-em-cartaz>C05</a><br><a href=../../modelagem/cenarios/#c06-consultar-filmes-em-cartaz>C06</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a>|✔|[Tela RF19](../telas/#RF19)|
|RF20| Ter uma área para notícias|<a href=../../modelagem/cenarios/#c17-ver-noticias>C17</a><br><a href=../../modelagem/use_case/#uc05-ver-noticias>UC05</a><br><a href=../../modelagem/istar/#32-noticia>Notícia</a><br><a href=../../modelagem/historias_usuario/#feature-15-noticia>US35</a>|✔|[Tela RF20](../telas/#RF20)|
|RF21| Apresentar informações sobre o filme|<a href=../../modelagem/cenarios/#c20-visualizar-detalhes-de-um-filme>C20</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-10-filmes>US27</a>|✔|[Tela RF21](../telas/#RF21)|
|RF22| Os cinemas devem apresentar os horários das sessões do filme nos próximos dois dias|<a href=../../modelagem/cenarios/#c07-escolher-sessao-do-filme>C07</a><br><a href=../../modelagem/cenarios/#c20-visualizar-detalhes-de-um-filme>C20</a><br><a href=../../modelagem/use_case/#uc08-ver-horarios>UC08</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US22</a>|✔|[Tela RF22](../telas/#RF22)|
|RF23| Ter como seguir o filme para acompanhar notícias e lançamentos|-|✖|-|
|RF24| Recomendar outros filmes|<a href=../../elicitacao/introspeccao/#3-requisitos-elicitados>I14</a><br><a href=../../elicitacao/analiseProtocolo/#5-requisitos-levantados>AP06</a>|✖|-|
|RF25| Compartilhar o filme|-|✔|[Tela RF25](../telas/#RF25)|
|RF26| Apresentar as informações do cinema|<a href=../../modelagem/cenarios/#c03-escolher-cinema>C03</a><br><a href=../../modelagem/use_case/#uc07-ver-cinemas>UC07</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-08-cinemas>US18</a>|✔|[Tela RF26](../telas/#RF26)|
|RF27| Apresentar as sessões com os horários e dias com vagas|<a href=../../modelagem/cenarios/#c05-consultar-filmes-em-cartaz>C05</a><br><a href=../../modelagem/use_case/#uc06-ver-filmes-em-cartaz>UC06</a><br><a href=../../modelagem/use_case/#uc08-ver-horarios>UC08</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US22</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US23</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US24</a>|✔|[Tela RF27](../telas/#RF27)|
|RF28| Apresentar informações da sessão|<a href=../../modelagem/cenarios/#c07-escolher-sessao-do-filme>C07</a><br><a href=../../modelagem/use_case/#uc06-ver-filmes-em-cartaz>UC06</a><br><a href=../../modelagem/use_case/#uc08-ver-horarios>UC08 <br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US22</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US23</a>|✔|[Tela RF28](../telas/#RF28)|
|RF29| Mostrar os assentos disponíves|<a href=../../modelagem/cenarios/#c08-escolher-assentos-da-sessao>C08</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US24</a>|✔|[Tela RF29](../telas/#RF29)|
|RF30| Apresentar os tipos de ingressos|<a href=../../modelagem/cenarios/#c09-escolher-o-tipo-de-ingresso>C09</a><br><a href=../../modelagem/historias_usuario/#feature-11-ingresso>US30</a>|✔|[Tela RF30](../telas/#RF30)|
|RF31| Oferecer acompanhamentos|<a href=../../modelagem/cenarios/#c10-escolher-o-que-vai-comer-na-sessao>C10</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-12-acompanhamentos>US31</a>|✔|[Tela RF31](../telas/#RF31)|
|RF32| Comprar com uma conta criada no domínio|<a href=../../modelagem/cenarios/#c11-realizar-pagamento-como-cliente-do-ingressocom>C11</a><br><a href=../../modelagem/use_case/#uc10-comprar-ingresso>UC10</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-13-pagamento>US32</a>|✔|[Tela RF32](../telas/#RF32)|
|RF33| Comprar com uma conta do Google ou Facebook|<a href=../../modelagem/cenarios/#c11-realizar-pagamento-como-cliente-do-ingressocom>C11</a><br><a href=../../modelagem/use_case/#uc10-comprar-ingresso>UC10</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-13-pagamento>US32</a>|✔|[Tela RF33](../telas/#RF33)|
|RF34| Comprar sem o cadastro|<a href=../../modelagem/cenarios/#c12-realizar-pagamento-sem-ser-cliente-do-ingressocom>C12</a><br><a href=../../modelagem/use_case/#uc10-comprar-ingresso>UC10</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-13-pagamento>US32</a>|✔|[Tela RF34](../telas/#RF34)|
|RF35| Mostrar um resumo da compra|<a href=../../modelagem/historias_usuario/#feature-14-carrinho>US34</a>|✔|[Tela RF35](../telas/#RF35)|
|RF36| Mostrar o total e informações do pagamento|<a href=../../modelagem/historias_usuario/#feature-14-carrinho>US34</a>|✔|[Tela RF36](../telas/#RF36)|
|RF37| O resumo do pedido deve ser enviado por e-mail|<a href=../../modelagem/historias_usuario/#feature-13-pagamentoo>US33</a>|✖|-|
|RF38| Ter uma área para os pedidos|<a href=../../modelagem/cenarios/#c19-ver-ingressos-comprados>C19</a><br><a href=../../modelagem/historias_usuario/#feature-14-carrinho>US34</a>|✔|[Tela RF38](../telas/#RF38)|
|RF39| Notificar a confirmação do pagamento|<a href=../../modelagem/historias_usuario/#feature-13-pagamento>US33</a>|✖|-|
|RF40| Apresentar informações do ingresso|<a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-11-ingresso>US30</a>|ρ|-|
|RF41| Enviar o ingresso por e-mail|-|✖|-|
|RF42| Notificar quando a sessão tiver chegando|-|ρ|-|
|RF43| O usuário deve poder visualizar senha digitada|-|✔|[Tela RF43](../telas/#RF43)|
|RF44| O usuário deve poder recuperar senha|<a href=../../modelagem/istar/#33-conta>Conta</a><br><a href=../../modelagem/historias_usuario/#feature-02-login>US05</a>|✔|[Tela RF44](../telas/#RF44)|
|RF45| O sistema deve enviar um email de recuperação de senha|<a href=../../modelagem/historias_usuario/#feature-02-login>US06</a>|✔|[Tela RF45](../telas/#RF45)|
|RF46| O usuário deve poder ver seus dados pessoais|<a href=../../modelagem/istar/#33-conta>Conta</a><br><a href=../../modelagem/historias_usuario/#feature-04-perfil>US09</a>|✔|[Tela RF46](../telas/#RF46)|
|RF47| O usuário deve poder ver seus Pedidos|<a href=../../modelagem/cenarios/#c19-ver-ingressos-comprados>C1</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-04-perfil>US11</a>|✔|[Tela RF47](../telas/#RF47)|
|RF48| O usuário deve poder ver seus Cartões Salvo|<a href=../../modelagem/historias_usuario/#feature-04-perfil>US10</a>|✔|[Tela RF48](../telas/#RF48)|
|RF49| O usuário deve poder sair da conta logada|<a href=../../modelagem/historias_usuario/#feature-03-logout>US07</a>|✔|[Tela RF49](../telas/#RF49)|
|RF50| O usuário deve poder enviar uma solicitação de atendimento|<a href=../../modelagem/historias_usuario/#feature-05-atendimento>US12</a>|✔|[Tela RF50](../telas/#RF50)|
|RF51| O usuário deve poder ver filmes que vão estar nos cinemas em breve|<a href=../../modelagem/cenarios/#c06-consultar-filmes-em-breve>C06</a><br><a href=../../modelagem/use_case/#uc09-ver-filmes-em-breve>UC09</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-10-filmes>US26</a>|✔|[Tela RF51](../telas/#RF51)|
|RF52| O usuário deve poder ver título, categoria, classificação indicativa, avaliação, duração, elenco, sinopse, direção, distribuidor e país de origem do filme selecionado|<a href=../../modelagem/cenarios/#c20-visualizar-detalhes-de-um-filme>C20</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-10-filmes>US27</a>|✔|[Tela RF52](../telas/#RF52)|
|RF53| O usuário deve poder ver as sessões do filme selecionado por dia da semana|<a href=../../modelagem/cenarios/#c05-consultar-filmes-em-cartaz>C05</a><br><a href=../../modelagem/cenarios/#c06-consultar-filmes-em-breve>C06</a><br><a href=../../modelagem/historias_usuario/#feature-10-filmes>US25</a>|✔|[Tela RF53](../telas/#RF53)|
|RF54| O usuário deve poder filtrar sessões do filme selecionado por Tipos de Exibição|-|✔|[Tela RF54](../telas/#RF54)|
|RF55| O usuário deve poder limpar filtros selecionados|-|✔|[Tela RF55](../telas/#RF55)|
|RF56| O usuário deve poder assistir trailer do filme|<a href=../../modelagem/cenarios/#c20-visualizar-detalhes-de-um-filme>C20</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-10-filmes>US28</a>|✔|[Tela RF56](../telas/#RF56)|
|RF57| O usuário deve poder ordenar cinemas por nome ou proximidade|<a href=../../modelagem/historias_usuario/#feature-08-cinemas>US16</a>|✔|[Tela RF57](../telas/#RF57)|
|RF58| O usuário deve poder favoritar cinemas|<a href=../../modelagem/cenarios/#c04-favoritar-cinema>C04</a><br><a href=../../modelagem/historias_usuario/#feature-08-cinemas>US21</a>|✔|[Tela RF58](../telas/#RF58)|
|RF59| O usuário deve poder ver nome, logo e endereço do cinema|<a href=../../modelagem/cenarios/#c03-escolher-cinema>C03</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/historias_usuario/#feature-08-cinemas>US18</a>|✔|[Tela RF59](../telas/#RF59)|
|RF60| O usuário deve poder ver a Legenda da Escolha de Assentos|<a href=../../modelagem/cenarios/#c08-escolher-assentos-da-sessao>C08</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US24</a>|✔|[Tela RF60](../telas/#RF60)|
|RF61| O usuário deve poder ver os números dos assentos|<a href=../../modelagem/cenarios/#c08-escolher-assentos-da-sessao>C08</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US24</a>|✔|[Tela RF61](../telas/#RF61)|
|RF62| O usuário deve poder aplicar código de desconto no pagamento|-|✔|[Tela RF62](../telas/#RF62)|
|RF63| O usuário deve poder ver Carrinho com as sessões selecionadas|<a href=../../modelagem/historias_usuario/#feature-14-carrinho>US34</a>|✔|[Tela RF63](../telas/#RF63)|
|RF64| O usuário deve poder remover sessões do Carrinho|<a href=../../modelagem/historias_usuario/#feature-14-carrinho>US34</a>|✔|[Tela RF64](../telas/#RF64)|
|RF65| O usuário deve poder ver cinemas favoritados|<a href=../../elicitacao/observacao_participativa/#31-requisitos>OP47</a><br><a href=../../modelagem/cenarios/#c04-favoritar-cinema>C04</a><br><a href=../../modelagem/istar/#31-cinema>Cinema</a>|✔|[Tela RF65](../telas/#RF65)|
|RF66| O usuário deve poder comprar os acompanhamentos junto dos ingressos|<a href=../../modelagem/cenarios/#c10-escolher-o-que-vai-comer-na-sessao>C10</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-08-cinemas>US16</a>|✔|[Tela RF66](../telas/#RF66)|
|RF67| O aplicativo deve permitir o cancelamento/reembolso da compra|-|ρ|-|
|RF68| O aplicativo deve informar o histórico de compra dos usuários logados|<a href=../../modelagem/historias_usuario/#feature-14-carrinho>US34</a>|✔|[Tela RF68](../telas/#RF68)|
|RF69| O aplicativo deve fornecer informações sobre eventos próximos a região escolhida|-|ρ|-|
|RNF01| O usuário deve poder navegar pelo aplicativo sem precisar de um cadastro|<a href=../../elicitacao/analiseProtocolo/#5-requisitos-levantados>AP16</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a>|✖|-|
|RNF02| O aplicativo deve ser de fácil instalação|<a href=../../modelagem/istar/#31-cinema>Cinema</a>|✖|-|
|RNF03| O aplicativo deve ser seguro por lidar com dados sensíveis|<a href=../../modelagem/istar/#33-conta>Conta</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a>|✖|-|
|RNF04| O aplicativo deve ser monetizado através de publicidade|<a href=../../modelagem/historias_usuario/#feature-17-anuncio>US39</a>|✖|-|
|RNF05| O aplicativo deve oferecer comodidade ao usuário|-|✖|-|
|RNF06| O pagamento de ingressos deve ser fácil|<a href=../../modelagem/istar/#34-ingressos>Ingressos</a>|✖|-|
|RNF07| O pagamento de ingresso deve ser rápido|<a href=../../modelagem/istar/#34-ingressos>Ingressos</a>|✖|-|
|RNF08| A plataforma deve ser rápida|-|✖|-|
|RNF09| Não há necessidade de autenticação para navegar entre os filmes e notícia|<a href=../../modelagem/cenarios/#c12-realizar-pagamento-sem-ser-cliente-do-ingressocom>C12</a>|✖|-|
|RNF10| O aplicativo deve ser fácil de ser utilizado|<a href=../../modelagem/istar/#34-ingressos>Ingressos</a>|✖|-|
|RNF11| O aplicativo deve estar sempre com os horários das sessões atualizados|<a href=../../modelagem/istar/#31-cinema>Cinema</a><br><a href=../../modelagem/istar/#34-ingressos>Ingressos</a><br><a href=../../modelagem/historias_usuario/#feature-09-sessoes>US23</a>|✖|-|
|RNF12| O aplicativo deve estar sempre com as notícias atualizadas|<a href=../../modelagem/cenarios/#c17-ver-noticias>C17</a><br><a href=../../modelagem/istar/#32-noticia>Notícia</a><br><a href=../../modelagem/historias_usuario/#feature-15-noticia>US35</a>|✖|-|
|RNF13| A lista de filmes e notícias devem ser claras e legíveis|<a href=../../modelagem/historias_usuario/#feature-15-noticia>US36</a>|✖|-|
|RNF14| O aplicativo deve prover conforto e menos tempos em filas para compra de ingressos|-|✖|-|
|RNF15| O aplicativo deve funcionar em todas as plataformas virtuais|-|✖|-|
|RNF16| O aplicativo deve funcionar em dispositivos de tamanhos diferentes|-|✖|-|
|RNF17| O sistema e o evento deve ter uma interface de comunicação prática|-|✖|-|
<h6 align="center">Tabela 1: Matriz de Rastreabilidade Forward-From</h6>
<h6 align="center">Fonte: Autores</h6>

## 5. Resumo da Matriz de Rastrabilidade

<center>
<img id="RF66" src="../../assets/pos_rastreabilidade/resumo.png" width="75%" />
<h6 align="center">Figura 1: Resumo da Matriz de Rastreabilidade</h6>
<h6 align="center">Fonte: Autores</h6>
</center>


## 6. Bibliografia
<p style="text-align: justify; text-indent: 20px">SERRANO, Milene; SERRANO, Maurício. <b>Requisitos - Aula 24</b>. 2019. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>