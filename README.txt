
Package estático listo para GitHub Pages.

Archivos incluidos:
- index.html        : Tienda pública (carga semilla.json desde la misma carpeta)
- admin.html        : Panel administrador (login simple). No escribe en servidor; permite editar en memoria y descargar semilla.json actualizado.
- semilla.json      : Productos iniciales (ya con +15%).

Instrucciones rápidas:
1. Subí el contenido de esta carpeta a tu repo (raíz) en GitHub.
2. En Settings -> Pages seleccioná Branch: main, Folder: / (root).
3. Esperá 1-2 minutos y abrí https://cell.github.io/districel/index.html
4. Para editar productos en el sitio sin Firebase:
   - Abrí https://cell.github.io/districel/admin.html
   - Logueá con admin@celldistribuciones.com / QWERTY123456
   - Editá/creá productos y luego clic en "Descargar semilla.json".
   - Subí el semilla.json nuevo al repo (reemplaza el existente) y pusheá/commit.
   - GitHub Pages actualizará y la tienda mostrará los cambios.

Notas:
- Esta versión **no** guarda automáticamente en el servidor (porque no querés configurar backend). En su lugar, el admin permite descargar el JSON actualizado para que lo reemplaces en el repo.
- Las imágenes subidas en admin se convierten a Data URL (base64) y se guardan dentro del JSON; funciona en GitHub Pages pero aumenta el tamaño del archivo si subís muchas fotos.
