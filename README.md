# Gina & Betsabé — Galería sincronizada

Esta versión conserva el HTML y el diseño original y cambia el almacenamiento de la galería para usar Firebase.

## Resultado

Una persona puede subir una foto o video y la otra persona puede verlo desde otro dispositivo. Ambos dispositivos reciben los cambios mediante Firestore en tiempo real.

## Configuración necesaria

1. Crear un proyecto en Firebase.
2. Registrar una aplicación Web.
3. Activar Authentication > Anonymous.
4. Crear Firestore Database.
5. Crear Storage.
6. Copiar la configuración de la aplicación Web en `firebase-config.js`.
7. Aplicar `firestore.rules` y `storage.rules`.
8. Subir todos los archivos a la raíz del repositorio de GitHub Pages.

## Archivos

- `index.html`
- `firebase-config.js`
- `firestore.rules`
- `storage.rules`
- `README.md`
- `.gitignore`
