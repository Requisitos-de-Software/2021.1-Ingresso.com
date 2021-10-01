## 1. Versionamento

| Versão | Data  | Descrição             | Autor(es)       |
| ------ | ----- | --------------------- | --------------- |
| 1.0    | 06/09 | Abertura do documento | Carlos |
| 1.1    | 07/09 | Adição da tabela product backlog | Carlos e Victor Lima |
| 1.2    | 08/09 | Adição das prioridades de cada item no backlog | Victor Lima |


## 2. Introdução

<p style="text-align: justify; text-indent: 20px">
O Product Backlog é uma lista contendo todas as funcionalidades desejadas para
um produto. O conteúdo desta lista é definido pelo Product Owner. O Product
Backlog não precisa estar completo no início de um projeto. Pode-se começar
com tudo aquilo que é mais óbvio em um primeiro momento. Com o tempo, o
Product Backlog cresce e muda à medida que se aprende mais sobre o produto e
seus usuários.
</p>

## 3. Product Backlog Ingresso.com

<b>Legenda:</b>

- E: Épico.
- F: Feature.
- US: Histórias de Usuário.

<style>
    #celula {
        vertical-align: middle;
        text-align: center;
        border: 0.5px solid rgba(0,0,0,0.2);
    }
</style>

<table>
    <thead>
        <tr>
            <th>Épico</th>
            <th>Feature</th>
            <th>ID / Rastreabilidade</th>
            <th>História de Usuário</th>
            <th>Prioridade</th>
        </tr>
    </thead>
    <tbody >
        <tr>
            <td id="celula" rowspan="7">E01<br>Cadastro e Autenticação</td>
            <td id="celula" rowspan="2"> <a href="../historias_usuario/#feature-01-cadastro"> F01 </a><br>Cadastro</td>
            <td id="celula">US01 / AP10</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo criar uma conta para eu ter acesso às funcionalidades completas do aplicativo.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US02</td>
            <td id="celula">Eu, como sistema, desejo realizar a validadação dos dados preenchidos no formulário de cadastramento para garantir que são reais.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="4"><a href="../historias_usuario/#feature-02-login"> F02 </a><br>Login</td>
            <td id="celula">US03 / AP16</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo fazer login para entrar na minha conta e aproveitar as funcionalidades do Ingresso.com</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US04</td>
            <td id="celula">Eu, como sistema, desejo realizar a validadação dos dados preenchidos no formulário de login para que possa autenticá-lo.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US05 / OP04</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo redefinir a senha da minha conta que esqueci para fazer login.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US06 / OP05</td>
            <td id="celula">Eu, como sistema, desejo enviar email para que o <a href=../../modelagem/lexicos/#usuario>usuário</a> redefina a senha.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="1"><a href="../historias_usuario/#feature-03-logout"> F03 </a><br>Logout</td>
            <td id="celula">US07 / OP09</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo realizar logout do aplicativo para que minha conta não esteja mais vinculada com o app.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="6">E02<br>Perfil</td>
            <td id="celula" rowspan="4"><a href="../historias_usuario/#feature-04-perfil"> F04 </a><br>Perfil</td>
            <td id="celula">US08 / OP53</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo alterar a senha da minha conta para uma de minha preferência.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US09 / OP06</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo alterar os dados pessoais da minha conta caso algum dado tenha mudado.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US10 / OP08</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar cartões salvos para que eu possa excluir algum ou alterá-lo.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US11 / OP07</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar meu pedidos realizados para que possa acompanhar quais <a href=../../modelagem/lexicos/#ingresso>ingressos</a> e <a href=../../modelagem/lexicos/#sessao>sessões</a> já assisti.</td>
            <td id="celula">SHOULD</td>
        </tr>
        <tr>
            <td id="celula" rowspan="1"><a href="../historias_usuario/#feature-05-atendimento"> F05 </a><br>Atendimento</td>
            <td id="celula">US12 / OP12</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo esclarecer dúvidas e/ou enviar solicitações de atendimento para o Ingresso.com para compreender melhor o aplicativo.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="1"><a href="../historias_usuario/#feature-06-sobre-o-app"> F06 </a><br>Sobre o App</td>
            <td id="celula">US13 / OP13</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar informações sobre o aplicativo para saber qual a versão que está instalada em meu smartphone.</td>
            <td id="celula">SHOULD</td>
        </tr>
        <tr>
            <td id="celula" rowspan="11">E03<br><a href=../../modelagem/lexicos/#cinema>Cinemas</a></td>
            <td id="celula" rowspan="2"><a href="../historias_usuario/#feature-06-sobre-o-app"> F07 </a><br><a href=../../modelagem/lexicos/#local>Localização</a></td>
            <td id="celula">US14 / AP01</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo adicionar minha <a href=../../modelagem/lexicos/#local>localização</a> ou escolher a cidade para que eu possa ver os <a href=../../modelagem/lexicos/#cinema>cinemas</a> da minha região.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US15 / AP01</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo alterar a <a href=../../modelagem/lexicos/#local>localização</a> ou cidade para que eu possa ver os <a href=../../modelagem/lexicos/#cinema>cinemas</a> da cidade em que estou.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="6"><a href="../historias_usuario/#feature-08-<a href=../../modelagem/lexicos/#cinema>cinemas</a>"> F08 </a><br><a href=../../modelagem/lexicos/#cinema>Cinemas</a></td>
            <td id="celula">US16 / AP04</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar <a href=../../modelagem/lexicos/#cinema>cinemas</a> da minha cidade para que eu possa escolher algum para ir.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US17 / AP05</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo pesquisar <a href=../../modelagem/lexicos/#cinema>cinemas</a> para ver se está aberto ou se vende <a href=../../modelagem/lexicos/#ingresso>ingressos</a> pelo app.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US18/ I16</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar informações sobre o <a href=../../modelagem/lexicos/#cinema>cinema</a> para que eu possa saber como chegar nele e entrar em contato.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US19 / AP08</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar as medidas preventivas adotadas pelo <a href=../../modelagem/lexicos/#cinema>cinema</a> para que eu possa me previnir melhor.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US20 / I15</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo compartilhar um <a href=../../modelagem/lexicos/#cinema>cinema</a> para meus amigos e/ou familiares para mostrar que tenho interesse nesse <a href=../../modelagem/lexicos/#cinema>cinema</a>.</td>
            <td id="celula">COULD</td>
        </tr>
         <tr>
            <td id="celula">US21 / OP28</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo favoritar um <a href=../../modelagem/lexicos/#cinema>cinema</a> para adicioná-lo a minha lista de <a href=../../modelagem/lexicos/#cinema>cinemas</a> favoritos e ter acesso mais fácil a ele.</td>
            <td id="celula">WOULD</td>
        </tr>
        <tr>
            <td id="celula" rowspan="3"><a href="../historias_usuario/#feature-08-<a href=../../modelagem/lexicos/#cinema>cinemas</a>"> F09 </a><br><a href=../../modelagem/lexicos/#sessao>Sessões</a></td>
            <td id="celula">US22 / I17</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar as <a href=../../modelagem/lexicos/#sessao>sessões</a> do <a href=../../modelagem/lexicos/#cinema>cinema</a> escolhido para escolher qual <a href=../../modelagem/lexicos/#filme>filme</a> assistir.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US23 / OP22</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar as <a href=../../modelagem/lexicos/#sessao>sessões</a> disponíveis do <a href=../../modelagem/lexicos/#filme>filme</a> escolhido para que eu possa escolher quando e onde assistir.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US24 / I19</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar os <a href=../../modelagem/lexicos/#assento>assentos</a> disponíveis na <a href=../../modelagem/lexicos/#sessao>sessão</a> para que eu possa escolher onde sentar.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="5">E04<br><a href=../../modelagem/lexicos/#filme>Filmes</a></td>
            <td id="celula" rowspan="5"><a href="../historias_usuario/#feature-10-<a href=../../modelagem/lexicos/#filme>filmes</a>"> F10 </a><br><a href=../../modelagem/lexicos/#filme>Filmes</a></td>
            <td id="celula">US25 / AP02</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar <a href=../../modelagem/lexicos/#filme>filmes</a> que estão em cartaz para que eu possa escolher algum <a href=../../modelagem/lexicos/#filme>filme</a> para assistir.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US26 / OP19</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar <a href=../../modelagem/lexicos/#filme>filmes</a> que em breve estarão nos <a href=../../modelagem/lexicos/#cinema>cinemas</a> para que eu possa me programar para assistir a ele.</td>
            <td id="celula">SHOULD</td>
        </tr>
        <tr>
            <td id="celula">US27 / OP20</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar as informações sobre o <a href=../../modelagem/lexicos/#filme>filme</a> para decidir se quero assistir a ele ou não.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US28 / OP26</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar o trailer do <a href=../../modelagem/lexicos/#filme>filme</a> para descobrir do que se trata o <a href=../../modelagem/lexicos/#filme>filme</a>.</td>
            <td id="celula">COULD</td>
        </tr>
        <tr>
            <td id="celula">US29 / OP26</td>
            <td id="celula">Eu, como sistema, desejo disponibilizar trailer do <a href=../../modelagem/lexicos/#filme>filme</a> do youtube para o aplicativo para que o <a href=../../modelagem/lexicos/#usuario>usuário</a> consiga assistir a ele.</td>
            <td id="celula">COULD</td>
        </tr>
        <tr>
            <td id="celula" rowspan="5">E05<br>Compra</td>
            <td id="celula" rowspan="1"><a href="../historias_usuario/#feature-11-<a href=../../modelagem/lexicos/#ingresso>ingresso</a>"> F11 </a><br><a href=../../modelagem/lexicos/#ingresso>Ingresso</a></td>
            <td id="celula">US30 / AP12</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo escolher os tipos de <a href=../../modelagem/lexicos/#ingresso>ingressos</a> da <a href=../../modelagem/lexicos/#sessao>sessão</a> escolhida para comprá-los.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="1"><a href="../historias_usuario/#feature-12-acompanhamentos"> F12 </a><br>Acompanhamentos</td>
            <td id="celula">US31 / BS10</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo escolher acompanhamentos para que eu não precise enfrentar filas no <a href=../../modelagem/lexicos/#cinema>cinema</a>.</td>
            <td id="celula">COULD</td>
        </tr>
        <tr>
            <td id="celula" rowspan="2"><a href="../historias_usuario/#feature-13-pagamento"> F13 </a><br>Pagamento</td>
            <td id="celula">US32 / AP14</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo escolher forma de pagamento disponível para pagar os <a href=../../modelagem/lexicos/#ingresso>ingressos</a> que quero comprar.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula">US33 / OP58</td>
            <td id="celula">Eu, como sistema, desejo enviar uma mensagem para o email do <a href=../../modelagem/lexicos/#usuario>usuário</a> para informar que a compra de <a href=../../modelagem/lexicos/#ingresso>ingresso</a> foi realizada.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="1"><a href="../historias_usuario/#feature-14-<a href=../../modelagem/lexicos/#carrinho>carrinho</a>"> F14 </a><br><a href=../../modelagem/lexicos/#carrinho>Carrinho</a></td>
            <td id="celula">US34 / OP43</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo ver quais <a href=../../modelagem/lexicos/#sessao>sessões</a> coloquei no <a href=../../modelagem/lexicos/#carrinho>carrinho</a> para que eu possa remover alguma, mudar os <a href=../../modelagem/lexicos/#assento>assentos</a>, tipo de <a href=../../modelagem/lexicos/#ingresso>ingresso</a>, acompanhamentos e forma de pagamento.</td>
            <td id="celula">MUST</td>
        </tr>
        <tr>
            <td id="celula" rowspan="4">E06<br>Engajamento</td>
            <td id="celula" rowspan="3"><a href="../historias_usuario/#feature-15-noticia"> F15 </a><br><a href=../../modelagem/lexicos/#noticia>Notícia</a></td>
            <td id="celula">US35 / I05</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar <a href=../../modelagem/lexicos/#noticia>notícias</a> sobre o mundo do <a href=../../modelagem/lexicos/#cinema>cinema</a> para que eu possa ficar por dentro das novidades.</td>
            <td id="celula">COULD</td>
        </tr>
        <tr>
            <td id="celula">US36 / ST07, I05 </td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo ler a <a href=../../modelagem/lexicos/#noticia>notícia</a> para que eu possa entendê-la por completo.</td>
            <td id="celula">COULD</td>
        </tr>
        <tr>
            <td id="celula">US37 / OP48</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo compartilhar uma <a href=../../modelagem/lexicos/#noticia>notícia</a> para que eu possa enviá-la para meus amigos e/ou parentes.</td>
            <td id="celula">WOULD</td>
        </tr>
        <tr>
            <td id="celula" rowspan="1"><a href="../historias_usuario/#feature-16-destaques"> F16 </a><br>Destaques</td>
            <td id="celula">US38 / AP06</td>
            <td id="celula">Eu, como <a href=../../modelagem/lexicos/#usuario>usuário</a>, desejo visualizar os destaques do aplicativo para que possa acompanhar a tendência do mundo do <a href=../../modelagem/lexicos/#cinema>cinema</a>.</td>
            <td id="celula">COULD</td>
        </tr>
        <tr>
            <td id="celula" rowspan="1">E07<br>Lucro</td>
            <td id="celula" rowspan="1"><a href="../historias_usuario/#feature-16-destaques"> F17 </a><br>Anúncio</td>
            <td id="celula">US39</td>
            <td id="celula">Eu, como sistema, desejo apresentar ao <a href=../../modelagem/lexicos/#usuario>usuário</a> propagandas para que seja gerada receita e lucro para minha empresa.</td>
            <td id="celula">MUST</td>
        </tr>
    </tbody>
</table>

## 4. Referência

<p style="text-align: justify; text-indent: 20px">[1] SERRANO, Milene; SERRANO, Maurício. <b>Requisitos - Aula 15</b>. 2019. 46 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>


