# 🌐 ARSW: Introducción a Spring Boot con MVC

Este proyecto es una introducción práctica al desarrollo web con **Spring Boot**, aplicando el patrón **MVC (Modelo-Vista-Controlador)** para separar la lógica de negocio, la presentación y el control de flujo.

---

## 🎯 Objetivo

Aprender cómo:

- Crear controladores en Spring Boot.
- Servir contenido estático (HTML) y dinámico (JSON / texto).
- Interactuar con el servidor mediante formularios HTML.
- Usar peticiones HTTP `GET` y `POST`.
- Implementar una interfaz interactiva con **JavaScript (AJAX)** para evitar recargas de página.

---

## 🛠️ Tecnologías y conceptos

| Tecnología         | Descripción                                                                 |
|--------------------|------------------------------------------------------------------------------|
| ⚙️ Spring Boot     | Framework para crear aplicaciones web robustas con Java.                    |
| 🧱 MVC             | Patrón de diseño que separa Modelo, Vista y Controlador.                   |
| 🌐 HTML + JS       | Para construir la interfaz de usuario.                                      |
| 💡 AJAX            | Comunicación asincrónica sin recargar la página.                            |
| 🧪 Postman         | Herramienta para probar endpoints de forma sencilla.                        |

---

## 🧪 Ejecución del proyecto

Se siguió el tutorial oficial de Spring:  
🔗 [https://spring.io/guides/gs/serving-web-content](https://spring.io/guides/gs/serving-web-content)

### 🖥️ Salida inicial

El programa muestra un saludo básico al acceder al endpoint:


![hello](https://github.com/user-attachments/assets/6b930c63-897a-40b9-bcee-152e6efc7b00)

---

## 📁 Contenido estático y dinámico

El servidor entrega correctamente los recursos HTML estáticos y los endpoints dinámicos como `/hello` y `/status`.

![static](https://github.com/user-attachments/assets/06d0234e-cff9-45a0-8f79-80eee71293ce)
![status](https://github.com/user-attachments/assets/09112658-b4ac-4c2d-8d2d-d7e4c10544a4)
![dinamico](https://github.com/user-attachments/assets/c8a8bf84-9db0-4290-a05d-d2f4c8fded5d)

---

## 📝 Parte 1: Formulario con método POST (recarga la página)

Se crea un HTML que permite al usuario ingresar su nombre y enviarlo mediante `POST`. Al hacer clic en enviar, se recarga la página con el mensaje personalizado.

![form](https://github.com/user-attachments/assets/24ed6d0e-912a-4c11-a333-6524fc7d7c94)
➡️
![resultado](https://github.com/user-attachments/assets/80291644-3993-4d8e-8dc2-3ed3aed5ca5e)

---

## 🚀 Parte 2: Formulario AJAX (sin recargar la página)

Se actualiza el formulario para que el envío se haga con **JavaScript** y la respuesta se muestre en la misma página, sin recargar.

![form-ajax](https://github.com/user-attachments/assets/623504a0-85c9-405b-aaaf-e1f7df0329fb)

Resultado inmediato:

![hello-ajax](https://github.com/user-attachments/assets/2da161f7-7b3f-4c4e-8964-8bd4337e3244)

---
