# Programa-o-Linear-MEB_V-e-MEB_L
Trabalho final da disciplina de matemática computacional na UFC - Quixadá

# Descrição do trabalho

Deve implementar as formulações MEB V e MEB L;
Usa a biblioteca NetworkX para gerar grafos bipartite, usando bipartite.random_graph(n,m,p);
O tamanho da instância será |L| \in {10, 20, 30, 40, 50}, com |L| = |R|;
O valor de k \in {3};


Gere instâncias com p = 0.5 e 0.8, considerando grafos esparsos e tensos.


Gere um notebook python contendo as comparações entre as duas formulações. As comparações serão feitas pelo tamanho do grafo, sua densidade e pelo valor do k. 


Tempo máximo de execução será de 30 minutos.



# Sets a time limit of 1800 seconds.
solver.parameters.max_time_in_seconds = 1800.0


https://networkx.org/documentation/networkx-1.9/reference/generated/networkx.generators.bipartite.bipartite_random_graph.html
