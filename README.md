# Portafolio Web

Un portafolio web moderno construido con Astro y Tailwind CSS.

## 🚀 Tecnologías

- **Astro 5.16.8** - Framework web moderno
- **Tailwind CSS** - Framework CSS de utilidad
- **TypeScript** - Tipado estático

## 📦 Estructura del Proyecto

```
/
├── public/          # Archivos estáticos
├── src/
│   ├── components/  # Componentes de Astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Projects.astro
│   │   ├── Skills.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/     # Layouts de página
│   │   └── Layout.astro
│   └── pages/       # Páginas
│       └── index.astro
├── astro.config.mjs
├── tailwind.config.js
└── package.json
```

## 🧞 Comandos

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                        |
| `npm run dev`             | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`           | Construye el sitio para producción en `./dist/` |
| `npm run preview`         | Vista previa de la construcción localmente       |

## 🎨 Personalización

1. **Información Personal**: Edita los componentes en `src/components/` para actualizar tu información
2. **Proyectos**: Modifica el array `projects` en `src/components/Projects.astro`
3. **Habilidades**: Actualiza el array `skillCategories` en `src/components/Skills.astro`
4. **Colores**: Personaliza los colores en `tailwind.config.js`

## 📝 Componentes Disponibles

- **Header**: Navegación principal con menú responsive
- **Hero**: Sección de introducción principal
- **About**: Sección "Sobre mí" con información personal
- **Projects**: Galería de proyectos
- **Skills**: Visualización de habilidades técnicas
- **Contact**: Formulario de contacto e información
- **Footer**: Pie de página con enlaces

## 🚀 Deployment

El sitio puede ser desplegado en cualquier plataforma que soporte sitios estáticos como:
- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages

## 📄 Licencia

Ver el archivo LICENSE para más detalles.
