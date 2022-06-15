## Display: flex ##
Torna a tag um elemento do tipo flex container, e assim, automaticamente todos os seus filhos diretos desta tag, tornam-se em flex items.

## Flex-direction ##

É a propriedade que estabelece o eixo principal do container,
definindo assim a direção que os flex items são colocados no flex container.

## Os eixos ##

● **row( padrão )**: à direção do texto, esquerda para direita
* **row-reverse**: sentido oposto à direção do texto
* **column**: ordenação de cima para baixo, em coluna unica
* **column-reverse**: ordenação inversa, de baixo para cima

## Flex-wrap ##

É a propriedade que define se os itens devem ou não quebrar a
linha.
<p>Por padrão eles não quebram linhas, isso faz com que os flex itens
sejam compactados além do limite do conteúdo.</p>
<p>**nowrap**: é o padrão, não permite a quebra de linha.</p>
<p>**wrap**: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado.</p>
<p>**wrap**: permite a quebra de linha assim que um dos flex itens não puder mais ser
compactado, porém na direção contrária da linha, acima.</p>

## Flex-flow ##

É um atalho para as propriedades flex-direction e flex-wrap.

Porém seu uso não é tão comum, visto que, quando mudamos o
flex-direction para column, mantemos o padrão do flex-wrap que
é nowrap.