ReactJs rápido
-

React é uma biblioteca javaScript criada pelo facebook, com o proposito de criar a parte visual da aplicação, front end.
Padrao de desenvolvimento baseada em ``componentes``.

  - componentes são pedaços de codigos que representa parte de uma interface de usuario (UI), e podem ser reutilizados em varias partes da aplicação.
  - componentes de classe,
    - é uma classe estendendo um componente da biblioteca react que redenriza algum tipo de retorno html.
  - componente funcional,
    - basicamente é uma função javaScript que retorna um html.

Intalação para trabalahr com o react
-
Vamos precisar ter o NodeJS instalado e o VS code.

No site ``vitejs.dev`` faça uso dos comandos no site para criar o projeto inicial.

Comando para rodar o projeto: ``npm run dev``.

Sobre estrutura
-
Na raiz do projeto temos o arquivo``index.html``.

Sobre JSX
-
Arquivo com a extensão jsx - basicamente é um javascript misturado com html.
Sintaxe muito intuitiva.

  -
    - Interpolações,
  
é injetar javascript dentro do html.

Sobre PROPS
-
São atributos ou propriedades que podemos dar aos componentes.

Sobre estados
-
É a memoria de um compodente, é como se fosse uma variavel que vai armazenar um valor e sempre que houver uma alteração no valor dessa variavel chamamos de ``estado``. O react entende que precisa redenrizar novamente o componente, ele ``reage`` (faz, jus ao seu nome) ao conteudo que ele tem dentro do estado, a sua memoria interna.


Sobre rotas
-
- Como navegar entre paginas usando o react?
  - é interessante lembrar que o react foi feito para ser uma ``Single Page Application``, ou seja 'tudo numa unica pagina'.

Para podermos navegar entre paginas, fugindo da ideia original pelo qual o react foi desenvolvido, precisamos instalar uma biblioteca de terceiros seguindo o seguinte comando via terminal: ``npm i react-router-dom``.






Referencia
-
https://www.youtube.com/watch?v=hd2B7XQAFls
