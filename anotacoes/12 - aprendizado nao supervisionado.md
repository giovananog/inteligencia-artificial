## Motivação

- Aprendizado a partir de features/atributos das instâncias.
- Principais classes de problemas:
  - Agrupamento (clustering).
  - Redução de Dimensionalidade.

## Agrupamento

- **Definição:** Técnicas capazes de agrupar os elementos de um dado conjunto em grupos, de modo que os elementos de um mesmo grupo apresentem similaridades.
- Dados não possuem rótulos (classes ou targets).
- Dados apresentam somente atributos/features.
- A separação é realizada por meio de métricas de distância.

### Principais Algoritmos

- K-Means.
- Self Organized Maps (SOM).
- Fuzzy C-Means.
- Agrupamento Hierárquico.
- Entre outros.

## Redução da Dimensionalidade

- **Objetivo:** Simplificar os dados e descrevê-los com menos features/atributos, sem perder muita generalidade.

### Como condensamos os atributos/features?

- Há muitas maneiras: é possível adicioná-los, subtraí-los, calcular a média entre pares, entre outras abordagens.
- Qual é a forma mais eficaz/eficiente?
  - Aquela que possui menor perda de informação.
  - A ideia dos algoritmos de redução de dimensionalidade é encontrar maneiras de condensá-los, perdendo o mínimo de informação possível.

### Principais Modelos

- Seleção de atributos (feature selection).
- Análise de componentes principais (PCA).
- Análise de componentes independentes (ICA).
- Fatoração matricial.
- Entre outros.
