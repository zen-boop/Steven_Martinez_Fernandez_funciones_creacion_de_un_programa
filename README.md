print("coloca 2 numeros para sumarlos,restarlos,multiplicarlos y dividirlos")
# Función para sumar dos números
def s(a,b):#def de s(a,b)
    return a+b#realiza la operacion y devuelve
# Función para restar dos números
def r(a,b):#def de r(a,b)
    return a-b#realiza la operacion y devuelve
# Función para multiplicar dos números
def m(a,b):#def de m(a,b
    return a*b#realiza la operacion y devuelve
# Función para dividir dos números
def d(a,b):#def de d(a,b)
    if b!=0:#si "b" es diferente de 0 se realiza la operacion
        return a/b#realiza la operacion y devuelve
    else:#si no imprime un error
        return "Error: División por cero"
# Función principal
def main():#def de main
    n1=float(input("Ingresa el primer número: "));print("")#separa define como float hace posible modificarlo y indica cuando colocar el numero
    n2=float(input("Ingresa el segundo número: "));print("")#separa define como float hace posible modificarlo y indica cuando colocar el numero
    print(f"Suma: {s(n1,n2)}")#imprime el resultado y gracias a la f hace operaciones de numeros adentro de los "{}"
    print(f"Resta: {r(n1,n2)}")#imprime el resultado y gracias a la f hace operaciones de numeros adentro de los "{}"
    print(f"Multiplicación:{m(n1,n2)}")#imprime el resultado y gracias a la f hace operaciones de numeros adentro de los "{}"
    print(f"División: {d(n1,n2)}")#imprime el resultado y gracias a la f hace operaciones de numeros adentro de los "{}"
# Ejecutar la función principal
if __name__ == "__main__":#si el "__name__" es igual a "__main__" se realiza lo de arriba
    main()#define el main
    ![image](https://github.com/user-attachments/assets/2c079943-02af-40d0-9442-5d8a3347705e)
