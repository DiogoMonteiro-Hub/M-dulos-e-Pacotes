# M-dulos-e-Pacotes
AT05 Módulos e Pacotes

# 1. Importe o módulo statistics e crie uma lista com 14 elementos em ordem crescente
import statistics

dados = [10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36]

# 2. Calcule a média e a mediana dos valores usando o módulo completo
media1 = statistics.mean(dados)
mediana1 = statistics.median(dados)
print("Usando import statistics:")
print("Média:", media1)
print("Mediana:", mediana1)

# 3. Use um alias para o módulo statistics
import statistics as st

media2 = st.mean(dados)
mediana2 = st.median(dados)
print("\nUsando import statistics as st:")
print("Média:", media2)
print("Mediana:", mediana2)

# 4. Importe apenas as funções mean e median
from statistics import mean, median

media3 = mean(dados)
mediana3 = median(dados)
print("\nUsando from statistics import mean, median:")
print("Média:", media3)
print("Mediana:", mediana3)

# 5. Importe todas as funções do módulo statistics
from statistics import *

media4 = mean(dados)
mediana4 = median(dados)
print("\nUsando from statistics import *:")
print("Média:", media4)
print("Mediana:", mediana4)
