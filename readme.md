# LUMIA Estudio - Sitio Web de Diseño de Interiores

![LUMIA Estudio](https://img.shields.io/badge/LUMIA-Estudio%20de%20Diseño-c9a96e)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Sitio web profesional para un estudio de diseño de interiores de lujo. Diseño elegante, moderno y totalmente responsive.

## 📁 Estructura del Proyecto
```bash

lumia-estudio/
│
├── index.html
├── proyectos.html
├── blog.html
├── contacto.html
│
├── proyectos/
│   ├── atico-moderno.html
│   ├── loft-industrial.html
│   └── restaurante-soho.html
│
├── blog/
│   ├── tendencias-diseno-2024.html
│   ├── iluminacion-perfecta.html
│   ├── materiales-sostenibles.html
│   └── ... (más artículos)
│
├── css/
│   └── style.css
│
├── js/
│   └── main.js
│
└── img/
    └── ...
│
└── README.md # Documentación del proyecto
```


## 🎨 Características

### Diseño
- **Estética de lujo**: Paleta de colores sofisticada con tonos dorados y azul marino
- **Tipografía elegante**: Playfair Display para títulos, Inter para cuerpo de texto
- **Animaciones suaves**: Transiciones y efectos hover profesionales
- **Totalmente responsive**: Adaptado a móviles, tablets y escritorio
- **Placeholders elegantes**: Gradientes con iconos mientras se añaden imágenes reales

### Funcionalidades
- **Menú de navegación premium**: Con barra superior de contacto y efectos hover
- **Sistema de proyectos**: Páginas individuales para cada proyecto con detalles completos
- **Filtros de proyectos**: Sistema de filtrado por categorías
- **Newsletter**: Formulario de suscripción en el footer
- **SEO optimizado**: Meta tags, descripciones y estructura semántica
- **Rendimiento**: Código limpio y optimizado

### Secciones
1. **Hero Section**: Impactante primera impresión con llamada a la acción
2. **Filosofía**: Valores y principios del estudio
3. **Servicios**: Residencial, comercial y consultoría
4. **Proyectos Destacados**: Grid con los mejores trabajos
5. **Proceso de Trabajo**: Timeline con la metodología
6. **Testimonios**: Valoraciones de clientes
7. **CTA Final**: Llamada a la acción para consultoría
8. **Footer Premium**: Con navegación, contacto y newsletter

## 🚀 Instalación y Uso

### Requisitos previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (recomendado: VS Code)
- Conocimientos básicos de HTML/CSS/JS (para personalización)

### Instalación local

1. **Clona o descarga el proyecto**
```bash
git clone https://github.com/tu-usuario/lumia-estudio.git
# o descarga el ZIP y extrae los archivos
```
2. **Estructura de carpetas**

```bash
cd lumia-estudio
```
# Asegúrate de tener la estructura de carpetas correcta

Abre el proyecto


# Opción 1: Abrir directamente
```bash
open index.html
```

# Opción 2: Usar un servidor local (recomendado)
# Con Python 3
```bash
python -m http.server 8000
```

# Con Node.js (usando http-server)
```bash
npx http-server
```

# Con PHP
```bash
php -S localhost:8000
```

## Accede al sitio
```bash
http://localhost:8000
```
## 🎨 Personalización
# Cambiar colores
Edita las variables CSS en css/style.css:
```bash
css
:root {
    --primary-color: #1a1a2e;      /* Color principal */
    --secondary-color: #c9a96e;    /* Color dorado/accento */
    --accent-color: #a0522d;       /* Color terciario */
}
```
# Añadir imágenes reales
Reemplaza los placeholders en los HTML:

```bash
html
<!-- Reemplazar esto -->
<div class="proyecto-imagen-placeholder" style="background: linear-gradient(...)">
    <i class="fas fa-home"></i>
</div>

<!-- Por esto -->
<img src="img/tu-imagen.jpg" alt="Descripción">
```
# Modificar contenido
Textos: Edita los textos directamente en los archivos HTML

Proyectos: Añade nuevos proyectos en proyectos/ siguiendo la estructura

Contacto: Actualiza email, teléfono y dirección en contacto.html

# Añadir nuevo proyecto
Crea un nuevo archivo en proyectos/nombre-proyecto.html

Copia la estructura de atico-moderno.html

Personaliza el contenido

Añade la tarjeta en proyectos.html y index.html

# 📱 Responsive Design
El sitio se adapta a diferentes dispositivos:

Móvil (< 768px): Menú hamburguesa, columnas apiladas

Tablet (768px - 1024px): Grid de 2 columnas

Escritorio (> 1024px): Diseño completo con grid de 3-4 columnas

# 🔧 Tecnologías Utilizadas
HTML5: Estructura semántica

CSS3:

Grid y Flexbox para layouts

Variables CSS para tematización

Animaciones y transiciones

Media queries para responsive

JavaScript:

Intersection Observer para animaciones

Menú móvil interactivo

Efectos de scroll

Filtros de proyectos

Font Awesome 6: Iconografía profesional

Google Fonts: Playfair Display e Inter

# 📊 SEO y Rendimiento
Meta tags implementados
Title y description únicos por página

Open Graph para redes sociales

Estructura semántica HTML5

URLs amigables

Optimizaciones
CSS y JS externos para mejor caché

Imágenes con lazy loading

Fuentes optimizadas con font-display

Sin dependencias pesadas

# 🎯 Próximas Mejoras
Página de Blog con artículos

Galería de imágenes con lightbox

Formulario de contacto funcional

Integración con redes sociales

Panel de administración

Versión multilingüe

Animaciones más avanzadas con GSAP

# 📝 Licencia
Este proyecto es de uso libre para fines educativos y personales. Para uso comercial, por favor contacta con el autor.

# 👤 Autor
LUMIA Estudio de Diseño

Website: www.lumiaestudio.com

Email: info@lumiaestudio.com

Instagram: @lumiaestudio

⌨️ con ❤️ por LUMIA Estudio