# Problema das N-Rainhas usando Algoritmo Genético
Resolvendo o Problema das N-Rainha usando Algoritmo Genético

O objetivo do problema das N-Rainhas é colocar N rainhas em um tabuleiro de xadrez N x N, de modo que nenhuma rainha esteja em conflito com as outras.



### Como o algoritmo genético resolve o problema das n-rainhas?
- Etapa 1: um cromossomo aleatório é gerado
- Etapa 2: o valor de adequação do cromossomo é calculado
- Etapa 3: Se o fitness não for igual a Fmax
- Passo 4: Reproduzir um novo cromossomo (cruzado) de dois melhores cromossomos selecionados aleatoriamente
- Etapa 5: A mutação pode ocorrer
- Passo 6: Novo cromossomo adicionado à população
- Repita os passos 2 a 6 até que um cromossomo (solução) com valor de Fitness = Fmax seja encontrado
