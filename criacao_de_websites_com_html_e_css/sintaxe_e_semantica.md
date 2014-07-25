# Sintaxe e semântica

É importante ressaltar que o HTML é a linguagem responsável pela organização e estrutura do conteúdo de uma página. Quando falamos em **semântica** no HTML queremos dizer que o código HTML está de acordo com o conteúdo que está sendo tratado. Por exemplo, se estamos escrevendo um parágrafo, devemos indicar isso no HTML assim como um título deve ser inserido com o código específico para títulos.

Podemos entender o HTML em 3 conceitos fundamentais: os elementos, as tags e os atributos.

## Elementos

Os elementos são os objetos de uma página HTML que informam ao navegador o que representa cada trecho do arquivo HTML. Através dos elementos que informamos que um parágrafo é um parágrafo, uma imagem é uma imagem, e por aí vai :)

Uma dica para para pensar um texto em elementos é tentar dividi-los em unidades: parágrafos, títulos, subtítulos, imagens, palavras destacadas, links.


## Tags
A tag é forma como escrevemos os elementos, representadas por `<`e `>` ao redor do elemento. Um elemento é normalmente representado por *tags de abertura* e *tags de fechamento* e tudo que estiver no meio das tags está contido no elemento. Exemplo, para escrevermos um parágrafo, utilizamos o seguinte código:
```
<p>Conteúdo do parágrafo</p>
```

Onde `<p>` é a tag de abertura do elemento `p` que representa parágrafo e `</p>` é a tag de fechamento. Sendo tudo que está entre elas o conteúdo do parágrafo.

## Atributos

Atributos são as propriedades atribuídas aos elementos. Sua sintaxe é sempre descrita com o nome do atributo, o sinal de `=` e um valor entre aspas: `nomeDoAtributo="valor"`.

Por exemplo, para o elemento `a`, que determina um link ou âncora, temos o atributo `href` que indica o caminho para onde o usuário será direcionado quando clicar em um certo trecho de texto. Veja em `<a href="http://pt.wikipedia.com" >Wikipedia</a>`, o texto "Wikipedia" é uma âncora para o endereço http://pt.wikipedia.com.
