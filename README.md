# Mail Library

**Mail Library** es una librer�a de Python para enviar correos electr�nicos con funcionalidades avanzadas. Facilita el env�o de correos b�sicos, correos con adjuntos, y correos HTML, adem�s de soportar configuraciones din�micas y manejar errores.

## Funcionalidades

- **Configuraci�n B�sica de Correo**
  - Configuraci�n del servidor SMTP, puerto, y credenciales de autenticaci�n.
  - Configuraci�n del remitente.

- **Env�o de Correos**
  - Env�o de correos b�sicos con asunto y cuerpo (texto o HTML).
  - Inclusi�n de archivos adjuntos.
  - Env�o de correos a m�ltiples destinatarios (a, cc, bcc).
  - Soporte para correos en formato HTML.

- **Configuraciones Avanzadas**
  - Cuerpo del correo en HTML con im�genes embebidas.
  - Seguridad y autenticaci�n con TLS/SSL.
  - Uso de variables de entorno y archivos de configuraci�n para manejar credenciales y par�metros.

- **Manejo de Errores y Registro**
  - Registro de actividades y errores.

- **Funcionalidades Adicionales**
  - Plantillas de correo.
  - Programaci�n de correos.
  - Seguimiento de correos (opcional).

- **Interfaz de L�nea de Comandos (CLI)**
  - Comandos para enviar correos directamente desde la terminal.

## Instalaci�n

Puedes instalar la librer�a usando `pip`. Ejecuta el siguiente comando en tu terminal:

```bash
pip install mail-library