# SR BM

PWA de lectura y consulta de los 251 bhajans de *Bhajans SR 1-227 Hindi* y su apéndice 228-251.

Aplicación publicada: <https://camilo31-svg.github.io/sr-bm/>

## Contenido

- Texto canónico en devanagari, con los versos, puntos suspensivos y marcas `(2)` conservados; los saltos impuestos únicamente por el margen del PDF se muestran unidos.
- Ficha táctil para cada aparición de palabra con su transliteración y glosa contextual en español.
- Traducción oficial española completa en una pestaña independiente.
- Índice, búsqueda, navegación anterior/siguiente y favoritos locales.
- Funcionamiento sin conexión después de la primera carga.

El texto y el orden proceden de los dos volúmenes devanagari. Las traducciones oficiales proceden de los volúmenes españoles 1-207, 208-249 y 250-251. Las glosas 1-227 proceden de la edición interlineal; las formas nuevas de 228-251 fueron cotejadas con el vocabulario existente y su contexto oficial.

## Ejecución local

Desde la carpeta del proyecto:

```powershell
python -m http.server 4173 --directory sr-bm
```

Después, abre `http://localhost:4173`.

## Instalación en iPhone

Abre la aplicación publicada en Safari, pulsa **Compartir** y elige **Añadir a pantalla de inicio**.
