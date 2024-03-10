# Pasos para Crear una Extensión de Google Chrome

## 1. Estructura de archivos:
   - Carpeta principal (Nombre de tu extensión)
     - manifest.json
     - popup.html
     - popup.css
     - popup.js
     - icon.png

## 2. Contenido de `manifest.json`:
   - Establece la información básica de la extensión, incluyendo permisos y configuración de la acción del navegador.

## 3. Icono (`icon.png`):
   - Coloca un archivo de imagen que servirá como ícono para tu extensión.

## 4. Contenido de `popup.html`:
   - Estructura básica de HTML.
   - Referencia a `popup.css` para estilos.
   - Referencia a `popup.js` para interactividad.

## 5. Contenido de `popup.css`:
   - Establece estilos básicos para el popup.

## 6. Contenido de `popup.js`:
   - Añade interactividad con JavaScript.

## 7. Cargar la extensión en Chrome:
   - Abre Google Chrome.
   - Ve a `chrome://extensions/`.
   - Habilita el "Modo de desarrollador".
   - Haz clic en "Cargar extensión no empaquetada" y selecciona la carpeta de tu extensión.

## 8. Visualización en el navegador:
   - Observa el ícono de tu extensión en la barra de herramientas.
   - Haz clic en el ícono para abrir el popup.
   - Comprueba que la extensión muestra el mensaje y tiene la interactividad esperada.
