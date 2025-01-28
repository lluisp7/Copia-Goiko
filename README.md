# Copia-Goiko

Un proyecto con el que voy a aprender conceptos basicos de javascript para despues ponerlo en practica desarrollando una copia de la web de Goiko.

## Roadmap (creado por IA):
Roadmap del Proyecto: Réplica de la Página de Goiko
Fase 1: Planificación y preparación
Analiza la página original:

Navega por la página web de Goiko y toma nota de sus secciones principales:
Header (barra de navegación, logo, menús desplegables).
Hero section (imagen destacada con texto).
Menú (hamburguesas, precios, categorías).
Información extra (sucursales, contacto, formulario, footer).
Define las funcionalidades que vas a implementar:
Menú interactivo.
Carrito de compras (opcional, para una fase avanzada).
Animaciones y transiciones.
Responsividad para móviles.
Prepara el entorno:

Crea la estructura base del proyecto:
bash
Copy
Edit
/proyecto-goiko
├── index.html
├── style.css
├── script.js
├── /assets (imágenes, iconos, etc.)
Esquema básico (Wireframe):

Dibuja un esquema (a mano o con herramientas como Figma) para visualizar las secciones.
Fase 2: HTML y CSS
Crea la estructura HTML:

Comienza con el esqueleto básico de la página:
Header con logo y menú.
Una sección principal con una imagen destacada y texto.
Un contenedor para las hamburguesas (usa listas o tarjetas para cada producto).
Footer con información de contacto.
Dale estilo con CSS:

Usa CSS para maquetar cada sección.
Añade un diseño responsivo con @media queries para que se vea bien en móviles y tablets.
Usa Flexbox o Grid para organizar los elementos (ejemplo: tarjetas de productos).
Consejo: No te preocupes por la funcionalidad aún; enfócate en que se vea parecido a la página original.

Fase 3: Comienza a usar JavaScript
Menú interactivo:

Implementa la barra de navegación:
Haz que el menú se despliegue y se oculte al hacer clic en el icono de "hamburguesa".
Añade clases dinámicamente con classList.toggle para manejar el estado abierto/cerrado.
Sección del menú (productos):

Crea una lista de productos con JavaScript (un array con objetos que tengan nombre, precio e imagen).
Usa innerHTML para renderizar dinámicamente los productos en la página.
Fase 4: Funcionalidades avanzadas
Filtro de categorías:

Añade botones de categorías (por ejemplo: "Veganas", "Clásicas", "Premium").
Al hacer clic en un botón, filtra los productos y muestra solo los de esa categoría.
Carrito de compras (opcional):

Implementa un botón "Añadir al carrito" en cada producto.
Crea una sección que muestre los productos añadidos, la cantidad y el precio total.
Guarda el carrito en localStorage para que se mantenga al recargar la página.
Fase 5: Animaciones y efectos
Desplazamientos suaves:

Usa el método scrollIntoView para crear un efecto de desplazamiento suave al hacer clic en enlaces del menú.
Slider de imágenes:

Implementa un slider para la sección principal (puedes usar setInterval para pasar las imágenes automáticamente).
Efectos visuales:

Añade transiciones con CSS (por ejemplo, al pasar el cursor sobre botones).
Usa JavaScript para mostrar animaciones al hacer scroll (por ejemplo, las tarjetas de productos aparecen progresivamente).
Fase 6: Responsividad y pruebas
Optimiza el diseño para móviles:

Ajusta los tamaños y márgenes con @media queries.
Asegúrate de que el menú desplegable funcione bien en pantallas pequeñas.
Pruebas:

Revisa toda la página en diferentes navegadores (Chrome, Firefox, Edge).
Haz pruebas en dispositivos móviles y tablets.
Fase 7: Opciones adicionales (para expandir el proyecto)
Formulario de contacto:

Implementa un formulario con validaciones básicas (por ejemplo, campos obligatorios).
Muestra mensajes de error o éxito al enviar el formulario.
Consumo de una API (opcional):

Si quieres ir más allá, conecta tu proyecto con una API real o simulada:
Por ejemplo, una API que devuelva las sucursales cercanas.
Despliegue:

Sube tu proyecto a GitHub Pages, Netlify o Vercel para que sea accesible en línea.

developed by lluisp7
