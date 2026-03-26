# Proyección Financiera — Wealth Solutions

Herramienta interna de planificación patrimonial para el equipo de Relationship Managers de Wealth Solutions.

## Acceso

Una vez publicado en GitHub Pages, los RMs acceden directamente desde el navegador — sin instalación, sin login.

## Funcionalidades

- **Proyección de patrimonio** con escenarios conservador / base / optimista
- **Monte Carlo** (500 simulaciones) y análisis de sensibilidad
- **Escenarios de estrés** (caída severa, inflación descontrolada, estancamiento)
- **Ingresos y gastos** personalizables con horizonte temporal por partida
- **Análisis de sensibilidad** rentabilidad vs. horizonte
- **Desglose anual** año por año
- **Autoguardado** en el navegador (localStorage) — cada RM tiene su propio estado
- **Exportar / Importar sesión** (.json) para compartir proyecciones entre compañeros
- **Exportar PDF** para entregar al cliente
- **Disclaimer legal** integrado

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (ej: `proyeccion-financiera`)
2. Sube estos ficheros al repositorio
3. Ve a **Settings → Pages → Source: Deploy from a branch → main / root**
4. En unos minutos tendrás la URL: `https://TU-USUARIO.github.io/proyeccion-financiera/`
5. Comparte esa URL con todo el equipo de RMs

## Uso local

Abre `index.html` directamente en el navegador — no requiere servidor.

## Tecnología

HTML + CSS + JavaScript puro. Sin dependencias externas excepto:
- [Chart.js 4.4](https://www.chartjs.org/) — gráficos
- [SortableJS](https://sortablejs.github.io/Sortable/) — drag & drop de partidas
- [Poppins](https://fonts.google.com/specimen/Poppins) — tipografía

---

*Uso interno — Wealth Solutions © 2026*
