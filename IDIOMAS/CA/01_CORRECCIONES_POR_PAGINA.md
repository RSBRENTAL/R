# CA — Catalán: correcciones por página

## Decisiones del propietario aplicadas
- Reseñas canónicas: **226**. No usar 222.
- Google Maps API: **restringida**; no modificar la key por ser visible en cliente.
- Reserva: **30 % transferencia + 70 % al recoger**.
- Depósito scooter de referencia: **250 €**.
- Sin depósito: bicicletas, patines en línea, patines clásicos, skateboards y longboards.
- Radio de servicio: **25 km**.
- No se ofrecen **e-scooters** ni **e-bikes**.

## Reglas
- La única corrección técnica de código transversal demostrada por la auditoría forense es la relación `width/height` de imágenes.
- No modificar `srcset` de forma masiva.
- Los hallazgos RSB-003 quedan como verificación externa ya confirmada por el propietario, sin cambio HTML.
- Para EN, RSB-008 queda resuelto por decisión del propietario: mantener 226.

## Páginas
### BIKE — `cat/bike/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-bike-rental-shop-olympic-village-barcelona.webp`: `1200×675` → `480×720`.

### BLOG_50CC_VS_125CC — `cat/blog/50cc-vs-125cc-scooter-rental-barcelona/index.html`
- No hay corrección no-imagen demostrada.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-scooter-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×936`.

### BLOG_BEGINNER_INLINE — `cat/blog/patinar-linia-barcelona-principiants/index.html`
- No hay corrección no-imagen demostrada.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-inline-skates-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×533`.

### BLOG_BEST_ROUTES — `cat/blog/best-rollerblading-routes-barcelona/index.html`
- No hay corrección no-imagen demostrada.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-inline-skates-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×533`.

### BLOG_BIKE — `cat/blog/bike/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-bike-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×533`.

### BLOG_HOURLY_INLINE_RENTAL — `cat/blog/lloguer-patins-linia-barcelona-per-hores/index.html`
- No hay corrección no-imagen demostrada.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-inline-skates-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×533`.

### BLOG_INDEX — `cat/blog/index.html`
- No hay corrección no-imagen demostrada.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-barcelona-rental-hero-group-beach-1600-v1.webp`: `1600×900` → `1600×874`.

### BLOG_INLINE_SKATES — `cat/blog/inline-skates/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-inline-skates-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×533`.

### BLOG_LONGBOARD — `cat/blog/longboard/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-longboard-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×478`.

### BLOG_ROLLER_SKATES — `cat/blog/roller-skates/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-quad-skates-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×533`.

### BLOG_SCOOTER — `cat/blog/scooter/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-scooter-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×936`.

### BLOG_SKATEBOARD — `cat/blog/skateboard/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-skateboard-rental-barcelona-vila-olimpica-800.webp`: `1600×900` → `800×360`.

### HOME — `cat/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 9 incidencia(s). Aplicar exactamente:
  1. `rsb-barcelona-rental-hero-group-beach-1600-v1.webp`: `1600×900` → `1600×874`.
  2. `9.webp`: `800×600` → `300×300`.
  3. `skateboards-rental-barcelona.webp`: `800×600` → `514×510`.
  4. `2.webp`: `800×600` → `400×400`.
  5. `rsb-barcelona-rental-rsb-villa-olimpica-del-poble-nou--rent-skateboard-barcelona-soleado-800-v1.webp`: `800×600` → `800×1200`.
  6. `9.webp`: `800×600` → `300×300`.
  7. `skateboards-rental-barcelona.webp`: `800×600` → `514×510`.
  8. `2.webp`: `800×600` → `400×400`.
  9. `rsb-barcelona-rental-rsb-villa-olimpica-del-poble-nou--rent-skateboard-barcelona-soleado-800-v1.webp`: `800×600` → `800×1200`.

### LOCATION_CONTACT — `cat/location-contact/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-rental-scooter-barcelona-shop-vila-olimpica.webp`: `1200×800` → `585×594`.

### LONGBOARD — `cat/longboard/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 3 incidencia(s). Aplicar exactamente:
  1. `rsb-longboard-rental-barcelona-hero-group-beach-1600-v1.webp`: `1600×900` → `1600×1066`.
  2. `rsb-longboard-rental-barcelona-vila-olimpica-800.webp`: `1200×675` → `800×478`.
  3. `rsb-bike-rental-shop-olympic-village-barcelona.webp`: `1200×675` → `480×720`.

### PRICES — `cat/Prices/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 6 incidencia(s). Aplicar exactamente:
  1. `rsb-barcelona-rental-hero-group-beach-800-v1.webp`: `800×449` → `800×437`.
  2. `rsb-scooter-rental-barcelona-vila-olimpica-800.webp`: `800×533` → `800×936`.
  3. `rsb-skateboard-rental-barcelona-vila-olimpica-800.webp`: `800×533` → `800×360`.
  4. `rsb-barcelona-rental-shop-interior-inline-skates-bike-vila-olimpica-640.webp`: `1200×800` → `640×336`.
  5. `rsb-bike-rental-shop-olympic-village-barcelona.webp`: `1200×675` → `480×720`.
  6. `rsb-barcelona-rental-hero-group-beach-800-v1.webp`: `1600×899` → `800×437`.

### QUADS — `cat/quads/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 1 incidencia(s). Aplicar exactamente:
  1. `rsb-bike-rental-shop-olympic-village-barcelona.webp`: `1200×675` → `480×720`.

### ROLLERBLADES — `cat/rollerblades/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 3 incidencia(s). Aplicar exactamente:
  1. `rsb-rollerblades-rental-barcelona-hero-group-beach-1600-v1.webp`: `1600×900` → `1600×874`.
  2. `rsb-rollerblades-rental-barcelona-hero-group-beach-1600-v1.webp`: `1600×900` → `1600×874`.
  3. `rsb-bike-rental-shop-olympic-village-barcelona.webp`: `1200×675` → `480×720`.

### SCOOTER — `cat/scooter/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 2 incidencia(s). Aplicar exactamente:
  1. `rsb-scooter-rental-barcelona-hero-group-v1-1536.webp`: `1536×864` → `1536×672`.
  2. `rsb-rental-scooter-barcelona-shop-vila-olimpica.webp`: `1200×675` → `585×594`.

### SKATEBOARD — `cat/skateboard/index.html`
- **RSB-003:** sin modificación HTML. La API Maps está restringida según confirmación del propietario.
- **Dimensiones de imagen:** 3 incidencia(s). Aplicar exactamente:
  1. `rsb-skateboard-rental-barcelona-hero-group-beach-1600-v1.webp`: `1600×900` → `1600×1066`.
  2. `rsb-skateboard-rental-barcelona-vila-olimpica-800.webp`: `1200×675` → `800×360`.
  3. `rsb-bike-rental-shop-olympic-village-barcelona.webp`: `1200×675` → `480×720`.
