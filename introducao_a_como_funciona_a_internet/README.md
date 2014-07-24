# Introdução sobre como funciona a internet

##O que é a Internet, a Web, o DNS e os tipos de conteúdo

Vamos esclarecer as diferenças entre cada um desses conceitos.

**O que é a internet e como ela funciona?**

A internet é uma rede global de computadores interligados que utilizam uma série de regras de comunicação para trocarem informações entre si. Ela surgiu em 1974, quando alguns pesquisadores criarem o **Internet Protocol Suite** ou **TCP/IP**, que um protocolo de comunicação entre computadores.

Com esse protocolo, cada computador possui um endereço único que servirá para que outros computadores o localizem. Esse endereço, chamado de **IP**, é o ponto fundamental para conectar um dispositivo à internet. O IP também é utilizado em redes locais, como por exemplo quando você tem um roteador em casa: esse dispositivo tem um IP próprio com o qual ele se conecta à internet e o seu computador tem um outro IP com o qual ele se conecta ao roteador.

Para trocar informações, todos esses dispositivos utilizam uma série de protocolos que nada mais são do que **regras de comunicação**. Um dos protocolos mais comuns é o TCP, considerado uma das bases da internet sendo que várias regras de comunicação dentro desse contexto baseiam-se nele.

**Qual a diferença entre internet e web?**

A internet é a rede de computadores, a Web que é um sistema de documentos interligados que acessamos na internet através de um **navegador**, é o famoso www (World Wide Web). Ao utilizar um navegador, você está, na prática, fazendo uma série de pedidos de informação para servidores na internet. Esses pedidos são feitos utilizando regras específicas que permitem que os servidores e seu navegador troquem informações. Logo, quando colocamos um endereço na barra do navegador, como por exemplo http://gitbook.io, ele gera um pequeno **pacote** com informações e envia para a internet. Este arquivo é utilizado para encontrar o servidor (dependendo do porte do site, podem ser vários servidores!) onde se encontram os arquivos do gitbook que então envia para seu computador, de usuário, as informações pedidas e que são exibidas pelo seu navegador.

**De onde vem as informações dos sites?**

Enviar arquivos para a internet quer dizer que estes arquivos estão sendo disponibilizados na rede através da placa de rede do seu computador. Ela envia o dado que é capturado pelo seu provedor de internet, que em seguida envia para servidores que contêm um sistema chamado **DNS** (Sistema de Nomes de Domínios), que, por sua vez, descobrem o servidor que contém as informações e arquivos do site que você está buscando. Estes tais servidores DNS são computadores que possuem o endereçamento de vários outros servidores e ajudam a mapear as informações da rede.

Ao receber todas as informações do servidor, seu navegador realiza sua leitura e as exibe em formato de página web. Essas informações vêm em vários formatos, como texto, imagem e vídeos. A informação textual divide-se em duas partes: uma que descreve como a página web deve se apresentar e se comportar e outra que contém o conteúdo a ser exibido.

---
###Quer aprender mais?

- Leia este pequeno ebook [20 lições que aprendi sobre navegadores e a web](http://www.20thingsilearned.com/pt-BR)
- [What's my DNS?](https://www.whatsmydns.net/) - Entenda visualmente como funcionam os servidores de DNS descobrindo onde são guardados os endereços dos sites no mundo inteiro os IPs dos servidores de cada site
