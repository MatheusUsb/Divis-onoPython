# DivisaonoPython
# Script que realiza divisões

def divisao(dividendo, divisor):
    try:
        resultado = dividendo / divisor
        return resultado
    except ZeroDivisionError:
        return "Erro: divisão por zero não é permitida"

# Exemplo de uso
num1 = float(input("Digite o dividendo: "))
num2 = float(input("Digite o divisor: "))

resultado_divisao = divisao(num1, num2)
print("Resultado da divisão:", resultado_divisao)
