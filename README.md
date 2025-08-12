# Novo-reposit-rio-
from random import randint
from time import sleep
 
 # Pedidindo para o computador escolher os números de 0 a 5

computador = randint(0,5)
print("-*-" * 20)
print("Vou pensar em um número entre 0 e 5, tente advinhar: ")
print("-*-" * 20)

# Agora o usuário irá informar o seu número 

jogador = int(input(("Em que número eu pensei? ")))
print("PROCESSANDO ... ")
sleep(3)

# Resultado 

if jogador == computador: 
    print("Parabéns, você venceu!!!")
else: 
    print(f"Errou haha eu pensei no número {computador}... eu venci!!")