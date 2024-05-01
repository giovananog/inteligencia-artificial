# K-NN (K-Nearest Neighbors)

- O k-NN pertence à classe dos classificadores preguiçosos (lazy learning).
  
  - **Lazy learning:** A cada novo objeto que se quer classificar, utiliza-se os dados de treinamento para verificar quais são os objetos que mais se assemelham ao novo objeto. O objeto será classificado dentro da classe mais comum a que pertencem os objetos mais similares a ele.

- Aprendizagem baseada em instâncias.
- O modelo simplesmente armazena os exemplos de treinamento.
- A generalização é feita somente quando uma nova instância deve ser classificada.
- Assumem que as instâncias podem ser representadas como pontos em um espaço.

## Principais Métricas de Distância

- Distância Euclidiana
- Distância de Minkowski
- Distância de Mahalanobis
- Distância de Manhattan
- Distância via operador Cosseno

  - A escolha dos operadores de manipulação de features pode ter um impacto significativo no desempenho do K-NN.
  - O operador adequado está diretamente relacionado com o problema em análise.

## Utilização do K-NN

- Para utilizar o K-NN é necessário:
  1) Um conjunto de treinamento.
  2) Definir uma métrica para calcular a distância dos dados.
  3) Definir o número de vizinhos mais próximos que serão considerados pelo algoritmo (k).

- Para classificar uma nova instância com o algoritmo k-NN é necessário:
  1) Calcular a distância entre a nova instância e os outros exemplos do conjunto de treino.
  2) Identificar os k vizinhos mais próximos.
  3) Utilizar o rótulo da classe dos vizinhos mais próximos para determinar o rótulo de classe do exemplo desconhecido (ex: votação majoritária).

- Como escolher o valor de K?
  - Se K for muito pequeno, a classificação fica sensível a pontos de ruído; se K for muito grande, a vizinhança pode incluir elementos de outras classes; é recomendado escolher um valor ímpar para K, visando evitar empates na votação.

## Vantagens:

- Técnica simples e facilmente implementada.
- Bastante flexível.
- Em alguns casos apresenta ótimos resultados.

## Desvantagens:

- Classificar um exemplo desconhecido pode ser um processo computacionalmente complexo.
- A precisão da classificação pode ser severamente degradada pela presença de ruído ou características irrelevantes.