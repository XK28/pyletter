Libros de automatizacion online: https://automatetheboringstuff.com/
Think Python: https://greenteapress.com/thinkpython2/html/thinkpython2001.html
Otros: https://pythonbooks.org/free-books/

Cómo funciona
Carga Excel con openpyxl y extrae encabezados y datos fila por fila.

Para cada fila, crea un diccionario data que mapea nombres de columna a su valor.

Carga la plantilla Word, busca y reemplaza cada marcador <ColumnName> por su valor correspondiente.

Guarda un archivo Word personalizado por cada fila en una carpeta especificada.

✅ Consejos útiles
Asegúrate de que tus columnas en Excel correspondan exactamente a los placeholders en la plantilla (sensibles a mayúsculas).

El placeholder puede aparecer también dentro de tablas o encabezados; puedes extender el reemplazo según tus necesidades.

Puedes mejorar el script si necesitas formatos, estilos o múltiples documentos por registro.

🛠️ Si necesitas funcionalidades avanzadas
Para incluir formato, imágenes o tablas completas, considera usar Spire.Doc / Spire.XLS o IronXL + python‑docx 

Estas bibliotecas permiten copia de estilos, fusión de celdas, manejo de colores, fuentes y más.

