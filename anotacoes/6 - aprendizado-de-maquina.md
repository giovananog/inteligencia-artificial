# Aprendizado de Máquina

## Definições

- **Machine Learning:**
  - Definição 1: “Aprender gera alterações no sistema que são adaptativas, criando adaptações que capacitam o sistema a realizar a mesma tarefa, ou tarefas provenientes da mesma população, de forma mais eficiente e eficaz na próxima vez” - (Simon, 1983)
  - Definição 2: “...todo aprendizado pode ser visto como o aprendizado de uma função” - (Russel & Norvig 1995)
  - Definição 3: “é a construção e a modificação da representação do que está sendo experimentado” – (Michalski, 1986)

## Principais Tipos de Problemas

- **Agrupamento (Clustering):**
  - Definição: Técnicas capazes de agrupar os elementos de um dado conjunto em grupos, de modo que os elementos de um mesmo grupo apresentem similaridades.
  - Dados não possuem rótulos (classes ou targets).
  - A separação é realizada por meio de métricas de distância.

- **Classificação:**
  - Dados possuem rótulo.
  - Treinamento realizado em dados rotulados.
  - Os modelos passam por um processo de treinamento monitorado.
  - Leva em consideração um conjunto de dados rotulados para realizar a classificação (dar rótulo) a um novo elemento desconhecido.
  - Aprende as relações dos dados rotulados (conjunto de treino) e utiliza estas relações em dados desconhecidos.
  - Durante a execução de um algoritmo de classificação de padrões nenhum novo rótulo (ou classe) é criado.
  - Os rótulos utilizados para ajustar (ou treinar) o classificador são aqueles existentes no conjunto de treino.
  - O objetivo de um classificador é encontrar o rótulo de um novo elemento levando em consideração o aprendizado obtido a partir do histórico de dados já rotulados.

- **Aproximação de Funções:**
  - Objetivo: Desenvolver modelos computacionais capazes de representar o comportamento de um fenômeno que varia em função do tempo com certo grau de aleatoriedade.
  - Criar modelos para estimar o comportamento de uma determinada série de dados.
