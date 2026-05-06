# Business Agency Landing Page

## Descripción

Proyecto frontend de una landing page moderna para una agencia de negocios y consultoría llamada **Archesky**. La aplicación está enfocada en presentar servicios empresariales con una interfaz limpia, profesional y responsive.

El proyecto fue desarrollado utilizando tecnologías fundamentales del ecosistema frontend:

* HTML5
* CSS3
* JavaScript
* Webpack

La landing page busca transmitir:

* Profesionalismo
* Diseño corporativo moderno
* Claridad visual
* Experiencia de usuario intuitiva

---

# Vista General

La aplicación incluye:

* Header de navegación
* Hero section principal
* Estadísticas empresariales
* Sección de servicios
* Assets gráficos SVG optimizados
* Diseño responsive

---

# Tecnologías Utilizadas

| Tecnología | Descripción                       |
| ---------- | --------------------------------- |
| HTML5      | Estructura semántica del proyecto |
| CSS3       | Diseño visual y responsive        |
| JavaScript | Funcionalidades dinámicas         |
| Webpack    | Bundling y entorno de desarrollo  |
| SVG Assets | Optimización gráfica vectorial    |

---

# Estructura del Proyecto

```bash
business-agency-landing/
│
├── css/
│   └── style.css
│
├── img/
│   ├── logo_archesky.png
│   ├── business_planning.svg
│   ├── strategy.svg
│   ├── consulting.svg
│   └── marketing.svg
│
├── js/
│   └── app.js
│
├── index.html
├── 404.html
├── package.json
├── webpack.config.dev.js
├── webpack.config.prod.js
└── webpack.common.js
```

---

# Instalación

## 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/business-agency-landing.git
```

---

## 2. Entrar al proyecto

```bash
cd business-agency-landing
```

---

## 3. Instalar dependencias

```bash
npm install
```

---

# Ejecutar el Proyecto

## Modo desarrollo

```bash
npm start
```

Esto iniciará el entorno de desarrollo utilizando Webpack Dev Server.

---

## Build de producción

```bash
npm run build
```

Webpack generará la versión optimizada y lista para despliegue.

---

# Características del Proyecto

## Diseño Responsive

La interfaz está adaptada para:

* Desktop
* Tablet
* Mobile

---

## Diseño Corporativo

El proyecto utiliza:

* Layout empresarial moderno
* Tipografía clara
* Secciones organizadas
* Componentes visuales limpios
* Distribución profesional de contenido

---

## Optimización con Webpack

Webpack se utiliza para:

* Bundling de archivos
* Optimización de assets
* Configuración de entorno desarrollo/producción
* Hot reload durante desarrollo

---

# Dependencias Principales

```json
{
  "webpack": "^5.101.3",
  "webpack-cli": "^6.0.1",
  "webpack-dev-server": "^5.2.2",
  "webpack-merge": "^6.0.1",
  "copy-webpack-plugin": "^13.0.1",
  "html-webpack-plugin": "^5.6.4"
}
```

---

# Mejoras Futuras

Posibles mejoras para evolucionar el proyecto:

* Dark Mode
* Animaciones avanzadas con GSAP
* Migración a React
* CMS para administración de contenido
* Integración con backend Node.js
* Formulario funcional de contacto
* Dashboard administrativo
* SEO avanzado
* Deploy automático con CI/CD

---

# Autor

Desarrollado por Jesús Restrepo.

---

# Licencia

Este proyecto está bajo licencia MIT.
