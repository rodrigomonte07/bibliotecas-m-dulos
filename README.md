# bibliotecas-m-dulos
import random

def lancar_dados():
    dado1 = random.choice([1, 2, 3, 4, 5, 6])
    dado2 = random.choice([1, 2, 3, 4, 5, 6])

    print(f"Dado 1 = {dado1} e Dado 2 = {dado2}")
    return dado1 + dado2


total = lancar_dados()

print(f"Soma dos dados é igual a {total}")
