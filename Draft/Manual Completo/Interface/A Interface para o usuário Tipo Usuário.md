## Entendo a interface de usuário do MRBS
O MRBS apresenta uma interface relativamente simples quanto à sua função sendo a parte mais importante do sistema está em sua tela principal e a tela de edição/ criação de entradas.

### Paginas do Sistema
Os usuário com a permissão Usuário ou seja do tipo Usuário apresenta as seguintes telas disponíveis para acesso:
- Pagina Principal
- Pagina de Criação e edição e de entradas 
- Pagina de Ajuda
- Pagina de Salas
- Pagina de Listagem de usuários
- A Pagina de usuário
- Pagina de pesquisa de entrada

Cada pagina tem a sua função e a sua utilidade que será descrita nessa parte do manual

#### A Pagina principal do MRBS

A Pagina Principal do sistema é a mesma pagina que é exibida ao entrar no sistema sem estar logado.
Essa pagina é o coração pulsante do sistema e nessa pagina é onde a grande parte das operações diárias serão executadas.
(Inserir aqui figura contendo a pagina principal )
A Pagina principal contem varias partes sendo elas:

##### Componentes pagina principal 
###### Cabeçalho

O cabeçalho tem a função de oferecer opções de navegação no sistema
(Inserir Figura do cabeçalho)


###### Barra lateral esquerda
A Barra lateral contem os minicalendários para poder visualizar e acessar datas da agenda

###### Área  da Agenda
A área da agenda contem no topo opções de navegação para datas futuras e passadas, ao centro contém a caixa de seleção do andar, direita a opção de visualização para a agenda e logo abaixo centralizado a listagem de salas  em forma de linhas e os horários  disponíveis em forma de coluna.
(Inserir aqui  figura da área de agenda )

As Linhas estão subdivididos em 30 minutos, sendo esse o período mínimo para uma reunião  

**Horários vagos VS. Horários Ocupado** 
Como uma agenda, o sistema MRBS tem os dois conceitos e logo somente é permitido a criação  de uma nova entrada em horários que estão vagos.
O sistema diferencia essa disponibilidade da seguinte forma:

*Horário Vago:*
O Horário vago em geral se apresenta na forma de espaço em branco na agenda
(Inserir figura contendo horário vago )

*Horário Ocupado:*
O Horário ocupado em geral se apresenta na forma de um preenchimento na cor verde, podendo ser um preenchimento inteiriço ou de forma gradual caso a marcação permita  o registro de convidados, sendo que assim que a marcação tenha sido lotada completamente a indicação de horário ocupado será completamente preenchida.


#### Pagina de criação ou edição de Entrada
Talvez a segunda página mais importante, logo após a pagina de entrada.
Nessa pagina você irá adicionar dados sobre a entrada que deseja marcar. 
(Inserir Figura contendo a pagina citada)
##### Campos da página de criação e/ou edição de entrada
O Sistema MRBS vai automaticamente preencher alguns campos para você conforme como você iniciou a criação da entrada. (Vide o capitulo de Ações, dentro da ação Criação de Entrada)
Como por exemplo: caso tenha arrastado o começo e o fim da entrada na pagina principal  o sistema irá automaticamente preencher os campos Inicio e Fim de acordo com o que foi arrastado.

###### Descrição Breve
O campo Descrição Breve ( Inserir o numero correspondente na figura acima) contém o nome da entrada, ou seja o nome da reunião

###### Descrição completa
O campo Descrição Completo ( Inserir o numero correspondente na figura acima) contém uma descrição mais detalhada da entrada.

###### Inicio
O campo Inicio ( Inserir o numero correspondente na figura acima ) contém a data e hora de inicio da entrada. Campo também inclui a opção de Todo Dia que faz com que a entrada tenha o seu fim correspondendo ao fim do dia de trabalho e ao mesmo tempo desabilita o campo Fim.

###### Fim
O campo Fim( Inserir o numero correspondente na figura acima) contém a data e hora de fim da entrada.

###### Área
O campo Área ( Inserir o numero correspondente na figura acima) contém a área da entrada.
A área nesse contexto seria o andar em que se encontra a sala de reunião, em geral esse campo é auto preenchido com os dados advindos da pagina principal mas nada impede que esse campo seja alterado.

###### Salas
O campo Salas( Inserir o numero correspondente na figura acima) contem a listagem de todas as salas que pertencem à aquela área e a sala selecionada é a sala que será utilizada

