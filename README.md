# Mis Documentos

App personal (PWA tipo iPhone) para guardar DNI, pasaporte, licencia, papeles del auto, credenciales de salud y demás documentos tuyos y de tu familia.

- **Sin servidor**: todo queda en el teléfono (IndexedDB), cifrado con AES-256.
- **Código de 6 números** + **Face ID** opcional (passkey con WebAuthn PRF, iOS 18+).
- **Avisos de vencimiento** al Calendario (archivo .ics con alarmas) y aviso dentro de la app.
- **Copia de seguridad cifrada** para guardar en Archivos, iCloud Drive, Google Drive o Gmail.
- Modo claro / oscuro automático, diseño estilo iOS con efecto vidrio.

## Publicar en GitHub Pages
1. Crear una organización nueva en GitHub (ej. `mis-documentos-app`) o usar tu cuenta.
2. Crear el repositorio `mis-documentos-app.github.io` (público).
3. Subir todos los archivos de esta carpeta (incluida `icons/` y `.nojekyll`).
4. Settings → Pages → Deploy from a branch → `main` / root.
5. Abrir `https://mis-documentos-app.github.io` en Safari → Compartir → **Agregar a inicio**.

El código es público, pero los documentos nunca: viven cifrados sólo en cada teléfono.
