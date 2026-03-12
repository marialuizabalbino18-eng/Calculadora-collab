# Calculadora-collab
print("Calculadora simples")

num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

print("Escolha a operação:")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

op = input("Digite o número da operação: ")

if op == "1":
    print("Resultado:", num1 + num2)

elif op == "2":
    print("Resultado:", num1 - num2)

elif op == "3":
    print("Resultado:", num1 * num2)

elif op == "4":
    print("Resultado:", num1 / num2)

else:
    print("Operação inválida")
