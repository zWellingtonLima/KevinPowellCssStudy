# Anotações
Quando definimos width ou height com tamanhos específicos (px) ao diminuir a tela abaixo do valor usado o browser cria uma barra de rolagem, o que não é legal quando se busca responsividade.
<p>
Trabalhar com porcentagens é uma saída melhor do que px. Um elemento pai naturalmente ocupa 100% do width quando este não é definido, logo, ele ocupa toda a tela horizontalmente.
</p>

<p>
Se o elemento pai ocupar 100% de width o filho também ocupada pois ele herda, quando se tratando de divs usando classes (.parent e .child). 
</p>

<p>
Caso eu colocasse a div.parent com um valor de width: 90%; e a div.child com width: 50%;, este 50 seria relativo aos 80% da div.parent.
</p>
<br>

## Why it's a good idea to avoid heights

<p>
Definir altura normalmente não é ideal pois em diferentes resoluções pode fazer o conteúdo se espremer muito e sair do parent. É recomendando evitar, sempre que der, estabelecer alguma altura, principalmente em px. Quando for usar o padding é uma boa saída. Portanto, pensando em responsividade, o padding deve usar uma medida responsiva também (o Rem ou Em).
</p>
