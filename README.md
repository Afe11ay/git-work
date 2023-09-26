## Paso 4: Crear un Fork
- En esta parte realizaremos un fork del repositorio del **User 1**.
IMAGEN_1
IMAGEN_1

## Paso 5: Clonar el Fork
- Ahora, en esta parte se realizara un clon del fork ya previamente realizado en el ***PASO 5***.
IMAGEN_2

## Paso 7: Crear y Modificar una Rama

- **User2** creará una nueva rama llamada `"custom-text"`.
  IMAGEN_3
- Modificará el fichero `index.html` personalizándolo para una supuesta startup.
  IMAGEN_3

## Paso 8: Enviar un Pull Request (PR)

- **User2** enviará un PR a **User1** desde GitHub.

1. Hacer cambios en tu rama local.

2. Hacer un commit de tus cambios.

   ```bash
   git add <archivos_modificados>
   git commit -m "Mensaje de commit"
   git push origin custom-text
   IMAGEN_4
   
   
## Paso 10: Incorporar Cambios de la Rama Principal

- **User2** deberá incorporar los cambios de la rama principal de **User1** en su propia rama principal.

1. Cambiar a la rama principal local.

   ```bash
   git pull (url ssh) upstream
IMAGEN_5

### Paso 13: Crear una Nueva Rama y Modificar el Archivo

- **User2** creará una nueva rama llamada `"cool-colors"`
-  Cambiará la línea 10 de `cover.css` a ``"color: darkgreen"``.

### Paso 14: Enviar un Pull Request (PR)

- **User2** enviará un Pull Request (PR) a **User1** para proponer los cambios realizados en la rama ``"cool-colors"``.
  IMAGEN_7
