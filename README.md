# prac_3_2do_parcial_1182_3w
Edgar Gael Garcia Camacho 3-W

print(" ")

print("Edgar gael garcia camacho1182:prac_3")

print(" ")

# 1- Guardar en una variable el diccionario {'Euro':'€', 'Dollar':'$', 'Yen':'¥'}, El usuario debe meter una divisa y debe mostrar el símbolo o un mensaje 

de que la divisa no está en el diccionario.

#El signo de los tipos de moneda guardados en un diccionario.

diccionario={

  "€" : "Euro",
  
  "$" : "Dollar",
  
  "¥":  "Yen",

}

#Te pide ingresar una divisa para saber si es valida o no

lo=str(input("Ingresa una divisa :"))

if lo == "$" :

  print(" ")

  print("Es Divisa valida")
  
  print(" ")

elif lo== "€":

  print(" ")
  
  print("Es una divisa valida")
  
  print(" ")

elif lo == "¥":

  print(" ")
  
  print("Es una divisa valida")
  
  print(" ")

else :

  print(" ")
  
  print("No es una divisa valida")
  
  print(" ")

  ![image](https://github.com/user-attachments/assets/8b66dcee-6829-492f-ba57-3f54481953a2)

![image](https://github.com/user-attachments/assets/96544850-c36a-4997-bb22-78c6b990198e) ![image](https://github.com/user-attachments/assets/177565bc-517e-4d33-a63c-9f5e11624951)


# 2- Preguntar al usuario nombre, edad, dirección y teléfono y lo guarde en un diccionario.   

#Te pide ingresar varios datos.

Nom = str(input("Ingresa tu nombre :"))

print(" ")

Edad =int(input("Ingresa tu edad :"))

print(" ")

Direc= str (input("Ingresa tu direccion : "))

print(" ")

Num = int(input("Ingresa tu numero telefonico :"))

print(" ")

#Se guardan los datos agregados en un diccionario.

D={

  "Nombre" : [Nom], 
  
  "Edad"  : [Edad],
  
  "Direccion" :  [Direc] ,
  
  "Numero telefonico" : [Num],

}

#Se imprime un mensaje con los datos agregados y guardados en el diccionario.

print("Tu nombre es :" ,D ["Nombre"])

print(" ")

print("Tu edada es :",D["Edad"],"años")

print(" ")

print("Tu direccion es :",D["Direccion"])

print(" ")

print("Tu numero telefonico es :", D ["Numero telefonico"])

print(" ")

![image](https://github.com/user-attachments/assets/eb1e5758-8cd6-4a09-88ec-2601b4756c02)

![image](https://github.com/user-attachments/assets/4de51571-c2c2-4c29-9475-bb3214c4b4bb)


# 3- Guardar en un diccionario precios de las frutas en una matriz, luego preguntar al usuario por fruta. 

precios_frutas = {

  'manzana': 2.5,
  
  'banana': 1.2,

  'naranja': 3.0,
  
  'fresa': 4.0,
  
  'uva': 5.0

}


# Preguntar al usuario por la fruta y la cantidad de kilos

fruta = input("Ingresa el nombre de la fruta: ").lower()

print(" ")

kilos = float(input("Ingresa la cantidad de kilos: "))

print(" ")

# Verificar si la fruta está en el diccionario

if fruta in precios_frutas:

  precio_kilo = precios_frutas[fruta]
  
  total_precio = precio_kilo * kilos
  
  print(" ")
  
  print("El precio de", kilos ,"kilos de ",fruta, "es: $",total_precio)

  print(" ")

else:

  print(" ")
  
  print("La fruta", fruta, "no está en el diccionario.")
    print(" ")
    
![image](https://github.com/user-attachments/assets/352ae11e-a109-43fd-a6da-67b04e8594c3)

![image](https://github.com/user-attachments/assets/a3a6bd5b-943e-4b60-b32f-b0168c2447e9)

