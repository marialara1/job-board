# **Proyecto ESAT JOBS**

## **Objetivo**

En este proyecto se pretende crear una página web de ofertas de empleo. Los usuarios puedan colgar las ofertas, acceder a las ya publicadas o postularse como candidatos.

## **Requisitos**
### **Instalación**
Puedes clonar el respositorio o descargarlo como un zip.
### **Contribuir**
Puedes crear un pull request al proyecto.

## **Programas utilizados**
El proyecto se ha construido con los siguientes programas:
- Para el diseño: 
  - <a href="https://www.figma.com/">Figma</a>: diseño de wireframes.
  - <a href="https://www.adobe.com/products/illustrator.html">Illustrator</a>: diseño de logotipo e iconos.
- Para el desarrollo: 
  - <a href="https://code.visualstudio.com/">Visual Studio Code</a>: editor de código fuente.
  - <a href="https://prepros.io/">Prepos</a>: compilador de archivos.

## **Nomenclatura**

### **Clases**

La convención de nombre para las clases de los elementos sigue el patrón BEM:

- .bloque{}
- .bloque__elemento{}
- .bloque--modificador{}

'.bloque' representa el primer nivel de una abstracción o componente, es el elemento padre.
'.bloque__elemento' representa un hijo del elemento padre '.bloque'.
'.bloque--modificador' representa un estado diferente de '.bloque'.

<!-- Ejemplo sacado del proyecto -->

### **Etiquetas archivos sass**

Para las etiquetas en los archivos sass se emplea la nomenclatura $NOMBRE, por ejemplo:

- $VARIABLES
- $CARDS

## **Estructura del respositorio del proyecto**
Para nuestro proyecto aplicaremos la metodología de ramas de Gitflow, basada en cinco palabras clave, estas determinaran la estructura de nuestro repositorio.

En primer lugar, tenderemos la rama principal llamada **Master**, donde está el código definitivo. (Es aconsejable no trabajar sobre esta rama.)

La segunda rama mas importante de nuestro repositorio será la **Develop**, donde se guardan las nuevas funcionalidades del proyecto. (Es recomendable no hacer commits directamente sobre ella, excepto cambios insignificantes como texto.)

Para el desarrollo de las nuevas funcionalidades crearemos una rama nueva que salga de la nombrada anteriormente, y la llamaremos **Feature**. Al finalizar la nueva funcionalidad la mezclamos con la rama Develop para que los cambios queden allí guardados. (Una vez mezclada estas ramas, se puede borrar la Feature.)

Es importante tener una rama llamada **Hotfix**, se encarga de solucionar los incidentes. (Esta rama debe ser generada a partir de la Master.)

Por últimos tendremos la rama **Releaes**, se utiliza para la entrega a producción o ambiente real. En ella se harán las pruebas para el cliente. (Una vez terminada la prueba si no tiene ningún fallo se mezcla con la rama Master.)

## **SCSS**

Los archivos scss son los encargados de aportar los estilos necesarios a los elementos html, estos se encuentran organizados en la carpeta sass/.

### **Estructura del repositorio scss/**

- sass/
  - style.scss
  - utilities/
    - _variables.scss
    - _functions.scss
    - _mixins.scss
  - style/
    - _typo.sass
  - htmlelements/
    - _buttons.scss
    - _tags.scss
  - structure/
    - grid.scss
  - layout/
    - _main.sass
    - _header.sass
    - _cards.sass
    - _newsletter.scss
    - _navigation.scss
    - _footer.scss
  - site/
    - _site.scss

El archivo main.sass nos indica el path de los elementos así como su nombre. Todos los archivos sass tienen una etiqueta para facilitar su localización mediante la búsqueda de nuestro editor (Cmd/Ctrl + f) y acceder a ellos fácilmente.


### **Variables**

<!-- Aquí hay que explicar como se van a usar las variables y como se van a llamar, no creo que haya que ponerlas todas aquí si no algun ejemplo que sea ejemplo de uso y se vea clara la nomenclatura -->

#### **Espaciado**

$space-unit: 6px;

#### **Color**

$color-white: #FFFFFF;
$color-black: #121212;
$color-grey: #E8E8E8;
$color-orange-esat: #EF7808;
$color-sec-violet: #7408EF;
$color-sec-turquoise: #08EFE0;

#### **Fuentes**

$font-family-main: 'Work Sans', sans-serif;
$font-family-sec: 'Poppins', sans-serif;

$font-size-title:

## **Brands**
