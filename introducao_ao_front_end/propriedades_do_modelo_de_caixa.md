# Propriedades do modelo de caixa

Como todos os elementos possuem forma retangular, podemos atribuir algumas propriedades relativas a isso, como altura e largura.

## Altura e largura

Para definir os valores de `width` e `height`, podemos utilizar as unidades de medidas como pixels, porcentagem e pontos. Essas unidades são utilizadas também para a propriedade `font`. Veja [aqui](http://reeddesign.co.uk/test/points-pixels.html) uma tabela bastante útil para conversões de medidas.

O exemplo a seguir determina a altura e a largura da imagem abaixo que possui a classe "exemplo-width-height". Nessa classe ela vai ocupar 50% da largura do seu elemento pai, ou seja, a largura da página.

    img.exemplo-width-height{
        width: 50%;
        height: auto;
    }

-- COLOCAR IMAGEM --

## Margin e padding

A propriedade `margin` (que traduzida significa margem) é o espaço que fica entre o elemento e os demais que estão ao seu redor.

A propriedade `padding` serve para definir o espaço **interno** que fica entre a borda e o conteúdo do elemento. Assim como em `width` e `height` você pode utilizar vários tipos de unidades de medida de acordo com a necessidade.
