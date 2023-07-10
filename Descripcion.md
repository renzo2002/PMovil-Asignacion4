# Descripción de aplicación de feedback
**Integrantes:**

* Sato Diaz, Andrés Kei - 20194786

* Villanueva, Renzo - 2019

*  Duarte Cabrejos, Juan Pablo - 20190651

* Vasquéz, Luciana - 2019

**Profesor:**
José Jesús Valdivia Caballero

## Explicación del entorno de desarrollo
Para generar el entorno de desarrollo se recomienda la instalación previa de las siguientes herramientas:

1. [Git](https://git-scm.com/downloads): Sistema de control de versiones.
2. [VSCode](https://code.visualstudio.com/download): Editor de texto y auxiliar para otros aspectos de programación que puedan ser necesarios.
3. [Xcode](xcodereleases), [Android Studio](https://developer.android.com/studio):   Simular el aplicativo en las distintas plataformas respectivas
4. [Postman](https://www.postman.com/downloads/): Controlar las peticiones 

Para esta siguiente sección se desea explicar la instalación del flutter SDK y el lenguaje de programación que se emplea, Dart. 

### __Instalación de Flutter:__

### __Instalación en macOS__

Una vez que se ha ingresado al sitio web de [Flutter](https://flutter.dev/?gclid=Cj0KCQjwtamlBhD3ARIsAARoaEwton1AgvhAKwa5FQS5hw6uB8SWkMsnZ_RfwgQJFs3v1ilvCsuAdOwaAuosEALw_wcB&gclsrc=aw.ds) se debe ir al botón superior y apretar "Get started"
![alt](/Imagenes/1.png)
Aquí encontrarás el apartado de instalación
![alt](/Imagenes/2.png)
Se apreta el botón de MacOs y posteriormente se obtendrá las descargas respectivas en relación a este sistema operativo. 
![alt](/Imagenes/3.png)
Dependiendo del chip de procesador se puede darle click a botón de descarga. 
![alt](/Imagenes/4.png)
Descomprimimos el zip que se descarga y lo colocamos en el path /Users/tusuario/development/. Si no existe esta carpeta, se puede crear. 
![alt](/Imagenes/5.png)
Colocamos los siguientes comando en el terminal.
![alt](/Imagenes/6.png)
Modificamos el zshrc con los siguientes comandos, para editar apretamos i, para salir esc. 
![alt](/Imagenes/7.png)
Con los cambios propuestos finalizamos con esc, :wq para guardar y salir
![alt](/Imagenes/8.png)
En otra terminal ponemos "flutter --version" para confirmar que se ha instalado.
![alt](/Imagenes/9.png)

### __Configuración en VSCode__

![alt](/Imagenes/vs1.png)
![alt](/Imagenes/vs2.png)

## Diagrama de despligue

![alt](/Imagenes/deploy.png)

## Requerimientos no funcionales
__RNF1: Seguridad:__
* La aplicación debe garantizar la seguridad de los datos del usuario, como el almacenamiento seguro de contraseñas al hacer uso de la autentificación de Firebase.

__RNF2: Rendimiento:__
* La aplicación debe ser rápida y responder de manera eficiente a las interacciones del usuario.

__RNF3: Usabilidad:__
* La interfaz de usuario debe ser intuitiva y fácil de usar, brindando una experiencia agradable al usuario. 

__RNF4: Compatibilidad:__
* La aplicación debe ser compatible con diferentes teléfonos móviles y tabletas con diferentes sistemas operativos iOS, Android.

## Requerimientos funcionales
__RF1: Crear un usuario:__
* data1

__RF2: Cerrar sesión:__
* data1

__RF3: Iniciar sesión__
* data1

__RF4: Calificar atención:__
* data1

__RF5: Ingresar un comentario:__
* data1

__RF6: Ver mi perfil:__
* data1

__RF7: Ver actividades:__
* data1

## Diagrama de Caso de Uso

![alt](/Imagenes/useCase.png)

## Descripción de Caso de Uso y Mockups
__Caso de uso: Creación de un usuario__
* El usuario accede a la aplicación y desea registrarse.
![alt](/Imagenes/m2.png)

__Caso de uso: Inicio de sesión__
* El usuario ya posee una cuenta registrada y desea usar sus credenciales para acceder.
![alt](/Imagenes/m1.png)

__Caso de uso: Visualización de actividades__
* El usuario busca la actividad que desee calificar en una lista.
![alt](/Imagenes/m3.png)

__Caso de uso: Calificación de atención__
* El usuario desea calificar el nivel de satisfacción en una escala de Likert.
![alt](/Imagenes/m4.png)

__Caso de uso: Ingreso de comentario__
* El usuario en caso desee, puede añadir un comentario para complentar su calificación.
![alt](/Imagenes/m5.png)

__Caso de uso: Visualización de perfil__
* El usuario puede visualizar su perfil con sus respectivas credenciales.
![alt](/Imagenes/m6.png)

__Caso de uso: Cerrar sesión__
* El usuario si desea puede cerrar su sesión para ya no calificar.
![alt](/Imagenes/m7.png)

__Listado de mockups__
![alt](/Imagenes/mock.png)
