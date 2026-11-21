# Mi Tienda: cómo obtener el APK

1. En github.com crea un repositorio nuevo (puede ser privado).
2. Sube TODO el contenido de esta carpeta, incluida la carpeta oculta `.github`.
   Si no se sube, crea el archivo a mano: Add file > Create new file, con el nombre
   `.github/workflows/build-apk.yml`, y pega el contenido del archivo del mismo nombre.
3. Entra a la pestaña **Actions**. Si no empieza solo, abre "Crear APK" y toca **Run workflow**.
4. Cuando termine (unos 5 a 10 minutos), abre la ejecución y descarga **mi-tienda-apk** al final de la página.
5. Descomprime el ZIP, pasa `app-debug.apk` al celular e instálalo (permite instalar apps de origen desconocido).

Para cambiar la app edita `www/index.html`; cada cambio genera un APK nuevo.
Los datos se guardan en el teléfono. Reinstalar o borrar los datos de la app los elimina: descarga el Excel como respaldo.
