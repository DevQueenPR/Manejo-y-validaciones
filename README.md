# Manejo y Validaciones con Flask-WTF

**Github:** [Manejo-y-validaciones](https://github.com/DevQueenPR/Manejo-y-validaciones)

## Descripción

Este proyecto implementa un formulario de registro utilizando **Flask** y **Flask-WTF**, con validaciones personalizadas en los campos más comunes: nombre, correo y contraseña. Es parte de la práctica de la Lección 2 del Módulo 2 del curso de desarrollo con Flask.
Se utilizó Python, Flask, Flask, WTF, WTF forms, email-validator. 
---

## Validaciones Implementadas

El formulario contiene las siguientes validaciones:

- **Nombre**
  - Obligatorio
  - Mínimo 3 caracteres

- **Correo**
  - Obligatorio
  - Formato de correo válido

- **Contraseña**
  - Obligatoria
  - Mínimo 6 caracteres
  - Debe coincidir con el campo "Confirmar Contraseña"

---

## Pantallas de Validación

### Validación de largo del nombre  
Muestra un mensaje si el nombre tiene menos de 3 caracteres.

![image](https://github.com/user-attachments/assets/e6d776f6-58b9-4d8f-93c9-3c091bf050a4)

###  Nombre vacío  
Muestra un error si el nombre no se completa.

![image](https://github.com/user-attachments/assets/22475881-a7f5-434d-89aa-fa5847bbb28e)

### Correo inválido  
Muestra un mensaje de error si el formato del correo no es válido.

![image](https://github.com/user-attachments/assets/8f91a1db-bb9c-440f-8aa4-1f3a23d3066f)


###  Correo vacío  
Muestra un error si no se introduce ningún correo.

![image](https://github.com/user-attachments/assets/3e62c845-4136-40b6-bbcc-99ebd2ee8556)


###  Contraseña corta  
Muestra un mensaje si la contraseña es menor de 6 caracteres.

![image](https://github.com/user-attachments/assets/deb24e9d-dc63-4eae-92e9-3f3e4581c8d6)


###  Contraseñas distintas  
Muestra un mensaje si las contraseñas no coinciden.

![image](https://github.com/user-attachments/assets/4f61c3df-ea71-40f5-899f-dfd303639b22)


###  Registro exitoso  
Se muestra un mensaje de confirmación cuando el formulario es válido.

![image](https://github.com/user-attachments/assets/8290750a-e77f-4a97-8dd6-74a746abd544)



