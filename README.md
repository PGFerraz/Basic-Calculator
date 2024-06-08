# parte 4 aprendendo a programar com o canal freeCodeCamp.org

# codigo 4 - Criando uma calculadora básica

num1 = float(input("Digite o Primeiro Número: "))  # um input float será guardado na variável
num2 = float(input("Digite o Segundo Número: "))  # outro input float será guardado na variável
oper = input("Escolha a operação (SOMA = a, SUBTRAÇÃO = b, MULTIPLICAÇÃO = c, DIVISÃO = d) ")  # input da operação
if oper == 'a':  # se a operação escolhida for soma, equevalente a letra 'a'
    resultado = num1 + num2  # somando as duas variáveis
    print("a soma de " + str(num1) + " por " + str(num2) + " é igual a: " + str(resultado))  # imprimindo o resultado
elif oper == 'b':  # se a operação escolhida for subtração, equevalente a letra 'b'
    resultado = num1 - num2  # subtraindo as duas variáveis
    print("A subtrção de " + str(num1) + " por " + str(num2) + " é igual a: " + str(resultado))  # print() o resultado
elif oper == 'c':  # se a operação escolhida for multiplicação, equevalente a letra 'c'
    resultado = num1 * num2
    print("A multiplicação de " + str(num1) + " por " + str(num2) + " é igual a: " + str(resultado))  # resultado
elif oper == 'd':  # se a operação escolhida for divisão, equevalente a letra 'd'
    resultado = num1 / num2
    print("A divisão de " + str(num1) + " por " + str(num2) + " é igual a: " + str(resultado))  # resultado
else:  # senão
    print("input errado!!")  # caso o input fornecido não esteja dentro das operações disponíveis
