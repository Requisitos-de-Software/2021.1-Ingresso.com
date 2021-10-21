## 1. Versionamento

| Versão | Data  | Descrição                   | Autor(es) |
| ------ | ----- | --------------------------- | --------- |
| 1.0    | 15/09 | Abertura do documento       | Carlos    |
| 1.1    | 15/09 | Adição da Verificação       | Carlos    |
| 1.2    | 17/10 | Adição do gráfico de resumo | Rafael    |

## 2. Introdução

<p style="text-align: justify; text-indent: 20px">
A verificação consiste em analisar se o modelo ou documento em termos de procedimentos, processo e notação está correto [1]. Baseando-se nisso, este documento tem como objetivo realizar a verificação dos <a href="../../../modelagem/use_case">  User Cases </a>(Casos de Uso).
</p>

## 3. Metodologia

<p style="text-align: justify; text-indent: 20px">
Usando como método a Inspeção, onde o objetivo é encontrar problemas no documento para avaliar se está de acordo com o modelo e com o que se espera [1], um checklist foi criado para os Casos de Uso.
</p>

### 3.1 Checklist

| ID  | Questão                                               | Justificativa                                                                               |
| --- | ----------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| 1   | Especificação condizente com o diagrama?              | A especificação deve condizer com sua referência no diagrama                                |
| 2   | Diagrama segue o padrão UML?                          | Por questão de padronização o diagrama deve seguir a padronização da linguagem UML          |
| 3   | O caso de uso apresenta fluxo principal?              | Deve estar claro na especificação qual o fluxo principal                                    |
| 4   | O caso de uso apresenta oração em tempo presente?     | Por questão de padronização                                                                 |
| 5   | O fluxo de ação segue uma ordem lógica?               | Verificar se fluxo está correto                                                             |
| 6   | O caso de uso possui rastreabilidade?                 | De qual requisito o caso de uso se origina                                                  |
| 7   | As frases representam o diálogo entre ator e sistema? | Necessário para um entendimento claro do caso de uso                                        |
| 8   | O caso de uso apresenta fluxo(s) alternativo(s)?      | Representação e diferenciação de fluxos alternativos                                        |
| 9   | Relacionamentos entre casos de uso necessários?       | Verificar a existência e necessidade de relação entre casos de uso                          |
| 10  | O caso de uso apresenta data?                         | Informação necessária pois aplicativo pode mudar de versão e assim modificar um caso de uso |
| 11  | As setas estão corretas?                              | Verificar se as setas estão indicadas corretamente                                          |
| 12  | Pré-condição bem detalhada?                           | Verificar a descrição da pré-condição                                                       |
| 13  | Pós-condição bem detalhada?                           | Verificar a descrição da pós-condição                                                       |

<h6 align = "center">Tabela 1: Tabela com checklist a ser usado na verificação </h6>
<h6 align = "center">Fonte: Autor</h6>

## 4. Verificação

<b>Legenda:</b>

- UC: Use Case.
- ✅ : Sim.
- ❌ : Não.
- E : Não se aplica.

| UC / Questão | UC01  | UC02  | UC03  | UC04  | UC05  | UC06  | UC07  | UC08  | UC09  | UC10  |
| :----------: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|      1       |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      2       |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      3       |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      4       |   ❌   |   ❌   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      5       |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      6       |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |
|      7       |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      8       |   E   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   E   |
|      9       |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      10      |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |   ❌   |
|      11      |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      12      |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |
|      13      |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |   ✅   |

<h6 align = "center">Tabela 2: Tabela com checklist Casos de Uso </h6>
<h6 align = "center">Fonte: Autor</h6>

## 5. Conclusão
<p style="text-align: justify; text-indent: 20px">
Abaixo foi elaborado um gráfico para melhor visualização da quantidade de casos de uso satisfeitos para cada questão:
</p>

<center>
<iframe width="600" height="360" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ9MTIOOoDp3Ict7aPCGTkI5MhpFi9Vw8ib5_SqdF9RM2ymcUPJwi_W9jkJeVoy4g5zv9DbLMepLuyY/pubchart?oid=884695015&format=interactive"></iframe>
<h6 align="center">Figura 1: Resumo da Verificação dos Casos de Uso</h6>
<h6 align="center">Fonte: Autores</h6>
</center>


<p style="text-align: justify; text-indent: 20px">
Correções sugeridas aos casos de uso:
</p>

<b>Legenda:</b>

- UC: Use Case.

<center>

| UC / Correção | Correções                                                                                                                             |
| :-----------: | ------------------------------------------------------------------------------------------------------------------------------------- |
|     UC01      | - Apresentar oração do caso de uso em tempo presente <br/> - Adicionar rastreabilidade <br/> - Apresentar data criação do caso de uso |
|     UC02      | - Apresentar oração do caso de uso em tempo presente <br/> - Adicionar rastreabilidade <br/> - Apresentar data criação do caso de uso |
|     UC03      | - Adicionar rastreabilidade <br/> - Apresentar data de criação do caso de uso                                                         |
|     UC04      | - Adicionar rastreabilidade <br/> - Apresentar data de criação do caso de uso                                                         |
|     UC05      | - Adicionar rastreabilidade <br/> - Apresentar data de criação do caso de uso                                                         |
|     UC06      | - Adicionar rastreabilidade <br/> - Apresentar data de criação do caso de uso                                                         |
|     UC07      | - Adicionar rastreabilidade <br/> - Apresentar data de criação do caso de uso                                                         |
|     UC08      | - Adicionar rastreabilidade <br/> - Apresentar data de criação do caso de uso                                                         |
|     UC09      | - Adicionar rastreabilidade <br/> - Apresentar data de criação do caso de uso                                                         |
|     UC10      | - Adicionar rastreabilidade <br/> - Apresentar data de criação do caso de uso                                                         |

</center>

<h6 align = "center">Tabela 3: Tabela com correções sugeridas aos Casos de Uso </h6>
<h6 align = "center">Fonte: Autor</h6>

## 6. Referência

<p style="text-align: justify; text-indent: 20px">SERRANO, Maurício; SERRANO, Milene; <b>Requisitos - Aula 23</b>. </p>
