# K_STREAM+ · Publicación para iPhone

Estos son únicamente los archivos de la aplicación web. No contiene el Excel ni datos de clientes.

Para publicarla con GitHub Pages, carga estos archivos en la raíz de un repositorio público y activa Pages desde la rama `main`, carpeta `/(root)`. Luego configura en Supabase Auth la URL publicada como dirección del sitio y redirección permitida.

La app usa el proyecto privado de Supabase configurado en `app.js`. Los archivos de esta carpeta pueden ser públicos; la base de clientes sigue protegida por inicio de sesión y RLS.
