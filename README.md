## Laboratorio No. 1

  

   

Presentado por:   

# Juan Esteban Ortiz Pastrana 

Vive en Ciudad Montes
Edad 22

Hobbies:

Entrenar
Jugar videojuegos

##Cosas que no me gustan en orden:

-La yuca
-La auyama
# Título del Proyecto

Descripción breve del proyecto.

## Lista de Elementos

- Elemento 1
- Elemento 2
- Elemento 3

## Otra Sección

...

##Cursando:

-CVDS
-SPTI
-FDGP
-SIML
-MATD

Link:

https://www.youtube.com/watch?v=dQw4w9WgXcQ

Fragmento de codigo

import socket

# Definir la contraseña actual
contrasena_actual = "contraseña_actual"

# Establecer la conexión al servidor en localhost y puerto 30000
with socket.socket(socket.AF_INET, socket.SOCK_STREAM) as s:
    s.connect(('localhost', 30000))
    
    # Enviar la contraseña actual al servidor
    s.sendall(contrasena_actual.encode())
    
    # Recibir la respuesta del servidor
    data = s.recv(1024)
    
    # Imprimir la respuesta del servidor
    print(data.decode())
 
Escuela Colombiana de Ingeniería Julio Garavito   

Grupo 1   


![Captura de pantalla 2024-02-07 180405](https://github.com/juaneortiz1/Lab01CVDS-/assets/97971732/412dd4c4-5c33-4c7d-916b-56d05b8d8b99)

![Captura de pantalla 2024-02-07 180431](https://github.com/juaneortiz1/Lab01CVDS-/assets/97971732/45ce8020-ec56-4b86-af5e-0cd44ce4e02f)
