while True:
      try:
        n1= (int(input("digitalize el primer numero") ))
        n2= (int(input("digitalize el segundo numero") ))
        print(n1+n2)
        break
      except ValueError:
        print("El valor introducido no es un número. Intenta de nuevo")


