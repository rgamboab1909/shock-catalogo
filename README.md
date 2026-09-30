# SHOCK · Catálogo oficial Vol. 01

Catálogo web de SHOCK, pensado para verse primero en el celular. Es una sola página (`index.html`) con sus fotos en `img/`.

## Publicarlo con GitHub Pages

1. Entra a github.com y crea un repositorio nuevo **público**, por ejemplo `shock-catalogo`.
2. En el repo, entra a **Add file → Upload files** y arrastra **todo el contenido** de esta carpeta: `index.html`, `README.md` y la carpeta `img`.
3. Haz clic en **Commit changes**.
4. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, luego la rama **main** y la carpeta **/ (root)**, y dale **Save**.
5. Espera 1 o 2 minutos. El link queda así: `https://TU-USUARIO.github.io/shock-catalogo/`

## Qué editar

- **Instagram de la tienda:** abre `index.html` y busca `const INSTAGRAM = "";`. Pon el usuario sin @, por ejemplo `const INSTAGRAM = "todo.shock";`. Con eso aparecen el botón "Pedir por DM" y el link en el footer.
- **Link directo a una pieza:** agrega `#` y el código al final del link, por ejemplo `.../shock-catalogo/#S021`. Así se abre esa pieza directamente, y sirve para mandarla por WhatsApp.
