# Dio-Ciencia_de_dados2.py

valores = input().split()

# Converte cada parte da entrada para um número inteiro
info = [int(valor) for valor in valores]

# Calcula a média
resultado = info[0] / info[1]

# Exibe o resultado formatado com duas casas decimais
print(f'{resultado:.2f}')
