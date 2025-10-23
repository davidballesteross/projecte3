# Guía de Uso de Bitwarden

**Autor:** David Ballesteros Antich  
**Curso:** 2B  
**Módulo:** Seguretat informàtica  
**Profesora:** Isabel Bosch  
**Fecha:** 21/10/2025  

---

## Índice
1. [Instalación y Configuración Inicial](#1-instalación-y-configuración-inicial)
2. [Generación de Contraseñas Seguras](#2-generación-de-contraseñas-seguras)
3. [Guardar y Usar Credenciales](#3-guardar-y-usar-credenciales)
4. [Copias de Seguridad (Backup)](#4-copias-de-seguridad-backup)
5. [Recomendaciones Finales](#5-recomendaciones-finales)

---

## 1. Instalación y Configuración Inicial

1. Visita la web oficial: [https://bitwarden.com](https://bitwarden.com).

<img src="img/imagen 1.png" alt="Búsqueda en Google del sitio oficial de Bitwarden">

2. Selecciona la versión según el dispositivo: **escritorio**, **móvil** o **extensión de navegador**.

<img src="img/imagen 2.png" alt="Página de extensiones del navegador de Bitwarden mostrando opciones como Chrome, Edge y Firefox">
  
3. Descarga e instala la aplicación.

<img src="img/imagen 3.png" alt="Página de descarga de Bitwarden para Windows con enlaces de instalación y logotipo de Windows">

<img src="img/imagen 4.png" alt="Instalador de Bitwarden en proceso de descarga e instalación en Windows"> 

4. Crea una cuenta con una **contraseña segura** (mínimo 16 caracteres, incluyendo mayúsculas, minúsculas, números y símbolos).

<img src="img/imagen 5.png" alt="Pantalla de inicio de Bitwarden con opción para crear una nueva cuenta">

<img src="img/imagen 6.png" alt="Formulario de creación de cuenta en Bitwarden con campos de correo electrónico y nombre">

<img src="img/imagen 7.png" alt="Formulario para establecer una contraseña maestra segura en Bitwarden">

5. Activa la **autenticación de dos factores (2FA)** para mayor seguridad

<img src="img/imagen 8.png" alt="Menú superior de Bitwarden mostrando opciones de cuenta y configuración para 2FA">

<img src="img/imagen 9.png" alt="Página de seguridad de Bitwarden mostrando opciones de inicio de sesión en dos pasos y proveedores de autenticación">

Y ponemos una de las tres opciones.


---

## 2. Generación de Contraseñas Seguras

1. En Bitwarden, abre el **Generador de contraseñas** (`+` → *Inici de sessió*).
   
<img src="img/imagen 10.png" alt="Vista del panel principal de Bitwarden mostrando la caja fuerte con los elementos guardados como cuentas de GitHub y Gmail.">
<img src="img/imagen 11.png" alt="Detalle de una entrada guardada en Bitwarden correspondiente a la cuenta de GitHub, con nombre de usuario, contraseña y opciones adicionales.">

2. Completa los parámetros:  

<img src="img/imagen 12.png" alt="Detalle de una entrada en Bitwarden para la cuenta de Gmail, mostrando el nombre de usuario, la contraseña y la dirección web asociada.">

3. Haz clic en **“Generar una contraseña”** la creas y guardas los cambios.

<img src="img/imagen 13.png" alt="Formulario de creación de un nuevo elemento en Bitwarden donde se pueden introducir usuario, contraseña, sitio web y notas adicionales.">
Le damos a utilizar esta contraseña
Le damos a guardar y se te guardaran los datos que has puesto anteriormente.

<img src="img/imagen 14.png" alt="Menú desplegable de Bitwarden con opciones para crear diferentes tipos de elementos como inicio de sesión, tarjeta, identidad, nota o clave SSH.">

Esta es una prueba y la contraseña no es muy segura mi recomendación es usar una
contraseña de 20 caracteres, incluir mayúsculas, minúsculas, números y símbolos para
garantir una contraseña segura.
Finalmente tendrias que copiar la contraseña generada y guardarla en la base de datos de
Bitwarden para poder usarla.

---

## 3. Guardar y Usar Credenciales

### 3.1 Correo Electrónico

1. Clic en `+` → selecciona **Inicio de sesión (Login)**.

<img src="img/imagen 15.png" alt="Formulario completado en Bitwarden con un ejemplo de elemento de prueba que incluye nombre de usuario, contraseña y enlace web.">
<img src="img/imagen 16.png" alt="Generador de contraseñas de Bitwarden mostrando una contraseña segura y las opciones configurables para su longitud y tipos de caracteres.">

3. Completa los campos:
   - **Nombre:** gmail  
   - **Usuario:** tu dirección de correo  
   - **Contraseña:** la del servicio  
   - **URL:** [https://mail.google.com](https://mail.google.com)

 <img src="img/imagen 17.png" alt="Interfaz de Bitwarden mostrando un aviso para guardar tiempo con el autocompletado al añadir un nuevo inicio de sesión.">

 

4. Guarda la credencial dentro del **cofre cifrado** de Bitwarden.

### 3.2 Aplicaciones o Servicios Web

1. Clic en `+` → tipo **Login**.  
2. Ejemplo:  
   - **Nombre:** GitHub  
   - **Usuario:** tu usuario de GitHub  
   - **Contraseña:** contraseña del servicio  
   - **URL:** [https://github.com/login](https://github.com/login)  
3. Guarda los datos para un acceso seguro y rápido.
 <img src="img/imagen 18.png" alt="Menú contextual de Bitwarden con opciones para añadir nuevos elementos como inicio de sesión, tarjeta, identidad, nota o clave SSH.">

### 3.3 Autocompletado en el Navegador

**Requisitos:**
- Tener instalada la extensión de Bitwarden (Chrome, Edge, Firefox).  
- Iniciar sesión con la misma cuenta.

**Pasos:**
1. Abre la página de inicio de sesión del servicio.  
2. Haz clic en el icono de Bitwarden.  
3. Selecciona la credencial guardada.  
4. Pulsa **“Autocompletar”** → los campos se rellenan automáticamente.
   
<img src="img/imagen 19.png" alt="Parte inferior de la interfaz de Bitwarden mostrando los botones de acceso a la caja fuerte y la opción de enviar elementos.">
<img src="img/imatge 20.png" alt="Ventana de guardado del archivo de exportación de Bitwarden mostrando la ubicación en la carpeta Downloads y el formato JSON.">

---

## 4. Copias de Seguridad (Backup)

1. En Bitwarden, abre **Fitxer → Exportar caja fuerte**.  
2. Introduce la **contraseña maestra**.  
3. Guarda el archivo **cifrado** en tu dispositivo.

<img src="img/imatge 21.png" alt="Cuadro de confirmación de Bitwarden para exportar la caja fuerte solicitando la contraseña maestra antes de proceder.">
<img src="img/imagen 22.png" alt="Menú principal de Bitwarden desplegado bajo la opción Fitxer, mostrando acciones como sincronizar, importar o exportar la caja fuerte.">
<img src="img/imagen 23.png" alt="Pantalla de inicio de sesión de Google donde Bitwarden sugiere automáticamente la cuenta guardada para completar la contraseña.">

**Recomendaciones:**
- Cifra la copia con herramientas como **7-Zip** o **VeraCrypt**.  
- Guarda una copia en una **memoria USB cifrada** y protégela físicamente.  
- Mantén otra copia en la nube, **cifrada y protegida con 2FA**.

---

## 5. Recomendaciones Finales

- Usa contraseñas largas y únicas.  
- Habilita siempre **2FA**.  
- No compartas tu contraseña maestra.  
- Realiza copias de seguridad cifradas periódicamente.


  [Tornar pàgina del projecte](../README.md)
