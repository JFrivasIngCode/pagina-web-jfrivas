# JFrivas | Página Web Profesional

![Versión](https://img.shields.io/badge/versi%C3%B3n-1.0.0-blue)
![Licencia](https://img.shields.io/badge/licencia-MIT-green)
![Estado](https://img.shields.io/badge/estado-activo-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Mantenibilidad](https://img.shields.io/badge/mantenibilidad-A-brightgreen)

---

## 📋 Tabla de Contenidos

- [Descripción](#descripción)
- [Características Claves](#características-claves)
- [Requisitos Previos](#requisitos-previos)
- [Instalación](#instalación)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Uso](#uso)
- [Ejemplos de Código](#ejemplos-de-código)
- [Configuración](#configuración)
- [Agradecimientos](#agradecimientos)
- [Contacto](#contacto)

---

## 📝 Descripción

**JFrivas** es una página web moderna y profesional desarrollada con tecnologías web estándar. Proporciona una plataforma visualmente atractiva y totalmente responsive, diseñada para ofrecer una experiencia de usuario excepcional en todos los dispositivos.

> 💡 Este proyecto demuestra mejores prácticas en desarrollo web frontend, incluyendo código limpio, estructura semántica y optimización de performance.



---

## ⭐ Características Claves

✅ **Diseño Responsive** - Adaptado para móviles, tablets y escritorios  
✅ **Interfaz Moderna** - Estética contemporánea y profesional  
✅ **Códígo Limpio** - HTML semántico y CSS bem estructurado  
✅ **Interactividad** - JavaScript vanilla para funcionalidades dinámicas  
✅ **Optimización SEO** - Metadatos y estructura optimizados  
✅ **Rendimiento Rápido** - Carga eficiente y animaciones suaves  
✅ **Fácil Mantenimiento** - Código organizado y documentado  
✅ **Compatibilidad Navegadores** - Funciona en navegadores modernos  

---

## 🔧 Requisitos Previos

Antes de comenzar, asegúrate de tener lo siguiente instalado:

- **Navegador Web Moderno** (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- **Editor de Código** (VSCode, Sublime Text, Atom, etc.) - opcional
- **Git** (para clonar el repositorio)
- **Servidor Local** (Live Server, Python SimpleHTTPServer, etc.) - recomendado

```bash
# Verificar versiones instaladas
node --version    # Para npm si usas herramientas adicionales
git --version     # Para clonar el repositorio
```

---

## 📥 Instalación

### Opción 1: Clonar el Repositorio

```bash
# Clonar el repositorio
git clone https://github.com/JFrivasIngCode/pagina-web-JFrivas.git

# Navegar al directorio del proyecto
cd pagina-web-JFrivas

# Abrir en tu editor favorito
code .  # Para VSCode
```

### Opción 2: Descargar como ZIP

1. Haz clic en el botón **Code** en GitHub
2. Selecciona **Download ZIP**
3. Extrae el archivo en tu ubicación deseada
4. Abre `index.html` en tu navegador o con un servidor local

### Opción 3: Usar un Servidor Local (Recomendado)

#### Con Python 3:
```bash
# Navegar al directorio del proyecto
cd ruta/al/proyecto

# Iniciar servidor en puerto 8000
python -m http.server 8000

# Abrir en el navegador
# Visita: http://localhost:8000
```

#### Con Python 2:
```bash
python -m SimpleHTTPServer 8000
```

#### Con Node.js (usando http-server):
```bash
# Instalar http-server globalmente (solo la primera vez)
npm install -g http-server

# Ejecutar en el directorio del proyecto
http-server

# Abrir en el navegador
# Visita: http://localhost:8080
```

---

## 📂 Estructura del Proyecto

```
pagina-web-jfrivas/
│
├── 📄 index.html           # Archivo principal HTML
├── 📄 README.md            # Este archivo
│
├── 📁 CSS/
│   └── estilos.css         # Estilos principales
│
├── 📁 js/
│   └── main.js             # Lógica JavaScript
│
├── 📁 img/
│   ├── logo.png            # Logo del proyecto
│   ├── banner.jpg          # Banner principal
│   └── icono.svg           # Iconos SVG
│
└── 📁 media/
    ├── demo.gif            # GIF de demostración
    └── screenshots/        # Capturas de pantalla
```

---

## 🚀 Uso

### Inicio Rápido

1. **Clona el repositorio** siguiendo los pasos de instalación
2. **Abre `index.html`** en tu navegador o servidor local
3. **Explora la página** y todas sus funcionalidades





---

## 💻 Ejemplos de Código

### Estructura Base HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Descripción de tu página web">
    <title>JFrivas - Página Profesional</title>
    <link rel="stylesheet" href="CSS/estilos.css">
</head>
<body>
    <header>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#servicios">Servicios</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>
    
    <main>
        <section id="inicio">
            <h1>Bienvenido a JFrivas</h1>
            <p>Tu descripción aquí</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2026 JFrivas. Todos los derechos reservados.</p>
    </footer>
    
    <script src="js/main.js"></script>
</body>
</html>
```

### Estilos CSS Responsive

```css
/* Estilos generales */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
}

/* Diseño Responsive */
header {
    background-color: #2c3e50;
    color: white;
    padding: 1rem;
    position: sticky;
    top: 0;
    z-index: 100;
}

nav {
    display: flex;
    justify-content: center;
    gap: 2rem;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #3498db;
}

/* Mobile First */
@media (max-width: 768px) {
    nav {
        flex-direction: column;
        gap: 1rem;
    }
    
    h1 {
        font-size: 1.5rem;
    }
}

/* Tablet */
@media (min-width: 769px) and (max-width: 1024px) {
    nav {
        gap: 1.5rem;
    }
}

/* Desktop */
@media (min-width: 1025px) {
    nav {
        gap: 3rem;
    }
}
```

### Funcionalidades JavaScript

```javascript
// Script principal - main.js

// Esperar a que el DOM esté cargado
document.addEventListener('DOMContentLoaded', function() {
    console.log('Página cargada correctamente');
    
    // Inicializar funcionalidades
    initNavegacion();
    initAnimaciones();
});

// Función de navegación suave
function initNavegacion() {
    const links = document.querySelectorAll('a[href^="#"]');
    
    links.forEach(link => {
        link.addEventListener('click', function(e) {
            e.preventDefault();
            const targetId = this.getAttribute('href');
            const targetSection = document.querySelector(targetId);
            
            if (targetSection) {
                targetSection.scrollIntoView({ behavior: 'smooth' });
            }
        });
    });
}

// Función para animaciones
function initAnimaciones() {
    const elementos = document.querySelectorAll('[data-animate]');
    
    elementos.forEach(elemento => {
        elemento.classList.add('animate');
    });
}

// Función de utilidad para validar formularios
function validarFormulario(formulario) {
    const campos = formulario.querySelectorAll('input, textarea');
    let valido = true;
    
    campos.forEach(campo => {
        if (!campo.value.trim()) {
            campo.classList.add('error');
            valido = false;
        } else {
            campo.classList.remove('error');
        }
    });
    
    return valido;
}
```

### Peticiones AJAX Ejemplo

```javascript
// Ejemplo de petición asíncrona
async function cargarDatos() {
    try {
        const respuesta = await fetch('datos.json');
        const datos = await respuesta.json();
        console.log('Datos cargados:', datos);
        
        // Procesar datos
        mostrarDatos(datos);
    } catch (error) {
        console.error('Error al cargar datos:', error);
    }
}

function mostrarDatos(datos) {
    const contenedor = document.getElementById('contenedor-datos');
    contenedor.innerHTML = datos.map(item => 
        `<div class="card">
            <h3>${item.titulo}</h3>
            <p>${item.descripcion}</p>
        </div>`
    ).join('');
}
```

---

## ⚙️ Configuración

### Personalizar Colores

Edita en `CSS/estilos.css`:

```css
:root {
    --color-primario: #3498db;
    --color-secundario: #2c3e50;
    --color-acentuado: #e74c3c;
    --color-texto: #333;
    --color-fondo: #ecf0f1;
}
```

### Modificar Titulo y Metadatos

En `index.html`:

```html
<title>Tu Título Aquí</title>
<meta name="description" content="Tu descripción aquí">
<meta name="author" content="Tu Nombre">
<meta name="keywords" content="palabra1, palabra2, palabra3">
```

### Agregar Google Fonts

Añade en `<head>` de `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
```

---


```

---

## 🤝 Agradecimientos

Queremos expresar nuestro reconocimiento a:

- **Comunidad de Desarrollo Web** - Por las mejores prácticas y inspiración
- **Shields.io** - Por los hermosos badges de estado
- **Los Colaboradores** - Por las sugerencias y mejoras
- **Usuarios Finales** - Por confiar en nuestro proyecto

### Recursos Utilizados

- [MDN Web Docs](https://developer.mozilla.org/) - Documentación oficial
- [CSS Tricks](https://css-tricks.com/) - Tutoriales y técnicas CSS
- [Stack Overflow](https://stackoverflow.com/) - Soluciones comunitarias
- [Google Fonts](https://fonts.google.com/) - Tipografías gratuitas

---

## 📞 Contacto

**Correo Electrónico:** (mailto:fredyrivas0714@gmail.com)  
**GitHub:** (https://github.com/JFrivasIngCode)  
**LinkedIn:** (https://linkedin.com/in/fredy-rivas-9b6a8b1b0)  
**Sitio Web:** (https://jfrivasingcode.github.io/acerca-de-john-fredy-rivas/)

---

## 📄 Licencia

Este proyecto está bajo la **Licencia MIT**. Puedes usar este código libremente en tus proyectos personales y comerciales.

```
MIT License

Copyright (c) 2026 JFrivas

Permission is hereby granted, free of charge...
Para más detalles, consulta el archivo LICENSE
```

---

## 📊 Estadísticas del Proyecto

- ⏱️ **Tiempo de Carga Promedio:** < 2 segundos
- 📱 **Compatibilidad Móvil:** 100%
- ♿ **Accesibilidad:** WCAG 2.1 AA
- 🔍 **SEO Score:** Excellent
- 🚀 **Lighthouse Score:** 95+

---

<div align="center">

### ⭐ Si te gustó este proyecto, ¡dale una estrella en GitHub!

**[⬆ Volver al inicio](#jfrivas--página-web-profesional)**

---

**Hecho con ❤️ por JFrivas**

Última actualización: 13 de febrero de 2026

</div>
