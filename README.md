# Gastos MP

Registro de gastos de Materiales Palenque: los encargados capturan desde el teléfono, el dueño revisa, aprueba y exporta al Excel del estado de resultados.

- Web: GitHub Pages (`index.html`, `sw.js`, `manifest.json`, íconos)
- Android: Capacitor, compilado por GitHub Actions (`.github/workflows/apk.yml`) y publicado en Releases (`apk-latest`)
- Datos: Firebase proyecto **creditosmp** (el mismo de la Agenda de Créditos), colecciones `gastos_*`
- Reglas: `firestore.rules` (incluye las de créditos sin cambios)

Para publicar cambios: edita `index.html`, sube `CACHE_NAME` en `sw.js` y el APK se recompila solo.
