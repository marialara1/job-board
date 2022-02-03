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

<!-- Estructura del repositorio -->

## **SCSS**

Los archivos scss son los encargados de aportar los estilos necesarios a los elementos html, estos se encuentran organizados en la carpeta sass/.

### **Estructura del repositorio scss/**

<!-- Pendiente de revisión -->

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

#### **Espaciado**

#### **Color**

#### **Fuentes**

## **Brands**
