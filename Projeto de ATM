saldo = float(input("digite seu saldo: "))
print(f"seu saldo é {saldo}, quanto deseja retirar?")

while True:
  Retirada = float(input(""))
  if Retirada < 0:
    print("impossivel realizar esta transação")
  elif Retirada > saldo:
    print("transação negada")
  else:
    break

if Retirada >= 400:
  print("saque realizado")
  print("valor muito alto")
else:
  print("saque realizado")

print(f"saldo Restante {saldo - Retirada:,.2f} ")
