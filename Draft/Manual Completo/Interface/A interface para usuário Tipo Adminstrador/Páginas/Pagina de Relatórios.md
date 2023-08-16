
Esse pagina permite que o administrador gere relatórios sobre as entradas feitas sistema

A pagina é divida em três partes:
 - Criterio de pesquisa
 - Opções de apresentação
 - Resultados 
 
Sendo que cada parte contem o seu conjunto de campos e componentes 
###### Componentes e campos da parte de Critérios de pesquisa: 
Nessa parte contem  os dados usados para buscar as entradas 

###### Campo Data Inicio
Esse campo determina a data  inicial a ser incluída no relatório
##### Campo Data Fim
Esse campo determina a data final a ser incluída no relatório
###### Campo Área
Determina a area a ser utilizada no relatorio.

###### Campo Sala
Determina qual sala a ser utilizada no relatorio

###### Campo Tipo 
Determina qual o tipo de entrada a ser utilizado pela relatório

###### Campo Breve descrição
Determina o texto a ser buscado nos campo Breve descrição das entradas e retorna apenas as entradas com este texto

###### Campo Descrição Completa
Determina o texto a ser buscado nos campo Descrição Completa das entradas e retorna apenas as entradas com este texto

###### Campo Marcado Por
Determina o texto a ser buscado nos campo Marcado Por das entradas e retorna apenas as entradas com este texto.

###### Campo Estado da Reserva:
Determina o valor do estado da reserva e retorna apenas aquelas que tem o estado selecionado. 

#####  Componentes e campos da parte das Opções de Apresentação:
Nessa parte contem as opções quanto como será exibido o resultado da busca 

###### Campo Saída
Esse campo determina qual o tipo saída da busca
Esse campo permite a geração de relatórios ou sumários, sendo o primeiro lista toda as entradas de acordo com os critérios fornecidos acima, o Sumário gera uma somatória de horas de uso das salas de a acordo com os critérios fornecidos acima.

###### Campo Formato
O campo formato determina qual o formato será exibido, sendo os formatos disponiveis:
- HTML
- CSV
- iCalendar (.ics)
Apenas o formato HTML é exibido no site sendo que os outros formatos geram o download de um arquivo.
O Arquivo CSV e a opção para importação para o excel, e o formato .ics permite a importação de volta para o sistema ou a adição em outros sistemas como Google Calendar e Calendar do iCloud. 

###### Campo Sumário Por
Esse campo determina qual o critério a ser usado para as linhas exibidas no sumário
Esse Campo somente é pertinente caso a saída seja igual a Sumário


##### Resultados

Essa parte somente é exibida caso o tipo de saída seja definido como HTML.
Para outras opções apenas seja gerado o arquivo correspondente
Caso seja selecionado o tipo sumário será apresentado uma tabela contendo as informações obtidas do resultado, sendo a mesma sem interatividade apenas uma visualização estática.
Case seja selecionado o tipo relatório, será apresentado uma listagem, que permite acessar as entradas e outras opções interativas, sendo os campos e componentes do relatório:
(Inserir figura do relatório)


*Barra de controle da listagem*
A barra de controle da listagem  ( Inserir o numero correspondente na figura acima ) permite editar o que visualizado na listagem.

**Exibir / Esconder colunas** 
O Botão Exibir / Esconder Colunas  (Inserir o numero correspondente na figura acima) permite esconder ou exibir colunas da listagem de salas.

**Copia**
O Botão Copiar  (Inserir o numero correspondente na figura acima) copia para a sua área de transferência os dados que estão sendo exibidos na listagem

**CSV**
O Botão CSV  (Inserir o numero correspondente na figura acima)  Gera um arquivo CSV contendo o que está sendo exibidos na listagem

**Excel**
O Botão Excel  (Inserir o numero correspondente na figura acima)  Gera um arquivo Excel contendo o que está sendo exibidos na listagem

**PDF**
O Botão PDF  (Inserir o numero correspondente na figura acima)  Gera um arquivo PDF contendo o que está sendo exibidos na listagem

**Imprimir**
O Botão Imprimir(Inserir o numero correspondente na figura acima)  Permite imprimir os dados que estão sendo exibidos na listagem

**Seletor de Numero de resultados**
O campo Seletor de Numero de resultados  (Inserir o numero correspondente na figura acima) , controla quantos resultado são exibidos por página de listagem de Salas.

*Campo de Busca*
O campo de Busca  (Inserir o numero correspondente na figura acima)  Permite filtrar os resultados exibidos na listagem de salas 

*Listagem de Salas*
O componente Listagem de Salas (Inserir o numero correspondente na figura acima) Exibe as Salas pertinentes à aquela área. 

*Paginador*
O componente Paginador (Inserir o numero correspondente na figura acima)  Permite navegar pela paginas de listagem caso o numero de itens na listagem seja maior que o selecionado no campo  Seletor de Numero de resultados.






