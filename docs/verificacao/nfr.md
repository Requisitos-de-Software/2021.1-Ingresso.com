## 1. Versionamento
| Versão | Data  | Descrição                                     | Autor(es) |
| ------ | ----- | --------------------------------------------- | --------- |
| 1.0    | 14/09 | Abertura do documento e adição da verificação | Thiago |

## 2. Introdução

<p style="text-align: justify; text-indent: 20px"> 
A verificação corresponde a uma metodologia que visa garantir que os produtos de um trabalho selecionado cumpram com seus requisitos especificados [1]. Essa etapa, também consiste de uma técnica que não depende da intervenção humana dos usuários, sendo feita através do viés do desenvolvedor. Sendo assim, o escopo desta verificação se limita ao documento de modelagem <a href="../../modelagem/nfr_framework">NFR Framework</a>.
</p>

## 3. Metodologia
<p style="text-align: justify; text-indent: 20px"> Para a realização dessa verificação, será utilizada a técnica de inspeção pela estratégia de leitura e checklist, os critérios abordados têm o papel de contribuir para verificar se de fato o NFR Framework atende a seu propósito e também identifica os defeitos, possibilitando uma correção. Os critérios podem ser respondidos com "✔" (Sim) ou "✖" (Não), onde o Não provavelmente evidencia algum defeito que precisa ser melhorado.</p>

## 4. Verificação

|Número|Questões|Usabilidade|Confiabilidade|Desempenho|Suportabilidade|
|:-:|---|:-:|:-:|:-:|:-:|
|1|O fluxo do diagrama está bem representado?|✔|✔|✔|✔|
|2|Os softgoals condizem com o contexto?|✔|✔|✔|✔|
|3|Os softgoals são decompostos em operacionalizações?|✔|✔|✔|✔|
|4|Existem softgoals suficientes no diagrama para representar o contexto?|✔|✔|✔|✔|
|5|As operacionalizações condizem com o contexto?|✔|✔|✔|✔|
|6|Existem operacionalizações suficientes no diagrama para representar o contexto?|✔|✔|✖|✔|
|7|As contribuições dos impactos estão devidamente embasadas?|✔|✔|✔|✔|
|8|A propagação está bem representada?|✔|✔|✔|✔|
|9|Os impactos estão propagados corretamente ?|✔|✔|✔|✔|
|10|As contribuições AND estão corretamente representadas e aplicadas?|✔|✔|✖|✔|
|11|As contribuições OR estão corretamente representadas e aplicadas?|✔|✔|✔|✔|
|12|Existem contribuições negativas?|✖|✔|✖|✖|
|13|As contribuições positivas estão corretamente representadas e aplicadas?|✔|✔|✔|✔|
|14|As contribuições negativas estão corretamente representadas e aplicadas?|✔|✔|✔|✔|
||**Porcentagem Total**|93%|100%|79%|93%|


## 5. Conclusão

<p style="text-align: justify; text-indent: 20px"> 
De acordo com a verificação, o documento NFR Framework se encontra de acordo com os padrões esperados. No entanto, a confecção da maioria dos Gráfico de Interdependência de Softgoal acabou priorizando apenas as contribuições positivas e esquecendo das negativas. As contribuições negativas são muito importantes, uma vez que permitirá que o desenvolvedor tenha conhecimento daquilo que não se deve fazer para atingir um determinado objetivo. Assim, essa verificação contribuirá bastante com a elaboração e aprimoramento da modelagem feita pela a equipe.
</p>

## 6. Bibliografia

<p style="text-align: justify; text-indent: 20px">[1] SERRANO, Milene; SERRANO, Maurício. <b>Requisitos - Aula 10</b>. 2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.</p>