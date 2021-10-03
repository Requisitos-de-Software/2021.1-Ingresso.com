## 1. Versionamento

|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|10/08|Abertura do documento de análise de protocolo|Rafael|
|1.1|10/08|Adição dos requisitos levantados|Rafael|
|1.2|03/10|Linkagem dos léxicos|Thiago|

## 2. Introdução

<p style="text-align: justify; text-indent: 20px">A análise de protocolo é uma técnica para elicitar requisitos, solicitando ao sujeito que engaje em uma tarefa e de maneira concorrente possa verbalizar ou explicar em voz alta o que está fazendo. Essa técnica permite analisar algo sob um dado ponto de vista. [1] </p>

## 3. Metodologia 
<p style="text-align: justify; text-indent: 20px">Para a execução dessa técnica, foi solicitado a um <a href="../../modelagem/lexicos/#usuario">usuário</a> que já havia utilizado previamente o aplicativo e então foi verbalizada suas ações por meio de uma gravação de tela e áudio concorrentes. A gravação foi realizada no dia 10/08/2021 às 13h. </p>

<center>

|Membro participante|Sujeito analisado|
|:--:|:--:|
|Rafael|Stefany|

</center>

## 4. Verbalização do [Usuário](../../modelagem/lexicos/#usuario)

|Ação|Observação|
|:---:|:---:|
| Inicialização pela primeira vez | Quando o [usuário](../../modelagem/lexicos/#usuario) abre o app pela primeira vez, é pedida permissão para utilizar a localização para poder sugerir [eventos](../../modelagem/lexicos/#filme) de acordo com a proximidade da localização informada.
|Alterar localização|No menu superior esquerdo tem como alterar a localização para ver [eventos](../../modelagem/lexicos/#filme) de outros lugares.|
| Ver destaques| Na tela inicial o primeiro menu aberto é o de destaques que apresenta o melhor [filme](../../modelagem/lexicos/#filme) em cartaz e as notícias em alta, se rolar a tela pra baixo pode ver também os [eventos](../../modelagem/lexicos/#filme) em alta, os [cinemas](../../modelagem/lexicos/#cinema) abertos que estão perto e os [eventos](../../modelagem/lexicos/#filme) que estão próximos de acontecer.|
|[Ver filmes](../../modelagem/lexicos/#visualizar-filme)|Será mostrado vários [filmes](../../modelagem/lexicos/#filme) em cartazes e é possível pesquisar qualquer [filme](../../modelagem/lexicos/#filme) que você quiser.|
|[Ver cinemas](../../modelagem/lexicos/#selecionar-cinema)| Os [cinemas](../../modelagem/lexicos/#cinema) são mostrados baseados na sua localização.|
|[Ver notícias](../../modelagem/lexicos/#ler-noticia)| As notícias são referentes aos [filmes](../../modelagem/lexicos/#filme) que estão em cartaz ou serão lançados e referentes também aos [cinemas](../../modelagem/lexicos/#cinema).|
|[Ver prevenções](../../modelagem/lexicos/#visualizar-prevencoes)| Informações de como está sendo tratado a questão da covid, aglomeração e segurança contendo as restrições específicas para cada [cinema](../../modelagem/lexicos/#cinema) de acordo com a região.|
|[Selecionar um filme](../../modelagem/lexicos/#visualizar-filme)| Ao selecionar um filme é mostrado todos os [cinemas](../../modelagem/lexicos/#cinema) onde ele está disponível, bem como os [horários](../../modelagem/lexicos/#sessao) e se é dublado ou legendado.|
|[Selecionar cinema](../../modelagem/lexicos/#selecionar-cinema)| Ao selecionar um cinema é possível escolher os [filmes](../../modelagem/lexicos/#filme) que estão em [cartaz](../../modelagem/lexicos/#filme-em-cartaz) referente a dois dias ( o atual e o próximo ), caso escolhido um filme ele apresenta as mesmas informações se fosse selecionado no ínicio.|
|[Regras de distanciamento](../../modelagem/lexicos/#visualizar-prevencoes)| É mostrado antes de [selecionar os assentos](../../modelagem/lexicos/#escolher-assento) a regra de distanciamento referente ao covid-19
|[Selecionar assento](../../modelagem/lexicos/#escolher-assento)| É possível escolher os [assentos](../../modelagem/lexicos/#assento) disponíveis na [sessão](../../modelagem/lexicos/#sessao) anteriormente selecionada e são bloqueados todos os assentos em volta por conta da pandemia (regra de distanciamento)
|[Tipos de ingresso](../../modelagem/lexicos/#ingresso)| É possível escolher os ingressos baseados nos seguintes critérios (Inteira, meia, meia telecine, cineticket, promoções referentes ao [cinema](../../modelagem/lexicos/#cinema) escolhido), tendo que mostrar o comprovante na hora de apresentar os ingressos.|
|Escolha de [combo](../../modelagem/lexicos/#acompanhamento)| É possível escolher os combos a serem consumidos (pipoca e refri por exemplo).
|Identificação de pagamento| Para poder realizar o pagamento é necessário se identificar de alguma forma, as disponíveis são: Entrar com uma rede social (facebook ou google), Entrar como cliente Ingresso.com e Entrar sem cadastro que seria somente com o e-mail e o cpf.|
|Formas de pagamento| É possível pagar com cartão de crédito, google pay, paypal ou cartão de débito, também é possível aplicar código de desconto.|
|Após o pagamento| É gerado um comprovante que atesta que você pagou pelo serviço.|

<h6 align = "center">Tabela 1: Tabela contendo as verbalizações das ações do sujeito</h6>
<h6 align = "center">Fonte: Autor</h6>

<center>
<h3> Acesso à <a href="https://drive.google.com/file/d/1wepFqr5pSS0Fe8-JQdHjwefvvhgvlwsO/view?usp=sharing">gravação do sujeito.</a></h3>
</center>




## 5. Requisitos levantados

<h4>Legenda:</h4>
* AP = Análise de protocolo
  
|ID|Descrição|Tipo de Requisito|
|:--:|:--:|:-----:|
|AP01|O aplicativo deve permitir selecionar a região desejada|Requisito funcional|
|AP02|O [usuário](../../modelagem/lexicos/#usuario) deve conseguir [ver os filmes](../../modelagem/lexicos/#visualizar-filme) em [cartaz](../../modelagem/lexicos/#filme-em-cartaz) na [região](../../modelagem/lexicos/#local) desejada|Requisito funcional
|AP03|O [usuário](../../modelagem/lexicos/#usuario) deve conseguir [pesquisar](../../modelagem/lexicos/#pesquisar) os [filmes em cartaz](../../modelagem/lexicos/#filme-em-cartaz) na [região](../../modelagem/lexicos/#local) desejada|Requisito funcional|
|AP04|O [usuário](../../modelagem/lexicos/#usuario) deve conseguir ver os [cinemas](../../modelagem/lexicos/#cinema) na [região](../../modelagem/lexicos/#local) desejada |Requisito funcional|
|AP05|O [usuário](../../modelagem/lexicos/#usuario) deve conseguir [pesquisar](../../modelagem/lexicos/#pesquisar) os [cinemas](../../modelagem/lexicos/#cinema) na [região](../../modelagem/lexicos/#local) desejada |Requisito funcional|
|AP06|O aplicativo deve recomendar os [filmes em alta](../../modelagem/lexicos/#filme-em-alta) (destaques) |Requisito funcional|
|AP07|O aplicativo deve recomendar [notícias](../../modelagem/lexicos/#noticia) em alta (destaques) |Requisito funcional|
|AP08|O aplicativo deve exibir as [prevenções](../../modelagem/lexicos/#visualizar-prevencoes) adotadas pelos cinemas referentes a pandemia do covid-19|Requisito funcional|
|AP09|O aplicativo deve deixar claro o que cada medida de [prevenção](../../modelagem/lexicos/#visualizar-prevencoes) significa|Requisito funcional|
|AP10|O [usuário](../../modelagem/lexicos/#usuario) deve se cadastrar utilizando redes sociais ou não|Requisito funcional|
|AP11|O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher o(s) seu(s) [assento](../../modelagem/lexicos/#assento)(s)|Requisito funcional|
|AP12|O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher qual tipo de [ingresso](../../modelagem/lexicos/#ingresso) vai querer|Requisito funcional|
|AP13|O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher o alimento(combo) que irá consumir na [sessão](../../modelagem/lexicos/#sessão)|Requisito funcional|
|AP14|O [usuário](../../modelagem/lexicos/#usuario) deve conseguir efetuar o pagamento de diferentes formas |Requisito funcional|
|AP15|O aplicativo deve identificar o [usuário](../../modelagem/lexicos/#usuario) no pagamento|Requisito funcional|
|AP16|O [usuário](../../modelagem/lexicos/#usuario) deve poder navegar pelo aplicativo sem precisar de um cadastro|Requisito não funcional|
|AP17|O aplicativo deve ser de fácil utilização (intuitivo)|Requisito não funcional|
|AP18|O aplicativo deve ser de fácil instalação|Requisito não funcional|
|AP19|O aplicativo deve ser seguro por lidar com dados sensíveis|Requisito não funcional|
|AP20|O aplicativo deve ser monetizado através de publicidade|Requisito não funcional|

<h6 align = "center">Tabela 2: Tabela contendo os requisitos levantados pela análise de protocolo</h6>
<h6 align = "center">Fonte: Autor</h6>


## 6. Referências

<p style="text-align: justify; text-indent: 20px">[1] SERRANO, Milene; SERRANO, Maurício. <b>Requisitos - Aula 07</b>. 2019. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>












