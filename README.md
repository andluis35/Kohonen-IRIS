# Kohonen-IRIS
Experimentos de afinação de parâmetros com o modelo de Kohonen (Mapas Auto-Organizáveis) aplicado à base de dados Iris.

| Experimento                     | Mapa  | Taxa de Aprendizado | Iterações | Raio Inicial    | Constante de Tempo | Acurácia         |
|---------------------------------|-------|---------------------|-----------|-----------------|--------------------|------------------|
| #1 (Referência)                 | 10x10 | 0.4                 | 20.000    | 5               | N/ln(5)            |                  |
| #2 (Mapa Menor)                 | 5x5   | 0.4                 | 20.000    | 2,5             | N/ln(2,5)          |                  |
| #3 (Mapa Maior)                 | 15x15 | 0.4                 | 20.000    | 7,5             | N/ln(7,5)          |                  |
| #4 (Aprendizagem Baixa)         | 10x10 | 0.1                 | 20.000    | 5               | N/ln(5)            |                  |
| #5 (Aprendizagem Alta)          | 10x10 | 0.5                 | 20.000    | 5               | N/ln(5)            |                  |
| #6 (Poucas Iterações)           | 10x10 | 0.4                 | 5.000     | 5               | N/ln(5)            |                  |
| #7 (Muitas Iterações)           | 10x10 | 0.4                 | 50.000    | 5               | N/ln(5)            |                  |
| #8 (Raio Menor)                 | 10x10 | 0.4                 | 20.000    | 3               | N/ln(3)            |                  |
| #9 (Raio Maior)                 | 10x10 | 0.4                 | 20.000    | 7               | N/ln(7)            |                  |
| #10 (Decaimento Mais Rápido)    | 10x10 | 0.4                 | 20.000    | 5               | 0,5tref            |                  |
| #11 (Decaimento Intermediário)  | 10x10 | 0.4                 | 20.000    | 5               | 1,5tref            |                  |
| #12 (Decaimento Mais Lento)     | 10x10 | 0.4                 | 20.000    | 5               | 2tref              |                  |