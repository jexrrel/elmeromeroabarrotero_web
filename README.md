# El Mero Mero Abarrotero

Una página web estática modular construida con Astro para la tienda de abarrotes "El Mero Mero Abarrotero".

## 🚀 Características

- **Estática y Rápida**: Construida con Astro para máximo rendimiento
- **Modular**: Componentes reutilizables fáciles de actualizar
- **Responsive**: Diseño adaptable a todos los dispositivos
- **SEO Optimizado**: Meta tags y estructura semántica
- **Fácil de Personalizar**: Contenido estático fácil de modificar

## 📁 Estructura del Proyecto

```
src/
├── components/          # Componentes reutilizables
│   ├── Header.astro    # Navegación principal
│   ├── Footer.astro    # Pie de página
│   ├── Hero.astro      # Sección hero
│   └── Features.astro  # Sección de características
├── layouts/            # Layouts base
│   └── BaseLayout.astro
├── pages/              # Páginas del sitio
│   ├── index.astro     # Página principal
│   ├── servicios.astro # Página de servicios
│   ├── productos.astro # Página de productos
│   ├── contacto.astro  # Página de contacto
│   └── 404.astro       # Página de error
└── styles/             # Estilos globales
    └── global.css
```

## 🛠️ Instalación y Uso

1. **Instalar dependencias**:
   ```bash
   npm install
   ```

2. **Ejecutar en modo desarrollo**:
   ```bash
   npm run dev
   ```

3. **Construir para producción**:
   ```bash
   npm run build
   ```

4. **Previsualizar build**:
   ```bash
   npm run preview
   ```

## 🎨 Personalización

### Cambiar Contenido

Para modificar el contenido de las páginas, edita los archivos en `src/pages/`:

- **Página principal**: `src/pages/index.astro`
- **Servicios**: `src/pages/servicios.astro`
- **Productos**: `src/pages/productos.astro`
- **Contacto**: `src/pages/contacto.astro`

### Modificar Componentes

Los componentes reutilizables están en `src/components/`:

- **Header**: Navegación y logo
- **Footer**: Información de contacto y enlaces
- **Hero**: Sección principal con título y botones
- **Features**: Sección de características/beneficios

### Cambiar Colores

Los colores se configuran en `tailwind.config.mjs` en la sección `theme.extend.colors`.

### Agregar Nuevas Páginas

1. Crea un nuevo archivo `.astro` en `src/pages/`
2. Importa el `BaseLayout` y los componentes necesarios
3. Agrega el enlace en el `Header.astro`

## 🔧 Tecnologías Utilizadas

- **Astro**: Framework estático
- **TypeScript**: Tipado estático
- **Tailwind CSS**: Estilos utilitarios
- **HTML5**: Estructura semántica

## 📱 Responsive Design

La página está optimizada para:
- Móviles (320px+)
- Tablets (768px+)
- Desktop (1024px+)

## 🚀 Despliegue

Esta página estática se puede desplegar en cualquier servicio de hosting estático:

- **Vercel**: `vercel --prod`
- **Netlify**: Arrastra la carpeta `dist/`
- **GitHub Pages**: Sube la carpeta `dist/`
- **Cualquier servidor web**: Sirve la carpeta `dist/`

## 📞 Soporte

Para cualquier pregunta o personalización adicional, contacta al desarrollador.

---

© 2025 El Mero Mero Abarrotero. Todos los derechos reservados.
