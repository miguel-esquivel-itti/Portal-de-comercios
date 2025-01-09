# Portal de Comercios

## Automatización de APIs 🚀

Este proyecto contiene pruebas automatizadas para garantizar la funcionalidad y consistencia de los endpoints del portal de comercios.

![Texto alternativo](http://ae7ff849bd3b3485592b93674c2cfd94-401474819.sa-east-1.elb.amazonaws.com/_next/static/media/login-img.9a1e4fe8.webp)

## 🔍 Propósito

Validar que las APIs del portal de comercios operen correctamente, proporcionando:

- **Autenticación segura:** Login y manejo de tokens (`access_token`).
- **Gestión de datos:** Validación y actualización de información del comercio.
- **Procesamiento de transacciones:** Validación de pagos y consultas.
- **Generación de reportes:** Comprobación de endpoints relacionados con informes.

---

## 📂 Estructura del Proyecto

### **Colección Principal**
1. **Autenticación:** Login.
2. **Gestión de datos del comercio:** Manejo de `sellerId` y otros datos.
3. **Transacciones:** Validación de pagos y consultas.
4. **Gestión de usuarios.**

### **Entornos Configurados**
- **Variables dinámicas:**
  - `{{base_url}}`
  - `{{onb_backend_access_token}}`

---

## 🤖 Automatización de Pruebas

- **Pre-request Scripts:** Configuración automática de tokens.
- **Tests:** Validaciones automatizadas de las respuestas y códigos de estado.

---

## 💡 Cómo Usar

1. Configura las variables de entorno:
   - `{{base_url}}` para la URL base del entorno.
   - `{{onb_backend_access_token}}` para el token de acceso.
2. Ejecuta la colección completa o una solicitud específica según el caso.
3. Revisa los resultados en el Test Runner.

---

## ✅ Criterios de Aceptación

- Todos los endpoints deben devolver el código de estado esperado (200, 401, etc.).
- Los tokens deben gestionarse dinámicamente sin interrupciones.
- La información clave como `sellerId` debe coincidir con los valores esperados.

---

## 📊 Beneficios del Proyecto

- **Eficiencia:** Reducción de tiempos manuales en pruebas.
- **Confiabilidad:** Identificación rápida de errores en las APIs.
- **Escalabilidad:** Fácil incorporación de nuevos endpoints.

---

## 🔗 Recursos Adicionales

- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
- [Documentación de Postman](https://learning.postman.com/docs/getting-started/introduction/)

---

¡Gracias por usar este proyecto! ✨
