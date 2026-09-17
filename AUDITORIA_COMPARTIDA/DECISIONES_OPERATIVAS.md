# DECISIONES OPERATIVAS PARA LOS CHATS POR IDIOMA

1. La corrección de código demostrada y autorizada en esta fase es **RSB-002: dimensiones `width`/`height` de imágenes**. Aplicar exactamente las filas de `02_ERRORES_DIMENSIONES_IMAGENES.csv`.
2. `srcset`: **NO modificar de forma masiva**. La auditoría forense no encontró un fallo general de los descriptores `w`.
3. RSB-003 / Google Maps: **NO es una corrección HTML**. El propietario confirma que la API key está restringida. No cambiarla ni eliminarla por ser visible en cliente.
4. Reseñas: mantener **226** donde ya exista. No sustituir por 222 ni insertar el número donde no exista.
5. Leer y respetar `AUDITORIA_COMPARTIDA/DATOS_CANONICOS_PROPIETARIO.md`.
6. La prioridad empresarial Scooter + Inline Skates / Rollerblades **no autoriza cambios automáticos de código, SEO, Schema, orden, navegación o contenido**.
7. `/quads/` y el grupo `QUADS` corresponden al servicio **Roller Skates / patines clásicos de cuatro ruedas**; no a vehículos quad.
8. Depósito: solo Scooter. Sin depósito: Inline Skates / Rollerblades, Bike, Roller Skates, Skateboard y Longboard. Esta regla sirve para detectar contradicciones, **no para insertar texto en páginas que no traten el tema**.
9. Una reseña de cliente no puede convertirse en política, precio, depósito, servicio, equipamiento ni condición empresarial.
10. Si aparece un supuesto dato empresarial no confirmado, no corregirlo: marcarlo como **PENDIENTE DE CONFIRMACIÓN DEL PROPIETARIO**.
11. No tocar canonical, hreflang, x-default, rutas, sitemap, JSON-LD, CSS, JS, imágenes físicas ni archivos raíz salvo autorización expresa.
12. No cambiar titles, descriptions, FAQs, textos visibles, precios, servicios, políticas comerciales o licencias salvo corrección exacta y autorizada.
13. No convertir diferencias de traducción o redacción entre idiomas en errores sin contradicción semántica demostrada.
14. No utilizar documentos históricos como autoridad empresarial. El archivo `00_AUDITORIA_NO_IMAGEN_ORIGINAL.csv` es evidencia histórica, no una orden de corrección.
15. Cada chat debe trabajar en su rama `correcciones/<idioma>`, abrir PR hacia `main`, no fusionarlo y entregar ZIP de respaldo con diff, informe y hashes.
