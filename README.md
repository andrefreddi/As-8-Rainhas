# AS 8 RAINHAS 

### O QUE EXATAMENTE SERIA O PROBLEMA
<p>
&nbsp &nbsp &nbsp Bom, é possivel colocar 8 rainhas em um tabuleiro só ? sabendo que as rainhas tem um movimento bem completo isso realmente pode sim se tornar um grande desafio, primeiramente acho interessante entendermos como a rainha se movimenta: 

  ![](ex01.jpg)
  
<p>
&nbsp &nbsp &nbsp Agora que ja estamos de acordo com as movimentacoes da nossa rainha vamos tentar entender o codigo que ira solucionar isso, colocando em um tabuleiro 8x8 8 rainhas posicionadas de maneira com que nenhumas delas se ataque. <strong>OBS: a rainha da critico</strong>

### VAMOS FALAR DE CÓDIGO

<p>
&nbsp &nbsp &nbsp Como nossas funções auxiliares vamos gerar as permutações do vetor, precisamos de uma função auxiliar que troca/inverte dois elementos de um vetor, veja:
  
  ![](ex02.jpg)
  
<p>
&nbsp &nbsp &nbsp Precisamos tambem verificar as nossas diagonais, e quem fara esse trabalho sera uma função que verifica se uma dada permutação do vetor linhas corresponde a uma solução do problema, veja.

  ![](ex03.jpg)
  
<p>
  
