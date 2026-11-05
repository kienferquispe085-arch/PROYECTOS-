# Parques de Ferreñafe — versión con render físico

## Descargar y reproducir

Descomprime el ZIP del video y abre
`VIDEO_PARQUES_FERRENAFE_RENDER_REALISTA_2_MIN.mp4` con un reproductor de video.
Formato horizontal Full HD, 1920 × 1080, 24 fotogramas por segundo, 120 segundos,
video H.264 y audio AAC. Se mantienen las tarjetas, nombres, rótulos, música
instrumental y tiempos de la primera presentación.

## Acabado del render

Se utiliza trazado de rayos con Blender Cycles, cielo físico y luz solar,
sombras, iluminación indirecta, reflejos, materiales con rugosidad y respuesta
física, microrelieve en las superficies y tratamiento del agua y los vidrios.
Las imágenes finales pasan por Open Image Denoise y gestión de color AgX.

Se conservan las posiciones, dimensiones, geometría, mobiliario, vehículos,
plazas de estacionamiento, encuadres y texturas de color del modelo anterior.
No se redistribuyen elementos del proyecto. La vegetación y las texturas
mantienen el nivel de detalle de los archivos originales; la mejora se centra
en el acabado de render y no equivale a rehacer el modelado.

Los estacionamientos siguen siendo una propuesta conceptual, como indica el
rótulo del video. Su capacidad y ubicación no constituyen un diseño vial
validado.

## Modelos editables

Los cinco `.blend` se abren en Blender 4.3.2 o compatible, con sus texturas
empaquetadas y los materiales del render. Los objetos `Luz_del_sol` y
`RENDER_ENTORNO_NEUTRO` son iluminación y fondo de representación, no elementos
añadidos al diseño urbano. La cámara conserva su animación de 22 segundos por
parque. El montaje MP4 agrega las tarjetas y rótulos y realiza acercamientos
suaves sobre las vistas renderizadas.

En esta instalación la eliminación de ruido se hizo como paso externo con
Open Image Denoise 2.5.1. Para renderizar los modelos en una instalación de
Blender que incluya ese filtro, activa Denoise en Cycles. Esto no requiere
cambiar la geometría ni los materiales.

La auditoría incluida compara los modelos originales con los de esta versión:
objetos, posiciones, geometría, UV y texturas de color. Los cambios permitidos
son el acabado de los materiales, normales de sombreado e iluminación.

## Recorrido de dos minutos

- 00:00–00:05: presentación.
- 00:05–00:27: P1 Central.
- 00:27–00:49: P2 Grau / Bolívar.
- 00:49–01:11: P3 Norte.
- 01:11–01:33: P4 Noreste.
- 01:33–01:55: P5 Sureste.
- 01:55–02:00: cierre.

Cada parque tiene una vista general, una vista del diseño y una vista de sus
estacionamientos conceptuales.
