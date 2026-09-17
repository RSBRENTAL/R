# RSB — Workspaces de corrección por idioma

Repositorio de trabajo para las correcciones controladas del candidato web auditado.

## Chats por idioma

Cada chat trabaja exclusivamente con una carpeta:
- `IDIOMAS/EN/`
- `IDIOMAS/ES/`
- `IDIOMAS/FR/`
- `IDIOMAS/IT/`
- `IDIOMAS/DE/`
- `IDIOMAS/NL/`
- `IDIOMAS/PT/`
- `IDIOMAS/CA/`
- `IDIOMAS/SV/`
- `IDIOMAS/PL/`

El prompt vigente de cada idioma está en `PROMPTS/<IDIOMA>.txt` y se refleja dentro de su carpeta como `05_PROMPT_GITHUB_<IDIOMA>.txt`.

## Fuente empresarial vigente

Leer `AUDITORIA_COMPARTIDA/DATOS_CANONICOS_PROPIETARIO.md`.

Reglas esenciales:
- 226 reseñas; no sustituir por 222.
- API de Google Maps confirmada como restringida.
- Servicios principales como prioridad empresarial: Scooter + Inline Skates / Rollerblades.
- Otros servicios: Bike, Roller Skates, Skateboard y Longboard.
- `/quads/` = Roller Skates / patines clásicos de cuatro ruedas; no vehículos quad.
- Depósito solo para Scooter; sin depósito para Inline Skates / Rollerblades, Bike, Roller Skates, Skateboard y Longboard.
- La prioridad de servicios y las reglas comerciales sirven para validar contradicciones, **no para reescribir automáticamente la web**.
- Las reseñas de clientes no son fuente de políticas empresariales.
- Datos históricos no confirmados no deben propagarse como hechos.

## Alcance de corrección

La corrección técnica demostrada en esta fase es la de dimensiones `width`/`height` de imágenes listadas por idioma.
No realizar refactor, rediseño ni cambios de contenido no autorizados.

## Auditoría avanzada del candidato completo

Para auditar el ZIP completo, sin usar la web pública como fuente de verdad, usar:
`PROMPTS/AUDITORIA_AVANZADA_ZIP.txt`

La auditoría avanzada no modifica el ZIP: inventaría, analiza y entrega informe + anexos.
