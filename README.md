# Landing Page - Práctica Responsive Design

Una landing page práctica desarrollada con HTML5 y CSS3 para aprender y dominar conceptos clave de **posicionamiento CSS** y **responsive design**.

## 📋 Descripción

Este proyecto es una práctica educativa que demuestra la implementación de:
- **Posicionamiento CSS** (`position: fixed`, `position: absolute`, `position: relative`)
- **Layouts responsivos** y flexibles
- **Estructura semántica HTML**
- **Diseño visual moderno** con tema oscuro

## 🎯 Características

- ✅ Header fijo en la parte superior
- ✅ Barra lateral (sidebar) con posicionamiento absoluto
- ✅ Sección de contenido principal con ancho flexible
- ✅ Sección de características con cards
- ✅ Footer adhesivo
- ✅ Tema de colores personalizado (verde sobre negro)
- ✅ Diseño centrado en la educación de CSS Position

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos y posicionamiento
- **Responsive Design** - Mobile-friendly

## 📁 Estructura del Proyecto

```
├── index.html          # Archivo HTML principal
├── styles.css          # Estilos CSS
├── arquitectura.excalidraw  # Diagrama de arquitectura
└── README.md          # Este archivo
```

## 🚀 Cómo Usar

1. Clona o descarga el repositorio
2. Abre el archivo `index.html` en tu navegador web
3. Redimensiona la ventana para ver cómo responde el layout

## 📚 Conceptos de CSS Implementados

### Header Fijo
```css
header {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 100;
}
```

### Sidebar Absoluto
```css
.sidebar {
  position: absolute;
  top: 0;
  right: 0;
}
```

### Contenido Principal
```css
main {
  position: relative;
  margin-top: 100px; /* Espacio para header fijo */
}
```

## 📖 Objetivo de Aprendizaje

Este proyecto fue creado para:
- Comprender cómo funciona `position: fixed`, `absolute` y `relative`
- Aprender a crear layouts sin usando `display: grid` o `flexbox`
- Practicar la estructuración HTML semántica
- Implementar diseños responsivos con técnicas de posicionamiento tradicionales

## 🎨 Paleta de Colores

- **Fondo**: `#000000` (Negro)
- **Texto**: `#9ad79b` (Verde claro)
- **Bordes**: `dashed 2-3px`

## 📝 Notas

Este es un proyecto educativo creado como parte de mi práctica en desarrollo web. Siéntete libre de modificar, mejorar o adaptarlo según tus necesidades.

---

**Última actualización**: 2026
