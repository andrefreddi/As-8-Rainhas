# AS 8 RAINHAS 

### O QUE EXATAMENTE SERIA O PROBLEMA
<p>
&nbsp &nbsp &nbsp Bom, é possivel colocar 8 rainhas em um tabuleiro só ? sabendo que as rainhas tem um movimento bem completo isso realmente pode sim se tornar um grande desafio, primeiramente acho interessante entendermos como a rainha se movimenta: 

  ![](ex01.jpg)
  
<p>
&nbsp &nbsp &nbsp Agora que ja estamos de acordo com as movimentacoes da nossa rainha vamos tentar entender o codigo que ira solucionar isso, colocando em um tabuleiro 8x8 8 rainhas posicionadas de maneira com que nenhumas delas se ataque. <strong>OBS: a rainha da critico</strong>

### Listas

<p>
&nbsp &nbsp &nbsp As listas encadeadas é um tipo de estrutura que contém nela um grupo de nós interligados através de ponteiros, onde nessa estrutura o início aponta para a o primeiro ponteiro e o segundo aponta para o próximo e assim até que o próximo ponteiro a ser apontado seja <strong>NULL</strong> denominando assim o fim da lista. Nas listas utilizamos o <strong>“malloc”<strong> para alocar um espaço na memória onde nossa lista irá ficar, e assim iremos poder atualizar a lista com os valores da posição de cada elemento.
<br>
&nbsp &nbsp &nbsp Para listas encadeadas temos diversas interações, umas delas adicionar um elemento ao fim da lista, para isso temos que fazer com que nosso último elemento, cujo aquele que aponta para <strong>NULL</strong> aponte para nosso novo elemento e nosso novo elemento aponta para <strong>NULL</strong>, vemos um exemplo com, um início, 2 elementos e um elemento a ser adicionado e <strong>NULL</strong>:
</p>

![](ex01.png)
