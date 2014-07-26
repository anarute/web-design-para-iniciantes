# Seletores

Existem vários tipos de seletores. Tratarei aqui apenas de três formas que conseguem cobrir muitos casos de uso. Se você quiser aprender mais, [este artigo](http://tableless.com.br/seletores-complexos-do-css/) traz alguns mais complexos.

## Seletor por elemento

É quando selecionamos utilizando o nome do elemento. Ao fazer isso, todos os elementos iguais serão afetados. Por exemplo, no código abaixo, todos os parágrafos ficarão com a cor de fonte azul.
```css
p {
    color: #000088;
}
```

## Seletor por classe

Ao selecionar por classe, todos os objetos que tiverem a classe indicada serão afetados. No exemplo abaixo, todos os elementos que tiverem como atributo `class="classe"` ficarão com texto em negrito:

```css
.classe {
    font-weight: bold;
}

```

## Seletor por id

```css
#iddoobjeto {
    border: 1px solid #CCC;
}

```

## Aprenda seletores com um joguinho

Aprenda a usar os seletores acima e outros tipos com [este joguinho](http://paularfurtado.github.io/css-selector-game) desenvolvido por [Atul Varma](http://toolness.com) da Mozilla e traduzido livremente para português pela [Paula Furtado](http://paulafurtado.blog.br).

Dúvidas? Deixe suas perguntas [aqui](https://github.com/anarute/web-design-para-iniciantes/issues/new).
