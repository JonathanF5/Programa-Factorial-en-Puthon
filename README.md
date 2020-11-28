# Programa-Factorial-en-Puthon
#Codigo usando la version 3.8 de Python 

def factorial(n):
    if n == 0 or n== 1:
        resultado =1
        
    elif n>1:
        
        resultado = n* factorial(n-1)
        print('FACTORIAL DE ',n,' ! es :',resultado)
        
    return resultado
    
n =int(input("Ingrese por favor un numero :"))

fact = factorial(n)
