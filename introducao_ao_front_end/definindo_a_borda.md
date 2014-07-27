# Definindo a borda dos elementos

Com as propriedades `border-*` conseguimos modificar o estilo das bordas dos elementos HTML. Veja abaixo:

## Espessura da borda: `border-width`

Podemos utilizar várias unidades de medida para a espessura da borda, mas a mais utilizada é pixels.

## Estilo da borda: `border-style`

Existem vários estilos de borda, como pontilhada, sólida, dupla. Para declarar os valores para essa propriedade, a sintaxe é `elemento {border-style: valor;}`. Os valores possíveis são:

- dotted
- dashed
- solid
- double
- groove
- ridge
- inset
- outset
- none
- hidden

Experimente na sua página esses valores e vejam como eles são.

## Cor da borda: `border-color`

As formas para declarar as [cores](http://escola.mupi.me/conteudos/design-cores) da borda são similares às da propriedade [color](propriedades_tipograficas.md): através do sistema hexadecimal, RGB ou RGBa. Veja o exemplo a seguir em que é declarada a cor vermelha (em RGB) para a borda:
`img {border-color: #000000;}`

## A propriedade `border`

A forma mais simplificada de declarar a borda é através da propriedade `border`. Ela já engloba as três propriedades descritas acima, sendo que a ordem deve ser `border-width`, `border-style` e `border-color`, como por exemplo em `footer {boder: 2px solid #444;}`

---

### Fica a dica!

Você pode declarar a borda de cada lateral de um elemento separadamente, caso elas tenham estilos diferentes. Para isso, usamos as propriedades `border-top` (superior), `border-left` (esquerda), `border-bottom` (inferior) e `border-right` (direita).
