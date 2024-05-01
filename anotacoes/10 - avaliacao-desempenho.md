Mensurar aplicabilidade
de um modelo

• A métrica utilizada pode refutar ou endossar a
aplicação de um modelo; • A utilização de métricas não adequadas pode
validar a escolha de modelos inadequados; • Cada problema possui uma abordagem ótima para
mensurar os resultados de um modelo;

Confiabilidade x Validade

(imagem que ta em "./imagens/confiabilidade-validade.png")


Matriz de confusão

• A matriz de confusão (confusion matrix) é usada
para criar um cenário de avaliação do
desempenho de um classificador. • True positive (TP) ou Verdadeiros Positivos (VP): casos
em a classe (+) é classificada como (+); • False positives (FP) ou Falsos positivos (FP): situações em que a classe (-) recebe classificação (+); • False Negative (FN) ou Falsos Negativos (FN):
situações em que a classe (+) é classificada como (-); • True Negative (TN) ou Verdadeiros Negativos (VN):
casos que a classe (-) recebe a classificação (-);

(imagem que ta em "./imagens/matriz-confusao.png")


Acurácia

• Número de acertos dividido pelo
número dos dados do teste;

(imagem que ta em "./imagens/acuracia-precisao.png")

Precisão

• É o número de resultados
positivos corretos (TP) dividido
pelo número de resultados
positivos previstos pelo
classificador (TP + FP).

Recall (Revocação) • É o número de resultados
positivos corretos dividido (TP)
pelo número de todas as amostras
que deveriam ter sido
identificadas como positivas
(TP+FN); • A frequência em que o seu
classificador encontra os
exemplos de uma classe, ou
seja, “quando realmente é da
classe X, o quão frequente você
classifica como X?”


F1 Score

Trata-se da média harmônica das
medidas precisão e recall. • F1-Score traz em uma única
medida de desempenho um
equilíbrio entre a precisão e
recall;

• F1 Score é uma métrica melhor que a Accuracy, principalmente em casos
onde falsos positivos e falsos negativos possuem impactos diferentes para
seu modelo;