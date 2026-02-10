# Página web: Vida y obra de una personalidad importante

Este proyecto consiste en una página web desarrollada con **HTML5 y CSS3** que expone la vida y obra de una personalidad relevante a nivel mundial.  
El objetivo principal es aplicar correctamente etiquetas semánticas, estilos con CSS y diseño responsivo.

---

## Tecnologías utilizadas

- HTML5
- CSS3
- Diseño responsivo (Media Queries)

---

## Requisitos cumplidos

- Uso correcto de etiquetas semánticas
- Navegación interna con `id`
- Enlaces externos en nueva pestaña
- Estilos aplicados principalmente con clases
- Uso de un solo `id` para estilado
- Media queries para diseño responsivo
- Imágenes adaptables al tamaño de pantalla
- Formulario de contacto estructural

---

## Etiquetas HTML utilizadas y su función

### Estructura básica
- `<html>`: Contiene todo el documento HTML
- `<head>`: Metadatos y enlaces a recursos
- `<body>`: Contenido visible

### Semánticas
- `<header>`: Encabezado del sitio
- `<nav>`: Barra de navegación
- `<main>`: Contenido principal
- `<section>`: División temática del contenido
- `<article>`: Contenido independiente
- `<footer>`: Pie de página

### Contenedores
- `<div>`: Contenedor genérico
- `<span>`: Contenedor en línea para texto

### Texto
- `<h1>`: Título principal
- `<h2>`: Títulos de sección
- `<h3>`: Subtítulos
- `<p>`: Párrafos
- `<hr>`: Separador visual

### Listas
- `<ul>`: Lista no ordenada
- `<ol>`: Lista ordenada
- `<li>`: Elemento de lista

### Enlaces e imágenes
- `<a>`: Enlaces internos y externos
- `<img>`: Imágenes con texto alternativo

### Formularios
- `<form>`: Contenedor del formulario
- `<label>`: Etiqueta descriptiva
- `<input>`: Campo de entrada
- `<button>`: Botón de envío

---

## Estilos CSS

### Reglas generales
- Estilado permitido por etiqueta: `body`, `p`, `h1`, `h2`, `h3`
- Estilado principal mediante clases
- Uso de un solo `id` (`#contacto`) para estilado

### Ejemplo de imagen responsiva
```css
.imagen {
    max-width: 100%;
    height: auto;
    object-fit: contain;
}
