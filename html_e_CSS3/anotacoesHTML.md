# HTML

## Estrutura básica
A primeira linha quando se escreve uma página HTML é:
```html
<!DOCTYPE html>
```
Ela é uma elemento html que apenas diz ao navegador que se trata de um arquivo do tipo HTML5. em seguida vem os outros elementos HTML.

```html
<html lang="pt-BR">
```
Essa tag é a saiz do documento, e portanto todos os elementos HTML devem estar dentro dela. É nela que nós informamos ao navegador qual é o idioma desse documento, através do atributo lang, para o português brasileiro usamos pt-br.

```html
<head>
```
A tag head contém os elementos que serão lidos pelo navegador, como os metadados. Um exemplo é o charset, que é a codificação de caracteres, e a mais comum é UTF-8, o javascript possui a tag script e o CSS através das tags style e link.

```html
<body>
```

Dentro do body colocamos todo o conteúdo visível do usuário: textos, imagens, vídeos...

## Semântica

Além dessas principais, há outras tags que são utilizadas como as div. Mas para o documento não virar uma sopa de divs é possível substituí-las para alguns casos.

A seântica nos permite escrever o conteúdo de forma precisa, e portante um bloco de texto terá mais sentido sendo um article ao invés de div, por exemplo.

```html
<section>
```
Representa uma seção genérica do contúdo quando não houver um elemento mais específico para isso.

```html
<header>
```
é o cabeçalho de uma página ou de uma seção de página e normalmente contém logotipos, menus e campos de busca.

```html
<article>
```
Representa um contúdo independente e de maior relevância dentro de uma página, como um post de blog, uma notícia em uma barra lateral ou um bloco de comtários. Um article pode conter outros elementos como header, cabeçalhos, parágrafos e imagens.

```html
<aside>
```
É uma seção que engloba contúdos relacionados ao contúdo principal, como artigos relacionados, biografia do autor e publicidade. Normalmente são representadas como barras laterais

```html
<footer>
```
Esse elemento representa o rodapé do contúdo ou de parte dele, pois é aceito dentro de vários elementos, como article e até body. Exemplos de conteúdo de um \<footer> são informações de autor e _links_ relacionados.

```html
<h1>-<h6>
```
Esses não foram criados na versão 5 do HTML e nem específicos para a semântica, mas servem para esse propósito. São utilizados para marcar a importância dos títulos, sendo \<h1> o mais importante e \<h6> o menos. Uma dica é usar o \<h1> apenas uma vez por página, pois ele representa o objetivo da sua página

## Textos e links
Anteriormente falamos sobre o uso de \<h1> e \<h6>, mas para textos maiores e mais densos usamos o elemento \<p>

\<p> representa um paragrafo mas ele não suporta apenas texto, podemos adicionar imagens, código, vídeos e outros tipos de conteúdos dentro dele.

Outro elemento importante é o \<a> que significa anchor/âncora, ele representa um hyperlink, é ele que interliga vários conteúdos e páginas na web.

O elemento \<a> tem vários atríbutos, mas vamos focar em dois href e o target.

O href representa o hyperlink para onde sua âncora aponta, pode ser uma página do seu ou outro site, um e-mail e até mesmo um telefone, os últimos dois precisam dos prefixos mailto: e tel: respectivamente

O target neste momento vai servir para nos ajudar a abrir nossos links em outra aba do navegador usando o valor _blank

## Imagens
A web também é feita de imagens e para representá-las temos o elemento \<img>, ele é um daqueles elementos sem tag de fechamento

O elemento \<img> é bem simples, pontendo apenas 2 atributos próprios, o src e o alt.

O src é obrigatório e guarda o caminho para a imagem que você quer mostrar na página.

O alt não é obrigatório mas é realmente recomendado para melhorar acessibilidade, ele mostra a descrição da imagem caso não carregue e leitores de tela usam esse atributo para descrever a imagem para o usuário saber o que ela significa.

## Listas
Listas servem para agrupar uma coleção de itens, como uma lista de ingredientes ou como será no nosso caso uma lista de contados.

O elemento ul cria uma lista não ordenada, onde a ordem dos elementos não é importante, e é representada com pontos, círculos e quadrados.

\<ol> serve para criar listas ordenadas, nessas a ordem importa portnato são representadas com números, algarismos romanos ou letras.

E o elemento \<li> é um item de uma dessas listas. Um \<li> pode conter vários tipos de contúdos, como parágrafos, imagens e até outras listas.



