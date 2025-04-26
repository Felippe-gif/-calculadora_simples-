 -calculadora_simples-


 print ('\n\t\t ====== CALCULADORA SIMPLES ========= \n')

 while True :
      print(' 1 soma')
      print(' 2 menos')
     print(' 3 multiplicaçao')
      print(' 4 divisao')

  opçao = int(input('escolha a opcao (1/2/3/4):'))
     

  n1= int(input("digite um numero:"))
  n2 = int(input("digite um numero:"))
      
 if opcao == 1:
        resultado = n1 + n2
        print(f'O resultado da soma é: {resultado}')
    
  elif opcao == 2:
    resultado = n1 - n2
    print(f'O resultado da subtração é: {resultado}')
         elif opcao == 3:
         resultado = n1 * n2
        print(f'O resultado da multiplicação é: {resultado}')
elif opcao == 4:
# Verifica se o segundo número é zero para evitar divisão por zero
  if n2 == 0:
       print("Erro! Não é possível dividir por zero.")
      else:
           resultado = n1 / n2
            print(f'O resultado da divisão é: {resultado}')

