# Servicio Envío de Emails.

Servicio que brinda la posibilidad de enviar emails a otro destinatario. Con el propocito de validar la identidad del usuario a ingresar.
(Este servicio complementa al proyecto "proyecto-sena", ya que su funcionalidad  ayuda en la validación de registro de usuarios.)

Características:
- HOST: https://service-email.vercel.app/
- HTTP REQUEST: POST
- PARAMS: /{email}/{codigo-Verificacion}

Uso:
- Genera una clave de acceso de tu cuenta de gmail, y cambia el user y la pass en el archivo configEmails.js.
<img width="408" height="184" alt="image" src="https://github.com/user-attachments/assets/f39aaa77-7743-451a-805e-2f34fde070e2" />


- Después, haz la siguiente solicitud y comprueba si todo va bien:

POST https://service-email.vercel.app/{email}/{codigo-verificacion}

