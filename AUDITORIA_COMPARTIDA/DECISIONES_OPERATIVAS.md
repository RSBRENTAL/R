# DECISIONES OPERATIVAS PARA LOS CHATS POR IDIOMA

1. RSB-002 (dimensiones): ES CORRECCIÓN DE CÓDIGO. Aplicar exactamente las filas del CSV de cada idioma.
2. `srcset`: NO modificar de forma masiva. La auditoría forense indica que no encontró errores generales de descriptor `w`.
3. RSB-003 (Maps): NO es corrección HTML. El propietario confirma que la API key está restringida. No cambiar la key.
4. RSB-008 (reseñas): el propietario fija 226 como valor canónico. El repo contiene 226 en los 200 HTML. NO cambiar a 222.
5. Reserva 30/70, depósito scooter 250 €, radio 25 km y ausencia de e-scooters/e-bikes: datos canónicos del propietario. Corregir únicamente contradicciones en páginas que traten esos temas; no insertar texto indiscriminadamente.
6. No tocar canonical, hreflang, x-default, rutas, sitemap, JSON-LD, CSS, JS, imágenes físicas ni archivos raíz en los trabajos por idioma, salvo que el prompt de ese idioma lo autorice expresamente.
7. Cada chat por idioma debe devolver únicamente los 20 HTML de ese idioma, conservando sus rutas originales, más informe de cambios y validación.
