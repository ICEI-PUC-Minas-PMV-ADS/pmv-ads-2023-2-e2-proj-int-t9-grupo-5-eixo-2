# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

| **Caso de Teste** | **CT-01 - Inventariar os produtos** |
|:---:	|:---:	|
| Requisito Associado | RF-001 - O usuário poderá inventariar os produtos.(de forma q seja possivel contar os items sempre que nescessario). |
| Objetivo do Teste | Verificar se o usuário consege inventariar produtos |
| Passos | - Acessar o navegador <br> - Fornecer informações do produto <br> - Clicar para registrar produto <br> |
| Critério de Êxito | - O produto foi registrado com as informações corretas bem como o número correto da quantidade em estoque |

| **Caso de Teste** | **CT-02 - Filtros e subfiltros** |
|:---:	|:---:|
| Requisito Associado | RF-003 - Aplicação de Filtros e subfiltros |
| Objetivo do Teste | Verificar se o usuário consege filtrar produtos |
| Passos | - Acessar o navegador <br> - Fornecer informações do produto <br> - Clicar para filtrar o produto<br> |
| Critério de Êxito | - O produto apresentado ao usuário está de acordo com os filtros e subfiltros fornecdios por ele |

| **Caso de Teste** | **CT-03 - Pesquisa de Itens** |
|:---:	|:---:|
| Requisito Associado | RF-004 - O usuário deve conseguir pesquisar por itens no estoque |
| Objetivo do Teste | Verificar se o usuário consege encontrar itens através da ferramenta de busca |
| Passos | - Acessar o navegador <br> - Fornecer nome do produto no campo de busca <br>|
| Critério de Êxito | - O produto apresentado ao usuário está de acordo com a informação por ele inserida no campo de busca |

| **Caso de Teste** | **CT-04 - Inserção, edição e exclusão de produtos** |
|:---:	|:---:|
| Requisito Associado | RF-005 - O usuário poderá inserir, editar e excluir cadastros de produtos. |
| Objetivo do Teste | Verificar a inserção, edição e exclusão de produtos. |
| Passos | - Acessar o navegador <br> - Cadastrar novo produto <br> - Clicar no botão de editar <br> - Editar alguma informação <br> - Clicar no botão de exclusão <br>|
| Critério de Êxito | - O produto cadastrado foi apresentado com informações altaradas após a edição e, posteriormente, foi excluído com sucesso (não sendo mais apresentado ao usuário depois dessa última ação) |

| **Caso de Teste** | **CT-05 - Criar agendamento para realização de tarefas** |
|:---:	|:---:|
| Requisito Associado | RF-006 - Usuário poderá criar agendamento para realização de tarefas |
| Objetivo do Teste | Verificar a possibilidade de agendar tarefas |
| Passos | - Acessar o navegador <br> - Acessar a área de tarefas <br> - Clicar no botão de criar tarefas <br> - Agendar a tarefa <br> |
| Critério de Êxito | - A tarefa foi agendada com sucesso e o usuário foi notificado a respeito deste agendamento |

| **Caso de Teste** | **CT-06 - Realizar login com conta Gmail** |
|:---:	|:---:|
| Requisito Associado | RF-007 - Usuário poderá realizar login com sua conta Gmail |
| Objetivo do Teste | Verificar a possibilidade de realizar login com a conta Gmail |
| Passos | - Acessar o navegador estando em uma conta Gmail <br> - Clicar para realizar login através do Gamil <br> |
| Critério de Êxito | - o Login através do Gmail obteve êxito |

| **Caso de Teste** | **CT-07 - Responsividade** |
|:---:	|:---:|
| Requisito Associado | RF-008 - Usuário poderá abrir aplicação em um dispositivo móvel e navegar por ele sem dificuldades |
| Objetivo do Teste | Verificar a responsividade da aplicação em dispositivos móveis |
| Passos | - Acessar a aplicação, através do navagador, em um dispositivo módel <br> |
| Critério de Êxito | - Através dispositivo móvel, não houve dificuldades para clicar em botões e para visualizar todas as informações |

| **Caso de Teste** | **CT-08 - Convidar pessoas** |
|:---:	|:---:|
| Requisito Associado | RF-009 - Usuário poderá convidar pessoas para participar de seu estoque |
| Objetivo do Teste | Verificar a possibilidade de convidar pessoas |
| Passos | - Abrir a aplicação no navegador <br> - Clicar na opção de convidar pessoas <br> - Inserir as informações da pessoa a ser convidada <br> - Clicar em adicionar pessoa <br> |
| Critério de Êxito | - O convite foi feito com êxito e a pessoa convidada foi notificada |

| **Caso de Teste** | **CT-09 - ChatBot de autoatendimento** |
|:---:	|:---:|
| Requisito Associado | RF-010 - Usuário poderá buscar suporte através de um chatbot |
| Objetivo do Teste | Verificar a possibilidade de obter suporte através de um chatbot |
| Passos | - Abrir a aplicação no navegador <br> - Clicar na opção de suporte <br> - Seguir as instruções fornecidas pelo chatbot |
| Critério de Êxito | - A dificuldade do usuário foi resolvida através do chatbot |

 
