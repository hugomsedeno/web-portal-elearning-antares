# Portal Web E-Learning «Antares Digital»

![HTML5](https://img.shields.io/badge/Lenguaje-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/Estilos-CSS3%20Flexbox-1572B6?style=flat-square&logo=css3&logoColor=white)
![Web](https://img.shields.io/badge/Arquitectura-Multip%C3%A1gina-0F172A?style=flat-square)

Sitio web corporativo multipágina desarrollado para **Antares Desarrollo Digital (ADD)**, plataforma de teleformación y factoría de contenidos SCORM, aplicando maquetación con **CSS3 Flexbox**, semántica **HTML5** y formularios estructurados.

---

## Arquitectura del Proyecto

El portal está compuesto por tres vistas principales interconectadas mediante una barra de navegación superior fija (`position: fixed`) con indicador visual de sección activa:

1. **[`index.html`](index.html) — Página Principal y Catálogo de Soluciones:**
   - Cabecera fija con logotipo corporativo y menú de navegación Flexbox (`justify-content: space-between`).
   - Sección *Hero* a pantalla completa con imagen de fondo adaptativa (`background-size: cover`) y superposición oscura mediante el pseudo-elemento `::before`.
   - Sección de tarjetas de servicios (*Desarrollo de Contenidos*, *Plataforma E-Learning* y *Reservas y Pedidos*) distribuida con Flexbox (`display: flex; flex-wrap: wrap; gap: 20px`).

2. **[`elearning.html`](elearning.html) — Plataforma de Teleformación:**
   - Presentación detallada de la plataforma LMS para centros de Formación Profesional, aula virtual integrada y emisión de diplomas con tecnología Blockchain.

3. **[`contenidos.html`](contenidos.html) — Desarrollo SCORM y Reserva de Cursos:**
   - Exposición de ventajas del estándar SCORM y formulario interactivo de reserva de cursos con campos tipados (`text`, `date`, `email`).

4. **[`styles.css`](styles.css) — Hoja de Estilos Centralizada:**
   - Reseteo universal con `box-sizing: border-box`, desplazamiento suave (`scroll-behavior: smooth`), sistema de tarjetas con sombras suaves (`box-shadow`) y maquetación de formularios con Flexbox en columna.

---

## Estructura del Repositorio

```text
web-portal-elearning-antares/
├── index.html          # Página de inicio (Hero + Tarjetas de Soluciones)
├── elearning.html      # Vista de características de la Plataforma LMS
├── contenidos.html     # Vista de contenidos SCORM y formulario de reserva
├── styles.css          # Hoja de estilos CSS3 con arquitectura Flexbox
├── LOGO.jpg            # Logotipo corporativo de Antares Digital
├── hero.jpg            # Imagen de cabecera de la sección Hero
└── README.md           # Documentación técnica del proyecto
```

---

## Autor

* **Hugo Marín Sedeño** — [GitHub (@hugomsedeno)](https://github.com/hugomsedeno) · [LinkedIn](https://www.linkedin.com/in/hugo-mar%C3%ADn-sede%C3%B1o-79bb27302)

