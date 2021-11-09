# Sobre

Irei organizar aqui um índice para os meus primeiros projetos, desde que conclui a graduação. Infelizmente não me preocupei em guardar os projetos e os resultados dos meus estudos durante a graduação, então verá aqui apenas desenvolvimentos bem recentes.

## Javascript

- [Calculadora](https://github.com/caiohscruz/Calculadora_com_Javascript) **[HTML|CSS|Javascript]**
A proposta deste projeto era replicar a aparência e os comportamentos da calculadora padrão do meu sistema operacional utilizando javascript puro.

## NodeJS

- [RocketQ](https://github.com/caiohscruz/RocketQ) 
**[HTML|CSS|JavaScript|NodeJS|EJS|Express|SQLite]**
A proposta deste projeto era criar uma plataforma onde usuários poderiam criar uma sala com senha para gerenciamento, poderiam acessar salas quaisquer e registrar perguntas, e aquele de posse da senha da sala pode alterar o estado das perguntas registradas.
- [Perguntas e Respostas](https://github.com/caiohscruz/Perguntas-e-Respostas)
**[HTML|CSS|Bootstrap|JavaScript|NodeJS|EJS|Express|MySQL|Sequelize|Dotenv]**
A proposta era criar uma plataforma de perguntas e respostas. Apesar da proposta não muito diferente do projeto anterior, as abordagens de desenvolvimento divergiram bastante em alguns pontos, tornando a experiência muito proveitosa.
- [GuiaPress](https://github.com/caiohscruz/GuiaPress)
**[HTML|CSS|Bootstrap|JavaScript|NodeJS|EJS|Express|MySQL|Sequelize|Dotenv|TinyMCE|bcryptjs|slugify|express-session]**
A proposta era desenvolver um protótipo de blog, onde um usuário qualquer, não logado, pode consultar os artigos publicados, filtrados ou não por categoria. Caso o usuário tenha um cadastro, ele pode, em sua área restrita, criar, editar e deletar artigos e categorias. 
- [excelToHtmlOrPdf](https://github.com/caiohscruz/excelToHtmlOrPdf) **[Javascript|NodeJS|HTML-PDF|FS|CSV]** A proposta deste projeto foi desenvolver um aplicativo capaz de gerar uma página html ou um pdf com uma tabela correspondente ao conteúdo de um arquivo de extensão CSV. [Deixo aqui](https://youtu.be/4H-yR07vUJ8) um link para um vídeo onde falo um pouco sobre o projeto.
- [MyFirstRESTAPI](https://github.com/caiohscruz/MyFirstRESTAPI)
**[JavaScript|NodeJS|EJS|Axios|JWT|Cors|dotenv|Sequelize|Mysql2|Express]**
A proposta deste projeto foi desenvolver uma API REST bem simples para começar a se familiarizar com webservices e com a arquitetura REST. Essa API será consumida por um outro projeto, MyFirstRESTAPIConsumer. Foi desenvolvida também a autenticação de clientes com JWT, dessa forma, a API não irá tratar solicitações de clientes que não possuam um token válido. Em resposta a uma requisição de autenticação bem sucessida, a API fornece ao cliente um token que fica salvo no navegador, no localStorage, o qual tem uma válidade, exigindo autenticações com alguma regularidade.
- [MyFirstRESTAPIConsumer](https://github.com/caiohscruz/MyFirstRESTAPIConsumer)
**[JavaScript|NodeJS|EJS|dotenv|Express]**
A proposta deste projeto foi desenvolver uma aplicação simples com um CRUD completo que consumisse uma API REST, que no caso foi desenvolvida em outro projeto, MyFirstRESTAPI, e que lidasse com autenticação de cliente com JWT. 
- [pokedex-vue-formacao-nodejs](https://github.com/caiohscruz/pokedex-vue-formacao-nodejs)
**[HTML|CSS|Bulma|JavaScript|VueJS|NodeJS|Express|Axios|Serve-Static]**
Uma pokédex simples desenvolvida com VueJS, os dados dos pokémons são obtidos via requisição para uma API REST [PokéApi](https://pokeapi.co/). Realizei o deploy da aplicação na Heroku, confira: [pokedex (vue-poke-api.herokuapp.com)](https://vue-poke-api.herokuapp.com/)
- [api-rest-users-knex](https://github.com/caiohscruz/api-rest-users-knex)
**[NodeJS|JavaScript|Express|jsonwebtoken (JWT)|Knex|NodeMailer|mysql2|cors|bcrypt|uuid|Validator]**
Trata-se de uma API REST com NodeJS para gerenciamento de usuários que utiliza, dentre outras coisas, o querybuilder 'knex' e o 'nodemail' para envio de e-mails. Gravei um [vídeo](https://youtu.be/FB5wtnTqQqM), mas devo avisar que ele não mais reflete o estado atual do projeto, pois comecei um [outro projeto](https://github.com/caiohscruz/formacao-node-vue-users) depois que tratava de desenvolver um Front que consumisse desta API, e acabei tendo que alterar algumas coisas e implementar outras.
- [formacao-node-vue-users](https://github.com/caiohscruz/formacao-node-vue-users)
**[VueJS|JavaScript|axios|Bulma|vue-router]**
Trata-se de uma aplicação em VueJS para gerenciamento de usuários que consome de uma API desenvolvida em [outro projeto](https://github.com/caiohscruz/api-rest-users-knex). Gravei um [vídeo](https://youtu.be/B-Qqsbi8a0o) mostrando brevemente a aplicação e falando sobre seu desenvolvimento.
- [formacao-node-chat-socket.io](https://github.com/caiohscruz/formacao-node-chat-socket.io)
**[NodeJS|JavaScript|Express|EJS|socket.io]**
A proposta deste projeto foi a concepção de um protótipo de chat com socket.io. Gravei um [vídeo](https://youtu.be/hhbYu4dN41c) mostrando o projeto, mas a qualidade do áudio está horrível, peço desculpas por isso.



## AJAX/PHP

- [landing-page-test](https://github.com/caiohscruz/landing-page-test)
**[HTML|CSS|Bootstrap|Javascript|AJAX|PHP|MySQL]**
A proposta foi desenvolver uma landing page que permitisse o cadastro de e-mails. Os e-mails deveriam ser validados e persistidos em um banco de dados com AJAX e PHP. Esse projeto foi um desafio técnico proposto em um processo seletivo.
