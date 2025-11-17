# Sitio Web Dimigas

Sitio web moderno y profesional para Dimigas, startup argentina que transforma residuos orgánicos de PyMEs en energía limpia y fertilizante premium mediante biodigestores compactos y automatizados.

## Características

- **Diseño moderno y responsivo**: Totalmente adaptable a dispositivos móviles, tablets y desktop
- **Animaciones suaves**: Efectos de scroll y transiciones elegantes
- **Formulario de contacto**: Sistema de contacto integrado
- **Optimizado para SEO**: Metadatos y estructura semántica correcta
- **Paleta de colores corporativa**: Verde sostenibilidad + azul tecnológico

## Estructura del Sitio

### 1. Hero Section
- Titular impactante con mensaje clave
- Subtítulo descriptivo
- Call-to-action principal
- Diseño con gradiente verde corporativo

### 2. Qué Hacemos
- Explicación clara del servicio
- Beneficios destacados con íconos
- Diseño en dos columnas con visual

### 3. Problemas que Resolvemos
- Tres pilares principales:
  - Sostenibilidad Corporativa Real
  - Reducción de Costos
  - Comunicación Ambiental
- Cards interactivas con hover effects

### 4. Nuestro Valor
- Cuatro propuestas de valor:
  - Solución Llave en Mano
  - Diseño Elegante
  - Ahorro Operativo
  - Acompañamiento Estratégico
- Numeración destacada y animaciones

### 5. Sobre el Fundador
- Perfil de Francisco Olivera Whyte
- Experiencia y credenciales
- Enlace a LinkedIn
- Diseño profesional en dos columnas

### 6. Contacto
- Formulario funcional con validación
- Información de contacto
- Enlaces a redes sociales
- Diseño limpio y accesible

### 7. Footer
- Links de navegación
- Redes sociales
- Copyright e información de empresa

## Instalación

1. Descarga o clona todos los archivos del proyecto
2. Abre el archivo `index.html` en tu navegador web

No se requieren dependencias adicionales ni proceso de compilación.

## Archivos del Proyecto

```
dimigas-website/
├── index.html       # Estructura HTML del sitio
├── styles.css       # Estilos y diseño visual
├── script.js        # Interactividad y animaciones
└── README.md        # Este archivo
```

## Personalización

### Colores
Los colores principales se definen en las variables CSS al inicio de `styles.css`:

```css
:root {
    --color-primary: #2E7D32;      /* Verde principal */
    --color-primary-light: #4CAF50; /* Verde claro */
    --color-secondary: #1976D2;     /* Azul tecnológico */
    --color-accent: #7CB342;        /* Verde acento */
}
```

### Imágenes
Actualmente el sitio usa placeholders SVG. Para agregar imágenes reales:

1. Coloca tus imágenes en una carpeta `/images`
2. Reemplaza los elementos `<div class="image-placeholder">` con etiquetas `<img>`
3. Actualiza la imagen de fondo del hero section en el CSS

### Formulario de Contacto
El formulario actualmente muestra un mensaje de éxito en el frontend. Para conectarlo a un backend:

1. Descomenta el código de ejemplo en `script.js` (líneas 68-87)
2. Reemplaza `/api/contact` con tu endpoint real
3. Configura el servidor backend para recibir y procesar los datos

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Diseño responsivo con Grid y Flexbox
- **JavaScript Vanilla**: Interactividad sin dependencias
- **Google Fonts**: Tipografía Inter
- **SVG Icons**: Íconos escalables integrados

## Navegadores Compatibles

- Chrome (últimas 2 versiones)
- Firefox (últimas 2 versiones)
- Safari (últimas 2 versiones)
- Edge (últimas 2 versiones)
- Opera (últimas 2 versiones)

## Optimizaciones Realizadas

- Smooth scrolling entre secciones
- Lazy loading de animaciones con Intersection Observer
- Diseño mobile-first responsivo
- Validación de formularios en el frontend
- Performance optimizado sin librerías pesadas
- Animaciones CSS hardware-accelerated

## Próximos Pasos Recomendados

1. **Agregar imágenes reales**:
   - Foto profesional de Francisco Olivera Whyte
   - Fotos de biodigestores en acción
   - Imágenes de empresas clientes
   - Video o imagen de fondo para el hero section

2. **Integrar backend para formulario**:
   - Configurar servidor para recibir emails
   - Agregar verificación anti-spam
   - Implementar sistema de notificaciones

3. **Agregar contenido adicional**:
   - Casos de estudio
   - Testimonios de clientes
   - Blog o noticias
   - Galería de proyectos

4. **SEO y Analytics**:
   - Instalar Google Analytics
   - Agregar Meta Tags para redes sociales (Open Graph)
   - Crear sitemap.xml
   - Configurar Google Search Console

5. **Hosting**:
   - Subir a un servidor web
   - Configurar dominio www.dimigas.com.ar
   - Instalar certificado SSL (HTTPS)
   - Configurar CDN para mejor performance

## Contacto

Para más información sobre Dimigas:
- **Web**: www.dimigas.com.ar
- **LinkedIn**: [Dimigas](https://www.linkedin.com/company/dimigas/)
- **Fundador**: [Francisco Olivera Whyte](https://www.linkedin.com/in/franciscoolivera-whyte-734b3049)

---

**Copyright © 2024-2025 Dimigas. Todos los derechos reservados.**
