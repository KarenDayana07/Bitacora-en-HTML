# Proyecto: Bitácora de Seguimiento Web - ADSO

**Aprendices:** Karen Dayana Villamizar Reyes, Silvia Fernanda Osorio Vargas, Jesús Arturo Rincón Villamizar
**Programa:** Análisis y Desarrollo de Software - SENA
**Ficha:** 3381732

## 📝 Descripción del Proyecto
Este repositorio contiene la transformación digital de la bitácora de seguimiento de la sesión del **03 de Septiembre de 2026** (originalmente en formato Excel) a un sitio web estático estructurado únicamente con HTML5 puro. El objetivo de este trabajo colaborativo fue documentar de manera cronológica, semántica y accesible las actividades, evidencias e impedimentos presentados durante esa jornada de formación.

## 📂 Estructura de las Vistas y Distribución del Trabajo
El proyecto web está compuesto por tres vistas principales que representan fielmente las tres hojas del libro de Excel original. El trabajo fue desarrollado en equipo distribuyendo las vistas de la siguiente manera:

1. **Vista de Información (`informacion-03.html`):**
   * **Desarrollado por:** Karen Dayana Villamizar Reyes.
   * **Contenido:** Datos generales del aprendiz, la competencia y el periodo de formación.

2. **Vista de Reglas (`reglas-03.html`):**
   * **Desarrollado por:** Jesús Arturo Rincón Villamizar.
   * **Contenido:** Detalla las reglas de oro para el llenado de la bitácora y la guía de cada una de las columnas de la tabla.

3. **Vista de Trazabilidad (`trazabilidad-03.html`):**
   * **Desarrollado por:** Silvia Fernanda Osorio Vargas.
   * **Contenido:** Es la tabla principal donde se registran cronológicamente las actividades, evidencias e impedimentos de la jornada.

*(Nota: El menú de navegación permite ir y volver entre estas tres vistas sin usar el botón "atrás" del navegador).*

## ♿ Prácticas Semánticas y de Accesibilidad Implementadas
Para garantizar que el sitio sea inclusivo, fácil de mantener y cumpla con los estándares web, se implementaron las siguientes prácticas:

**Semántica HTML:**
* Uso de etiquetas estructurales claras como `<header>`, `<nav>`, `<main>` y `<footer>` para delimitar las zonas de la página.
* Uso correcto de la jerarquía de encabezados (`<h1>`, `<h2>`) para crear un índice lógico del contenido.
* Uso de la etiqueta `<table>`, junto con `<tbody>`, `<tr>` y `<th>` para representar datos tabulares de manera estructurada.
* Uso de la etiqueta `<caption>` para darle un título descriptivo a las tablas.
* Uso de la etiqueta `<abbr>` para definir siglas (como ADSO), mejorando la comprensión del texto.

**Accesibilidad (a11y):**
* **Atributo `lang="es"`:** Declarado en la etiqueta `<html>` para que los lectores de pantalla pronuncien el texto con fonética española.
* **Atributos ARIA:** Uso de `aria-label="Navegación principal"` en el menú y `aria-labelledby` en las secciones para guiar a los lectores de pantalla.
* **Atributo `aria-current="page"`:** Utilizado en el enlace de la página actual, para que los usuarios con discapacidad visual sepan en qué pestaña se encuentran.
* **Atributo `scope`:** Utilizado en los encabezados de la tabla (`<th scope="row">`) para que los lectores de pantalla asocien correctamente cada dato con su categoría.
* **Enlaces descriptivos:** Los textos de los enlaces son claros y describen exactamente a dónde llevan.

## 🛠️ Tecnologías Utilizadas
* **HTML5:** Para la estructura y el contenido (sin CSS ni JavaScript).
* **Git y GitHub:** Para el control de versiones y el trabajo colaborativo en equipo.
* **GitHub Pages:** Para la publicación del sitio web en producción.