# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de Classes

![image](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t9-grupo-5-eixo-2/assets/80500257/c84668fe-6201-47e9-a0d6-5d3998d91713)

Neste diagrama:
- SistemaGerenciamento: é a classe principal que possui métodos para adicionar, remover, modificar e buscar itens no estoque, bem como para gerenciar funcionários.
- EstoqueItem: representa os itens do estoque e armazena informações como nome, data de entrada, data de saída, quantidade e validade. Existem métodos getters e setters para cada atributo.
- Funcionario: representa informações sobre os funcionários, como nome e cargo. Também possui métodos getters e setters para os atributos.

Observação: Na classe ‘’EstoqueItem’’ também possui três atributos adicionais: ‘’adicionadoPor’’, ‘’removidoPor’’ e ‘’modificadoPor’’, que representam os funcionários que adicionaram, removeram ou modificaram o item no estoque.Essas associações ajudam a rastrear qual funcionário realizou cada ação no estoque.

## Modelo ER (Projeto Conceitual)

![img_2.png](img_2.png)

Principais entidades:
- Usuarios: contem as informações básicas e necessárias para prenchimento de telas de perfil e administração, bem como relações para atividades tais como roles e estado.
- Itens: Core para gestāo de inventário, bem como entender o histórico e estado atual dos mesmos.
- Atividades: históricos, consultas, estados.

## Projeto da Base de Dados

O projeto da base de dados corresponde à representação das entidades e relacionamentos identificadas no Modelo ER, no formato de tabelas, com colunas e chaves primárias/estrangeiras necessárias para representar corretamente as restrições de integridade.
 
Para mais informações, consulte o microfundamento "Modelagem de Dados".

## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.

## Hospedagem

Explique como a hospedagem e o lançamento da plataforma foi feita.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
