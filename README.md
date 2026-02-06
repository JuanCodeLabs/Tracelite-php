# Tracelite - Sistema de Gestión de Activos

## Estructura del Proyecto

```
Tracelite-php/
├── assets/                 # Recursos locales (sin dependencias externas)
│   ├── css/
│   │   └── tailwind.css    # Tailwind CSS local
│   ├── fonts/
│   │   ├── plus-jakarta-sans.css    # Google Fonts Plus Jakarta Sans
│   │   ├── material-symbols-rounded.css  # CSS para Material Symbols Rounded
│   │   └── material-symbols-rounded.ttf   # Archivo de fuente TTF
│   └── js/              # Archivos JavaScript (vacío actualmente)
├── index.html             # Dashboard principal
├── areas.html            # Gestión de Áreas
├── equipos.html           # Gestión de Equipamiento
├── reportes.html         # Sistema de Reportes
└── gradientes.html        # Selector de gradientes (herramienta de diseño)
```

## Características

### ✅ Funcionalidad Offline
- **Independencia total de internet**: Todas las dependencias están locales
- **Fuentes auto-hospedadas**: Material Symbols Rounded y Plus Jakarta Sans
- **CSS local**: Tailwind CSS descargado y personalizado
- **Gradiente Mesh Moderno**: Fondo elegante con múltiples capas

### 🎨 Diseño
- **Glassmorphism**: Efectos de cristal con blur y transparencias
- **Gradiente Mesh Moderno**: 
  - Radial ellipse top-left (púrpura transparente)
  - Radial ellipse bottom-right (azul transparente)  
  - Radial ellipse center (rosa transparente)
  - Linear gradient base (#0a0a0c a #1a1a2e)
- **Iconos Material Symbols Rounded**: Consistentes y modernos
- **Tipografía Plus Jakarta Sans**: Limpia y profesional

### 📱 Responsive
- **Mobile-first**: Diseño adaptativo para todos los dispositivos
- **Sidebar colapsable**: Navegación optimizada para móviles
- **Grid layouts**: Sistema flexible de columnas

## Páginas

| Página | Archivo | Descripción |
|---------|-----------|-------------|
| Dashboard | `index.html` | Vista principal con estadísticas y gráficos |
| Áreas | `areas.html` | Gestión de áreas y ubicaciones |
| Equipos | `equipos.html` | Administración de equipamiento |
| Reportes | `reportes.html` | Sistema de generación de reportes |
| Gradientes | `gradientes.html` | Herramienta de diseño para selección de fondos |

## Tecnologías

- **HTML5** semántico y accesible
- **Tailwind CSS** (local) para estilos
- **JavaScript** vanilla para interactividad
- **Material Symbols Rounded** para iconos
- **Plus Jakarta Sans** para tipografía

## Instalación Local

1. Clonar o descargar el proyecto
2. Abrir cualquier página HTML en un navegador
3. No requiere servidor web (funciona directamente desde el sistema de archivos)

## Notas de Desarrollo

- **Sin dependencias externas**: Todo funciona offline
- **Optimizado para rendimiento**: Mínimas solicitudes de red
- **Compatible con navegadores modernos**: Chrome, Firefox, Safari, Edge
- **Código limpio**: Estructura semántica y mantenible

## Personalización

### Cambiar colores primarios
Editar el objeto `tailwind.config` en cualquier página HTML:

```javascript
colors: {
  primary: "#A855F7",        // Color principal (púrpura)
  "background-light": "#F8FAFC", // Fondo claro
  "background-dark": "#0A0A0C",   // Fondo oscuro
}
```

### Modificar gradiente de fondo
Editar la clase `.bg-gradient-mesh` en el CSS de cada página.

---

**Desarrollado con ❤️ para Tracelite**
