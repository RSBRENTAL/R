# DECISIONES OPERATIVAS PARA LOS CHATS POR IDIOMA

1. RSB-002 (dimensiones): ES CORRECCIÓN DE CÓDIGO. Aplicar exactamente las filas del CSV de cada idioma.
2. `srcset`: NO modificar de forma masiva. La auditoría forense indica que no encontró errores generales de descriptor `w`.
3. RSB-003 (Maps): NO es corrección HTML. El propietario confirma que la API key está restringida. No cambiar la key.
4. RSB-008 (reseñas): el propietario fija 226 como valor canónico. El repo contiene 226 en los 200 HTML. NO cambiar a 222.
6. No tocar canonical, hreflang, x-default, rutas, sitemap, JSON-LD, CSS, JS, imágenes físicas ni archivos raíz en los trabajos por idioma, salvo que el prompt de ese idioma lo autorice expresamente.
7. Cada chat por idioma debe devolver únicamente los 20 HTML de ese idioma, conservando sus rutas originales, más informe de cambios y validación.

## Rectificación expresa del propietario
- El esquema de reserva 30 % + 70 % NO EXISTE y queda anulado. No usarlo, no corregir ninguna página hacia ese esquema y no tratarlo como dato oficial.
- La cifra de 250 € de depósito NO es una política oficial de RSB: procede de una reseña de cliente. No usarla como dato canónico ni insertarla en la web.
- Regla sobre reseñas: las experiencias narradas por clientes NO son políticas ni hechos empresariales oficiales. No convertir en contenido de la web anécdotas de reseñas sobre depósitos, importes, playa, toallas, bañador u otros detalles similares salvo que exista una fuente oficial independiente de RSB que lo confirme.