###### Tipo
O campo Tipo( Inserir o numero correspondente na figura acima) contém o tipo da entrada, sendo que o tipo Interno é para entradas solicitadas de forma interna, ou seja advindas do mesmo andar, e o tipo Externo é para entradas que são advindas de solicitações externas.

###### Estado da reserva
O campo Estado da reserva ( Inserir o numero correspondente na figura acima) contém se a reserva já esta confirmada ou se apenas uma intenção de uso. 

###### Repetir Tipo
O campo Repetir Tipo( Inserir o numero correspondente na figura acima) define se a entrada irá repetir e o regime de repetição.


###### Voltar
O botão voltar ( Inserir o numero correspondente na figura acima) volta à pagina anterior sem salvar as alterações.


###### Salvar 
O botão Salvar ( Inserir o numero correspondente na figura acima) salva as alterações feitas e edita ou cria a entrada.

###### Indicador de conflitos de agenda 
O Indicador de conflitos de agenda ( Inserir o numero correspondente na figura acima)mostra se existe algum conflito na agenda com a marcação que está sendo atualmente editada. 
Ao clicar no indicado aparecerá uma janela exibindo os conflitos encontrados.
Conflitos são por exemplo duas reuniões marcadas na mesma sala no mesmo horário, sendo que a precedência é daquela entrada que foi criada anteriormente.

###### Indicador de conflitos de politica 
O Indicador de conflitos de politica ( Inserir o numero correspondente na figura acima)mostra se existe algum conflito quanto a politicas definidas na aplicação com a marcação que está sendo atualmente editada. 
Ao clicar no indicado aparecerá uma janela exibindo os conflitos encontrados.
Conflitos de politica  são por exemplo uma marcação que não segue as politicas definidas na aplicação. 
No momento nenhuma politica está em vigor logo não será necessário se preocupar com esse indicador. 

#### Pagina de visualização de salas
Esse página contem a listagem de cada sala por andar, permitindo assim que se visualize as salas e também se visualize detalhes de cada sala. 
A página contém vários  campos e componentes para obter os dados desejados. 
(Inserir aqui figura contendo a pagina principal )
##### Componentes pagina de visualização de salas

###### Campo Área
O campo Área ( Inserir o numero correspondente na figura acima) permite selecionar qual área deseja visualizar.

###### Componente Listagem de salas
O componente Listagem de salas ( Inserir o numero correspondente na figura acima) contém vários sub campos e permite ao usuário buscar e exibir uma listagem de todas as salas que pertencem à área.
(Inserir figura contendo o componente)
Seus subcampos  e subcomponentes são:

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

#### Pagina de visualização de usuários
Esse página contem a listagem de usuários do sistema, mas permite que apenas edite as informações pertinentes ao seu usuário

A página contém vários  campos e componentes para obter os dados desejados.
Esses componentes são  quase idênticos aos que são usados na pagina de visualização de sala.
(Inserir aqui figura contendo a pagina principal )

##### Componentes pagina de visualização de usuários

###### Componente Listagem de usuários
O componente Listagem de Usuários ( Inserir o numero correspondente na figura acima) contém vários sub campos e permite ao usuário buscar e exibir uma listagem dos usuários
(Inserir figura contendo o componente)
Seus subcampos  e subcomponentes são:

*Barra de controle da listagem*
A barra de controle da listagem  ( Inserir o numero correspondente na figura acima ) permite editar o que visualizado na listagem.

**Exibir / Esconder colunas** 
O Botão Exibir / Esconder Colunas  (Inserir o numero correspondente na figura acima) permite esconder ou exibir colunas da listagem de usuários.

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
O campo de Busca  (Inserir o numero correspondente na figura acima)  Permite filtrar os resultados exibidos na listagem de usuários

*Listagem de Usuários*
O componente Listagem de Usuários (Inserir o numero correspondente na figura acima), Exibe uma listagem de todos os usuários, sendo que o seu usuário aparece em negrito e permite que seja clicado para editar as informações.

*Paginador*
O componente Paginador (Inserir o numero correspondente na figura acima)  Permite navegar pela paginas de listagem caso o numero de itens na listagem seja maior que o selecionado no campo  Seletor de Numero de resultados.


