Instagram Photo Feed con Bootstrap

Este proyecto consiste en la creación de un Instagram Photo Feed utilizando HTML5, Bootstrap y JavaScript, tomando como base la plantilla HTML Hello proporcionada por 4Geeks Academy.

El objetivo fue reproducir la estructura y funcionalidades principales de un feed de Instagram mediante componentes de Bootstrap.

📦 Plantilla utilizada

El proyecto comenzó a partir de la plantilla HTML Hello de 4Geeks Academy.

Esta plantilla proporciona una estructura básica para comenzar un proyecto web desde cero y permite trabajar con archivos HTML, CSS y un servidor local mediante Flask.

A partir de esta base desarrollamos nuestro propio proyecto, agregando la estructura visual y las funcionalidades necesarias para crear el Instagram Photo Feed.

🛠️ Tecnologías utilizadas
HTML5 — estructura y contenido de la página.
Bootstrap 5.3.8 — diseño, grid, componentes y clases utilitarias.
Bootstrap Icons — iconos utilizados en la interfaz.
JavaScript — interacción para cambiar entre las vistas del feed.
Flask — servidor local para visualizar el proyecto.
Git — control de versiones.
GitHub — almacenamiento y sincronización del repositorio.
📱 Componentes implementados
Navbar

Se creó una barra de navegación utilizando componentes y clases de Bootstrap.

Incluye:

Icono de Instagram.
Nombre del proyecto.
Botón Create a new post.
Menú desplegable de configuración.
Grid de fotografías

Se creó una vista en formato cuadrícula utilizando el sistema Bootstrap Grid.

Las fotografías se organizan en:

3 imágenes por fila.
Columnas utilizando .col-4.
Espaciado utilizando .g-2.
Imágenes cuadradas mediante .ratio.ratio-1x1.
Imágenes adaptables mediante .img-fluid.
Recorte de imágenes utilizando .object-fit-cover.
Vista de publicaciones individuales

Se creó una segunda vista donde cada publicación aparece individualmente en formato de tarjeta.

Cada publicación contiene:

Título.
Fecha.
Imagen.
Cantidad de likes.
Descripción.

Para organizar esta vista se utilizaron componentes como:

.card
.row
.col-12
.col-md-8
.col-lg-6

Esto permite que el contenido tenga diferentes anchos dependiendo del tamaño de la pantalla.

Cambio entre vistas

Se implementaron dos botones para cambiar entre:

Vista Grid
Vista de publicaciones individuales

JavaScript controla la visibilidad de cada sección utilizando las clases de Bootstrap:

d-none

Cuando se selecciona una vista, JavaScript agrega o elimina esta clase para mostrar u ocultar el contenido correspondiente.

Modal para crear una publicación

Se implementó un Modal de Bootstrap para simular la creación de una nueva publicación.

Incluye:

Campo para escribir el caption.
Icono de cámara.
Icono de ubicación.
Botón Close.
Botón Publish.

El botón Publish solamente forma parte de la interfaz visual, ya que este ejercicio no requiere guardar información en una base de datos ni implementar un backend para las publicaciones.

Dropdown

Se implementó un menú desplegable utilizando el componente Dropdown de Bootstrap.

Incluye:

Profile
Accessibility
Privacy and Data
Log out

También se utilizó un divisor para separar las opciones del menú.

🎨 Bootstrap Icons

Se utilizaron Bootstrap Icons para agregar iconos a la interfaz.

Entre ellos:

Instagram
Configuración
Cámara
Ubicación

Los iconos se incorporan mediante clases como:

<i class="bi bi-instagram"></i>
📚 Lo aprendido

Durante este proyecto trabajamos principalmente los siguientes conceptos:

HTML
Estructura básica de un documento HTML5.
Etiquetas semánticas.
Uso de atributos.
Enlaces a recursos externos.
Organización del contenido mediante elementos HTML.
Bootstrap

Aprendimos a utilizar:

Sistema de Grid.
Filas y columnas.
Responsive Design.
Containers.
Cards.
Navbar.
Dropdown.
Modal.
Clases utilitarias.
Espaciado.
Display.
Ratios para mantener proporciones.
Componentes reutilizables.

También aprendimos que Bootstrap permite construir interfaces utilizando clases predefinidas sin tener que crear todo el CSS desde cero.

JavaScript

Aprendimos conceptos básicos de interacción con el DOM:

getElementById()
addEventListener()
classList.add()
classList.remove()

Estos métodos permiten seleccionar elementos HTML, detectar eventos y modificar las clases de los elementos para cambiar dinámicamente la interfaz.

Entorno local

Trabajamos el proyecto localmente utilizando:

Ubuntu.
Visual Studio Code.
Python.
Flask.
Entorno virtual venv.

Utilizamos Flask para ejecutar un servidor local y visualizar el proyecto desde el navegador.

Git y GitHub

Trabajamos el flujo básico de control de versiones:

Modificar archivos
      ↓
Guardar cambios
      ↓
git status
      ↓
git add
      ↓
git commit
      ↓
git push
      ↓
GitHub

También trabajamos con:

Repositorio local.
Repositorio remoto.
origin.
Commits.
Sincronización entre Git y GitHub.
.gitignore.

El directorio venv/ se excluye mediante .gitignore porque pertenece al entorno local de Python y no debe formar parte del repositorio.

▶️ Ejecutar el proyecto localmente

Activar el entorno virtual:

source venv/bin/activate

Instalar Flask si es necesario:

pip install flask

Ejecutar el servidor:

python3 server.py

Después abrir:

http://127.0.0.1:3000
📁 Estructura principal del proyecto
4geeks-pro2-instagram-feed-bootstrap/
├── index.html
├── server.py
├── .gitignore
├── README.es.md
├── README.md
├── README.cn.md
├── learn.json
└── .vscode/

El directorio venv/ existe en el entorno local, pero está excluido del repositorio mediante .gitignore.

🎯 Resultado final

El proyecto reproduce las principales características visuales del ejercicio Instagram Photo Feed con Bootstrap:

Navbar.
Menú desplegable.
Vista Grid.
Vista de publicaciones individuales.
Cambio entre vistas.
Modal para crear una publicación.
Iconos.
Diseño responsive.
Fotografías relacionadas con escalada en roca.

El proyecto fue desarrollado desde la plantilla inicial y posteriormente construido y documentado paso a paso para comprender no solamente el resultado, sino también las herramientas y conceptos utilizados.

🔗 Repositorio

GitHub:

https://github.com/DocGus/4geeks-pro2-instagram-feed-bootstrap

🙏 Proyecto basado en 4Geeks Academy

Este ejercicio forma parte del aprendizaje de desarrollo web de 4Geeks Academy y utiliza su plantilla inicial HTML Hello como punto de partida.