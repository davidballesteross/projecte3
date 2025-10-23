# GUIA T01: Gestor de contraseñas

**Autor:** David Ballesteros Antich  
**Curso:** 2B  
**Módulo:** Seguretat informàtica  
**Profesora:** Isabel Bosch  
**Fecha:** 21/10/2025  

---

## Índice
1. [Introducción y Justificación](#1-introducción-y-justificación)
2. [Comparativa Técnica](#2-comparativa-técnica)
3. [Ventajas e Inconvenientes](#3-ventajas-e-inconvenientes)
4. [Recomendación](#4-recomendación)

---

## 1. Introducción y Justificación

Las contraseñas débiles o reutilizadas representan un riesgo crítico para la seguridad:

- **Ataques de diccionario:** los ciberdelincuentes prueban contraseñas comunes.  
- **Credential stuffing:** el uso repetido de la misma contraseña facilita el robo masivo de datos.

Un **gestor de contraseñas** permite:

- Generar contraseñas fuertes y únicas.  
- Almacenarlas cifradas de forma segura (end-to-end).  
- Acceder a ellas desde múltiples dispositivos sin necesidad de recordarlas.

---

## 2. Comparativa Técnica

| Característica              | Bitwarden (Online / Nube)                              | KeePassXC (Offline / Escritorio)                     |
|-----------------------------|----------------------------------------------------------|------------------------------------------------------|
| **Sincronización**          | Automática entre dispositivos vía nube                  | Manual mediante archivo `.kdbx`                      |
| **Modelo de seguridad**     | Cifrado AES-256 end-to-end, *zero-knowledge*            | Cifrado local AES-256 o ChaCha20, open source        |
| **Acceso multi-dispositivo**| Sí (escritorio, móvil, extensión navegador)              | Sí, pero requiere transferir archivo manualmente     |
| **Costo / Modelo**          | Gratis (freemium) + premium opcional                    | 100% gratuito y open source                          |
| **Portabilidad**            | Alta (desde cualquier dispositivo con Internet)         | Depende del archivo `.kdbx`                          |
| **Dependencia de la nube**  | Sí                                                       | No, todo local                                       |

---

## 3. Ventajas e Inconvenientes

### Bitwarden (Online)
**Pros:**
- Sincronización automática y acceso fácil desde cualquier dispositivo.  
- Cifrado validado y auditado.  
- Interfaz intuitiva y sencilla.

**Contras:**
- Dependencia de Internet.  
- Riesgo potencial de ataques online.

### KeePassXC (Offline)
**Pros:**
- Independencia total de la nube.  
- Control completo del archivo de contraseñas.  
- Código abierto y auditable.

**Contras:**
- Sincronización manual.  
- Menor comodidad para múltiples dispositivos.

---

## 4. Recomendación

Para el personal técnico de **EverPia**, se recomienda **Bitwarden**:

- Facilita la sincronización automática.  
- Minimiza errores humanos en la gestión de contraseñas.  
- Ofrece equilibrio entre **seguridad, usabilidad y continuidad del negocio**.

