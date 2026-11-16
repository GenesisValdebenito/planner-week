# Planificador Semanal Editable ("Mi Semana")

Planificador asemanal interactivo diseñado para navegador web y optimizado para impresión/exportación en **1 hoja tamaño Carta Horizontal (`letter landscape`)**.

## Estructura del Proyecto

* `index.html`: Estructura limpia y semántica del planificador.
* `styles.css`: Estilos personalizados, texturas de papel, líneas de escritura y reglas `@media print`.
* `app.js`: Lógica de edición en vivo, guardado automático (`localStorage`), e importación/exportación de respaldos en JSON.
* `data.json`: Configuración inicial de columnas, estructura vacía e iconos SVG de estado de ánimo.
* `favicon.svg`: Icono vectorial del planificador para la pestaña del navegador y GitHub.

## Uso

1. Abre `index.html` en tu navegador (o publícalo directamente con **GitHub Pages**).
2. Haz clic en cualquier campo para escribir tus metas, horarios o notas.
3. Usa **Exportar JSON** / **Importar JSON** para respaldar o mover tus semanas entre dispositivos.
4. Presiona **Imprimir / PDF (Carta)** para guardar en formato Carta horizontal en una sola página.
