print("David Macuixtle Velazquez")
#Aqui se define una funcion
def longitud_letras(palabra):
    #esto ayudara a que se pueda medir la longitud
    palabras = palabra.strip().split()
    if palabras:
        return len(palabras[-1])
    return 0
#aqui se pide que escribas una palabra
palabra = input("Esribe una palabra: ")

longitud = longitud_letras(palabra)
#aqui se impurme la longitud
print(f"la longitud es de:{longitud}")
![image](https://github.com/user-attachments/assets/4bc81f8e-209f-486e-bc76-63b99a8387f1)
