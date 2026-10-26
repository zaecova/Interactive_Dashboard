# Dashboard de ejecución presupuestal de la MPD

## Abrir el proyecto
1. Extrae todos los archivos del ZIP en una misma carpeta.
2. Abre index.html con tu navegador.
No requiere instalar programas ni dependencias. Funciona sin conexión.

## Subir a GitHub
En el repositorio Interactive_Dashboard, selecciona Add file > Upload files, arrastra index.html, app.js y README.md y confirma los cambios. No subas el ZIP sin extraer si deseas publicar la página.
Para GitHub Pages: Settings > Pages > Deploy from a branch > main > /(root) > Save.

## Funciones
- Comparativo anual 2023–2025 y línea acumulada en orden cronológico.
- Barras agrupadas y apiladas.
- Gráfico de evolución con selección múltiple de años y categorías.
- Mensajes con porcentaje ejecutado y clasificación al pulsar cada punto.
- Descarga de datos CSV.
- Fondo gris y bordes dorados.

## Datos
Fuente: archivos 2023 vALIDO.xls, 2024.xls y 2025.xls, exportados de Consulta Amigable del MEF, con fecha de consulta del 25 de octubre de 2026. Los datos están incorporados en app.js.
Avance = devengado / PIM × 100. Avances anuales: 2023: 95,3%; 2024: 71,4%; 2025: 91,5%.
El devengado representa obligaciones de pago reconocidas, no necesariamente pagos efectuados. La clasificación sigue la escala proporcionada por la usuaria. El avance financiero no mide por sí solo la calidad del gasto. El acumulado de porcentajes no representa gasto monetario acumulado.

## Archivos
index.html: página y estilos.
app.js: datos, gráficos y filtros.
README.md: instrucciones.
