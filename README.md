# alocadorArtigos
Aloca artigos para revisores de acordo com preferência. Utiliza algoritmo genético com elitismo. Gera gráficos com resultados das várias etapas da simulação. Gera também a saída com o melhor resultado. 

Recebe uma matriz como entrada represantando os revisores de artigos e a afinidade deles por cada artigo. A última coluna da matriz representa o número máximo de artigos que cada revisor aceita avaliar.

A saída é um vetor de artigos, onde cada posição do vetor (cada artigo) contém o número do seu revisor.

O artigo em golang é um gerador de matrizes aleatório. 
