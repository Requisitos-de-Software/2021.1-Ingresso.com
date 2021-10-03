## 1. Versionamento
|Versão|Data|Descrição|Autor(es)|
|------|----|---------|---------|
|1.0|09/08|Criação do documento|Carlos Eduardo|
|1.1|09/08|Adição do resultado|Carlos Eduardo|
|1.2|03/10|Linkagem dos léxicos|Thiago|

## 2. Introdução
<p style="text-align: justify; text-indent: 20px">A técnica de elicitação observação participativa compreende do engenheiro de software se passar como um <a href="../../modelagem/lexicos/#usuario">usuário</a> do aplicativo, o que o leva a observar aspectos, funcionalidades e características para documentar os requisitos do sistema. [1]</p>

## 3. Resultado
- Data de realização da observação: 09/08/2021
- Versão do aplicativo: 3.1.4 Build 192

### 3.1. Requisitos

|ID|<p style="text-align: center" >Descrição</p>|<p style="text-align: center" >Tipo de Requisito</p>|
|----|----|--|
|OP01|O [usuário](../../modelagem/lexicos/#usuario) deve poder se [cadastrar](../../modelagem/lexicos/#cadastrar-usuario) inserindo como quer ser chamado, e-mail, senha data de aniversário, gênero, cadastro de pessoa física, DDD e telefone, endereço composto por (logradouro número, complemento, referência, bairro, estado e cidade)|<p style="text-align: center">Requisito Funcional</p>|
|OP02|O [usuário](../../modelagem/lexicos/#usuario) deve poder entrar com email e senha, conta do google ou facebook|<p style="text-align: center">Requisito Funcional</p>|
|OP03|O [usuário](../../modelagem/lexicos/#usuario) deve poder visualizar senha digitada|<p style="text-align: center">Requisito Funcional</p>|
|OP04|O [usuário](../../modelagem/lexicos/#usuario) deve poder recuperar senha|<p style="text-align: center">Requisito Funcional</p>|
|OP05|O sistema deve enviar um email de recuperação de senha|<p style="text-align: center">Requisito Funcional</p>|
|OP06|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver seus dados pessoais|<p style="text-align: center">Requisito Funcional</p>|
|OP07|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver seus [pedidos](../../modelagem/lexicos/#pedido)|<p style="text-align: center">Requisito Funcional</p>|
|OP08|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver seus Cartões Salvos|<p style="text-align: center">Requisito Funcional</p>|
|OP09|O [usuário](../../modelagem/lexicos/#usuario) deve poder sair da conta logada|<p style="text-align: center">Requisito Funcional</p>|
|OP10|O [usuário](../../modelagem/lexicos/#usuario) deve poder trocar a cidade de [localização](../../modelagem/lexicos/#local) dos [cinemas](../../modelagem/lexicos/#cinema)|<p style="text-align: center">Requisito Funcional</p>|
|OP11|O [usuário](../../modelagem/lexicos/#usuario) deve poder acessar Políticas e Regras do sistema|<p style="text-align: center">Requisito Funcional</p>|
|OP12|O [usuário](../../modelagem/lexicos/#usuario) deve poder enviar uma solicitação de atendimento|<p style="text-align: center">Requisito Funcional</p>|
|OP13|O [usuário](../../modelagem/lexicos/#usuario) deve poder acessar informações sobre o aplicativo|<p style="text-align: center">Requisito Funcional</p>|
|OP14|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [filmes em alta](../../modelagem/lexicos/#filme-em-alta)|<p style="text-align: center">Requisito Funcional</p>|
|OP15|O [usuário](../../modelagem/lexicos/#usuario) deve poder acessar [filmes em Alta](../../modelagem/lexicos/#filme-em-alta)|<p style="text-align: center">Requisito Funcional</p>|
|OP16|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [notícias](../../modelagem/lexicos/#noticia) em Alta|<p style="text-align: center">Requisito Funcional</p>|
|OP17|O [usuário](../../modelagem/lexicos/#usuario) deve poder acessar [notícias](../../modelagem/lexicos/#noticia) em alta|<p style="text-align: center">Requisito Funcional</p>|
|OP18|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [cinemas](../../modelagem/lexicos/#cinema) abertos próximos a sua [localização](../../modelagem/lexicos/#local)|<p style="text-align: center">Requisito Funcional</p>|
|OP19|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [filmes](../../modelagem/lexicos/#filme) que vão estar nos [cinemas](../../modelagem/lexicos/#cinema) em [breve](../../modelagem/lexicos/#filme-em-breve)|<p style="text-align: center">Requisito Funcional</p>|
|OP20|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver título, categoria, classificação indicativa, avaliação, duração, elenco, sinopse, direção, distribuidor e país de origem do [filme](../../modelagem/lexicos/#filme) selecionado|<p style="text-align: center">Requisito Funcional</p>|
|OP21|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver sessões disponíveis do [filme](../../modelagem/lexicos/#filme) selecionado|<p style="text-align: center">Requisito Funcional</p>|
|OP22|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver as [sessões](../../modelagem/lexicos/#sessao) do [filme](../../modelagem/lexicos/#filme) selecionado por dia da semana|<p style="text-align: center">Requisito Funcional</p>|
|OP23|O [usuário](../../modelagem/lexicos/#usuario) deve poder filtrar [sessões](../../modelagem/lexicos/#sessao) do [filme](../../modelagem/lexicos/#filme) selecionado por Tipos de Exibição|<p style="text-align: center">Requisito Funcional</p>|
|OP24|O [usuário](../../modelagem/lexicos/#usuario) deve poder limpar filtros selecionados|<p style="text-align: center">Requisito Funcional</p>|
|OP25|O [usuário](../../modelagem/lexicos/#usuario) deve poder [compartilhar filme](../../modelagem/lexicos/#compartilhar)|<p style="text-align: center">Requisito Funcional</p>|
|OP26|O [usuário](../../modelagem/lexicos/#usuario) deve poder assistir trailer do [filme](../../modelagem/lexicos/#filme)|<p style="text-align: center">Requisito Funcional</p>|
|OP27|O [usuário](../../modelagem/lexicos/#usuario) deve poder ordenar [cinemas](../../modelagem/lexicos/#cinema) por nome ou proximidade|<p style="text-align: center">Requisito Funcional</p>|
|OP28|O [usuário](../../modelagem/lexicos/#usuario) deve poder [favoritar cinemas](../../modelagem/lexicos/#cinema-esta-favoritado)|<p style="text-align: center">Requisito Funcional</p>|
|OP29|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver nome, logo e endereço do [cinema](../../modelagem/lexicos/#cinema)|<p style="text-align: center">Requisito Funcional</p>|
|OP30|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver as [sessões](../../modelagem/lexicos/#sessao) do [cinema](../../modelagem/lexicos/#cinema)|<p style="text-align: center">Requisito Funcional</p>|
|OP31|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver as Prevenções do [cinema](../../modelagem/lexicos/#cinema)|<p style="text-align: center">Requisito Funcional</p>|
|OP32|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver Sobre o [cinema](../../modelagem/lexicos/#cinema)|<p style="text-align: center">Requisito Funcional</p>|
|OP33|O [usuário](../../modelagem/lexicos/#usuario) deve poder [compartilhar cinema](../../modelagem/lexicos/#compartilhar)|<p style="text-align: center">Requisito Funcional</p>|
|OP34|O [usuário](../../modelagem/lexicos/#usuario) deve poder filtrar [sessões](../../modelagem/lexicos/#sessao) do [cinema](../../modelagem/lexicos/#cinema) por Tipo de Exibição|<p style="text-align: center">Requisito Funcional</p>|
|OP35|O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher os [assentos disponíveis](../../modelagem/lexicos/#assento-disponivel) da [sessão](../../modelagem/lexicos/#sessao)|<p style="text-align: center">Requisito Funcional</p>|
|OP36|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver a legenda da [escolha de assentos](../../modelagem/lexicos/#escolher-assento)|<p style="text-align: center">Requisito Funcional</p>|
|OP37|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver os números dos [assentos](../../modelagem/lexicos/#assentos)|<p style="text-align: center">Requisito Funcional</p>|
|OP38|O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher o tipo de cada [ingresso](../../modelagem/lexicos/#ingresso) selecionado|<p style="text-align: center">Requisito Funcional</p>|
|OP39|O [usuário](../../modelagem/lexicos/#usuario) deve poder fornecer as informações do tipo de [ingresso](../../modelagem/lexicos/#ingresso) selecionado|<p style="text-align: center">Requisito Funcional</p>|
|OP40|O [usuário](../../modelagem/lexicos/#usuario) deve poder escolher qual a forma de pagamento|<p style="text-align: center">Requisito Funcional</p>|
|OP41|O [usuário](../../modelagem/lexicos/#usuario) deve poder cadastrar formas de pagamento|<p style="text-align: center">Requisito Funcional</p>|
|OP42|O [usuário](../../modelagem/lexicos/#usuario) deve poder aplicar código de desconto no pagamento|<p style="text-align: center">Requisito Funcional</p>|
|OP43|O [usuário](../../modelagem/lexicos/#usuario) deve poder poder ver [carrinho](../../modelagem/lexicos/#Carrinho) com as [sessões](../../modelagem/lexicos/#sessao) selecionadas|<p style="text-align: center">Requisito Funcional</p>|
|OP44|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver formas de retirada de [ingresso](../../modelagem/lexicos/#ingresso) disponíveis para as sessões|<p style="text-align: center">Requisito Funcional</p>|
|OP45|O [usuário](../../modelagem/lexicos/#usuario) deve poder remover sessões do [Carrinho](../../modelagem/lexicos/#Carrinho)|<p style="text-align: center">Requisito Funcional</p>|
|OP46|O [usuário](../../modelagem/lexicos/#usuario) deve poder resgatar [ingresso](../../modelagem/lexicos/#ingresso) da [sessão](../../modelagem/lexicos/#sessao)|<p style="text-align: center">Requisito Funcional</p>|
|OP47|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [cinemas](../../modelagem/lexicos/#cinema) favoritados|<p style="text-align: center">Requisito Funcional</p>|
|OP48|O [usuário](../../modelagem/lexicos/#usuario) deve poder [ver notícias](../../modelagem/lexicos/#ler-noticia)|<p style="text-align: center">Requisito Funcional</p>|
|OP49|O [usuário](../../modelagem/lexicos/#usuario) deve poder [ver prevenções](../../modelagem/lexicos/#visualizar-prevencoes)|<p style="text-align: center">Requisito Funcional</p>|
|OP50|O [usuário](../../modelagem/lexicos/#usuario) deve poder ver [filmes em cartaz](../../modelagem/lexicos/#filme-em-cartaz) |<p style="text-align: center">Requisito Funcional</p>|
|OP51|O [usuário](../../modelagem/lexicos/#usuario) deve poder sair da conta|<p style="text-align: center">Requisito Funcional</p>|
|OP52|O [usuário](../../modelagem/lexicos/#usuario) deve poder pesquisar [cinemas](../../modelagem/lexicos/#cinema) por iniciativas de prevenção|<p style="text-align: center">Requisito Funcional</p>|
|OP53|O [usuário](../../modelagem/lexicos/#usuario) deve poder alterar senha|<p style="text-align: center">Requisito Funcional</p>|
|OP54|O [usuário](../../modelagem/lexicos/#usuario) deve poder alterar seus dados pessoais|<p style="text-align: center">Requisito Funcional</p>|
|OP55|O [usuário](../../modelagem/lexicos/#usuario) deve poder optar por receber novidades e mensagens do aplicativo|<p style="text-align: center">Requisito Funcional</p>|
|OP56|O sistema deve enviar novidades e mensagens para o [usuário](../../modelagem/lexicos/#usuario) pelo email|<p style="text-align: center">Requisito Funcional</p>|
|OP57|O [usuário](../../modelagem/lexicos/#usuario) deve poder editar ou excluir seus cartões salvos|<p style="text-align: center">Requisito Funcional</p>|
|OP58|O sistema deve enviar um email confirmando a compra de [ingressos](../../modelagem/lexicos/#ingressos)|<p style="text-align: center">Requisito Funcional</p>|

<h6 align = "center">Tabela 1: Tabela contendo os requisitos elicitados</h6>
<h6 align = "center">Fonte: Autor</h6>

## 4. Referências
<p style="text-align: justify; text-indent: 20px">[1] SERRANO, Maurício; SERRANO, Milene; <b>Requisitos - Aula 07</b>. </p>