#### Pagina de edição do usuário
Essa Página permite que você edite as informações pertinentes ao seu usuário. 
Essa pagina contem vários campos para essa função.

##### Campos pagina de visualização de usuários

######  Campo Direitos
Esse Campo (Inserir o numero correspondente na figura acima)  não e disponível para o usuário alterar sendo somente permitido à usuários  do tipo administrador.
Esse campo alterar o tipo de usuário no sistema
###### Campo Nome de usuário (username)
Esse Campo (Inserir o numero correspondente na figura acima) não e disponível para o usuário alterar sendo somente permitido à usuários  do tipo administrador.
Esse Campo alterar o seu nome de usuário

###### Campo Nome 
Esse Campo (Inserir o numero correspondente na figura acima)  não e disponível para o usuário alterar sendo somente permitido à usuários  do tipo administrador.
Esse Campo altera o seu nome usado no sistema

###### Campo Endereço de E-mail
Esse Campo (Inserir o numero correspondente na figura acima) é alterável pelo usuário do tipo usuário.
Esse campo altera o e-mail utilizado pelo sistema


###### Campos Senha Acesso
Esse Campo (Inserir o numero correspondente na figura acima)  se repete duas vezes e permite o usuário editar a sua senha de acesso sendo necessário repetir a senha em ambos os campos para validar a alteração

###### Botão Voltar
Esse botão  (Inserir o numero correspondente na figura acima) volta à pagina anterior sem salvar as alterações feitas.

###### Botão Salvar 
Esse botão (Inserir o numero correspondente na figura acima) permite salvar as alterações feitas na pagina

#### Pagina de busca
A Pagina de busca permite buscar entradas feitas usando um texto de busca 
(Inserir Figura contendo a pagina citada)
##### Campos e componentes  pagina de visualização de usuários
Os campos e componentes se divide em duas parte a primeira sendo para executar a buscar e a segunda que contem os resultados gerados pela busca feita. 

###### Parte de Pesquisa
(Inserir Figura contendo a parte citada)
A parte de pesquisa contem meios de buscar as entradas feitas no sistema

*Campos e componentes da parte de pesquisa*

**Campo Pesquisar por**
Esse campo  (Inserir o numero correspondente na figura acima) é onde e colocado o texto que deseja pesquisar.

**Campo De**
Esse campo (Inserir o numero correspondente na figura acima) permite alterar a data mínima da criação da entrada a ser incluída na busca.

**Botão Pesquisar**
Esse Botão (Inserir o numero correspondente na figura acima) executa a busca e retorna os resultados

###### Parte de Resultados
(Inserir Figura contendo a parte citada)
Essa parte exibe os resultados retornados pela pesquisa. caso a pesquisa retorne nenhum resultado essa parte fica escondida e não exibe os componentes abaixo citado.
Podendo também exibir erros caso dados inválidos seja inseridos no campo de pesquisa.

*Campos e componentes da parte de pesquisa*

Os componentes usados no resultado da pesquisa são os mesmos usados na pagina de listagem de usuários e salas, apenas alterando os dados exibidos.  

O componente da parte de pesquisa ( Inserir o numero correspondente na figura acima) contém vários sub campos e permite ao usuário buscar e exibir uma listagem dos resultados obtidos pela pesquisa
(Inserir figura contendo o componente)
Seus subcampos  e subcomponentes são:

*Barra de controle da listagem*
A barra de controle da listagem  ( Inserir o numero correspondente na figura acima ) permite editar o que visualizado na listagem.

**Exibir / Esconder colunas** 
O Botão Exibir / Esconder Colunas  (Inserir o numero correspondente na figura acima) permite esconder ou exibir colunas da listagem de resultados.

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
O campo Seletor de Numero de resultados  (Inserir o numero correspondente na figura acima) , controla quantos resultado são exibidos na listagem

*Campo de Busca*
O campo de Busca  (Inserir o numero correspondente na figura acima)  Permite filtrar os resultados exibidos na listagem de resultados da pesquisa

*Listagem de Resultados*
O componente Listagem de Resultados (Inserir o numero correspondente na figura acima), Exibe uma listagem com os resultados sendo que somente é possível editar as entradas feitas pelo usuário

*Paginador*
O componente Paginador (Inserir o numero correspondente na figura acima)  Permite navegar pela paginas de listagem caso o numero de itens na listagem seja maior que o selecionado no campo  Seletor de Numero de resultados.

