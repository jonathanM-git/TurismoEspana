# Proyecto: Turismo España

## Descripción
Este proyecto es una página web responsiva desarrollada en **HTML** y **SCSS**, que se convierte en **CSS** utilizando el comando `watch`. La página permite explorar diferentes aspectos del turismo en España, incluyendo arte y cultura, turismo urbano, naturaleza, gastronomía y enología. Además, implementa un sistema de cambio de tema claro y oscuro según la configuración del navegador.

## Estructura del Proyecto
La estructura del proyecto se organiza de la siguiente manera:
```
TurismoEspaña/
│── clases/
│   ├── index.html
│   ├── arteCultura.html
│   ├── turismoUrbano.html
│   ├── naturaleza.html
│   ├── gastronomiaEnologia.html
│   ├── formulario.html
│
│── assets/
│   ├── css/
│   │   ├── index.css
│   │   ├── arteCultura.css
│   │   ├── turismoUrbano.css
│   │   ├── naturaleza.css
│   │   ├── gastronomiaEnologia.css
│   │   ├── formulario.css
│   │   ├── styles.css
│   │
│   ├── scss/
│   │   ├── index.scss
│   │   ├── arteCultura.scss
│   │   ├── turismoUrbano.scss
│   │   ├── naturaleza.scss
│   │   ├── gastronomiaEnologia.scss
│   │   ├── formulario.scss
│   │   ├── styles.scss
│
│── img/ (Contiene las imágenes utilizadas en el sitio web)
│── js/ (Archivos JavaScript, incluyendo Bootstrap)
│── README.md (Este archivo)
```

## Tecnologías Utilizadas
- **HTML5**
- **SCSS** (convertido a CSS con `watch`)
- **Bootstrap 5**
- **Font Awesome**
- **JavaScript**

## Instalación y Uso
### 1. Clonar el Repositorio
```bash
git clone https://github.com/jonathanM-git/TurismoEspana.git
cd TurismoEspana
```

### 2. Instalar Dependencias (Opcional)
Si deseas modificar los estilos SCSS, asegúrate de tener instalado **Sass**:
```bash
npm install -g sass
```

### 3. Compilar SCSS a CSS
Para que los archivos SCSS se conviertan en CSS de forma automática, ejecuta:
```bash
sass --watch assets/scss:assets/css
```

### 4. Ejecutar el Proyecto
Simplemente abre el archivo `index.html` en tu navegador o utiliza un servidor local como Live Server en VS Code.

## Funcionalidades
- **Diseño Responsivo**: Adaptado a distintos dispositivos.
- **Modo Claro/Oscuro**: Se ajusta según la configuración del navegador.
- **Navegación Intuitiva**: Diferentes secciones organizadas en el menú.
- **Bootstrap Integrado**: Mejora el diseño y la interactividad.

## Descripción de las Páginas
Resumen de las páginas del proyecto:

1. **Página de Inicio (`index.html`)**: Presenta el sitio con imágenes destacadas y enlaces a secciones clave.
2. **Arte y Cultura (`arteCultura.html`)**: Muestra obras y lugares culturales con imágenes y videos.
3. **Turismo Urbano (`turismoUrbano.html`)**: Explora sitios icónicos con videos y un carrusel de provincias.
4. **Naturaleza (`naturaleza.html`)**: Destaca paisajes y actividades al aire libre con imágenes y descripciones.
5. **Gastronomía (`gastronomia.html`)**: Presenta platos típicos, recomendaciones y experiencias gastronómicas.
6. **Formulario de Registro (`formulario.html`)**: Permite a los usuarios suscribirse para recibir información turística personalizada.

## Principales Características de los Estilos
- Uso de variables para colores y estilos.  
- Mixins para reutilización de código.  
- Diseño modular y escalable.  
- Estructura clara con separación de estilos globales y específicos.  

## Tema Oscuro / Claro
El proyecto soporta modo oscuro y claro mediante `prefers-color-scheme`, ajustando colores de fondo, texto y otros elementos visuales.  

## Recursos Gráficos
- Imágenes y videos de fondo.  
- Carruseles interactivos con transiciones suaves.  
- Uso de sombras y efectos de escala en imágenes.  

## Responsive Design
- Uso de `flexbox` y `grid` para adaptabilidad.  
- Diseño optimizado para distintos tamaños de pantalla.  

## Consideraciones Generales
- Se han aplicado buenas prácticas en la estructura SCSS.  
- Se usa `@use` para la importación de módulos.  
- Código organizado para facilitar la mantenibilidad y escalabilidad.  


## Contribución
Si deseas contribuir, sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una rama con tu nueva funcionalidad (`git checkout -b nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Agrega nueva funcionalidad'`).
4. Sube tus cambios (`git push origin nueva-funcionalidad`).
5. Abre un Pull Request.

## Autor
Desarrollado por **[Jonathan Mínguez]**.
Asignatura **[Desarrollo de interfaces]**.  

## Licencia
Este proyecto está bajo la licencia MIT.

