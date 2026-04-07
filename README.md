# Balanza Comercial

Dashboard web para comparar **clientes** vs **proveedores** desde archivos Excel e identificar oportunidades de negocio ganar/ganar (relaciones bilaterales con logísticas que te contratan y a las que contratas).

## Cómo usarlo

1. Abre `index.html` en tu navegador (doble clic) — **no necesitas instalar nada**.
2. Sube tu archivo Excel de **Clientes** (lo que te compran).
3. Sube tu archivo Excel de **Proveedores** (a quienes les compras).
4. El dashboard detecta automáticamente las columnas de **nombre** y **monto**, cruza los datos y te muestra:
   - KPIs: total ventas, compras, balanza neta, número de relaciones bilaterales.
   - Top 10 clientes y top 10 proveedores en gráficas.
   - **Oportunidades ganar/ganar**: empresas que están en ambas listas, con sugerencia de negociación.
   - Tabla combinada con búsqueda, filtros y exportación a Excel.

## Formato esperado del Excel

Cualquier hoja con al menos una columna de **nombre de empresa** (ej. `Cliente`, `Razón Social`, `Proveedor`) y una de **monto** (ej. `Total`, `Importe`, `Venta`). Las columnas se detectan automáticamente.

## Tecnología

100% navegador, sin servidor: HTML + JavaScript con [SheetJS](https://sheetjs.com) y [Chart.js](https://www.chartjs.org).

## Publicar gratis (opcional)

En GitHub: Settings → Pages → Source: `main` → carpeta `/ (root)`. Tendrás una URL pública.
