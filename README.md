# Mail Library

Las funcionalidades son prácticamente nulas pero sirve de pruebas para publicar una libería hecha con poetry y publicada en Pypi.

**Mail Library** es una librería de Python para enviar correos electrónicos con funcionalidades avanzadas. Facilita el envío de correos básicos, correos con adjuntos, y correos HTML, además de soportar configuraciones dinámicas y manejar errores.

## Funcionalidades

- **Configuración Básica de Correo**
  - Configuración del servidor SMTP, puerto, y credenciales de autenticación.
  - Configuración del remitente.

- **Envío de Correos**
  - Envío de correos básicos con asunto y cuerpo (texto o HTML).
  - Inclusión de archivos adjuntos.
  - Envío de correos a múltiples destinatarios (a, cc, bcc).
  - Soporte para correos en formato HTML.

- **Configuraciones Avanzadas**
  - Cuerpo del correo en HTML con imágenes embebidas.
  - Seguridad y autenticación con TLS/SSL.
  - Uso de variables de entorno y archivos de configuración para manejar credenciales y parámetros.

- **Manejo de Errores y Registro**
  - Registro de actividades y errores.

- **Funcionalidades Adicionales**
  - Plantillas de correo.
  - Programación de correos.
  - Seguimiento de correos (opcional).

- **Interfaz de Línea de Comandos (CLI)**
  - Comandos para enviar correos directamente desde la terminal.

## Instalación

Puedes instalar la librería usando `pip`. Ejecuta el siguiente comando en tu terminal:

```bash
pip install mail-library