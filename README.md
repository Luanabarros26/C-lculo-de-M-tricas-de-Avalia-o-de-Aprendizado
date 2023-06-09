# C-lculo-de-M-tricas-de-Avalia-o-de-Aprendizado
Neste projeto, vamos calcular as principais métricas para avaliação de modelos de classificação de dados, como acurácia, sensibilidade (recall), especificidade, precisão e F-score.
# Definir a matriz de confusão
VP = 50  # Verdadeiros positivos
VN = 80  # Verdadeiros negativos
FP = 20  # Falsos positivos
FN = 10  # Falsos negativos

# Calcular sensibilidade (recall)
sensibilidade = VP / (VP + FN)

# Calcular especificidade
especificidade = VN / (FP + VN)

# Calcular acurácia
N = VP + VN + FP + FN
acuracia = (VP + VN) / N

# Calcular precisão
precisao = VP / (VP + FP)

# Calcular F-score
f_score = 2 * (precisao * sensibilidade) / (precisao + sensibilidade)

# Imprimir os resultados
print(f"Acurácia: {acuracia}")
print(f"Sensibilidade: {sensibilidade}")
print(f"Especificidade: {especificidade}")
print(f"Precisão: {precisao}")
print(f"F-score: {f_score}")
Neste exemplo, utilizamos uma matriz de confusão fictícia com valores arbitrários de Verdadeiros Positivos (VP), Verdadeiros Negativos (VN), Falsos Positivos (FP) e Falsos Negativos (FN).

Em seguida, utilizamos as fórmulas correspondentes às métricas mencionadas para calcular seus respectivos valores.
