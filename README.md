# Teste Desenvolvedor .NET

Neste teste serão avaliados seus conhecimentos e a metodologia aplicada no desenvolvimento de uma aplicação .NET.

## O Desafio

Crie um sistema básico de blog onde os usuários podem visualizar, criar, editar e excluir postagens. O projeto deve utilizar os princípios de orientação a objetos, seguir os princípios SOLID, integrar o Entity Framework para manipulação de dados e incluir uma comunicação simples usando WebSockets para notificar os usuários sobre novas postagens em tempo real.

## Requisitos Funcionais

Esses requisitos são obrigatórios e devem ser desenvolvidos para a entrega do teste.

Autenticação: Usuários devem ser capazes de se registrar, fazer login.
Gerenciamento de Postagens: Os usuários autenticados podem criar postagens, editar suas 
próprias postagens e excluir postagens existentes.
Visualização de Postagens: Qualquer visitante do site pode visualizar as postagens existentes.
Notificações em Tempo Real: Implemente um sistema de notificação em tempo real usando 
WebSockets para informar os usuários sobre novas postagens assim que são publicadas.

### Métodos

Utilize a arquitetura monolítica organizando as responsabilidades, como autenticação, 
gerenciamento de postagens e notificações em tempo real.
Aplique os princípios SOLID, especialmente o princípio da Responsabilidade Única (SRP) e o 
princípio da Inversão de Dependência (DIP).
Utilize o Entity Framework para interagir com o banco de dados para armazenar informações 
sobre usuários e postagens.
Implemente WebSockets para notificações em tempo real. Pode ser uma notificação simples 
para interface do usuário sempre que uma nova postagem é feita


## O que é permitido

* Linguagem C#

* .NET Core ou Superior.

* PostgreSQL, SqlServer

* Mapeamento objeto-relacional (ORM)

* Qualquer tecnologia complementar as citadas anteriormente são permitidas desde que seu uso seja justificável

## O que não é permitido

* Bancos de Dados **não relacionais**.
  
* Utilizar bibliotecas ou códigos de terceiros que implementem algum dos requisitos.

* Outras linguagens diferentes de C#

## Recomendações
* O teste é propositalmente simples para permitir que você demostre suas habilidades e conhecimentos sem escrever muito código, sendo assim é interessante utilizar design patters e padrões de arquitetura.
* Desenvolva o projeto utilizando algum padrão de formatação de código.
* Idealmente a nomeclatura de classes, métodos, atributos e propriedades devem estar no idioma Ingles.

## Extras

Aqui são listados algumas sugestões para você que quer ir além do desafio inicial. Lembrando que você não precisa se limitar a essas sugestões, se tiver pensado em outra funcionalidade que considera relevante ao escopo da aplicação fique à vontade para implementá-la.

* **Documentação**: Gerar a documentação da API de forma automatizada, utilizando o `swagger` ou equivalentes

* **Containerização**: Realizar a conteinerização da aplicação utilizando Docker

* **Front-end da aplicação**: Se seu foco é ser fullstack, você pode explorar isso desenvolvendo um front-end para a aplicação, seja em tecnologia .NET (MVC, Razor, Blazor) ou javacript (VueJS, Angular, ReactJS, etc.)

## Entregas

Para realizar a entrega do teste você deve:

* Relizar o fork e clonar esse repositório para sua máquina
  
* Criar uma branch com o nome de Teste-C-NET_datum
  
* Faça um commit da sua branch com a implementação do teste
  
* Realize o pull request da sua branch nesse repositório

Além do pull request você deve **gravar um vídeo de no máximo 30 minutos** mostrando o que foi desenvolvido, falando sobre as decisões que foram tomadas, as tecnologias utilizadas, arquitetura e tudo que você achar relevante. A facecam é opcional, mas é um extra desejável. Esse vídeo deve ser postado no youtube (pode ser não listado) e seu link deve estar no `README.md` do projeto.