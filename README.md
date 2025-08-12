# 🎲 Jogo de Adivinhação em Python

Este projeto é um simples jogo de adivinhação onde o computador escolhe um número aleatório entre 0 e 5, e o jogador tenta adivinhar.

## Código

```python
from random import randint
from time import sleep

# Computador escolhe um número aleatório
computador = randint(0, 5)

print("- -" * 20)
print("Vou pensar em um número entre 0 e 5. Tente adivinhar!")
print("- -" * 20)

# Jogador faz sua escolha
jogador = int(input("Em que número eu pensei? "))

print("PROCESSANDO...")
sleep(3)

# Resultado
if jogador == computador:
    print("Parabéns, você venceu!!!")
else:
    print(f"Errou! Eu pensei no número {computador}... eu venci!!")
