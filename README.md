# 👩🏻‍💻 Práctica HTML5 + CSS3 (Portfolio)

> 👤 Marta Vilaseca Foradada  
> 💻 XVI Bootcamp Full Stack Web  
> 📅 28 Enero 2024

## 🌳 There and back again - the Bilbo Baggins portfolio

Para la práctica he decidido crear un portfolio de uno de mis personajes ficticios favoritos, **Bilbo Baggins** (_Bilbo Bolsón_ en la traducción española) de los libros y películas de _El Hobbit_ y _El Señor de los Anillos_.

### ✅ Requisitos obligatorios

- Siguiendo las indicaciones recibidas, **no se ha utilizado Javascript ni librerías CSS externas en toda la práctica**
- Diversas hojas de estilo CSS, debidamente etiquetadas según su función o el apartado/sección al que corresponden
- Se ha comprobado que la página de visualice correctamente en las versiones actuales de **Google Chrome**, **Mozilla Firefox** y **Microsoft Edge**
- Se han tenido en cuenta las etiquetas HTML de contenido semnántico
- La web se ha maquetado siguiendo la estrategia _mobile first_

### 📃 Sección por sección

| Archivos comunes o generales css |                                                                                                                     |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| [common.css](./css/common.css)   | Estilos comunes y definición de variables                                                                           |
| [reset.css](./css/reset.css)     | Reset sencillo ([referencia](https://twitter.com/midudev/status/1747273887703044418?t=q_NWcWtS4M8OyfTyNiTO1w&s=33)) |

#### Header [[header.css]](./css/header.css)

- Presente en [index.html](./index.html) y en [proyectos.html](./proyectos.html) con las modificaciones de enlaces pertinentes
- Barra de navegación con enlaces a cada elemento del portfolio, visible sólo en versión no móvil
- Dichos enlaces tienen un efecto hover sencillo de cambio de color y aparición de una pastilla de color de fondo al hacer hover, suavizada con una transición
- **<span style="color: goldenrod">OPCIONAL:</span>** menú burger con solo CSS y un input checkbox, activo sólo en versiones móbil. Dadas las limitaciones de usar sólo CSS, es necesario volver a clicar manualmente en el menú para cerrarlo una vez abierto.

#### Sección About + Sección Skills [[about.css]](./css/about.css), [[skills.css]](./css/skills.css)

- Con una descripción sobre el personaje y un listado de habilidades mostradas en forma de barras de progreso
- Dichas barras de progreso están animadas con CSS (la animación se ejecuta una sola vez al cargarse la página)

#### Banner con imagen de fondo [[banner.css]](./css/banner.css)

- Con distintas imágenes y proporciones de tamaño para el mismo, en función de cada resolución

#### Formulario de Contacto [[form.css]](./css/form.css)

- Con los campos requeridos **Nombre**, **Apellidos**, **Teléfono** (con validación de formato), **Tag de github** (con validación de formato) y **Mensaje** (textarea)
- Con los campos opcionales **¿Cómo me conociste?** y **Acceso a newsletter** (checkbox)
- Y los dos botones **Enviar/Guardar** y **Reset**

#### Footer [[footer.css]](./css/footer.css)

- Presente en [index.html](./index.html) y en [proyectos.html]
- Enlaces a cuentas oficiales relacionadas (con _El Hobbit_ y los decorados de las películas como destino turístico) en **Facebook**, **Twitter/X**, **Instagram** y **Youtube**
- Con el añadido de un enlace extra (de aspecto ligeramente distinto en versión móvil y la no móvil) para volver arriba del todo de la página

#### Video + Proyectos [[video.css]](./css/video.css), [[projects.css]](./css/projects.css)

- Ambas cosas en una nueva página que carga un vídeo (el primer trailer promocional de la primera película de la trilogía _El Hobbit_), con efecto fade in y autoreproducción
- El listado de proyectos se ha hecho en forma de grid, siguiendo las capturas de ejemplo para el diseño
- La cuadrícula tiene dos columnas, tres o cuatro en función de la resolución del dispositivo

#### <span style="color: goldenrod">OPCIONAL:</span> Páginas de error [[e404.css]](./css/e404.css), [[e500.css]](./css/e500.css)

- Páginas de [error de recurso no encontrado](./404.html) y [de error interno de servidor](./500.html), de libre diseño y con sus correspondientes hojas de estilo css (cada una con ligeros ajustes para hacerlas responsive)
