# Modern Art Gallery

Landing page responsive para una galería de arte moderno, desarrollada con **HTML5, CSS3 y Sass (SCSS)**.

El proyecto consiste en la maquetación de una página web a partir de un diseño de referencia, aplicando la metodología **Mobile First** y adaptando su estructura a dispositivos móviles, tablets y ordenadores.

## Tecnologías utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## Características

- Diseño responsive mediante metodología Mobile First.
- Adaptación a dispositivos móviles, tablets y ordenadores.
- Maquetación con CSS Flexbox y CSS Grid.
- Organización modular de estilos mediante Sass.
- Uso de variables y mixins para gestionar los breakpoints.
- Estructura HTML semántica.
- Botones personalizados con iconos SVG y efectos hover.
- Imágenes adaptativas mediante `object-fit` y `background-size`.
- Navegación entre la página principal y la página de ubicación.
- Separación de estilos generales, tipografía y componentes.

## Diseño responsive

El desarrollo se ha realizado comenzando por las pantallas más pequeñas y ampliando progresivamente la distribución.

### Mobile First

Los estilos iniciales se aplican a dispositivos móviles. Mediante media queries se modifican únicamente las propiedades necesarias para las resoluciones superiores.

Para facilitar su mantenimiento, los breakpoints se centralizan mediante mixins de Sass.

## Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

Acceder al directorio:

```bash
cd modern-art-gallery
```

### 2. Instalar Sass

Es necesario disponer de Node.js y npm.

```bash
npm install --save-dev sass
```

### 3. Compilar los estilos

Ejecutar desde la raíz del proyecto:

```bash
npx sass --watch scss/style.scss css/style.css
```

### 4. Abrir el proyecto

Abrir `index.html` en el navegador, preferiblemente utilizando la extensión Live Server de Visual Studio Code.

## Objetivo del proyecto

El objetivo principal es practicar y consolidar conocimientos de maquetación frontend, especialmente:

- Transformación de diseños visuales a HTML y CSS.
- Desarrollo responsive mediante Mobile First.
- Organización de proyectos con Sass.
- Uso combinado de Flexbox y Grid.
- Reutilización de componentes y estilos.
- Mantenimiento de una estructura de código clara y escalable.

## Autor

**Jesús Espinar**

GitHub: [jesusespinardelacruz](https://github.com/jesusespinardelacruz)

---

Proyecto desarrollado como práctica de maquetación frontend con HTML5, CSS3 y Sass.
