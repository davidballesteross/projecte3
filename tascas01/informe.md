# 🛡️ Gestor de Contraseñas  
**Autor:** David Ballesteros Antich  
**Curso:** 2B  
**Módulo:** Seguretat Informàtica  
**Profesora:** Isabel Bosch  
**Fecha:** 21/10/2025  

---

## 📑 Índice  
1. [Introducción y Justificación](#1-introducción-y-justificación)  
2. [Comparativa Técnica](#2-comparativa-técnica)  
3. [Ventajas e Inconvenientes](#3-ventajas-e-inconvenientes)  
4. [Recomendación](#4-recomendación)  

---

## 1. Introducción y Justificación  

Las contraseñas débiles o reutilizadas representan un **riesgo crítico** para cualquier empresa.  

**Principales amenazas:**  
- **Ataques de diccionario:** los ciberdelincuentes prueban contraseñas comunes para acceder a cuentas.  
- **Credential stuffing:** el uso repetido de la misma contraseña facilita el robo masivo de datos si alguna se filtra.  

Un **gestor de contraseñas** permite:  
- Generar contraseñas **fuertes y únicas**.  
- Almacenarlas de forma **segura mediante cifrado de extremo a extremo**.  
- Acceder a ellas desde **múltiples dispositivos** sin necesidad de memorizarlas.  

---

## 2. Comparativa Técnica  

| Característica | **Bitwarden (Online/Nube)** | **KeePassXC (Offline/Escritorio)** |
|----------------|-----------------------------|------------------------------------|
| **Sincronización** | Automática entre dispositivos vía nube | Manual mediante archivo `.KDBX` |
| **Modelo de seguridad** | Cifrado **AES-256 end-to-end**, *zero-knowledge* | Cifrado local **AES-256 o ChaCha20**, *open source* |
| **Acceso multi-dispositivo** | Sí, apps de escritorio, móvil y extensión de navegador | Sí, pero requiere transferir el archivo manualmente |
| **Costo / Modelo freemium** | Gratis con funciones básicas; *premium* opcional | 100% gratuito y *open source* |
| **Portabilidad** | Alta (acceso desde cualquier dispositivo con Internet) | Depende del archivo `.KDBX` (USB o nube) |
| **Dependencia del cloud** | Sí | No, todo local |

---

## 3. Ventajas e Inconvenientes  

### 🧩 Bitwarden (Online)
**Pros:**  
- Sincronización automática y acceso fácil desde cualquier dispositivo.  
- Cifrado seguro validado y auditado.  
- Experiencia de usuario sencilla.  

**Contras:**  
- Dependencia de la nube e Internet.  
- Riesgo de vulnerabilidad frente a ataques online.  

---

### 💻 KeePassXC (Offline)
**Pros:**  
- Total independencia del cloud.  
- Control completo sobre el archivo de contraseñas.  
- *Open source* y auditable.  

**Contras:**  
- Sincronización manual entre dispositivos.  
- Menos cómodo para usuarios con varios dispositivos.  

---

## 4. Recomendación  

Para el **personal técnico de EverPia** se recomienda **Bitwarden**, ya que:  

- Garantiza **facilidad de uso** y **sincronización automática**.  
- Minimiza **errores humanos** en el almacenamiento y gestión de contraseñas.  
- Ofrece un **equilibrio óptimo entre seguridad, usabilidad y continuidad del negocio**.  

---

**Conclusión:**  
 Un gestor de contraseñas no solo protege los accesos, sino que mejora la seguridad operativa global.  
 Bitwarden, por su balance entre seguridad y comodidad, es la opción más recomendable para entornos empresariales modernos.


