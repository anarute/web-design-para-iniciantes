# Inserindo CSS

Existem 3 formas básicas de aplicar css em uma página:

## Inline

Significa realizar alterações diretamente na tag do elemento a ser estilizado no código html, através do atributo chamado style.
```html
<p style="color: #FF0000;">
  Oi! A cor deste parágrafo foi mudada inline através
  do atributo style na tag <p>.
</p>
```
Que gera este resultado:
<p style="color: #FF0000;">
  Oi! A cor deste parágrafo foi mudada inline através
  do atributo style na tag `<p>`.
</p>

## Tag style

Dentro do código html, é possível inserir uma tag de nome `style` que será lida apenas pelo navegador e pode conter o css de todos os elementos da página. O ideal é inserir dentro das tags `<head></head>`
```html
<style type="text/css">
    p.exemplo{
        border: 1px dashed #00F;
    }
</style>
<p class="exemplo">
    Oi! A borda deste parágrafo foi mudada através da tag <code>style</code>.
</p>
```
Que gera o resultado:
<style type="text/css">
    p.exemplo{
        border: 1px dashed #00F;
    }
</style>
<p class="exemplo">
    Oi! A borda deste parágrafo foi mudada através da tag <code>style</code>.

## Arquivo externo

A forma mais utilizada e recomendada é colocar o css em um arquivo externo que terá que ser importado, através de um link entre arquivos, para a página HTML. Podem ser usados um ou mais arquivos e essa é uma decisão de organização do projeto que deve ser realizada de acordo com a complexidade dele, você pode ter um arquivo CSS para cada tipo de template, por exemplo.

Para inserir o CSS desta maneira, você precisa indicar o caminho de onde está o arquivo. Para isso, utilizamos a elemento `link`, com os atributos `type` e `rel`, que indicam que o conteúdo do arquivo é uma folha de estilo em CSS, e o atributo `href` para indicar a localização do arquivo:
```html
<link rel="stylesheet" type="text/css" href="caminho/arquivo.css" />
```

## Boas práticas

A forma mais recomendada para utilização de CSS é através de importação de arquivos externos pelos seguintes motivos:
- Organização do projeto de um site, separando a parte de conteúdo da parte visual em arquivos específicos, de acordo com a linguagem (HTML ou CSS).
- Permitir que o mesmo estilo seja aplicado em diferentes páginas do mesmo site e facilitando a modificação visual de elementos similares, já que suas propriedades visuais estão num mesmo arquivo CSS. Para isso, basta inserir o link em toda página HTML que se queira usar esse estilo.
- Ao aplicar um mesmo estilo a diferentes páginas de um mesmo site, evitamos a repetição de código no projeto e dessa forma economizamos na quantidade de dados enviados para o usuário, que em certos dispositivos e conexões com a internet podem fazer uma grande diferença.
- Facilita a manutenção do site, uma vez que é muito mais fácil você ir direto no arquivo CSS para fazer alterações de estilo do que ficar buscando no meio das páginas HTML.
