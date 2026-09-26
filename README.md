# Finanzas Personales PWA

Aplicación instalable para administrar movimientos, deudas, proyectos, extractos y perfiles separados.

## Importante

No abras `index.html` directamente para instalarla. Las PWA requieren publicarse mediante HTTPS o ejecutarse en `localhost`.

## Publicación gratuita recomendada: GitHub Pages

1. Crea una cuenta gratuita en GitHub.
2. Crea un repositorio público, por ejemplo `finanzas-pwa`.
3. Sube todo el contenido de esta carpeta, manteniendo la estructura.
4. En el repositorio abre Settings > Pages.
5. Selecciona Deploy from a branch, rama `main`, carpeta `/root` y guarda.
6. Abre la dirección HTTPS generada por GitHub Pages.

No necesitas comprar dominio. GitHub Pages proporciona una dirección gratuita bajo `github.io`.

## Instalación

- iPhone/iPad: abre la dirección en Safari > Compartir > Añadir a pantalla de inicio.
- Android: abre en Chrome > menú > Instalar aplicación.
- Windows: abre en Edge o Chrome > Instalar aplicación.

## Perfiles y privacidad

Cada perfil separa sus finanzas dentro del mismo navegador/dispositivo. No hay cuentas en la nube ni sincronización automática. Para mover datos, usa Datos y configuración > Exportar copia JSON, y luego impórtala en el otro dispositivo.

## Uso local para pruebas

Desde esta carpeta ejecuta `python -m http.server 8080` y abre `http://localhost:8080` en el mismo equipo. Esto sirve para pruebas, no para acceder desde otros dispositivos de forma permanente.
