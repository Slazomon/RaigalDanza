# SPEC.md - Página Web Compañía de Danza

## 1. Project Overview

- **Project name**: Pulse Dance Company
- **Type**: Multi-page website
- **Core functionality**: Presentación de compañía de danza con información, galerías, eventos y contacto
- **Target users**: Potenciales clientes, fans y público en general interesados en contratar servicios de danza

## 2. UI/UX Specification

### Layout Structure

- **Navigation**: Header fijo con menú de navegación horizontal
- **Pages**: 
  - Inicio (index.html)
  - Nosotros (nosotros.html)
  - Galería (galeria.html)
  - Eventos (eventos.html)
  - Contacto (contacto.html)
- **Responsive**: Diseño mobile-first con breakpoints en 768px y 1024px

### Visual Design

#### Color Palette
- **Primary**: `#1a1a2e` (Dark navy)
- **Secondary**: `#e94560` (Vibrant coral-red)
- **Accent**: `#f8b500` (Golden yellow)
- **Background**: `#16213e` (Deep blue)
- **Text light**: `#eaeaea`
- **Text muted**: `#a0a0a0`

#### Typography
- **Headings**: "Bebas Neue", sans-serif (bold, dramatic)
- **Body**: "Poppins", sans-serif (modern, readable)
- **Accent text**: "Dancing Script", cursive (for artistic touches)

#### Spacing System
- Section padding: 80px vertical
- Container max-width: 1200px
- Card gap: 30px

#### Visual Effects
- Parallax scrolling en header
- Hover animations en tarjetas
- Smooth transitions (0.3s ease)
- Gradient overlays en imágenes

### Components

1. **Navbar**: Logo + menú horizontal, efecto sticky
2. **Hero section**: Imagen grande con texto superpuesto y CTA
3. **Cards**: Para eventos y galería con hover zoom
4. **Footer**: Redes sociales, links rápidos, copyright
5. **Form**: Inputs estilizados para contacto

## 3. Functionality Specification

### Core Features

#### Página Inicio (index.html)
- Hero con imagen de fondo y slogan
- Breve descripción de la compañía
- Llamada a acción (CTA) hacia contacto

#### Página Nosotros (nosotros.html)
- Historia de la compañía
- Estilo de danza que practican
- Logros y trayectoria

#### Página Galería (galeria.html)
- Grid de imágenes (placeholder usando picsum)
- Sección de videos (embed de YouTube placeholder)
- Lightbox al hacer click

#### Página Eventos (eventos.html)
- Calendario visual con eventos próximos
- Lista de próximos espectáculos
- Fechas, lugares y horarios

#### Página Contacto (contacto.html)
- Formulario de contacto (nombre, email, teléfono, mensaje)
- Información de contacto (email, teléfono, dirección)
- Mapa placeholder

### Interactions
- Navegación smooth scroll
- Animaciones CSS en scroll (fade-in)
- Menu hamburguesa en móvil
- Validación básica de formulario

## 4. Acceptance Criteria

- [ ] Navegación funciona entre todas las páginas
- [ ] Diseño responsivo funciona en móvil y desktop
- [ ] Animaciones suaves sin lag
- [ ] Formulario tiene validación visual
- [ ] Imágenes cargan correctamente (usar placeholders)
- [ ] Colores y tipografía cumplen spec
- [ ] Footer presente en todas las páginas