# PUCP: Product Management Fundamentals 01

Una experiencia completa de aprendizaje sobre Product Management en la era de la IA, diseñada para la Pontificia Universidad Católica del Perú (PUCP).

## 🎯 Overview

Este proyecto incluye dos componentes:

1. **Landing Page** ([index.html](index.html)) - Puerta de entrada emocional e inspiracional
2. **Presentación Principal** ([pucp-pres.html](pucp-pres.html)) - 20 slides sobre AI-Native Product Management

Ambos componentes comparten un diseño moderno con glassmorphism, gradientes animados y navegación fluida.

## 🚀 Quick Start

### Local Development

Abre cualquiera de los archivos HTML en un navegador moderno:

```bash
# Landing page
open index.html

# Presentación completa
open pucp-pres.html
```

### Deployment to Vercel

Este proyecto está configurado para deployment fácil en Vercel:

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Update: PUCP presentation"
   git push origin main
   ```

2. **Deploy to Vercel:**
   - Ve a [vercel.com](https://vercel.com)
   - Importa tu repositorio GitHub: `huayaney-exe/diplomado-pucp`
   - Vercel detectará automáticamente la configuración
   - Click "Deploy"

3. **URLs del proyecto:**
   - `/` → Landing page (index.html)
   - `/presentacion` → Presentación completa (pucp-pres.html)
   - Puedes acceder directamente a `pucp-pres.html` también

4. **¡Tu sitio estará en vivo!** 🎉

### Manual Vercel Deployment

Alternatively, you can deploy using the Vercel CLI:

```bash
npm install -g vercel
vercel
```

## 🎨 Estructura del Proyecto

### Landing Page (index.html)

La landing page incluye 5 secciones:

1. **Hero Section** - Mensaje principal inspiracional
2. **Por Qué Este Momento Es Especial** - 3 tarjetas con razones para ser PM ahora
3. **Qué Dominarás** - 4 bloques de aprendizaje (Fundamentos)
4. **Sobre la Sesión** - Bio del speaker y detalles
5. **CTA Final** - Llamado a la acción para entrar a la presentación

### Presentación Principal (pucp-pres.html)

La presentación incluye 20 slides cubriendo:

1. Opening statement about the best moment to create
2. Title slide with AI-Native Product Management
3. Introduction to the speaker
4. The fundamental shift AI brings
5. First principles: What is a product?
6. Evolution of modern problems
7. Product power formula
8. Classic product trinity
9. Why traditional methods break
10. AI compression effect
11. The hype trap warnings
12. Reality check
13. Productive tension
14. Builder's evolution
15. Who thrives in this new world
16. AI-enhanced arsenal
17. Transformation in action
18. New product playbook
19. Winning framework
20. Call to action

## 🎨 Características

**Compartidas (Landing + Presentación):**
- **Diseño Moderno**: Efectos glassmorphism con gradientes animados
- **Sistema de Color Prisma**: Cyan (#47FFBF), Purple (#8376FF), Pink (#FF48C7)
- **Responsive**: Funciona en desktop, tablet y mobile
- **Sin dependencias**: HTML, CSS y JavaScript puro
- **Tipografía Inter**: Familia de fuentes profesional

**Landing Page:**
- **Scroll suave**: Animaciones al hacer scroll
- **Cards interactivas**: Hover effects con glow
- **Optimizada para conversión**: CTAs estratégicos

**Presentación:**
- **Navegación fluida**: Scroll-snap con atajos de teclado
- **Interactiva**: Progress dots, indicadores, scroll hints
- **20 slides**: Contenido completo sobre AI-Native PM

## 🔧 Detalles Técnicos

- HTML, CSS y JavaScript puro (sin dependencias)
- Sistema de diseño inspirado en Prisma
- CSS scroll-snap para navegación suave (presentación)
- Intersection Observer para tracking y animaciones
- Completamente responsive con optimización mobile
- Configuración Vercel para routing inteligente

## 🎤 Sobre el Speaker

**Luis Huayaney**
- Lead Product Manager en Interbank
- Arquitecto de innovación y líder de producto
- Educador en metodologías ágiles en universidades de Lima
- Construyendo el futuro del desarrollo de productos AI-first

## 🚀 Flujo del Usuario

1. Usuario accede al sitio → **Landing page inspiracional** (index.html)
2. Lee sobre el momento especial para ser PM + herramientas AI
3. Entiende qué aprenderá: Fundamentos, herramientas, frameworks
4. Click en CTA "Iniciar el Aprendizaje" → **Presentación completa** (pucp-pres.html)
5. Navega 20 slides interactivas sobre AI-Native Product Management

## 📂 Estructura de Archivos

```
PUCP-PRES/
├── index.html              # Landing page principal
├── pucp-pres.html         # Presentación de 20 slides
├── vercel.json            # Configuración de routing
├── .gitignore             # Archivos ignorados por git
└── README.md              # Este archivo
```

## 📝 Licencia

Esta presentación es con fines educativos para PUCP.

---

Hecho con ❤️ para PUCP · Product Management Fundamentals 01
