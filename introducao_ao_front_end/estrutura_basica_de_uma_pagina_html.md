# Estrutura básica de uma página HTML

Para começar, abaixo está a estrutura básica de uma página HTML.

```html
<!DOCTYPE html>
<html lang="pt">
    <head>
        <meta charset="utf-8">
        <title>Meu primeiro site</title>
    </head>
    <body>
        <h1>Olá mundo!</h1>
        <p>Oba, eu sei criar sites!</p>
    </body>
</html>
```

- `<!DOCTYPE html>` significa que o arquivo em questão é uma página HTML
- A tag `<html lang="pt">` dá início ao conteúdo HTML, com o atributo `lang="pt"` indicando que o conteúdo da página é em português.
- Os elementos `head` e `body` são estruturais e fundamentais para toda página HTML. Dentro das tags `<head>` é onde inserimos as informações sobre a página que serão lidas apenas pelo navegador. Dentro dessa tag, estão inclusive as informações para mecanismos externos de redes sociais e busca. Essas informações **não** são visíveis ao usuário, apenas o elemento `<title>` que normalmente é mostrado na janela dos navegadores.
- O `<body>` contém todo o conteúdo HTML da sua página que será visível ao usuário.
- `<h1>` é a tag utilizada para os títulos principais e `<p>` representa parágrafos.


## Mãos à obra!

Escolha um editor de sua preferências, nós recomendamos o [Sublime Editor](http://www.sublimetext.com/) mas pode ser até o bloco de notas, crie um arquivo com a extensão .html e insira o código acima. Pronto, você já tem sua primeira página HTML!
