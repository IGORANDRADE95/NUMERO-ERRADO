# NUMERO-ERRADO
Retorna erro se o número digitado não esteja nos parâmetros

num1 = int(input("Digite um valor entre 0 e 10: "))
while num1 < 0 or num1 > 10:
  print("Valor inválido!")
  num1 = int(input("Errado! Digite um valor entre 0 e 10: "))
