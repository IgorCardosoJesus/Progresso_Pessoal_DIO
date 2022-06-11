# HTML
<div a8lign-"center">
<img src="https://i.im.ge/2022/06/11/rzKk8L.png" width="500px" />
</div>

O Elemento é a base de um HTML, **tudo** dentro de um arquivo html é um elemento.



<div a8lign-"center">
<img src="https://i.im.ge/2022/06/11/rzKvxa.md.png" width="500px" />
</div>

!DOCTYPE html - Só diz para o sistema que você está escrevendo.

html - abre a tag, tudo que diz respeito ao doc vai estar ai dentro.

Head - contém meta informações que o navegador necessita.

 title - coloca o título na aba do navegador

body - vai conter o conteúdo da nossa página

e fechamos com o elemento html.


## Falando de SEMÂNTICA ##

#### section ####

Representa uma seção genérica de conteúdo quando não houver um elemento mais específico para isso.

#### header ####

É o cabeçalho da página ou de uma seção da página e normalmente contém logotipos, menus, campos de busca.

#### article ####

Representa um conteúdo independente e de maior relevância dentro de uma página, como um post de blog, uma notícia em uma barra lateral ou um bloco de comentários. Um article pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens.

#### aside ####

É uma seção que engloba conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografia do autor e publicidade. Normalmente são representadas como barras laterais.

#### footer ####

Esse elemento representa o rodapé do conteúdo ou de parte dele, pois ele é aceito dentro de vários elementos, como article e section e até do body. Exemplos de conteúdo de um _footer_ são informações de autor e links relacionados.

#### h1>-<h6 ####

Eles não foram criados na versão 5 do HTML e nem são específicos para semântica, mas servem para esse propósito. São utilizados para marcar a importância dos títulos, sendo _h1_ o mais importante e _h6_ o menos. **Uma dica**: use apenas um _h1_ por página, pois ele representa o objetivo da sua página.

## Falando sobre **Textos e Links** ## 

Um outro elemento interessante e extremamente necessário na web é o **\<a>** que significa anchor/âncora, ele representa um hyperlink, é ele que _interliga vários conteúdos e páginas na web_.

O elemento **a** tem vários atributos, mas vamos focar em dois, o **href e o target**.

O **href** representa o hyperlink para onde sua âncora aponta, pode ser uma página do seu ou de outro site, um e-mail e até mesmo um telefone, os dois últimos precisam dos prefixos _mailto: e tel_:, respectivamente.

O target vai servir para abrir links em outra aba do navegador usando o valor **_blank.**

<div a8lign-"center">
<img src="https://i.im.ge/2022/06/11/rHL7X8.md.png" width="500px" />
</div>

## Imagens ##
Para representar imagens, temos o elemento <img>, ele é um daqueles elementos sem tag de fechamento.

O elemento img contem apenas 2 atributos :próprios, o src e o alt.

O _src_ é obrigatório e guarda o caminho para a imagem que você quer mostrar na página.

O _alt_ não é obrigatório mas é altamente recomendado por melhorar a acessibilidade, ele mostra a descrição da imagem caso ela não carregue e leitores de tela usam esse atributo para descrever a imagem para o usuário saber o que ela significa.

<div a8lign-"center">
<img src="https://i.im.ge/2022/06/11/rHUcd4.md.png" width="500px" />
</div>

## Listas ##
Os últimos elementos que veremos neste módulo são os relacionados a listas: **\<ul>**, **\<ol>** e **\<li>**.

Listas servem para agrupar uma coleção de itens, como uma lista de ingredientes ou uma lista com contatos.

O elemento _ul_ cria uma lista não ordenada, onde a ordem dos elementos não é importante, e é representada com pontos, círculos ou quadrados.

O **\<ol>** serve para criar lista ordenadas, nessas a ordem importa, portanto elas são representadas com números, algarismos romanos ou letras.

E o elemento li é um item dentro de uma dessas listas. Um **\<li>** pode conter vários tipos de conteúdos, como parágrafos, imagens e até outras listas.