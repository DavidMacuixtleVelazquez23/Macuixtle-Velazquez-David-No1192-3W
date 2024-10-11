print("\nDavid Macuixtle Velazquez\n")
#aqui se define una funcion 
def myFunction(letra) :
    a = 'aeiouAEIOU'
    #esto es para saber si una vocal se encuentra
    return letra in a 

#te pide escribir una letra
letra = input("Escribe una letra ")
#funcion if que vera si tu letra es vocal o no
if myFunction(letra) :
  print("YES!")
else:
  print("NO!")

  ![image](https://github.com/user-attachments/assets/ba30f929-be99-4b76-b1a9-f18668ca73e5)
