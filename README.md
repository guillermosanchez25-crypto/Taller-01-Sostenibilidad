# Taller-01-Sostenibilidad

## Fase 1: Inventario y Dimensión Ambiental (A)

### 1. Medición inicial. Utiliza herramientas gratuitas como Website Carbon Calculator o Lighthouse (pestaña de rendimiento en Chrome/Edge) para obtener la huella de carbono estimada por visita.

<img width="1660" height="940" alt="image" src="https://github.com/user-attachments/assets/62259d26-dec6-4457-840a-8e8c9382c47e" />

<img width="1092" height="733" alt="image" src="https://github.com/user-attachments/assets/7c5f968d-292a-4ccb-a822-a38ae12e1602" />

### 2. Identificación de Bloatware. Inspecciona la red (Network) en las herramientas de desarrollador del navegador. Identifica los 3 recursos más pesados que se descargan al abrir la web (imágenes sin comprimir, vídeos de fondo, librerías JavaScript pesadas, etc.).

- Imagenes de banners y productos con alta resolucion: Esto incrementa la transferencia de datos, el uso de CPU  y el consumo energetico pues la web tarda mas en cargar las imagenes, esto aumenta la huella de carbono y hace la experiencia para dispositivos moviles mas lenta.

- Librerias externas: La web usa multiples funcionalidades externas como cookies, sliders, analiticaas y mas, Esto provoca cargar scripts externos que no tienen por que ser necesarios y plugins de marketing que molestan.

- Recursos de terceros: Usa Google Fonts, iconos externos y CDN multiples, esto aumenta la latencia, el consumo energeticvo y ralentiza la web.

### 3. Análisis. ¿Crees que la web sufre de "inflación de software"? Justifica tu respuesta.

La web si presenta inflacion de software porque utiliza demasiados recursos para algo que no deja de ser una pagina que vende libros y deberia de ser una web simple ya que solo es un catalogo electronico.

La primera causa es el exceso de imagenes de alta calidad, los banners y elementos graficos tambien cuentan, esto provoca descargas pesadas e innecesarias 
Otra causa son las librerias externas que puede que ni siquiera el usuario haga uso de ellas, todo se carga desde el inicio.
Por ultimo esta el elevado numero de peticiones HTTP externas, las cookies y servivios externos sobrecargan la pagina.

## Fase 2: Dimensión Social y Equidad (S)

### 1. Test de Accesibilidad. Pasa una herramienta como WAVE Web Accessibility Evaluation Tool o el propio Lighthouse (pestaña Accessibility).

<img width="528" height="497" alt="image" src="https://github.com/user-attachments/assets/c2ee0a44-ef8e-46f9-beb6-fa16ee2762ea" />



### 2. Identificación de barreras. Documenta al menos 2 problemas graves que impidan a personas con diversidad funcional usar la web correctamente (ej. falta de atributos alt en imágenes clave, bajo contraste de colores en botones, formularios sin etiquetas).

-  La web no es accesible para usuarios discapacitados como los ciegos o usuarios de baja vision, una opcion seria implementar atributos descriptivos de la web.

-  La navegacion por la web podria resultar ser molesta o compleja para algunos usuarios con movilidad reducida, una opcion seria redistribuir algunas opciones como donde colocar el carrito de compra.


## Fase 3: Dimensión de Gobernanza y Ética (G)

### 1. Transparencia. ¿Es fácil rechazar las cookies no esenciales o utilizan "patrones oscuros" (Dark Patterns) para forzar al usuario a aceptarlas?

<img width="896" height="616" alt="Captura de pantalla 2026-05-06 134936" src="https://github.com/user-attachments/assets/e3b37d7f-2a5f-491b-975c-63f158c71992" />

La web te permite navegar por ella solo usando las cookies imprescindibles, te da la opción de aceptarlas todas incluidas las opcionales, en este caso no hay Dark patterns.

### 2. Datos innecesarios. ¿Pide la web datos personales excesivos en su formulario de contacto o registro?

<img width="747" height="748" alt="Captura de pantalla 2026-05-06 135512" src="https://github.com/user-attachments/assets/3878e4b8-12ca-4fcf-9d20-37c33b93b1a1" />

No hay datos personales excesivos o innecesarios, tal vez la direccion pero puede ser por si deseas pedir algun producto desde tu casa.






  


