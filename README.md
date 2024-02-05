# Projeto
Esse projeto utiliza um algoritmo genético evolucionário para a análise de 5 bases de dados diferentes com coordenadas para que formam o Problema do Caxeiro Viajante.

# Conclusão
Utilizado de maneira correta no final serão gerados 5 arquivos em formato .txt ou .xlsx para verificação dos resultados.
O resultado final é composto por 6 diferentes combinações de métodos sendo esses: 

**Leia-se cx = método de cruzamento, mut = método de mutação e sel = método de seleção de indivíduos**

Combinação 1: cxPartialyMatched # mutShuffleIndexes # selTournament <br/>
Combinação 2: cxPartialyMatched # mutShuffleIndexes # selRoulette <br/>
Combinação 3: cxUniformPartialyMatched # mutShuffleIndexes # selTournament <br/>
Combinação 4: cxUniformPartialyMatched # mutShuffleIndexes # selRoulette <br/>
Combinação 5: cxOrdered # mutShuffleIndexes # selTournament <br/>
Combinação 6: cxOrdered # mutShuffleIndexes # selRoulette <br/>

Para cada uma das combinações a seguir são exibidos 10 rodadas de soluções com o Melhor Custo, a Média e o Desvio Padrão.
