# CSS 3 #
## Definição e seletores ##

Uma regra CSS é representada por um seletor ou um grupo de seletores, no nosso caso é o \<a>, então dentro de um par de chaves adicionamos as declarações, no exemplo acima estamos alterando cor e tamanho da fonte dessa âncora, as declarações são formadas por uma propriedade e um valor.

Percebam que podemos colocar vários seletores em uma regra separando-os por vírgula.

E há um último detalhe nesse exemplo: a pseudo-classe. Elementos HTML sofrem alterações causadas pela interação do usuário, como mover o mouse por cima ou clicar nesse elemento.

O a:hover do exemplo significa que a âncora também terá essa aparência quando o usuário passar o mouse por cima de um hyperlink.

<div a8lign-"center">
<img src="https://i.im.ge/2022/06/11/rH5Isy.md.jpg" width="500px" />
</div>

## ID X CLASSE ##

No exemplo anterior criamos uma regra que altera um elemento HTML diretamente, **mas isso significa que todos os elementos \<a> ficarão com aquela aparência**, e normalmente temos sites mais complexos que precisam de várias regras diferentes para elementos iguais.

Para ficar mais tangível vamos relembrar um pouco o site que começamos a fazer no módulo passado, ele tinha vários elementos header, mas **não vamos querer que o header principal tenha a mesma formatação que o header de uma postagem**, é aí que entram os IDs e Classes.

O seletor que vimos no primeiro exemplo é um **seletor de tipo**, pois ele representa um elemento HTML, e com IDs e Classes podemos representar qualquer tipo de elemento mas há algumas diferenças entre eles:

**ID: é representado pelo símbolo # (hash) seguido de um nome para esse ID.**

**Classe: a classe é representada de forma parecida do ID, mas é precedida por um ponto em vez do hash.**

E a diferença mais importante entre eles é a forma como devem ser usados: o _ID só pode ser usado uma vez em uma página HTML_ enquanto a classe não tem restrições.


<div a8lign-"center">
<img src="https://i.im.ge/2022/06/11/rH5Uzz.md.jpg" width="500px" />
</div>


<div a8lign-"center">
<img src="https://i.im.ge/2022/06/11/rH5jo9.md.jpg" width="500px" />
</div>

## Box-model ##


Quando estamos criando o layout de um site o navegador representa cada elemento HTML  como uma caixa retangular, isso é o box-model. E com CSS nós alteramos a aparência dessa caixa (largura, altura, cor de fundo, etc.). Essa caixa é composta por 4 áreas: o conteúdo, o padding, a borda e a margem.

<div a8lign-"center">
<img src="https://i.im.ge/2022/06/11/rH9N0L.jpg" 
width="500px"/>
</div>

As **margens (margin)** são espaçamentos entre elementos;
As **bordas (border)** circundam o pedding e o conteúdo;
O **padding** é um espaçamento entre as bordas e o conteúdo, a diferença para as margens é que declarações de imagem de fundo funcionam nele;
O **conteúdo (content)** é o que o seu bloco representa, um texto, uma imagem, um vídeo;

## Padding e Margin ##

 Se quisermos atribuir tamanhos diferentes para cada lado do box nós podemos, e vamos ver três formas de fazer isso.

A primeira é colocando um valor para as partes superior e inferior e depois para os lados esquerdo e direito.

<div a8lign-"center">
<img src="https://i.im.ge/2022/06/12/rHjWF0.jpg" 
width="500px"/>
</div>

**_O valor de 10 pixels se refere ao eixo Y, ou partes superior e inferior, e os 5 pixels se referem aos lados esquerdo e direito_**

A segunda forma é dando valores para cada lado do box.

<div a8lign-"center">
<img src="https://i.im.ge/2022/06/12/rHjH4a.jpg" 
width="500px"/>
</div>

Então começamos pelo topo com 15 pixels, passamos o lado direito com **10 pixels, depois para a parte inferior com 5 pixels e por último o lado esquerdo com 0**, e sempre nessa ordem.
Quando o valor for 0 não precisamos não precisamos colocar a unidade.

 
A terceira forma é com as propriedades específicas para cada lado, até agora tínhamos visto atalhos para essas propriedades.

<div a8lign-"center">
<img src="https://i.im.ge/2022/06/12/rHjnzS.jpg" 
width="500px"/>
</div>

Essa opção é mais usada quando temos o mesmo valor para 3 lados, e o quarto precisa ter um valor diferente, então usamos o padding com apenas um valor e uma dessas opções para representar o lado diferente.

 

### Background ###

E aqui temos 3 formas de colocar uma cor de fundo, e ainda existem outras.

A primeira é pelo nome da cor em inglês, a segunda é pelo código hexadecimal e a terceira é usando apenas o atalho background.

### Border ###
Vimos que a propriedade border pode ter 3 valores: a largura, a cor e o estilo, mas existem algumas particularidades nisso.

A largura pode ser usada com várias unidades, como px, em e mm. A cor pode ser atribuída pelo nome ou por um código hexadecimal, e o estilo é representada por palavras-chave, vamos ver algumas delas:

solid: mostra uma borda simples e reta;

dotted: são bolinhas com um pequeno espaçamento entre elas;

dashed: forma uma linha tracejada.

-Estilização dos lados de uma borda

E se você não quiser usar a propriedade border existem as propriedade específicas para cada aspecto de uma borda, são elas border-width para a largura, border-color para a cor e border-style para o estilo.

### Border-radius ###

E a última propriedade é o border-radius, ele permite arredondar os cantos de um elemento. Podemos usar várias unidades, mas as mais comuns são os pixels e a porcentagem.

Colocando apenas um valor mudamos todos os cantos do elemento, mas seguindo aquela mesma ordem que vimos no padding e margin - topo, direita, inferior e esquerda -  conseguimos alterar cada canto separadamente.

Nota - BORDA RADIUS 50% DEIXA O OBJETO NA FORMA DE UM CÍRCULO

Podemos manter o background branco, mas vamos diminuir a largura das bordas para 2 pixels e mudar a cor para a mesma do texto - #505050 - e por último adicionaremos um border-radius, 5 pixels são suficientes. Podemos adicionar esse mesmo de valor de border-radius na imagem, para isso vamos acrescentar uma class a imagem antes.

## Estilizando textos ##

Podemos mudar cor e tamanho de algumas fontes, e agora vamos nos aprofundar nisso.

_font-family_
Com o font-family podemos alterar a fonte dos nossos textos, como uma fonte da internet ou uma que esteja instalada no nosso computador, mas vamos nos ater às fontes seguras, chamadas de web safe fonts.

Essas fontes são chamadas assim pois são encontradas em quases todos os sistemas e podem ser usadas sem preocupação.

_font-size_
O font-size nos ajuda a mudar o tamanho do texto, existem algumas unidades de medida para ele mas por enquanto os pixels são suficientes para nós.

 

_font-style_
Usamos o font-style para tornar um texto itálico, na maioria das vezes você usará apenas o valor italic para ele, mas se precisar tirar o itálico de um texto você pode usar o valor normal.