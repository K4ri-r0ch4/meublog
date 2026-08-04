# 📖 DevLog

Registro da evolução do meu blog e do meu aprendizado em programação.

---

## 07/07/26

### o que eu fiz
Dei inicio a criação do meu primeiro site que foi inicialmente editado pelo primeiramente pelo bloco de notas.

### o que eu aprendi 
- os comandos que eu quiser por podem ir no "p" ou no "h".
- os comandos `style=background` é para mudar a cor do fundo do site e o `style=color` para mudar a cor das letras mas ambos tem que ser logo apos o comando principal "body(fundo do site) ou h1 e p(paragrafos).
estou usando até agr somente o html (estrutura) e o css (estilo/designer).
- `font-family: 'Segoe UI', sans-serif;` Explicação: O navegador tentará carregar a 'Segoe UI' (fonte moderna do Windows). Se o usuário estiver num computador muito antigo ou Mac que não a tenha, a vírgula joga para a segunda opção 'sans-serif'. inicio de todo conteudo visivel na tela. 

##  08/07/26

### o que eu fiz e aprendi

- `display` que é como um elemento será exibido na pagina.
- a tag `style`
- Como estruturar uma pag. web basica.
- Limpar as margens padrao do navegador(`margin: 0` e `padding: 0`)
- A diferença entre comentarios de HTML e CSS.
- Como usar o Flexbox (`display: flex`,`justify-content`e `align-items`) para colocar os elementos no centro da tela.
- e a como organizar os elementos em coluna (`flex-direction: column`).
- Publicar e atualizar um site real usando o Github.
- `br` forma mas comum e simples de criar um espaço entre as linhas, posso utilizar o "margin-bottom" tbm mas tem que ser ao lado dos codigos principais `h` ou `p`.

### O que pretendo utilizar algum dia 
-    BIBLIOTECA DE FONTES EXTERNAS (FUTURO)
    O que é isso: Quando você quiser usar fontes personalizadas da internet, 
    você vai acessar o site: https://google.com
    Lá você escolherá a fonte e colará os links gerados aqui dentro do <head>.
<link rel="preconnect" href="https://googleapis.com">
<link rel="preconnect" href="https://gstatic.com" crossorigin> 
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">

## 17/07/26

### o que eu fiz

Comecei a organizar o projeto e separar documentação do código.

### O que eu aprendi
Hoje aprendi sobre as tags e seus significados:
- <META> que é Informação sobre outra informação.
- <charset> que é o nome do atributo, ou seja, ele diz qual informação estamos fornecendo.
<UTF-8>  que é o é o valor desse atributo e representa o conjunto (ou codificação) de caracteres que será utilizado.
<meta charset="UTF-8"> que sem esse codigo o navegador pode interpretar os caracteres usando outra codificação, fazendo com que acentos e símbolos apareçam incorretamente.
<name> ela serve para dizer ao navegador Qual configuração (meta informação) eu estou definindo
<viewport> Área visível da página.
<content> é o conteudo dessa configuração
<meta name="viewport"> significa Esta meta informação é sobre a área visível da página <content="width=device-width,>significa Esta meta informação é sobre a área visível da página<initial-scale=1.0"> e essa parte controla o zoom inicial e o 1.0=100% que é Quando o usuário abre o site, ele aparece no tamanho normal sem zoom. Onde tudo junto basicamente serve para usar a largura real do aparelho do usuário para exibir o site.

### dificuldades
ainda aprendendo a usar o VS code e manter os arquivos entre casa e trabalho atualizados

## 24/07/26

### O que eu fiz


### O que eu  aprendi
- Aprendi que o CSS pode ficar separado do HTML atraves do arquivo (style.css) pois ajuda a organizar meu projeto assim dividindo a aparencia dele e de sua estrutura fazendo com que facilite localizar e modificar os codigos.
- Entendi que o atributo `href` informa o caminho do arquivo que será carregado pelo HTML.
- No caso de `href="style.css"`, ele procura o arquivo `style.css` para aplicar a aparência da página.
- O atributo `rel` informa qual é o tipo do arquivo que está sendo carregado (`stylesheet` = folha de estilos CSS).
- Como o arquivo já é um arquivo de CSS, ele já é reconhecido como estilo. As tags <style> só servem para indicar ao HTML que aquele trecho contém CSS.
- HTML responde pela estrutua e pelo conteúdo. CSS responde pela aparência
- aprendi sobre <ul> Ela é a "caixa" que envolve a lista inteira. e o <li> que é cada coisa que fica dentro da caixa
- <div> que funciona como uma caixa invisivel onde eu posso criar no html epara agrupar coisas que estao dentro dela
- `class="lista"` é um nome que você dá para um elemento HTML para conseguir encontrar ele no CSS(ela é como uma etiqueta que fica na caixa=div). como por exemplo a lista que acrescentei
- .lita este foi no nome do class que coloquei no css e o ponto que vem antes é um comando para procurar no html algo que tenha essa class.
- deixei meu div com um formato de balao atravez do .list
- o <box-shadow: 0px 5px 15px gray;> faz uma sombra embaixo, dando aquele efeito de caixa flutuando.

