# Estruturas-de-Dados SME0827
Trabalho realizado para a disciplina de Estruturas de Dados
- O problema envolvia a otimização da alocação de k brigadas até n focos de incêndios
- Cada foco de incêndio possuia uma taxa de crescimento diária
- Cada brigada possuia uma capacidade específica de de combate a incêndios
- Os focos e as brigadas estavam distribuídos como em um grafo, em que as arestas representam o tempo de deslocamento 

Foi usada uma heurística que distribuia as capacidades levando em conta tanto a demanda de cada foco quanto a capacidade real de cada brigada em relação a cada foco (essa capacidade real nada mais é que a capacidade da brigada por hora x horas úteis que ela tem para um foco, descontando o deslocamento). Claro, essa não era a solução ótima, mas forneceu resultado satisfatório.
