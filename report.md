# Informe del Proyecto web multipágina

## Enlace de repositorio GitHub

https://github.com/USUARIO/REPO-ACTUALIZAR

## Carátula

**Título:** ChullaCine

**Autor:** Diego Montesdeoca

**Unidad:** 1

**Curso:** Diseño y Desarrollo Web Básico

## Descripción general del proyecto

El proyecto es un sitio web multipágina llamado ChullaCine, diseñado como la página online de un cine local.
El sitio muestra la cartelera, describe la idea del cine, incluye un formulario de contacto con método GET y organiza la información en páginas con rutas relativas.

## Estructura de carpetas

- `index.html` - Página principal con la presentación del cine y navegación.
- `about.html` - Página con la explicación del proyecto y la estructura del sitio.
- `services.html` - Página de cartelera con películas, horarios y descripciones.
- `contact.html` - Página de contacto con formulario GET, tabla de horarios y datos de atención.
- `css/styles.css` - Estilos del sitio con paleta de colores y tipografía cinematográfica.
- `images/` - Ilustraciones SVG relacionadas con cine y entretenimiento.
- `package.json` - Configuración para generar el informe PDF.
- `.gitignore` - Archivos excluidos del control de versiones.

## Descripción de cada página

### Inicio (`index.html`)
- Presenta ChullaCine, su propósito y la navegación hacia otras páginas.
- Usa un héroe principal con llamada a la acción, lista de características y una imagen temática.
- Contiene enlaces relativos que conectan con `about.html`, `services.html` y `contact.html`.

### Acerca (`about.html`)
- Explica la idea del sitio y cómo fue pensado el proyecto.
- Incluye etiquetas semánticas como `article`, `aside` y `section`.
- Describe la estructura de carpetas y la lógica de diseño.

### Cartelera (`services.html`)
- Muestra películas destacadas en formato de tarjetas.
- Presenta horarios y beneficios de cada función.
- Utiliza imágenes, listas y texto semántico para cada opción.

### Contacto (`contact.html`)
- Contiene un formulario de consulta con método `GET`.
- Incluye campos de nombre, correo, película y mensaje.
- Añade una tabla de horarios y datos de contacto del cine.

## Imágenes utilizadas

- `images/hero.svg`
- `images/services.svg`
- `images/about.svg`
- `images/contact.svg`

Estas ilustraciones acompañan el diseño de un cine y ayudan a reforzar la identidad de ChullaCine.

## Capturas de pantalla y evidencia de versionamiento

Toma capturas de pantalla desde el navegador al abrir cada página:
- `index.html`
- `about.html`
- `services.html`
- `contact.html`

El proyecto ya tiene un repositorio Git inicializado en la carpeta local. Para completar el versionamiento, sube los archivos al repositorio GitHub y conserva el historial antes de la entrega.

## Notas adicionales

- El formulario de contacto usa `method="get"`, acorde con el contenido visto en la Unidad 1.
- El sitio está estructurado con HTML semántico, rutas relativas, navegación funcional, tipografía, colores y fondo.
- Se añadió una presentación realista de un cine local dividido en páginas con funciones específicas.
