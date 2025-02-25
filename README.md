iniciar = input('Deseja iniciar a calculadora? (1-SIM, 2-NĀO):')
if iniciar == '1':
  print('Inicie suas operações e cálculos matemáticos')
  escolha_n1 = float (input("Escreva um número:"))
  escolha_n2 = float (input('Escreva outro número:'))
else:
  if iniciar == '2':
    print('Calculadora não iniciada')
opção_1 = input('''Qual operação aritmética deseja realizar? (1-soma ,
                                                     2-multiplicação ,
                                                     3-divisão ,
                                                     4-divisão inteira ,
                                                     5-subtração ,
                                                     6-resto do divisão ,
                                                     7-potenciação )''')
if opção_1 == '1':
  print('O resultado da soma foi de:', escolha_n1 + escolha_n2)
elif opção_1 == '2':
  print('O resultado da multiplicação foi de:', escolhan_1 * escolha_n2)
elif opção_1 == '3':
  print('O resultado da divisão foi de:', escolha_n1 / escolha_n2)
elif opção_1 == '4':
  print('O resultado da divisão inteira foi de: ', escolha_n1 // escolha_n2)
elif opção_1 == '5':
  print('O resultado da subtração foi de:', escolha_n1 - escolha_n2)
elif opção_1 == '6':
  print('O resultado do resto da divisão foi de:', escolha_n1 % escolha_n2)
elif opção_1 == '7':
  print('O resultado da potenciação foi de:', escolha_n1 ** escolha_n2)



opção_2 = input(''' Qual operação relacional deseja realizar? (1-menor
                                                               2-maior
                                                               3-igual
                                                               4-diferente)''')
if opção_2 == '1':
  print('O primeiro número é menor? : ', escolha_n1 < escolha_n2)
elif opção_2 == '2':
  print('O primeiro número é maior? : ', escolha_n1 > escolha_n2)
elif opção_2 == '3':
  print('Os números são iguais? : ', escolha_n1 == escolha_n2)
elif opção_2 == '4':
  print('Os números são diferentes? : ', escolha_n1 != escolha_n2)
else:
  print('Escreva uma opção válida')

print('Obrigado por utilizar a calculadora!')


