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
Seus subcampos são:

*Barra de controle da listagem*

Seletor de Numero de resultados*

**Exibir / Esconder colunas** 

**Copia**

**CSV**

**Excel**

**PDF**

**Imprimir**

*Campo de Busca*

*Listagem de Salas*

*Paginador*







