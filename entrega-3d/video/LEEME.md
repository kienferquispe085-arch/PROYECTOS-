# Parques de Ferreñafe — presentación 3D

## Descarga

Descarga `Video_Parques_Ferrenafe.zip`, descomprímelo y abre el MP4 incluido
con tu reproductor de video. Para los archivos editables, descarga y extrae
`Modelos_3D_Parques.zip`. Los enlaces directos están en el README principal.
Si GitHub abre la página de un ZIP, pulsa **Download raw file**.

## Video

`VIDEO_PARQUES_FERRENAFE_2_MIN.mp4`: presentación de 120 segundos, horizontal
1920 × 1080, 24 imágenes por segundo, H.264 y audio AAC. Incluye vistas
renderizadas de los cinco parques, acercamientos suaves, rótulos en español,
transiciones y música instrumental original, sin locución.

Orden del recorrido:

- 00:00–00:05: presentación.
- 00:05–00:27: P1 Central; fuente y ocho jardines.
- 00:27–00:49: P2 Grau / Bolívar; jardines, fuentes y pérgola.
- 00:49–01:11: P3 Norte; paseo y recinto deportivo.
- 01:11–01:33: P4 Noreste; canal y pasarelas.
- 01:33–01:55: P5 Sureste; estanque, pérgola y graderías.
- 01:55–02:00: cierre.

Cada parque incluye una vista general, una vista de detalle y una toma de los
estacionamientos propuestos.

## Modelos editables

Los cinco archivos `Pn_PARQUE_Y_ESTACIONAMIENTO.blend` se abren con Blender
4.3.2 o compatible. Contienen los modelos de parque originales, texturas
empaquetadas, vehículos, demarcaciones, señalización y cámara con fotogramas
clave. No requieren instalar pycollada para abrirlos. La colección de objetos
propuestos se identifica por el objeto padre
`ESTACIONAMIENTOS_PROPUESTA_CONCEPTUAL`.

Las cámaras editables están configuradas para 22 segundos por parque. El MP4
entregado se monta con las vistas renderizadas, acercamientos en edición y
rótulos; renderizar directamente la cámara del archivo Blender genera otra
versión de movimiento y no reconstruye por sí solo las tarjetas ni el montaje.

## Alcance de los estacionamientos

Se añaden como propuesta conceptual, indicada en pantalla durante el video.
Capacidad ilustrada: P1, una plaza; P2, dos; P3, P4 y P5, cuatro cada uno.
Cada plaza se representa de 6 × 2,4 m, con una franja de asfalto contigua de
3,6 m. La comprobación de las mallas sitúa las plazas sobre asfalto, sin
superponerlas a parques, veredas, ciclovías o edificios. Ubicaciones y capacidad
deben verificarse en un plano vial; P1 queda próximo a una esquina. Esta
comprobación geométrica no valida distancias a cruces, accesibilidad ni diseño
de tráfico.

Las coordenadas y comprobaciones están en `parking-layout.json` y sus detalles
en `PARKING_LAYOUT.md`. Los archivos de parque originales no se modificaron.

## Procedencia y reproducción

Modelos originales: `kienferquispe085-arch/PROYECTOS-`, revisión
`af42d4de18389c0324aa8586603831a8217ce715`, paquetes COLLADA P1–P5.
Se mantienen las dimensiones, geometría y texturas de esos entregables. La
conversión de eje Y_UP a Z_UP conserva la escala en metros.

Para renderizar se empleó Blender 4.3.2 y para el montaje FFmpeg 7.1.5.
Los `.blend` y sus texturas empaquetadas son la entrega editable autónoma.
