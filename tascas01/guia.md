# Guía de Uso de Bitwarden

**Autor:** David Ballesteros Antich  
**Curso:** 2B  
**Módulo:** Seguretat informàtica  
**Profesora:** Isabel Bosch  
**Fecha:** 21/10/2025  

---

## Índice
1. Instalación y Configuración Inicial
2. Generación de Contraseñas Seguras
3. Guardar y Usar Credenciales
4. Copias de Seguridad (Backup)
5. Pequeñas recomendaciones

---

## 1. Instalación y Configuración Inicial

1. Abrir la página oficial: https://bitwarden.com  
2. Seleccionar la versión adecuada: escritorio, móvil o extensión navegador.  
3. Descargar e instalar la aplicación.

<!-- En el PDF, primero se ve la búsqueda y luego la página de extensiones y la de Windows -->
<img src="img/imagen 1.png" alt="Búsqueda en Google del sitio oficial de Bitwarden">
<img src="img/imagen 2.png" alt="Página de extensiones del navegador de Bitwarden mostrando opciones como Chrome, Edge y Firefox">
<img src="img/imagen 3.png" alt="Página de descarga de Bitwarden para Windows con enlaces de instalación y logotipo de Windows">

4. Create una cuenta con una contraseña segura.  
( Recomendación: contraseña con 16 caracteres, mayúsculas, minúsculas, números y símbolos.)

<!-- Orden del PDF: instalador, pantalla de inicio para crear cuenta, formulario de creación, luego establecer contraseña segura -->
<img src="img/imagen 4.png" alt="Instalador de Bitwarden en proceso de descarga e instalación en Windows">
<img src="img/imagen 5.png" alt="Pantalla de inicio de Bitwarden con opción para crear una nueva cuenta">
<img src="img/imagen 6.png" alt="Formulario de creación de cuenta en Bitwarden con campos de correo electrónico y nombre">
<img src="img/imagen 7.png" alt="Formulario para establecer una contraseña maestra segura en Bitwarden">

Ara habilitamos autenticación de dos factores (2FA) para mejor proteccion de la cuenta.  
Y ponemos una de las tres opciones.

<!-- En el PDF aquí aparecen dos imágenes: menú de Cuenta y la página de Seguridad con 2FA -->
<img src="img/imagen 8.png" alt="Menú superior de Bitwarden mostrando opciones de cuenta y configuración">
<img src="img/imagen 9.png" alt="Página de seguridad de Bitwarden con opciones de inicio de sesión en dos pasos (2FA)">

---

## 2. Generación de Contraseñas Seguras

1. Abrir Bitwarden → Generador de contraseñas.  
Para crear una nueva contraseña hay que darle al boton +  
En este caso inicio de session  
Y ya te dejararia crear una contraseña y poner el nombre de usuario.

<!-- En el PDF: primero se ve el botón +, luego el menú de tipos, después el formulario del ítem y el generador -->
<img src="img/imagen 10.png" alt="Área principal de Bitwarden con el botón para añadir nuevo ítem">
<img src="img/imagen 13.png" alt="Menú para añadir nuevo ítem: inicio de sesión, tarjeta, identidad, nota o clave SSH">
<img src="img/imagen 12.png" alt="Formulario de creación de nuevo elemento con campos de usuario, contraseña y URI">
<img src="img/imagen 11.png" alt="Generador de contraseñas de Bitwarden con opciones de longitud, tipos de caracteres y mínimos">

Le damos a utilizar esta contraseña  
Le damos a guardar y se te guardaran los datos que has puesto anteriormente.

<!-- En el PDF después se ve el formulario ya completado -->
<img src="img/imagen 14.png" alt="Formulario completado con contraseña generada y sitio web añadido">

Esta es una prueba y la contraseña no es muy segura mi recomendación es usar una  
contraseña de 20 caracteres, incluir mayúsculas, minúsculas, números y símbolos para  
garantir una contraseña segura.  
Finalmente tendrias que copiar la contraseña generada y guardarla en la base de datos de  
Bitwarden para poder usarla.

---

## 3. Guardar y Usar Credenciales

### 3.1 Correo Electrónico

1. Haz clic en el botón + para crear un nuevo ítem.  
2. Selecciona el tipo: Inicio de sesión (Login).

<!-- En el PDF aquí vuelve a mostrarse el contexto de añadir ítem y luego el detalle de Gmail -->
<img src="img/imagen 10.png" alt="Área principal de Bitwarden con el botón para añadir nuevo ítem">
<img src="img/imagen 13.png" alt="Menú para añadir nuevo ítem: inicio de sesión, tarjeta, identidad, nota o clave SSH">

