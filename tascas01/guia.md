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

1. Abrir la página oficial: [https://bitwarden.com](https://bitwarden.com)  
2. Seleccionar la versión adecuada: escritorio, móvil o extensión navegador.  
3. Descargar e instalar la aplicación.  

<img src="img/imagen 1.png" alt="Búsqueda en Google del sitio oficial de Bitwarden">  
<img src="img/imagen 2.png" alt="Página de extensiones del navegador de Bitwarden mostrando opciones como Chrome, Edge y Firefox">  
<img src="img/imagen 3.png" alt="Página de descarga de Bitwarden para Windows con enlaces de instalación y logotipo de Windows">  
  
(Recomendación: contraseña con 16 caracteres, mayúsculas, minúsculas, números y símbolos.)

<img src="img/imagen 4.png" alt="Instalador de Bitwarden en proceso de descarga e instalación en Windows">  

4. Crear una cuenta con una contraseña segura.
   
(Recomendación: contraseña con 16 caracteres, mayúsculas, minúsculas, números y símbolos.)
<img src="img/imagen 5.png" alt="Pantalla de inicio de Bitwarden con opción para crear una nueva cuenta">  
<img src="img/imagen 6.png" alt="Formulario de creación de cuenta en Bitwarden con campos de correo electrónico y nombre">  

Ahora habilitamos autenticación de dos factores (2FA) para mejor protección de la cuenta.  
Y ponemos una de las tres opciones.

<img src="img/imagen 7.png" alt="Formulario para establecer una contraseña maestra segura en Bitwarden">  
<img src="img/imagen 8.png" alt="Menú superior de Bitwarden mostrando opciones de cuenta y configuración">  
<img src="img/imagen 9.png" alt="Página de seguridad de Bitwarden mostrando opciones de inicio de sesión en dos pasos y proveedores de autenticación">  

---

## 2. Generación de Contraseñas Seguras  

1. Abrir Bitwarden → Generador de contraseñas.  
Para crear una nueva contraseña hay que darle al botón “+”.  
En este caso inicio de sesión.  
Y ya te dejaría crear una contraseña y poner el nombre de usuario.  

<img src="img/imagen 10.png" alt="Menú principal de Bitwarden con el botón para añadir nuevos ítems a la caja fuerte">  
<img src="img/imagen 11.png" alt="Generador de contraseñas de Bitwarden mostrando una contraseña segura y opciones de longitud y caracteres">  

Le damos a utilizar esta contraseña.  
Le damos a guardar y se te guardarán los datos que has puesto anteriormente.  

<img src="img/imagen 12.png" alt="Formulario de creación de nuevo elemento en Bitwarden con campos de usuario, contraseña y URI">  
<img src="img/imagen 13.png" alt="Menú de Bitwarden para añadir nuevos ítems como inicio de sesión, tarjeta, identidad o nota">  

Esta es una prueba y la contraseña no es muy segura.  
Mi recomendación es usar una contraseña de 20 caracteres, incluir mayúsculas, minúsculas, números y símbolos para garantizar una contraseña segura.  
Finalmente tendrías que copiar la contraseña generada y guardarla en la base de datos de Bitwarden para poder usarla.

<img src="img/imagen 14.png" alt="Formulario completado en Bitwarden con nombre de elemento, contraseña generada y enlace del sitio web">  

---

## 3. Guardar y Usar Credenciales  

### 3.1 Correo Electrónico  

1. Haz clic en el botón “+” para crear un nuevo ítem.  
2. Selecciona el tipo: Inicio de sesión (Login).  

<img src="img/imagen 15.png" alt="Extensión de Bitwarden abierta en el navegador mostrando las credenciales guardadas de Gmail y GitHub">  

3. Completa los siguientes campos:  
- **Nombre:** escribe un nombre descriptivo, por ejemplo “gmail”.  
- **Nombre de usuario:** introduce tu dirección de correo (por ejemplo alu.david.ballesteros@mataro.epiaedu.cat).  
- **Contraseña:** pon la contraseña de tu Gmail para poder iniciar sesión correctamente.  
- **URL:** añade la dirección del servicio, en este caso: [https://mail.google.com](https://mail.google.com).  

Opcionalmente, agrega notas o asigna la credencial a una carpeta llamada “Correo”.  
Pulsa “Guardar”. Y la contraseña quedará almacenada de forma cifrada dentro del cofre de Bitwarden.  

<img src="img/imagen 16.png" alt="Vista detallada de credenciales de Gmail guardadas en Bitwarden con usuario, contraseña y URL">  

---

### 3.2 Aplicaciones o Servicios Web  

1. En Bitwarden, volvemos a seleccionar “Nuevo ítem” y elegimos el tipo Login.  
2. Sigue los pasos y completa los siguientes campos:  
   - **Nombre:** escribe el nombre de la aplicación o servicio web (por ejemplo: GitHub).  
   - **Usuario:** introduce tu nombre de usuario de la aplicación o web.  
   - **Contraseña:** pon la contraseña de tu cuenta para poder iniciar sesión correctamente.  
   - **URI:** agrega la dirección web de inicio de sesión, en este caso: [https://github.com/login](https://github.com/login).  
   - Opcionalmente, agrega una nota para avisarte que esta contraseña es para GitHub.  
   - Haz clic en “Guardar”.  

<img src="img/imagen 17.png" alt="Vista detallada de credenciales de GitHub guardadas en Bitwarden con usuario, contraseña y URL del sitio">  

---

### 3.3 Autocompletado en el Navegador  

**Requisitos previos:**  
- Tener instalada la extensión de Bitwarden en el navegador (Chrome, Edge o Firefox).  
- Haber iniciado sesión con la misma cuenta que usas en la aplicación.  

<img src="img/imagen 18.png" alt="Página de inicio de sesión de Google con autocompletado de Bitwarden en el campo de contraseña">  

**Pasos a seguir:**  
1. Abre la página de inicio de sesión del servicio (por ejemplo [https://mail.google.com](https://mail.google.com)).  
2. Haz clic en el icono de Bitwarden en la barra del navegador.  
3. Si la página coincide con la URI guardada, Bitwarden mostrará la credencial disponible.  
4. Selecciona la credencial y pulsa “Autocompletar” o el logo azul de escudo.  
5. Los campos de usuario y contraseña se rellenarán automáticamente.  
6. Haz clic en “Iniciar sesión” para acceder.  

---

## 4. Copias de Seguridad (Backup)  

1. Ir a **Fitxer → Exportar caja fuerte**.  
2. Introducir la **contraseña maestra**.  
3. Guardar archivo cifrado.  

<img src="img/imagen 19.png" alt="Menú de Bitwarden mostrando opción para exportar la caja fuerte y realizar copia de seguridad cifrada">  
<img src="img/imatge 20.png" alt="Ventana de confirmación de exportación y guardado de la caja fuerte cifrada de Bitwarden">  
<img src="img/imatge 21.p



  [Tornar pàgina del projecte](../README.md)

