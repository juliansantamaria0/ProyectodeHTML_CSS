## LuxTime - Sitio Web Corporativo
 
 
 Bienvenido al sitio web corporativo de LuxTime, una experiencia digital diseñada para capturar la esencia del lujo, la precisión y la elegancia atemporal. Este proyecto es una maqueta estática creada con HTML y CSS nativos, sin librerías externas, que refleja la identidad de LuxTime: una marca dedicada a ofrecer relojes de lujo auténticos y certificados, tejidos con historias de artesanía y pasión. Explora nuestro legado, descubre colecciones exclusivas y sumérgete en un viaje donde el tiempo se convierte en arte.

# Visita el sitio en vivo: https://delicate-lollipop-9de829.netlify.app/

# ✨ Sobre el Proyecto
LuxTime nos encomendó crear un sitio web que no solo muestre sus relojes icónicos, sino que cuente su historia de más de un siglo de excelencia relojera. Desde un banner que deslumbra con imágenes rotativas hasta una línea cronológica que narra su evolución, cada página está diseñada para evocar sofisticación y confianza. El sitio es completamente responsivo, adaptándose con elegancia a cualquier dispositivo, y utiliza animaciones CSS para simular interacciones dinámicas, como carruseles y formularios, sin necesidad de backend.
Páginas y Experiencias

# Inicio (Home): 
Un banner principal que rota entre tres imágenes de relojes emblemáticos, con un texto inspirador y un botón que invita a explorar. Incluye una sección de relojes destacados con seis modelos estrella, un resumen de la historia de LuxTime, y un llamado a descubrir la colección completa.
Catálogo de Relojes: Un escaparate con 20 relojes destacados, presentados en tarjetas con imágenes, nombres, precios y disponibilidad, diseñadas para destacar su exclusividad.
Detalle del Producto: Una vista ampliada de cada reloj, con una imagen que crece sutilmente al pasar el cursor, detalles técnicos (materiales, tamaño, peso), opciones simuladas de personalización (grabado y correas), y un carrusel de productos relacionados.
Historia de la Empresa: Una línea cronológica interactiva que recorre hitos clave desde 1905 hasta 2025, acompañada de una galería visual que muestra la evolución de LuxTime, desde talleres antiguos hasta ateliers modernos.
Contacto: Un formulario elegante para conectar con LuxTime, con validaciones visuales que resaltan campos vacíos o incorrectos, junto a datos de contacto y enlaces a redes sociales.

# Características Destacadas

