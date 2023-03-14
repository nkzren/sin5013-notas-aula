# Análise de Algoritmos

## Problema NP-complexo
*Non-Polinomial* complex, que é um problema que só possui soluções com
complexidade não-polinomial.

---

Na área de análise de algoritmos, é possível analisar um algoritmo em particular
ou uma classe de algoritmos

## Análise de um algoritmo particular

Questões que geralmente são levantadas envolvem estimar o custo de um algoritmo
para resolver um problema específico, qual o custo de memória, quantas vezes
cada parte do algoritmo é executado

## Análise de classe de algoritmos

Quando estamos analisando uma classe de algoritmos, geralmente queremos
encontrar o de menor custo para resolver um problema específico. Para isso, é
necessário investigar uma família de algoritmos.

Um algoritmo é ótimo quando seu custo é o menor possível.


## Complexidade

Para medir o custo de um algoritmo há algumas abordagens:
1. Medição direta. Muitos fatores externos de software e hardware influenciam
   essa métrica.
2. Computador ideal em que cada instrução tem um custo fixo (proposto por Donald Knuth).
3. Considerar apenas as operações mais significativas. Método usual.

Nos slides da aula há alguns exemplos de funções de complexidade

---

### Função de Complexidade

#### Teorema
Qualquer algoritmo para encontrar o maior elemento num conjunto de n elementos
(n >= 1), faz ao menos `n - 1` comparações

#### Prova
Cada um dos n - 1 elementos deve ser verificar que é menor do que algum outro
elemento por meio de comparações. Logo, o mínimo são `n-1` comparações

---

### Exercícios
1. Determinar função de complexidade para busca sequencial (pior, melhor, médio)
Melhor -> 1
Pior -> n
Médio -> (n+1)/2 (Média da soma da P.A. com todos os casos possíveis)

2. Determinar a função de complexidade da ordenação por inserção direta no pior
   caso
[Resposta](https://pt.wikipedia.org/wiki/Insertion_sort)