### O que fiz

- Criei o arivo style.css e fiz a separação do html e do css
- acrescentei uma pequena lista contendo <ul> e o <li>
- coloquei o <div> e class
- deixei minha lista com o formato de balao

### dificuldade
- deixar meu div no canto da tela sem passar por cima dos outros textos e nem tirar a estrutura inicial centralizada do site.


## 27/07/26

### O que fiz 


### O que aprendi
- Hoje aprendi que a `class` pode ser usada em vários elementos iguais, enquanto o `id` deve ser único dentro da página.
-as tags `<header>`, `<main>` e `<footer>` têm uma função específica.
- `<header>` representa o cabeçalho da página.
- `<main>` representa o conteúdo principal.
- `<footer>` representa o rodapé, onde normalmente ficam os contatos e informações finais.
- Também entendi que usar essas tags deixa o código mais organizado e facilita entender a estrutura do site.
- <head> = Configurações da página (não aparece no site).
- <header> = Cabeçalho visível do site (aparece para o visitante).

## 28/07/26

### O que fiz
- Comecei a restruturção do site.
- Didivi dentro do body o heater, main e footer
- apliquei o nav para divisao do menu dentro do heater
- retirei as frases e reorganizei o css

### O que aprendi
- Entendi a função da tag `<nav>`.
- Aprendi que o menu serve para navegar entre páginas ou seções do site.
- Percebi que elementos com a mesma função podem ser agrupados.
- Continuei planejando a estrutura do cabeçalho antes de escrever o código.
- <a>: É a tag de link (abreviação de anchor, ou âncora). Ela avisa ao navegador que o texto ali dentro pode ser clicado.
- `href="":` É o atributo de destino (abreviação de hypertext reference). Ele diz para onde o usuário vai ao clicar.
- # (Sinal de hashtag): Este é o segredo. No HTML, a hashtag significa "procure um ID nesta mesma página".

## 04/08/26

### Oque fiz
- Finalização da estrutura semântica do HTML.
- Organização completa do <header>, <main> e <footer>
- apaguei o conteudo rascunho inicial do site e iniciei dois conteudos através da <section> sobre postagens e galeria. fiz com a `section` e nao con o `div` pois são dois conteúdos de áreas grandes, 
- Na <section postagens>coloquei um `article` dentro da `section`, coloquei um `aside`. acrescentei um `header` e um `footer` dentro do `article`.
- <section galeria>colequei um `figure` e dele coloquei a 
`img` e `figcapition`.
- No `footer` do site acrescentei um `h2` e um <address>


## O que Aprendi
- <Article> que é artigo ou seja ele representa um conteudo independente que será a área de postagens, o conteudo do site.
- que da pra por `header` dentro do `article` pois ele será o cabeçalho de qualquer postagem especifica (ele nao substitui o cabeçalho do site).la conseguirei por um titulo, data, texto e talvez uma imagem. Assim como o `footer` pois la ele vai servir para ter, tags, categorias, links, botoes e etcs
- <aside> significa conteúdo complementar, sua funçao é ser o a estrutura para comentarios, informaçoes, posts relacionados, anuncios, links e etc... o que acompanha a postagem mas que nao faz parte dela.
- <figure> que representa um conteúdo visual que pode ser: imagem, print, grafico, desenho e etc.
- O `figure` é uma tag semantica assim como o `article` pois ela cria um proprio bloco para o conteudo visual.
- <igm src="" alt=""> que é uma tag para inserir uma imagem onde possui dois atributos como o `src` que é o caminho de onde a imagem está e `alt` que a função é descrever a imagem quando a propria nao carregar.
- <figcaption> que é a legenda da figura.

### Dificuldade
 - Durante a reorganização do HTML, o layout ficou completamente desalinhado. No início pensei que o problema fosse o HTML, mas percebi que o CSS antigo havia sido criado para uma estrutura diferente. Também precisei entender que centralizar todo o body não é a melhor escolha para um site, já que isso faz com que header, main e footer sejam tratados como um único bloco.