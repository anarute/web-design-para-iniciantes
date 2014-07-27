# Propriedades tipográficas


## Cor de texto: `color`
Recebe valores em RGB, RGBa, hexadecimal ou nome da cor em inglês. Entenda como funcionam as cores na web [neste artigo](http://docs.escolamupi.com.br/conteudos/design-cores).

## Família de fonte: `font-family`

Esta propriedade indica qual será a fonte do texto e quais serão as fontes de reserva caso a desejada não seja carregada pelo navegador. A sintaxe utilizada para este caso deve ser conforme o exemplo a seguir, que declara fontes para o elemento p:

    p {font-family: 'Georgia', 'Courier New', serif;}

A declaração acima significa que todo elemento `p`, ou seja, todos os parágrafos da página serão exibidos com a fonte de nome "Georgia". Caso o navegador não encontre esta fonte ou tenha problemas para exibi-la, ele utilizará a fonte de nome "Courier New" para a exibição dos parágrafos. E, por fim, caso esta também não funcione, ele utilizará a principal fonte com serifa do sistema que o usuário está usando.

## Tamanho da fonte: `font-size`

Com esta propriedade, conseguimos modificar o tamanho do texto numa página. Existem vários tipos de unidade de medida para se declarar o tamanho da fonte, como pixels, porcentagem e pontos. Em nossos exemplos, utilizaremos px que é a unidade de medida em pixels.

No exemplo abaixo, declaramos que todo parágrafo (ou seja, texto contido dentre as tags <p></p>) da página HTML terá seu texto exibido com tamanho de 14 pixels:

    p {font-size: 14px;}

## Estilo de fonte: `font-style`

A propriedade font-style tem três possibilidades de valor a ser atribuído: `normal` (padrão), `italic` (traduzindo, itálico) e `oblique` (traduzindo, oblíquo).

Tipograficamente falando, italic é uma variante da fonte criada pelo designer tipográfico com o intuito de criar uma versão caligráfica e inclinada do texto. Já o valor oblique é uma forma simplificada na qual a fonte é inclinada em apenas alguns graus via software. Por isso, recomendamos sempre o uso de italic ou invés de oblique.

O exemplo abaixo mostra como declarar esta propriedade a um elemento HTML, no caso p:

    p {font-style: italic;}


## Peso da fonte: `font-weight`

Para dar destaque a algum conteúdo, é comum deixarmos o texto em negrito. Para este caso, podemos dizer que aumentamos o "peso" da fonte. É desse contexto que vem o nome da propriedade, em que a palavra inglesa weight, quando traduzida para o português, significa peso. Para ela, podemos atribuir cinco valores: `normal`, `bold` (negrito), `bolder` (um valor mais pesado que o negrito), `lighter` (que traduzido temos "mais leve", ou seja, que deixa a fonte mais "fina") e `inherit` (que traduzido temos "herdado", ou seja, ele recebe o valor que foi atribuído a elementos que o contém).

Também é possível utilizar como valor a escala de números de 100, 200, 300, 400, 500, 600, 700, 800 e 900, sendo que 100 é o mais leve/fino e 900 o mais pesado/grosso. Entretanto, para usar esses valores é preciso verificar antes se a fonte escolhida possui essas variações, senão, não irá funcionar.

Observe o exemplo abaixo:

    p {font-weight: bold;}

## Altura da linha: `line-height`

A propriedade `line-height` refere-se à distância entre duas linhas de um texto, ou seja, controla o espaçamento das linhas. Os valores que podem ser atribuídos são similares aos possíveis no `font-size` e as medidas mais utilizadas são pixel, porcentagem ou valores numéricos.

Ao utilizar a medida em pixel, você está atribuindo um valor estático/absoluto à linha, que independe de outras propriedades. Isso quer dizer que se, por exemplo, for atribuído 30px à altura da linha, ela terá sempre o espaçamento de 30px.

Porcentagem, numeral e `em` são valores dinâmicos que se baseiam no tamanho da fonte do texto. Por exemplo, se o texto tem o font-size de 14px, ao atribuir um line-height de 100%, a linha terá a altura de 14px. Mas, mantendo a font-size de 14px e atribuindo o valor 2 para a line-height, o espaçamento terá a altura de 28px, sendo 14px multiplicado por 2.

    p {line-height: 2;}

## A propriedade `font`

Diferentemente da propriedade `color` que recebe apenas um valor, a propriedade `font` é uma forma resumida ou a forma curta de aplicar todas as propriedades acima de uma só vez. Para isso, deve-se escrever os valores desejados na seguinte ordem: `font-style`, `font-variant`, `font-weight`, `font-size`, `line-height` e `font-family`, conforme o exemplo a seguir:

    p {font: italic normal bold 14px 100% Georgia, serif;}

**Importante**: exceto `font-size` e `font-family`, as outras propriedades são opcionais.
