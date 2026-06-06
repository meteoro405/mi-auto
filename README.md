# MiGarage 🚗🏍

Aplicación web de mantenimiento de vehículos, lista para GitHub Pages.

## Características (v1.0)

- **Gestión de vehículos**: autos, motos, camionetas. Foto, VIN, patente, combustible, km.
- **Historial de servicios**: cada intervención con repuestos detallados, costos, taller.
- **Agenda & Alertas**: próximos mantenimientos por km y/o por fecha, con semáforo de estado.
- **Dashboard**: resumen por vehículo con gastos, km, últimas alertas y últimos servicios.
- **Exportar / Importar** JSON para backup.
- **Moneda configurable** (por defecto `$`).
- Datos guardados en `localStorage` (sin servidor).

## Deploy en GitHub Pages

1. Crear un repositorio en GitHub (puede ser privado o público).
2. Subir `index.html` y `manifest.json` a la rama `main`.
3. Ir a **Settings → Pages → Source → Deploy from branch → main / root**.
4. En unos segundos la app queda en `https://TU_USUARIO.github.io/NOMBRE_REPO/`.

## Stack

- HTML + CSS + JS puro (sin frameworks, sin build steps).
- `localStorage` como base de datos.
- Google Fonts: Fraunces + DM Sans + DM Mono.

## Próximos módulos planeados

- [ ] Módulo de neumáticos con historial por posición
- [ ] Estadísticas y gráficos de costos
- [ ] Registro detallado de neumáticos
- [ ] Sincronización con GitHub Gist (backup en la nube)
