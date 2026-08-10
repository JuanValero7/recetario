# Recetario (PWA offline)

Planificador de comidas, lista de compra e inventario. **Funciona sin conexión**:
todos los datos se guardan en el propio dispositivo (localStorage). No hay servidor
ni backend — el repositorio solo contiene el código; **ningún dato personal**.

## Uso
Abre la URL (GitHub Pages) en el móvil y **"Añadir a pantalla de inicio"**. Se instala
como app y funciona offline. La primera vez: pestaña **Datos → Importar** y carga tu
archivo `mis-datos-recetario.json`.

## Estructura
- `index.html` — app completa (UI + lógica + capa de datos local).
- `seed.json` — datos iniciales (vacío en el repo público).
- `manifest.webmanifest`, `sw.js` — soporte PWA (instalar + offline).
- `icon-192.png`, `icon-512.png` — iconos.

## Copia de seguridad
Pestaña **Datos → Exportar** descarga un JSON con todo. Guárdalo cada tanto.
