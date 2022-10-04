# Anotações
Quando definimos width ou height com tamanhos específicos (px), ao diminuir a tela abaixo do valor usado, o browser cria uma barra de rolagem, o que não é legal quando se busca responsividade.
<p>
Trabalhar com porcentagens é uma saída melhor do que com px. Um elemento pai naturalmente ocupa 100% do width quando este não é definido, logo, ele ocupa toda a tela horizontalmente.
</p>

<p>
Se o elemento pai ocupar 100% de width o filho também ocupada pois ele herda, quando se tratando de divs usando classes (.parent e .child). 
</p>

<p>
Caso eu colocasse a div.parent com um valor de width: 90%; e a div.child com width: 50%;, este 50 seria relativo aos 90% da div.parent.
</p>
<br>

<p>Usar tamanhos fixos em elementos filhos podem promover problemas com responsividade pois, digamos que no mesmo exemplo, o elemento filho tem 700px, quando o browser atingir esse limite a div vai se alongar para o lado e gerar o scroll lateral.</p>
## Why it's a good idea to avoid heights

<p>
Definir altura normalmente não é ideal pois em diferentes resoluções pode fazer o conteúdo se espremer muito e sair do parent. É recomendando evitar, sempre que possível, estabelecer alguma altura, principalmente em px. Quando eu precisar setar alguma altura é possível usar o padding. Portanto, pensando em responsividade, o padding deve usar uma medida responsiva também (o Rem ou Em) invés de px, por exemplo.
</p>
 
 