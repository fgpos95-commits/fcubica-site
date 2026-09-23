# FCúbica — contexto para Claude

Sitio estático de FCúbica (arquitectura y desarrollo inmobiliario). Se publica en Vercel automáticamente con cada push a `main`. No hay build: todo vive en `index.html` + `img/`.

## Estructura del sitio
- Navegación por hash: `#inicio`, `#proyectos`, `#p-<slug>` (ficha), `#nosotros`, `#contacto`.
- Datos de proyectos en `const PROJECTS = [...]` dentro de `index.html`. Hoy solo hay uno visible: **Casa 501**.
- Imágenes en `img/`. Comprimir a ~2400 px de ancho, JPG calidad ~80, antes de subir.

## Estilo visual (copiado del sitio anterior en Base44 — respetarlo)
- Fondo blanco, tinta `#1A1A18`, grises cálidos (`--muted #8A8880`, `--line #E6E4DE`).
- Tipografías: Space Grotesk (títulos y texto) + Space Mono (etiquetas en mayúsculas con tracking amplio).
- Botones rectos sin radio, header fijo que es transparente sobre el hero y blanco al hacer scroll.
- Filas de portafolio: texto a la izquierda (contador, estado, nombre, ubicación, m², "Ver proyecto ↗") e imagen grande a la derecha.

## Casa 501 (datos confirmados en el Project de Claude "F3 - Casa 37")
- Jalpa de Cánovas, Purísima del Rincón, Guanajuato, a 1 hora de León.
- 2,000 m² de terreno, 170 m² construidos, una planta, 2 recámaras, 2 baños completos, 2 estacionamientos.
- Terraza con fogatero y jacuzzi, pérgola de madera. Piedra, stucco, madera, bóvedas de ladrillo.
- Preventa. Obra no iniciada: las imágenes son renders (etiquetarlas "Render"). Entrega 8 meses desde inicio, precio de construcción fijo por contrato.
- Escriturable de inmediato, libre de gravamen.
- Precio final aún no definido: NO publicar precio hasta que el dueño lo confirme.

## Reglas de copy
- Español de México, trato de "usted" en textos de venta.
- No usar: exclusivo, único, hermoso, espectacular, amplio (sin m²), de lujo, tranquilidad o plusvalía como gancho suelto, acogedor, sofisticado. Usar datos concretos (m², una planta, precio de obra fijo, fecha de entrega).

## Pendientes
- Formulario de contacto sin conectar (usar Formspree o Web3Forms).
- Teléfono (+52 55 0000 0000), sección de equipo y cifras de "Trayectoria" son de muestra.
