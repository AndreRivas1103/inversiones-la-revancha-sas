# Sitio web Empresa Random

Sitio web corporativo de **Empresa Random**, sociedad comercial dedicada al cultivo y comercialización de plátano en Urabá, Antioquia. Incluye información institucional, procesos, cultura organizacional y documentación de software.

---

## Descripción del proyecto

Empresa Random es una sociedad comercial dedicada principalmente al cultivo de plátano. Se formalizó como sociedad el 14 de diciembre de 2020 y desde entonces se ha especializado en la producción y comercialización de plátano, con actividades que abarcan desde la preparación del terreno y la siembra hasta la cosecha y distribución de los productos.

Este proyecto es una **página web estática** (HTML, CSS, JavaScript) que presenta:

- Información corporativa y descripción de la empresa
- Valores empresariales y objetivos estratégicos
- Mapa de procesos
- Documentación de procesos actuales y soluciones
- Diccionario de datos y reglas de negocio
- Cultura organizacional: misión, visión y matriz DOFA
- Recomendaciones de software y mejor opción

---

## Tecnologías

| Tecnología        | Uso                          |
|------------------|------------------------------|
| **HTML5**        | Estructura y contenido       |
| **CSS3**         | Estilos (Bootstrap + custom)  |
| **JavaScript**   | Interactividad (jQuery)       |
| **Bootstrap 5**  | Grid, componentes, responsive|
| **jQuery**       | DOM, animaciones, scroll     |
| **WOW.js**       | Animaciones al hacer scroll  |
| **Owl Carousel** | Carruseles (si se usan)      |
| **Font Awesome / Bootstrap Icons** | Iconos        |
| **Google Fonts** | Tipografías (Open Sans, Lora) |

---

## Estructura del proyecto

```
inversiones-la-revancha-sas/
│
├── index.html              # Página principal (inicio)
├── README.md               # Este archivo
│
├── paginas/                # Páginas internas del sitio
│   ├── mision.html         # Misión
│   ├── vision.html         # Visión
│   ├── valores.html        # Valores empresariales (página extendida)
│   ├── dofa.html           # Matriz DOFA
│   ├── procesosactual.html # Proceso actual
│   ├── procesosolucion.html# Solución del proceso
│   ├── diccionariodatos.html# Diccionario de datos
│   ├── reglasnegocio.html  # Reglas de negocio
│   ├── recomendaciones.html# Recomendaciones de software
│   └── mejoropcion.html    # Mejor opción de software
│
├── css/
│   ├── style.css           # Estilos personalizados del sitio
│   └── bootstrap.min.css    # Bootstrap compilado
│
├── js/
│   └── main.js             # Lógica principal (spinner, navbar, back-to-top, etc.)
│
├── img/                    # Imágenes y recursos gráficos
│   ├── icono.ico           # Favicon
│   ├── logo-removebg-preview.png
│   ├── plantacion.webp
│   ├── descripcion.png
│   ├── mapadeprocesos.jpg
│   ├── platanitostuki.jpg
│   └── ...                 # Otras imágenes según uso
│
├── lib/                    # Librerías de terceros
│   ├── animate/            # Animate.css
│   ├── easing/             # jQuery Easing
│   ├── owlcarousel/        # Owl Carousel
│   ├── waypoints/          # Waypoints (scroll)
│   └── wow/                # WOW.js
│
└── scss/                   # Fuentes SCSS (Bootstrap, etc.) si se usa compilación
```

---

## Contenido por sección

### Página principal (`index.html`)

- **Hero**: carrusel con imagen de plantación y nombre de la empresa
- **Descripción de la empresa**: texto institucional e imagen
- **Valores empresariales**: bloque con fondo imagen y overlay
- **Mapa de procesos**: imagen del mapa
- **Misión y visión**: enlaces a páginas dedicadas
- **Objetivos estratégicos**: lista con metas (2026, 2027, 2030)
- **Software**: enlaces a recomendaciones y mejor opción
- **Footer**: contacto (Urabá, teléfono, correo) y accesos rápidos

### Menú de navegación

- **Inicio** → ancla a la portada
- **Conocer más** → Información, Valores, Mapa de procesos, Objetivos estratégicos (anclas)
- **Proceso** → Proceso actual, Solución del proceso
- **Reglas y diccionario** → Diccionario de datos, Reglas de negocio
- **Cultura organizacional** → Visión, Misión, Matriz DOFA
- **Software** → Recomendaciones, Mejor opción

### Páginas en `paginas/`

Cada página mantiene la misma barra superior (contacto + menú), breadcrumb cuando aplica, contenido central y pie con marca y copyright.

---

## Cómo ejecutar el proyecto

Es un sitio **estático**: no requiere servidor de aplicaciones ni base de datos.

1. **Abrir directamente en el navegador**  
   Haz doble clic en `index.html` o arrástralo a una ventana del navegador.

2. **Servidor local (recomendado para evitar restricciones de CORS)**  
   Desde la raíz del proyecto:

   ```bash
   # Con Python 3
   python -m http.server 8000

   # O con Node.js (npx)
   npx serve .
   ```

   Luego abre en el navegador: `http://localhost:8000`

3. **Con Live Server (VS Code / Cursor)**  
   Instala la extensión "Live Server" y usa "Open with Live Server" sobre `index.html`.

---

## Contacto (referencia en el sitio)

- **Ubicación:** Urabá, Antioquia  
- **Teléfono:** 350 8246196  
- **Correo:** info@larevancha.org  

---

## Notas

- El sitio está en **español** (`lang="es"`).
- Diseño **responsive** con Bootstrap.
- Incluye **scroll suave** para anclas y botón **“Volver arriba”**.
- Uso de **meta description** y **keywords** para SEO básico.
