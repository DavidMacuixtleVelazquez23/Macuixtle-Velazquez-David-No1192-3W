print("\nDavid Macuixtle Velazquez\n")
#Aqui te pide que escribas un numero
n = int(input("escribe un numero: "))
#A coninuacion se define la funcio ya con el numero escrito previamente
def fact_number(n):
    #una secuancia if 
    if n == 0:
        return 1
    else:
        return n * fact_number(n - 1)

print("la factorial es",fact_number(n))

![image](https://github.com/user-attachments/assets/507aea22-e03a-4335-afa8-1e429269c720)
