# Juego_ionioc
## Funcionalidad

El juego "Adivinar número", consiste en que nosotros acertemos un número aleatorio del 1 al 10, ingresando otro número desde un input.

**Pasos para la implemantación:**
  - Creamos un nuevo proyecto en blanco: ionic start game 
  - Seleccionamos que sea de tipo **angular**
  - Para esta aplicación no instalamos alguna librería adicional.

**Versiones usadas:**
  - node: v19.1.0
  - npm: 8.19.3
  - ng: angular/cli 15.0.1
  - cordova: 11.0.0
  - ionic: 6.20.4
  
**Vista del homepage.html**

![image](https://user-images.githubusercontent.com/118954638/209368429-aac415d9-0102-4bc9-af6b-3326c9a0e0a4.png)

 ### Código homepage.html
 
![image](https://user-images.githubusercontent.com/118954638/209374180-11e1a367-9665-44d3-a60f-fc787480c855.png)

![image](https://user-images.githubusercontent.com/118954638/209374205-fb5f35fe-245e-4ae4-8bed-715d22d53f21.png)

### Controlador de la página home.page.ts

Tenemos las funciones que generan el número aleatorio que deseamos advinar. La función que nos hira diciendo si el número que ingresamos es mayor o menor al que estamos buscando. La función que nos ayudará a reiniciar las variables.

![image](https://user-images.githubusercontent.com/118954638/209374957-4cf73a97-4760-4a0b-bef0-6038b5ef27c0.png)

![image](https://user-images.githubusercontent.com/118954638/209374998-5643abea-3298-4033-8cdf-392444ad4701.png)

### Pasos para generar la APK:
 -  Dentro del directorio de la aplicación abrimos una terminal.
 - Ingresamos los comandos: 
    - ionic build
    - ionic cap add android
    - ionic build
    
Vemos que se nos generaron 2 carpetas: android y www

![image](https://user-images.githubusercontent.com/118954638/209376246-a378d2de-2389-4f0f-9f32-ae54fcc0e4b1.png)

En android studio, abrimos la carpeta llamada **andoid**

![image](https://user-images.githubusercontent.com/118954638/209376334-e4a70a6d-4c21-481e-851c-9db9017224af.png)

Generamos la APK

![image](https://user-images.githubusercontent.com/118954638/209376727-47c491bd-8509-4a56-9565-946f27571d37.png)

Una vez que termine de ejecutarse nos vamos al directorio C:\Users\Administrador\Desktop\JUEGO_IONIC\game\android\app\build\outputs\apk\debug

![image](https://user-images.githubusercontent.com/118954638/209378449-7a5def9c-9553-41dc-b23e-b56d0f1260ec.png)

Tenemos claramente la APK generada.


referencias: https://reviblog.net/2019/11/16/tutorial-de-ionic-4-5mini-juego-de-acertar-numeros-actualizado/

En caso de descargar este repositorio, para iniciar la aplicación debemos ejecutar el comando **npm i** dentro del proyecto. Esta descargará todas las librerias que necesitemos.
