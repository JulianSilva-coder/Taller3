# Proyecto Final: Primera Entrega


## 1.	Usuarios que debe soportar la aplicación

Entidades veterinarias, funcionarios del gobierno, propietarios y ciudadanos.

## 2.	Funcionalidades que debe cumplir la aplicación web

-	La aplicación debe permitir, para propietarios y médicos veterinarios, el ingreso y registro de los datos de la mascota y de los propietarios. Cada mascota posee la siguiente información: especie, sexo, raza, tamaño, fotografía, ubicación o dirección y microchip. Cada propietario posee la siguiente información: nombre, apellido, dirección, celular.
-	La aplicación debe permitir el seguimiento de las actividades asociadas a la mascota como puede ser: esterilización, vacunación, pérdida, robo, abandono, entre otros.
-	La aplicación debe permitir la modificación de la información de cualquier mascota ya registrada.
-	La aplicación debe ofrecer un chat de soporte donde se registre un caso relacionado con las actividades de las mascotas.
-	La aplicación debe ofrecer para funcionarios de gobierno una visualización de los casos de las mascotas y de sus datos y a su vez consultar los eventos de una mascota gracias a su microchip
 ## 3. Diagramas
![](https://i.imgur.com/gtCvFey.jpg)
![](https://i.imgur.com/2JLEEo8.jpg)
![](https://i.imgur.com/w6w7duG.jpg)
![](https://i.imgur.com/SWGUaAP.jpg)
 ## 4. Mockups/Prototipos
 ### 4.1 Pantalla de Registro de Mascotas
 #### 4.1.1 Casillas del Registro de Mascotas cuando los datos extra no se han actualizado
![Registro sin actualizaciones](https://i.imgur.com/1kLCy6A.png)
 #### 4.1.2 Casillas del Registro de Mascotas cuando los datos extra se han actualizado y, por ende, el formulario está completo
 Se ejemplifica en algunas casillas, en otras no.
 
 ![](https://i.imgur.com/xpRTSoo.png)
 ### 4.2 Pop-Up de Adición en la Pantalla de Registro de Mascotas
 #### 4.2.1 Adición de los seis campos iniciales del .csv
 Parte 1 de la adición de un animal nuevo.
 
![enter image description here](https://i.imgur.com/8fMPbtF.png)
 #### 4.2.2 Adición de los campos extra cuando faltan datos por registrar
  Esta pantalla puede apreciarse tanto cuando faltan 6 datos de los originales (Microchip, especie, sexo, tamaño, peligro potencial y vecindario) como cuando faltan datos extra (Imágen, dirección, dueño y raza), pues el sitio permite al usuario navegar entre las dos partes que conforman al formulario de adición de animal (Datos Originales y Extras) aunque no se haya completado, pero no permitirá la carga de los datos hasta que no haya rellanado todos los campos.
  
![Pop-Up de Adición en Extras cuando faltan datos](https://i.imgur.com/wX9M8qw.png)
 #### 4.2.3 Adición de los campos extra cuando el formulario ha sido llenado
![Pop-Up de Adición en Extras cuando faltan datos](https://i.imgur.com/BhSQC4j.png)
 ### 4.3 Pop-Up de Actualización en la Pantalla de Registro de Mascotas
![Pop-Up de Actualización](https://i.imgur.com/M1b72MU.png)
### 4.4 Chat de la sección de atención
#### 4.4.1 Aspecto cuando no hay contacto con un agente
Solo se muestra al chatbot sin nada más cuando, por decirlo así, con el usuario no se está realizando seguimiento de ningún reporte.

![Chatbot activo preguntando sobre el caso](https://i.imgur.com/9Q2e5RR.png)

Dependiendo de la información requerida por el Chatbot, se activará un campo de texto para redactar respuestas o se mostrarán botones que permitan responder sin manipular el teclado.

![enter image description here](https://i.imgur.com/ZIjuHwo.png)
### 4.4.2 Chat de la sección de atención cuando hay contacto con un agente
Cuando ya se está realizando una consulta al agente, el chat cambia su aspecto para parecerse a una aplicación de mensajería instantánea.

![enter image description here](https://i.imgur.com/7iXc19W.png)
### 4.5 Chat de la sección de atención desde el punto de vista de un agente

El agente tendría acceso a todos los chats con los mensajes que el usuario tuvo con el chatbot como si fueran mensajes previos y a datos básicos como una identificación del caso y el nombre de quien hizo la denuncia.

![enter image description here](https://i.imgur.com/u8Gt4gl.png)
### 4.6 Sección de atención desde el punto de vista de un funcionario
El funcionario podría observar los datos de las denuncias y los chats, sin ser capaz de intervenir en las conversaciones.
![enter image description here](https://i.imgur.com/3qmJTaT.png)
