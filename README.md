# FCúbica — sitio web

Sitio estático (HTML + CSS + JS en un solo archivo). No necesita instalación ni build.

## Estructura
- `index.html` — todo el sitio (inicio, proyectos, ficha de Casa 501, nosotros, contacto)
- `img/` — renders de Casa 501

## Editar contenido
Los datos del proyecto están en `index.html`, dentro de `const PROJECTS = [...]`.
Para agregar un proyecto, copia el objeto de Casa 501, cambia los datos y agrega sus fotos en `img/`.

## Publicar en Vercel
1. Sube esta carpeta a un repositorio de GitHub.
2. En vercel.com → Add New → Project → importa el repositorio.
3. Framework Preset: **Other**. Deja Build Command y Output Directory vacíos.
4. Deploy. Cada push a `main` vuelve a publicar el sitio.

## Pendiente
- El formulario de contacto no envía mensajes todavía (conectar Formspree, Web3Forms o similar).
- Teléfono, equipo y cifras de trayectoria son de muestra.