3. Completa los siguientes campos:  
- Nombre: escribe un nombre descriptivo, por ejemplo “gmail”.  
- Nombre de usuario: introduce tu dirección de correo, en mi caso  
(alu.david.ballesteros@mataro.epiaedu.cat).  
- Contraseña: pon la contraseña de tu gmail para poder iniciar sesión correctamente.  
- url : añade la dirección del servicio, en este caso: https://mail.google.com.  
Opcionalmente, agrega notas o asigna la credencial a una carpeta llamada “Correo”.  
Pulsa “Guardar”. Y la contraseña quedará almacenada de forma cifrada dentro del cofre de  
Bitwarden.

<img src="img/imagen 16.png" alt="Credencial de Gmail guardada mostrando usuario, contraseña y URL">

### 3.2 Aplicaciones o Servicios Web

1. En Bitwarden, volvemos a seleccionar “Nuevo ítem” y elige el tipo Login.  
2. Sigue los pasos y completa los siguientes campos:  
- Nombre: escribe el nombre de la aplicación o servicio web que quieres guardar la  
contraseña, por ejemplo: GitHub.  
- Usuario: introduce tu nombre de usuario de la aplicación o web.  
- Contraseña: pon la contraseña de tu cuenta para poder iniciar sesión correctamente.  
- URI: agrega la dirección web de inicio de sesión, en este caso:  
https://github.com/login.  
- Opcionalmente, agrega una nota para avisarte que por ejemplo esta contraseña es para  
github.  
- Haz clic en “Guardar”.

<img src="img/imagen 17.png" alt="Credencial de GitHub guardada mostrando usuario, contraseña y sitio">

### 3.3 Autocompletado en el Navegador

Requisitos previos:  
- Tener instalada la extensión de Bitwarden en el navegador (Chrome, Edge o Firefox).  
- Haber iniciado sesión con la misma cuenta que usas en la aplicación.

<!-- En el PDF primero se ve la extensión abierta y luego la página de Google con el autocompletado -->
<img src="img/imagen 15.png" alt="Extensión de Bitwarden abierta en el navegador mostrando elementos de la caja fuerte">

Pasos a seguir:  
1. Abre la página de inicio de sesión del servicio (por ejemplo  
https://mail.google.com).  
2. Haz clic en el icono de Bitwarden en la barra del navegador.  
3. Si la página coincide con la URI guardada, Bitwarden mostrará la credencial disponible.  
4. Selecciona la credencial y pulsa “Autocompletar” o el logo azul de escudo.  
5. Los campos de usuario y contraseña se rellenará automáticamente.  
6. Haz clic en “Iniciar sesión” para acceder.

<img src="img/imagen 18.png" alt="Página de inicio de sesión de Google con autocompletado sugerido por Bitwarden">

---

## 4. Copias de Seguridad (Backup)

1. Ir a Fitxer → Exportar caja fuerte  
2. Introducir contraseña maestra  
3. Guardar archivo cifrado

<!-- En el PDF se ve primero el menú para exportar y luego la confirmación y el guardado -->
<img src="img/imatge 21.png" alt="Menú Fitxer con la opción Exporta caixa forta">
<img src="img/imagen 22.png" alt="Cuadro de confirmación solicitando la contraseña maestra para exportar la caja fuerte">
<img src="img/imagen 23.png" alt="Diálogo del explorador de archivos para guardar la exportación de Bitwarden en formato JSON">

La mejor práctica es cifrar la copia de seguridad antes de guardarla, usando una contraseña  
fuerte o una herramienta como 7-Zip o VeraCrypt.  
Se recomienda guardar una copia en una memoria USB cifrada y conservarla en un lugar  
físico seguro (como una caja fuerte).  
Opcionalmente, puedes mantener una segunda copia en la nube, siempre que esté cifrada  
y protegida con autenticación en dos pasos (2FA).

---

## 5. Pequeñas recomendaciones

- Usa contraseñas largas y únicas (mejor 20+ caracteres).  
- Activa la autenticación en dos pasos (2FA) en Bitwarden y en tus servicios.  
- No compartas tu contraseña maestra.  
- Mantén el cofre sincronizado y bloqueado cuando no lo uses.  
- Realiza copias de seguridad periódicas y **cifradas** y guárdalas en un lugar seguro.



  [Tornar pàgina del projecte](../README.md)

