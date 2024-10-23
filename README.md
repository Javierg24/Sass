# Proyecto Sass - Sección de Servicios Responsiva

Este proyecto demuestra el uso de **Sass** para crear una sección de servicios responsiva en una página web. Utilizamos variables, mixins y media queries para facilitar la gestión de los estilos y mejorar la legibilidad del código.

## Estructura del Proyecto
El proyecto está organizado en las siguientes carpetas:

- `/scss`: Aquí se encuentra el archivo fuente de Sass (`styles.scss`).
- `/css`: Contiene el archivo CSS compilado (`styles.css`).
- `/img`: Incluye los iconos que se muestran en la sección de servicios.
- `index.html`: Archivo HTML que simula la página web para ver el resultado.
- `servicios.html`: Archivo HTML que simula la página web para ver el resultado.
- `README.md`: Este documento explicativo.

## Uso de Sass
### 1. Variables
Utilizamos variables para definir los colores principales, las fuentes y otros estilos reutilizables en todo el proyecto.

### 2. Mixins
Creamos mixins para los botones reutilizables y para la estructura de columnas, lo que nos permite aplicar estos estilos de forma consistente en todo el proyecto.

### 3. Media Queries
Se utilizan media queries para que el diseño sea completamente responsivo, adaptando el número de columnas según el tamaño de la pantalla.

## Compilación
Para compilar el archivo `.scss` a `.css`, ejecuta el siguiente comando:

```bash
sass scss/styles.scss css/styles.css

