# Teste Desenvolvedor .NET

Neste teste ser�o avaliados seus conhecimentos e a metodologia aplicada no desenvolvimento de uma aplica��o .NET.

## O Desafio

Crie um sistema b�sico de blog onde os usu�rios podem visualizar, criar, editar e excluir postagens. O projeto deve utilizar os princ�pios de orienta��o a objetos, seguir os princ�pios SOLID, integrar o Entity Framework para manipula��o de dados e incluir uma comunica��o simples usando WebSockets para notificar os usu�rios sobre novas postagens em tempo real.

## Requisitos Funcionais

Esses requisitos s�o obrigat�rios e devem ser desenvolvidos para a entrega do teste.

Autentica��o: Usu�rios devem ser capazes de se registrar, fazer login.
Gerenciamento de Postagens: Os usu�rios autenticados podem criar postagens, editar suas 
pr�prias postagens e excluir postagens existentes.
Visualiza��o de Postagens: Qualquer visitante do site pode visualizar as postagens existentes.
Notifica��es em Tempo Real: Implemente um sistema de notifica��o em tempo real usando 
WebSockets para informar os usu�rios sobre novas postagens assim que s�o publicadas.

### M�todos

Utilize a arquitetura monol�tica organizando as responsabilidades, como autentica��o, 
gerenciamento de postagens e notifica��es em tempo real.
Aplique os princ�pios SOLID, especialmente o princ�pio da Responsabilidade �nica (SRP) e o 
princ�pio da Invers�o de Depend�ncia (DIP).
Utilize o Entity Framework para interagir com o banco de dados para armazenar informa��es 
sobre usu�rios e postagens.
Implemente WebSockets para notifica��es em tempo real. Pode ser uma notifica��o simples 
para interface do usu�rio sempre que uma nova postagem � feita


## O que � permitido

* Linguagem C#

* .NET Core ou Superior.

* PostgreSQL, SqlServer

* Mapeamento objeto-relacional (ORM)

* Qualquer tecnologia complementar as citadas anteriormente s�o permitidas desde que seu uso seja justific�vel

## O que n�o � permitido

* Bancos de Dados **n�o relacionais**.
  
* Utilizar bibliotecas ou c�digos de terceiros que implementem algum dos requisitos.

* Outras linguagens diferentes de C#

## Recomenda��es
* O teste � propositalmente simples para permitir que voc� demostre suas habilidades e conhecimentos sem escrever muito c�digo, sendo assim � interessante utilizar design patters e padr�es de arquitetura.
* Desenvolva o projeto utilizando algum padr�o de formata��o de c�digo.
* Idealmente a nomeclatura de classes, m�todos, atributos e propriedades devem estar no idioma Ingles.

## Extras

Aqui s�o listados algumas sugest�es para voc� que quer ir al�m do desafio inicial. Lembrando que voc� n�o precisa se limitar a essas sugest�es, se tiver pensado em outra funcionalidade que considera relevante ao escopo da aplica��o fique � vontade para implement�-la.

* **Documenta��o**: Gerar a documenta��o da API de forma automatizada, utilizando o `swagger` ou equivalentes

* **Containeriza��o**: Realizar a conteineriza��o da aplica��o utilizando Docker

* **Front-end da aplica��o**: Se seu foco � ser fullstack, voc� pode explorar isso desenvolvendo um front-end para a aplica��o, seja em tecnologia .NET (MVC, Razor, Blazor) ou javacript (VueJS, Angular, ReactJS, etc.)

## Entregas

Para realizar a entrega do teste voc� deve:

* Relizar o fork e clonar esse reposit�rio para sua m�quina
  
* Criar uma branch com o nome de Teste-C-NET_datum
  
* Fa�a um commit da sua branch com a implementa��o do teste
  
* Realize o pull request da sua branch nesse reposit�rio

Al�m do pull request voc� deve **gravar um v�deo de no m�ximo 30 minutos** mostrando o que foi desenvolvido, falando sobre as decis�es que foram tomadas, as tecnologias utilizadas, arquitetura e tudo que voc� achar relevante. A facecam � opcional, mas � um extra desej�vel. Esse v�deo deve ser postado no youtube (pode ser n�o listado) e seu link deve estar no `README.md` do projeto.