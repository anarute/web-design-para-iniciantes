# Principais tags

- **Títulos**: `<h1>Título principal</h1>` Para títulos, temos uma série de elementos que vão de `h1` a `h6`, onde quanto maior o número menor a importância do título. Por exemplo, o título principal deve ser representado pelo elemento `h1`, o título de um conteúdo que está abaixo do principal deve vir entre tags `h2`, e por aí vai até o nível 6.
- **Parágrafo**: `<p>Conteúdo</p>`
- `<br/>` representa quebra de linha e é uma tag "auto fechante", pois a mesma tag de abertura é a de fechamento.
- **Âncoras**:
```html
<a href="https://webmaker.org/pt-BR" target="_blank">Webmaker</a>
```
`href` é o endereço do link e `target` onde o link será aberto, neste caso `_blank` abrirá numa nova aba.
- **Listas**: as listas são representadas pelos elementos `<ul>`quando a lista não é ordenada e `<ol>` quando ordenadas. As listas contém itens, que também são elementos HTML, representados pelas tags `<li>`, por exemplo:
```html
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
    </ul>
```
- **Imagens**:
```
<img src="http://escola.mupi.me/img/fotoGato1.png" title="Gato fofinho" alt="Foto de gatinho" />
```
Onde: `src` é o endereço onde está a imagem (source em inglês),  `title` é o título da imagem e `alt` é o texto que aparecerá caso a imagem não possa ser carregada. Esse código mostrará a seguinte imagem:
<img src="http://escola.mupi.me/img/fotoGato1.png" title="Gato fofinho" alt="Foto de gatinho" />
