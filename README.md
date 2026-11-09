# Natural Soap — Bilingual Product Website

**Bilingual project documentation / Documentación bilingüe**

## English

### Overview

Natural Soap is a static, multi-page website concept for an artisanal soap brand. It combines a product catalogue, brand information and educational content in a responsive interface. The site includes Spanish and English language options.

**Live website:** https://jeremy-megajs.github.io/natural-soap/  
**Source code:** https://github.com/Jeremy-MegaJS/natural-soap

### My contribution

Designed and developed independently by Jeremy Torres. The work covers the page structure, styling, client-side interactions, language switching and the presentation of the product catalogue.

### Main features

- Landing page with brand introduction and product highlights.
- Product catalogue with individual products and bundle examples.
- About page with brand and process information.
- Spanish / English language switching.
- Responsive navigation and page layouts.
- Additional educational content about environmental topics.
- WhatsApp contact / order entry points configured in the client-side scripts.

### Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- Font Awesome
- GitHub Pages

### Project structure

```text
natural-soap/
├── index.html
├── productos.html
├── sobre-nosotros.html
├── secret-es.html
├── assets/
│   ├── css/
│   └── js/
├── img-sources/
└── sitemap.xml
```

### Run locally

From the repository root, start a static server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

The website is static. It does not include a server-side application, database, payment processor or integrated checkout. Product and contact actions are handled through links and client-side JavaScript.

### Deployment

The public version is hosted with GitHub Pages from this repository. Changes pushed to the configured publishing branch are deployed through the repository's Pages workflow.

### Scope and responsible use

This repository is a web-development portfolio project. Product descriptions, prices, availability and contact destinations are website content and should be verified by the business before being used for real commercial operations. The presence of a WhatsApp action does not mean that the website processes payments or manages orders.

---

## Español

### Descripción general

Natural Soap es un concepto de sitio web estático de varias páginas para una marca de jabones artesanales. Combina un catálogo de productos, información de marca y contenido educativo en una interfaz adaptable. El sitio incluye opciones de idioma español e inglés.

**Sitio web:** https://jeremy-megajs.github.io/natural-soap/  
**Código fuente:** https://github.com/Jeremy-MegaJS/natural-soap

### Mi aporte

Diseñado y desarrollado individualmente por Jeremy Torres. El trabajo abarca la estructura de las páginas, los estilos, las interacciones del lado del cliente, el selector de idioma y la presentación del catálogo.

### Funcionalidades principales

- Página de inicio con presentación de la marca y productos destacados.
- Catálogo con productos individuales y ejemplos de paquetes.
- Página «Sobre nosotros» con información de marca y proceso.
- Selector de idioma español / inglés.
- Navegación y diseño de páginas adaptables.
- Contenido educativo adicional sobre temas ambientales.
- Accesos de contacto y pedidos mediante WhatsApp configurados en los scripts del cliente.

### Tecnologías

- HTML5
- CSS3
- JavaScript puro
- Google Fonts
- Font Awesome
- GitHub Pages

### Estructura del proyecto

```text
natural-soap/
├── index.html
├── productos.html
├── sobre-nosotros.html
├── secret-es.html
├── assets/
│   ├── css/
│   └── js/
├── img-sources/
└── sitemap.xml
```

### Ejecución local

Desde la raíz del repositorio, inicia un servidor estático:

```bash
python -m http.server 8000
```

Después abre `http://localhost:8000`.

El sitio es estático. No incluye una aplicación del lado del servidor, base de datos, procesador de pagos ni proceso de compra integrado. Las acciones de productos y contacto se gestionan mediante enlaces y JavaScript del lado del cliente.

### Publicación

La versión pública está alojada mediante GitHub Pages desde este repositorio. Los cambios enviados a la rama configurada para publicación se despliegan mediante el flujo de Pages del repositorio.

### Alcance y uso responsable

Este repositorio es un proyecto de desarrollo web para portafolio. Las descripciones, precios, disponibilidad y destinos de contacto son contenido del sitio y deben ser verificados por el negocio antes de utilizarlos en operaciones comerciales reales. La presencia de un acceso a WhatsApp no significa que el sitio procese pagos ni administre pedidos.
