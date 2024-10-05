print ("Cristian David Salas De La O 3-W") #esta linea muestra el nombre del programador
numeros_ganadores = [] #esta linea define el numeros de ganadores

cantidad = int(input("Cuantos numeros ganadores deseas ingresar? ")) #esta linea define la cantidad de numeros ganadores

for i in range(cantidad): #esta linea define la cantidad
    while True: #esta linea ejecuta algo mientras la linea sea cierta
        try:  #esta linea es el numero de setencias 
            numero = int(input(f"Ingrese el numero ganador #{i + 1}: ")) #esta linea solicita saber cuantos numeros ganadores hay 
            if numero < 0: #esta linea definen como saber si el numero es negativo 
                print("Por favor ingrese un numero positivo.") #esta linea muestra un aviso si el numero es negativo 
            else: #esta linea muestra que hacer si no se cumple con ninguna peticion 
                numeros_ganadores.append(numero) #esta linea define como hacer el error 
                break #esta linea concluye la ejecucion 
        except ValueError: #esta linea define que hacer si el numero ingresado no es un numero entero
            print("Entrada invalida Por favor ingrese un numero entero.") #esta linea avisa que el numero ingresado no es un entero  
 
numeros_ganadores.sort() #esta linea define los numeros ganadores 

print("Numeros ganadores de la loteria en orden de menor a mayor:") #esta linea avisa que mostrara los numeros de la loteria 
print(numeros_ganadores) #esta linea muestra los numeros de la loteria 
![image](https://github.com/user-attachments/assets/c61f74fb-a606-4609-b045-ccd4687f5e49)
![image](https://github.com/user-attachments/assets/4c3cbb9e-092b-49bc-87d3-32be981b5e00)
