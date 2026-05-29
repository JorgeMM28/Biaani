# Biaani — Velas Artesanales Premium

Biaani es una plataforma web moderna, rápida y totalmente responsiva diseñada para presentar y comercializar veladoras artesanales únicas, elaboradas manualmente con diferentes tipos de cera natural (cera de soya 100%), aromas exclusivos de autor y diseños decorativos personalizados.

Este proyecto está construido sobre Astro, utilizando componentes ultraligeros, CSS moderno con un diseño de alta gama (tonos beige, rosa y dorado) y animaciones de alta fidelidad optimizadas para el rendimiento móvil y de escritorio.

---

## Características Principales

- **Diseño de Autor**: Estilo visual premium con degradados sofisticados, tipografía cuidada (Cormorant Garamond y Jost) y detalles dorados y rosados.
- **Rendimiento Impecable**: Carga instantánea y transiciones ultra fluidas gracias a la arquitectura de islas de Astro y animaciones aceleradas por hardware.
- **100% Responsivo e Inclusivo**: Adaptación perfecta a todos los viewports y dispositivos móviles, evitando saltos de diseño y optimizando la experiencia táctil.
- **Favicon Dinámico y de Alta Fidelidad**: Favicon multicapa generado a partir del logotipo real, con soporte SVG y resoluciones de hasta 256px.
- **Filtros de Difuminado CSS Avanzados**: Desvanecimiento suave y difuminado radial de los bordes de los productos para una integración perfecta con el fondo.
- **Galería de Producto y Carrusel Premium**: Sistema de visualización interactivo con animaciones en cascada para textos y zoom suave para las imágenes al activarse.
- **Optimización de Recursos**: Imágenes upscaleadas mediante algoritmos avanzados de remuestreo (Lanczos) para asegurar una visualización cristalina en pantallas de alta densidad (Retina).

---

## Estructura del Proyecto

```text
/
├── public/                # Favicons, logotipo y recursos de imágenes
│   ├── promo/             # Mockups de alta calidad para objetos promocionales
│   ├── 3velas.png         # Imagen principal del Hero optimizada con difuminado CSS
│   └── logo.png           # Logotipo oficial transparente
├── src/
│   ├── components/        # Componentes interactivos independientes (.astro)
│   │   ├── Hero.astro     # Portada con transiciones suaves basadas en carga
│   │   ├── Navbar.astro   # Cabecera fija con drawer absoluto antidesplazamiento
│   │   ├── Product.astro  # Carrusel interactivo premium
│   │   ├── Promotional.astro # Galería con difuminado sutil en bordes de imágenes
│   │   └── ...            # Secciones de contacto, misión y visión
│   ├── layouts/           # Plantillas globales
│   │   └── Layout.astro   # Estilos globales y meta etiquetas SEO
│   └── pages/             # Rutas y páginas principales
│       └── index.astro    # Página de inicio consolidada
└── package.json           # Dependencias y scripts de desarrollo
```

---

## Comandos de Desarrollo

El proyecto utiliza gestores de paquetes estándar (npm / pnpm / yarn). Desde la raíz del directorio, puedes ejecutar:

| Comando | Acción |
| :--- | :--- |
| `npm install` | Instala todas las dependencias necesarias. |
| `npm run dev` | Inicia el servidor de desarrollo local en `http://localhost:4321`. |
| `npm run build` | Compila la landing page de producción en la carpeta `./dist/`. |
| `npm run preview` | Previsualiza localmente el build de producción antes de desplegar. |

---

## Paleta de Colores y Tipografía

- **Colores Primarios**:
  - Rosas Elegantes: `#f2a5b4` / `var(--rose-100)`
  - Beiges Cálidos: `#f0dfc8` / `var(--beige-100)`
  - Dorados Distinguidos: `#c8936c` / `var(--gold-500)`
- **Tipografías**:
  - Títulos: *Cormorant Garamond* (Serif elegante y cursiva no exagerada)
  - Cuerpo: *Jost* (Sans-serif limpia y moderna)
