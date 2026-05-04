PROYECTO: Fichas personales con links y QR

ARCHIVOS:
- index.html: muestra la ficha de una persona según el ID del link.
- datos.json: acá cargás o editás los datos de las personas.
- generar_links.html: muestra los links y QR de cada persona.

CÓMO FUNCIONA:
Cada link tiene esta forma:
index.html?id=12345678

El ID se busca dentro de datos.json.

EJEMPLOS:
index.html?id=12345678
index.html?id=87654321

IMPORTANTE:
Para que el QR funcione desde cualquier celular, tenés que subir la carpeta a internet.
Una opción gratis es GitHub Pages o Netlify.

Si querés probarlo en tu computadora:
1) Abrí una terminal dentro de la carpeta.
2) Ejecutá:
   python -m http.server 8000
3) Entrá a:
   http://localhost:8000/index.html?id=12345678
