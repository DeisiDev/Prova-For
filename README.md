numero1= int(input( ' Digite o primeiro número:'))
numero2= int(input( ' Digite o último número: '))

somar_pares= 0

tem_pares= False

for i in range(numero1, numero2 + 1):
    if i % 2 == 0:
        somar_pares += i
        tem_pares= True

if tem_pares:
         
         print( f" A soma dos números pares no intervalo é: {somar_pares}")
         
else:
        print(" Não há números pares!")
