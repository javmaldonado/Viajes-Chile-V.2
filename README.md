Crear estructura de carpetas del proyecto con ello obtengo mis carpetas assets que incluye css,img,js,sass,gitignore,Html.

Ejecutar en la terminal "npm init -y" el adminstrador de paquetes. Con ello se me genera un archivo package.json.

Instalar dependencias en este caso es Bootstrap "npm install bootstrap@5.3.3", lo que me genera un package-lock.json y node_modules (la cual debo incluir en "gitignore" para que no se suba a Github)

Integrar Bootstrap, utilizando un @import "@import "../../node_modules/bootstrap/scss/bootstrap.scss", en el archivo main.scss.

Linkear el style.css de la estructura index.html.

Compilar Sass para corroborar que se integraron correctamente "sass --watch ./assets/sass/main.scss:./assets/css/style.css" para comenzar a programar.

Agregar los componentes solicitados en la maqueta, un menu de navegacion que sea fondo transparente, se mantenga fija en la parte superior de la pantalla e incluya link a las diferentes secciones de la página.

Un carrusel que se adapte a dispositivos pequeños y dispositivos pequeños.

La seccion quienes somos debe incluir una imagen y a la derecha un texto en dispositivos grandes y la imagen desaparece en dispositivos pequeños.

Cards horizontales que pasan a una columna vertical en dispotivos pequeños.

Crear una seccion Testimonio 

Una seccion de contacto que incluya un formulario al lado izquierdo y datos al derecho, en vertical en dispositivos pequeños.

Utilizar componentes JavaScript, tooltips en formulario, modal en terminos y condiciones,alerta con un mensaje de éxito.
