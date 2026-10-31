# Aula en perspectiva
Blog académico estático de Alexander Reyes.

## Archivos
- generar.py: combina plantilla y tres entradas; genera cinco páginas HTML e ilustraciones SVG.
- dist/index.html: portada e índice de entradas.
- dist/*html: tres artículos y página Acerca del blog.
- dist/assets/estilos.css: diseño compartido, Grid y adaptación a pantallas pequeñas.
- dist/assets/*svg: imágenes originales.

## Uso y edición
Abre dist/index.html en tu navegador. No requiere instalación para consultarlo.
Para cambiar textos, edita los datos en generar.py y ejecuta `python3 generar.py`.
Para cambiar colores, tipografía o espacios, edita dist/assets/estilos.css.
El generador no sobrescribe la hoja CSS.
Publica el contenido de dist en un alojamiento estático, conservando las rutas relativas.

## Comprobaciones
Tres artículos con texto e imagen, enlaces locales, menú compartido, navegación circular entre artículos, atributo lang y textos alternativos en todas las imágenes. Diseño adaptable mediante CSS.
