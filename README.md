# HuellaAgro — Dashboard de Huella de Carbono Agropecuaria

Dashboard estático (HTML/CSS/JS) que presenta de forma visual e interactiva el inventario de huella de carbono de un establecimiento agropecuario, cubriendo Scope 1, 2 y 3.

🔗 **Demo en vivo:** [hulais05.github.io/huellaagro](https://hulais05.github.io/huellaagro/)

## Contenido

- `index.html` — dashboard completo (single-page), sin dependencias de build ni backend

## Secciones del dashboard

- **KPIs principales**: huella total, intensidad por hectárea, intensidad por tonelada producida, alcances declarados
- **Distribución por alcance**: gráfico Scope 1 / 2 / 3 (tCO₂e)
- **Fuentes de emisión**: detalle por categoría
- **Comparativa con benchmarks sectoriales**: AAPRESID (soja/maíz Argentina), FAO-LAC (ganadería), ESG Consulting NOA
- **Oportunidades de reducción**
- **Inventario de emisiones — detalle**: tabla completa por alcance/categoría/fuente
- **Estado de preparación para certificación ISO 14064-1**

## Metodología y referencias

- Factor eléctrico: MINEM Argentina 2024
- Benchmarks sectoriales: AAPRESID, FAO/IPCC (LAC), ESG Consulting NOA
- Marco de referencia: ISO 14064-1

## Cómo verlo localmente

Al ser un archivo estático, alcanza con abrirlo directamente en el navegador:

```bash
open index.html
```

## Despliegue

El sitio se publica automáticamente vía **GitHub Pages** desde la rama `main` (carpeta raíz). Cualquier cambio en `index.html` que se suba a `main` se refleja en la URL pública en pocos minutos.

## Relación con otros proyectos

Este dashboard estático es una vista de presentación/demo. Para un sistema con planilla de carga de datos conectada a un dashboard interactivo y actualizable (sector agropecuario, IPCC AR6 + GHG Protocol + ISO 14064-1), ver [matriz-huella-carbono-agro](https://github.com/hulais05/matriz-huella-carbono-agro).
