## 1. Versionamento

| Versão | Data  | Descrição                              | Autor(es)       |
| ------ | ----- | -------------------------------------- | --------------- |
| 1.0    | 08/09 | Abertura do documento de NFR Framework | Rafael e Thiago |
| 1.1    | 09/09 | Adição dos gráficos                    | Rafael e Thiago |
| 1.2    | 10/09 | Adição da metodologia                  | Rafael          |

<hr>

## 2. Introdução
<p style="text-align: justify; text-indent: 20px">O NFR Framework é uma maneira de se representar e analisar requisitos não-funcionais, ajudando os desenvolvedores na implementação de soluções personalizadas, tomando em consideração os requisitos funcionais, não funcionais, prioridades e carga de trabalho do domínio de um sistema em questão, no caso o do Ingresso.com [1].</p>

<p style="text-align: justify; text-indent: 20px">A técnica de modelagem acima trata de decompor os requisitos não funcionais a niveis operacionais, facilitando a compreensão, priorização e garantindo que as expectativas dos stakeholders sejam atendidas.</p>
<hr>

## 3. Metodologia

<p style="text-align: justify; text-indent: 20px">Cada tema de diagrama NFR elaborado nesse documento foi retirado dos requisitos não funcionais levantados na <a href="https://requisitos-de-software.github.io/2021.1-Ingresso.com/modelagem/especificacao/">especificação suplementar</a>. Também foram identificados novos requisitos não funcionais ou operacionalizações (requisitos funcionais) que não tinham sido elicitadas em nenhum momento anterior. </p>

Os tipos de contribuição utilizados nos diagramas foram [1]: 

* **AND**: Caso os softgoals descendentes sejam satisfeitos, serão também os ascendentes.
* **OR**: Caso algum softgoal descendentes seja satisfeitos, será também os ascendente.
* **MAKE (++)**: Caso o softgoal descendente for suficientemente satisfeito, será também o
ascendente, porém, a contribuição é fornecida como suficientemente positiva concebida no
nível mais alto de satisfação.
* **HELP (+)**: Caso o softgoal descendente seja parcialmente satisfeito, será parcialmente
satisfeito o ascendente.
* **HURT (-)**: Caso o softgoal descendente seja satisfeito, o softgoal ascendente será
parcialmente negado.

Os rótulos utilizados foram:

* <img src="https://user-images.githubusercontent.com/74625814/132792024-ea80c111-9026-4d63-a9ea-7d1fcdfa3f67.png" width="50"/> Satisfeito.
* <img src="https://user-images.githubusercontent.com/74625814/132792077-05580cd5-a83f-4437-94fc-67e15b82aafa.png" width="50"/> Negado.
* <img src="https://user-images.githubusercontent.com/74625814/132791951-ffad085e-c92e-47d0-9cdd-e3aedefc58e2.png" width="50"/> Fracamente satisfeito. 
* <img src="https://user-images.githubusercontent.com/74625814/132792526-b64033fa-2bf4-449c-9e96-0263a458c3d4.png" width="50"/> Fracamente negado.

## 4. Gráfico de Interdependência de Softgoal

### 4.1 Usabilidade

<img class="zoom" src="../../assets/modelagem/nfr/nfr_usabilidade.png">
<h6 align = "center">Figura 1: SIG de usabilidade</h6>
<h6 align = "center">Fonte: Autores</h6>
<hr>

### 4.2 Usabilidade com propagação

<img class="zoom" src="../../assets/modelagem/nfr/nfr_usabilidade_propagacao.png">
<h6 align = "center">Figura 2: SIG de usabilidade com propagaçao</h6>
<h6 align = "center">Fonte: Autores</h6>
<hr>

### 4.4 Confiabilidade

<img class="zoom" src="../../assets/modelagem/nfr/nfr_confiabilidade.png">
<h6 align = "center">Figura 3: SIG de confiabilidade</h6>
<h6 align = "center">Fonte: Autores</h6>
<hr>

### 4.4 Confiabilidade com propagação

<img class="zoom" src="../../assets/modelagem/nfr/nfr_confiabilidade_propagacao.png">
<h6 align = "center">Figura 4: SIG de confiabilidade com propagação</h6>
<h6 align = "center">Fonte: Autores</h6>
<hr>

### 4.5 Desempenho

<img class="zoom" src="../../assets/modelagem/nfr/nfr_desempenho.png">
<h6 align = "center">Figura 5: SIG de desempenho</h6>
<h6 align = "center">Fonte: Autores</h6>
<hr>

### 4.6 Desempenho com propagação

<img class="zoom" src="../../assets/modelagem/nfr/nfr_desempenho_propagacao.png">
<h6 align = "center">Figura 6: SIG de desempenho com propagação</h6>
<h6 align = "center">Fonte: Autores</h6>
<hr>

### 4.7 Suportabilidade

<img class="zoom" src="../../assets/modelagem/nfr/nfr_suportabilidade.png">
<h6 align = "center">Figura 7: SIG de suportabilidade</h6>
<h6 align = "center">Fonte: Autores</h6>
<hr>

### 4.8 Suportabilidade com propagação

<img class="zoom" src="../../assets/modelagem/nfr/nfr_suportabilidade_propagacao.png">
<h6 align = "center">Figura 8: SIG de suportabilidade com propagação</h6>
<h6 align = "center">Fonte: Autores</h6>
<hr>

## 5. Referências 

<p style="text-align: justify; text-indent: 20px">[1] SILVA, Reinaldo Antônio da. <b>NFR4ES:Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados</b>. Recife, 2019</p>