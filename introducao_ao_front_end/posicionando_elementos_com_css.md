# Posicionando elementos com CSS

Antes de aprender a posicionar elementos com CSS, é importante que você entenda o que é o [modelo de caixa](http://docs.escolamupi.com.br/modelo-de-caixa).

De forma resumida, todo elemento HTML tem o formato de uma caixa retangular, mesmo que isso não seja visível ao usuário. Por isso, é possível atribuir a todo elemento propriedades como altura e largura. Uma maneira fácil de visualizar isso, é colocar bordar em todos os elementos da sua página, como fiz com essa página que você está lendo:

    * { border: 1px solid #CCC;}

Onde `*` seleciona todos os objetos da página. Perceba como tudo tem um formato retangular. Esse conceito é chamado de **modelo de caixa**.

Perceba também que existem elementos que englobam outros, essa relação cria um "parentesco" entre eles, nos permitindo chamá-los de pais ou filhos, sendo pai o elemento que engloba e filho o que está dentro do outro. Entender essa relação é muito importante ao se trabalhar com CSS, pois existe um conceito chamado **hierarquia** no qual algumas propriedades são *herdadas* e passadas de pai para filho.