Diseño Responsivo: El sitio brilla en pantallas grandes, tablets y móviles, con tres puntos de quiebre (desktop >992px, tablet ≤992px, móvil ≤768px) para una experiencia fluida.
Interacciones Simuladas: Animaciones CSS crean un banner rotativo, carruseles de productos, y validaciones visuales en el formulario, dando vida al sitio sin necesidad de JavaScript.
Estilo Elegante: Un tema claro con blanco puro (#FFFFFF), dorado sofisticado (#B8860B), y negro profundo (#0A0A0A), inspirado en la precisión suiza y el lujo atemporal.
Flexbox: Todos los layouts, desde el header hasta el footer, usan Flexbox para un diseño limpio y adaptable.
Accesibilidad: Textos con alto contraste, atributos aria-label para navegación, y soporte para usuarios con preferencias de movimiento reducido.


README.md: Esta documentación.
LICENSE: Licencia MIT.

🚀 Cómo Explorar el Sitio

Clonar el Repositorio:
git clone https://github.com/<tu-usuario>/luxtime-website.git
cd luxtime-website


Abrir el Sitio:

Abre src/index.html en un navegador (Chrome, Firefox, Safari).
Para una experiencia óptima, usa un servidor local:python -m http.server 8000



Dependencias:

El sitio usa HTML y CSS nativos, sin librerías externas.
Las fuentes Playfair Display y Open Sans se cargan desde Google Fonts.



🛠️ Planificación y Diseño
Wireframes
Los wireframes (en docs/wireframes/) fueron el primer paso para dar vida a LuxTime. Cada página se planificó cuidadosamente para reflejar la elegancia de la marca:

Inicio: Banner rotativo con tres imágenes, sección de seis relojes destacados, y un resumen histórico con hitos, misión, visión, valores, y galería.
Catálogo: Grid de 20 tarjetas, cada una con imagen, nombre, precio y disponibilidad.
Detalle del Producto: Imagen grande con zoom, detalles técnicos, opciones de personalización (grabado, correas), y carrusel de relacionados.
Historia: Línea cronológica interactiva (desplazamiento horizontal) y galería en mosaico.
Contacto: Formulario con campos para nombre, correo, teléfono, mensaje, y enlaces a redes sociales.

UI/UX

Estilo Visual: Inspirado en la relojería suiza, con un fondo blanco puro, acentos dorados y tipografía elegante (Playfair Display para títulos, Open Sans para texto).
Navegación: Un header fijo con un logo clickable y un menú claro, accesible en todas las páginas.
Interacciones: Animaciones CSS simulan dinamismo, como el carrusel del banner (rotación automática), el zoom en imágenes de productos, y validaciones visuales en el formulario.
Responsividad: Diseñado para pantallas grandes (>992px), tablets (≤992px), y móviles (≤768px, ≤480px), con layouts que se adaptan usando Flexbox y media queries.

🎨 Componentes Interactivos Simulados

Banner Rotativo (Inicio): Tres imágenes que cambian cada 5 segundos mediante animaciones CSS, con texto superpuesto y un botón de acción.
Carrusel de Relojes Destacados (Inicio): Seis tarjetas que se desplazan horizontalmente con scroll suave, simulando un carrusel interactivo.
Carrusel de Productos Relacionados (Detalle): Tarjetas de productos que se deslizan horizontalmente con scroll snap, con hover para destacar cada reloj.
Validación Visual (Contacto): El formulario resalta campos vacíos o incorrectos con bordes rojos y animaciones sutiles, sin JavaScript.
Línea Cronológica (Historia): Una línea de tiempo desplazable que resalta hitos clave (1905-2025) con íconos y descripciones.
Zoom en Imagen (Detalle): La imagen principal crece ligeramente al pasar el cursor, con un borde dorado que se intensifica.

📜 Control de Versiones
El proyecto utiliza Conventional Commits para un historial claro y organizado. Ejemplos de commits:

feat: add banner rotativo con animaciones CSS en index.html
style: implement tema claro con blanco y dorado en Style.css
docs: create wireframes para todas las páginas
fix: adjust responsividad de carrusel en móviles

Consulta el historial completo en el repositorio.
📋 Notas Técnicas

Tecnologías: HTML5 y CSS3 nativos. Sin frameworks ni JavaScript.
Fuentes: Google Fonts (Playfair Display para títulos, Open Sans para texto).
Responsividad: Media queries para desktop (>992px), tablet (≤992px), móvil (≤768px, ≤480px).
Accesibilidad: Uso de aria-label, alto contraste, y soporte para prefers-reduced-motion.
Imágenes: Incluidas en Relojsimage/ (relojes) y images/ (galería histórica). Asegúrate de que todas las imágenes estén en su lugar para evitar errores.

🤝 Contribuciones
Este proyecto es una maqueta estática para LuxTime. Si deseas contribuir:

Crea un fork del repositorio.
Usa Conventional Commits para tus cambios.
Envía un pull request con una descripción clara.

📧 Contacto

Desarrolladores: Julian Santamaria (GitHub), María Alejandra (GitHub)
Correo: contacto@luxtime.com
Teléfono: +57 300 123 4567

📜 Licencia
Este proyecto está bajo la Licencia MIT. © 2025 LuxTime.

LuxTime: Donde el tiempo se convierte en eternidad.