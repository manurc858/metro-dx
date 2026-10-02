# Metro DX · Termografía túnel–estación

Visualización 3D (three.js) de la temperatura del aire en 210 m de túnel de metro de vía doble seguidos de una estación en caverna, enfriada con unidades de expansión directa (DX) a partir de una temperatura base de 30 °C.

**Ver en web:** https://manurc858.github.io/metro-dx/

## Qué muestra

- Túnel en herradura y estación abovedada con andenes, pasarela, catenaria y trenes en ambos sentidos.
- Planos de temperatura (horizontal, longitudinal y transversal) con isotermas cada 1 °C, partículas de aire y modo termografía de superficies.
- Unidades interiores DX con su chorro de aire frío, tuberías de refrigerante y condensadoras en el pozo de ventilación o en un nicho del túnel.
- Comparación en paralelo con el mismo escenario sin DX: indicadores, perfil longitudinal a 1,7 m y evolución temporal en el andén.

## Modelo

Malla 3D de 2 × 1 × 1 m con advección longitudinal (ventilación y efecto pistón), difusión turbulenta, mezcla convectiva vertical e intercambio con los hastiales. Cargas de frenado, tracción, auxiliares de los trenes, pasajeros y alumbrado. Cada unidad DX recircula el aire de su zona, limitada por su capacidad sensible y modulada por la consigna.

Es un modelo de orden reducido para estudiar tendencias y órdenes de magnitud. No sustituye un cálculo CFD o SES de proyecto.

## Archivos

- `index.html`: página completa (la que publica GitHub Pages).
- `termografia-tunel-estacion.html`: el mismo contenido sin la cabecera del documento.

Se puede abrir `index.html` localmente con doble clic; necesita conexión a internet para cargar three.js desde CDN.
