# Cinco parques separados — COLLADA con texturas

Archivos DAE independientes, a escala 1:1 en metros, basados en el DXF de
Ferreñafe y detallados a partir de las cinco propuestas visibles en las
cuatro imágenes compartidas. No contienen renders.

| Modelo | Referencia | Descarga |
|---|---|---|
| P1 | Central: fuente y ocho jardines | [P1_PARQUE_DAE.zip](https://github.com/kienferquispe085-arch/PROYECTOS-/raw/refs/heads/main/entrega-3d/parques-separados/P1_PARQUE_DAE.zip) (2.3 MiB) |
| P2 | Grau / Bolivar: parque en L | [P2_PARQUE_DAE.zip](https://github.com/kienferquispe085-arch/PROYECTOS-/raw/refs/heads/main/entrega-3d/parques-separados/P2_PARQUE_DAE.zip) (1.8 MiB) |
| P3 | Norte: paseo y recinto deportivo | [P3_PARQUE_DAE.zip](https://github.com/kienferquispe085-arch/PROYECTOS-/raw/refs/heads/main/entrega-3d/parques-separados/P3_PARQUE_DAE.zip) (2.0 MiB) |
| P4 | Noreste: parque del canal | [P4_PARQUE_DAE.zip](https://github.com/kienferquispe085-arch/PROYECTOS-/raw/refs/heads/main/entrega-3d/parques-separados/P4_PARQUE_DAE.zip) (2.4 MiB) |
| P5 | Sureste: parque diagonal y graderias | [P5_PARQUE_DAE.zip](https://github.com/kienferquispe085-arch/PROYECTOS-/raw/refs/heads/main/entrega-3d/parques-separados/P5_PARQUE_DAE.zip) (1.0 MiB) |

Extrae todo el ZIP y en SketchUp de escritorio selecciona **Archivo →
Importar → COLLADA (.dae)**. Mantén `texturas` junto al DAE. Después guarda
como `.skp`. Cada ZIP contiene un solo parque con su contexto inmediato.

Si el navegador muestra la página del archivo ZIP en lugar de descargarlo,
pulsa **Download raw file**. No es necesario descargar todo el repositorio.

## Medidas y alcance

El DXF declara metros (`INSUNITS=6`). Se preservan sus coordenadas y escala,
con origen común desplazado a (6350,1750). Se incluyen medidas de las
entidades principales en `MEDIDAS_DXF.csv` y las decisiones por parque en
`LEEME.txt` y `DATOS_DEL_MODELO.json`.

P1 conserva el perímetro CAD y cierra extremos abiertos de los jardines.
P2 conserva el contorno en L, regularizando su pequeño solape de cierre.
P3 conserva los dos recintos CAD y la calle entre ambos. P4 mantiene canal
e islas verdes del dibujo; los encuentros de paseos son propuestos porque
no se identificó un contorno cerrado único. P5 une los vértices de las
líneas CAD de borde para cerrar su perímetro.

Alturas, profundidades y dimensiones de detalles no acotados se interpretan
de las imágenes y se documentan como propuestas. Las curvas se aproximan
con tolerancia de 0,012 m. No se presenta como una reproducción exacta de
todos los detalles constructivos ni como dimensionamiento hidráulico.

La estructura COLLADA, los índices, las transformaciones, las unidades y
las texturas se validaron; los modelos se leyeron con pycollada. No se ha
hecho una prueba en una instalación nativa de SketchUp.

Estos archivos detallados sustituyen a la primera base simplificada para
trabajar parque por parque; el ZIP de todo el sector sigue disponible en
la carpeta superior como antecedente.
