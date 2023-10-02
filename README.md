# desafio-projeto-criando-tag-web-html
Criação de uma página web utilizando tags aprendidas
<html>
    <body>
        <head>
            <h1>Modulo1 - Meu primeiro projeto Tags</h1>
            <hr />
            <h2 id="Inicio">Menu</h2>
            
            <ul>
                <li> <a href="# O que" >O que é o HTML? </a></li>
                <li> <a href="# Ferramentas" >Ferramentas Utilizadas </a></li>
                <li><a href="# Usando" > Usando o Inspetor de Elementos</a></li>
                <li><a href="# Estrutura" > Estrutura Basica do HTML</a></li>
                <li><a href="#Tags" >O que são Tags</a></li>
                
            </ul>

            <h2 id="O que"><strong> O que é o HTML? </strong></h2>
            <small><a href="#Inicio"> (Voltar)</a></small>
          <p>  Para que você possa trabalhar com a ferramenta é importante saber o que é HTML e para que serve, o HTML foi criado pelo britânico Tim Berners-Lee e HTML significa Hiper Text Markup Language, em tradução é linguagem de marcação de hipertexto. O HTML permite inserir o conteúdo e estabelecer a estrutura básica de um website. Portanto, ele serve para dar significado e organizar as informações de uma página na WEB. Os hipertextos são conjuntos de elementos conectados. Esses podem ser palavras, imagens, videos, documentos enntre outros. Quando conectados, formam uma rede de informações que permite a comunicação de dados, organizando conhecimento e guardando informações.</p>
    <h3 id="Ferramentas"><strong> Ferramentas Utilizadas</strong></h3>
    <small><a href="#Inicio"> (Voltar)</a></small>
   <p> Para que possamos utilizar o html, recomendamos o uso da ferramenta <a href="https://code.visualstudio.com/" target="_blank"> Visual Studio Code</a>, atravês desse link você consegue realizar o Download da ferramenta ou utilizar no formato online, a ferramenta é bem objetiva e você consegue utilizada mesmo sendo o seu primeiro contato com a ferramenta, atravês dela é possivel inserir conteúdos e realizar uma estruturação básica so html</p>

    <h2>Usando o Inspetor de Elementos</h2>
    <small><a href="#Inicio"> (Voltar)</a></small>
   <p> Mas Jana, como posso entender o que foi inserido no website? ah, para você que é novo nesse mundo da programação e acredita ser dificil pensar como posso criar códigos do zero, e não esquenta com isso porque é possivel visualizar os código de todos os website usando em seu navegador o F12 ou no canto superior direito vá nos 3 pontinhos > Mais ferramentas > Ferramentas do Desenvolver após realizar esse passo você entra no universo WebSite, nele você consegue observar toda a estrutura criada pelo desenvolver para aquele site, você consegue observar todos os elementos utilizado e ai meu amigo, o céu é o limite. nos proximos passos vamos falar sobre estrutura básica que nortea o seu pensamento porque até mesmo analisando todo esse processo que o desenvolver utilizou ele seguiu alguns passos básicos para chegar no resultado atual.</p>
        
    <h2 id="Estrutura"><strong>Estrutura básica do HTML</strong></h2>
    <small><a href="#Inicio"> (Voltar)</a></small>
   <p> Para criar HTML existe uma estrutura basica e padronizada para você iniciar o documento deve conter uma declaração informando o doctype, que no caso do HTML5, basta declarar com o elemento <!DOCTYPE html>. Após isso iniciamos nosso documento com a tag <html> que deverá ser fechada ao final do documento com </html>. Posteriormente, nosso documento deverá ter um elemento <head> que receberá todas as informações básicas da sua página, como o título, links de elementos externos, metadados, etc. Declaramos então um título para página através da tag "title". Finalmente abrimos então a tag "body" que consiste no corpo do nosso documento, onde ficarão todos os elementos que serão renderizados na tela do navegador. Dessa forma, temos a estrutura básica do nosso documento html:</p>
       <p>Para que não ocorram erros de renderização ou incompatibilidade de caracteres, devemos também declarar o padrão de teclado. No Brasil e em boa parte da América Latina, utilizamos o padrão UTF-8. Dessa forma, através da tag de metadados <meta/>, vamos declarar dentro de um atributo charset que nosso padrão é o UTF-8. Temos assim a estrutura básica de nosso documento HTML:</p> 

<h2 id="Tags"><strong>O que são Tags?</strong></h2>
<small><a href="#Inicio"> (Voltar)</a></small>

<p>As tags são códigos que definem toda a estrutura da página, tais como o seu tamanho, a fonte da letra, as cores, as quebras de linha e etc. A maioria dos elementos do documento HTML são compostos por uma estrutura de abertura e uma de fachamento, como "tag" e "/tag". Há também tags de estrutura única, como a  tag 'br/' que realiza uma quebra de linha.</p>

<p>Digamos que você queria escrever um paragrafo, chamamos então a tag "p", escrevemos o paragrafo e finalmente fechamos a tag com "/p":"/p"

   <p> "p" Meu primeiro paragrafo."/p"</p>
<p>Dessa forma, ao salvar o arquivo com a extensão .html e abri-lo em um navegador, você verá o parágrafo escrito na tela do navegador.</p>
<h1><strong>Principais Tags do HTML</strong></h1>
Atualmente existem mais de 140 tags, mas algumas delas quase não são utilizadas. Dentre as mais utilizadas temos:

<ul>
    <li><strong>head:</strong> local para declarar todas informações, como título e metadados da sua página;</li>
    <li><strong>title </strong>: define o título;</li>
     <li>   <strong>body</strong> : local para declarar todos os elementos que irão compor o corpo da página;</li>
     <li>  <strong>h1,h2,h3,h4,h5 e h6 </strong> : Tags para definir um título e subtítulos, variando de 1 a 6, sendo h1 o título mais importante e h6 o de menor importância; </li> 
    <li><strong>p</strong> : Tag para definir um parágrafo.+;</li>
      <li>  <strong>a</strong> : Tag de link, junto ao atributo href=”” é responsável pela principal característica da web;</li>
       <li> <strong>header</strong>: define um cabeçalho;</li>
       <li><strong>section</strong> : define uma seção;</li>
      <li> <strong>article</strong> : define um artigo; </li>
       <li> <strong>div</strong></div> : define uma divisão;</li>
        <li><strong> footer</strong> : define um rodapé; </li>
        <li><strong>nav</strong> : define uma área de navegação (como menus);</li>
        <li><strong>table</strong> : define uma tabela; </li>
       <li><Strong>ol</Strong> : define uma lista ordenada;</li>
        <li><strong>ul</strong>: define uma lista não ordenada; </li>
       <li><strong>li</strong>strong> : define o item de uma lista; </li>
       <li> <strong>form</strong>: define um formulário; </li>
       <li><strong>input</strong>: define os campos do formulário; </li>
       <li><strong>textarea</strong>: define uma área para o usuário digitar um texto;</li>
        <li><strong>button</strong>: define um botão;</li>
       <li><strong>img</strong> : permite inserir uma imagem no seu documento.</li>


</head>
    </body>
</html>
