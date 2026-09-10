# g4-catalogo-img

Imágenes del catálogo de G4 Descartables con el marco de marca horneado, para los
anuncios de catálogo de Meta (Feed, Instagram, Historias y Reels).

- `img/<sha1>.jpg` — una por foto del catálogo. El nombre es `sha1(url_original)[:16]`.
- `img/index.json` — lista de hashes disponibles.
- `feed_brandeado.csv` — feed completo que alimenta el catálogo brandeado.
- `sync.py` — rehace el horneado y el feed desde las páginas públicas de la tienda.
  Corre solo por GitHub Actions, al :10 de cada hora.

El marco (`marco.png`) lleva "Despachamos en 24 hs a todo el país" y "Hasta 10% OFF".
Fuente y proceso: `G4 Descartables/meta-overlay/` en el drive de Scale Labs.
