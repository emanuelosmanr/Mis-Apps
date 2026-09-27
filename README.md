# Finanzas 2.1

Sube todos los archivos a la raíz del repositorio GitHub Pages, conservando `assets/icons`.

En la primera apertura se crea el administrador. Después de iniciar sesión, el administrador puede crear perfiles totalmente vacíos y asignarles contraseña.

Las contraseñas derivan una clave con PBKDF2 y cada perfil se cifra con AES-GCM usando Web Crypto. No existe recuperación de contraseñas. Al ser una aplicación local, la separación protege frente al acceso casual en el mismo navegador, pero no sustituye la seguridad de un servidor con autenticación profesional o la seguridad física del dispositivo.
