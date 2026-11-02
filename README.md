# PRESS START — Website Project

## Publicación

- `index.html`: página principal lista para publicar.
- `assets/osciloscopio2.glb.gz`: modelo 3D comprimido que carga automáticamente el visor.
- `assets/osciloscopio2.glb`: copia original del modelo (respaldo).
- `assets/osciloscopio2_optimized.glb`: versión ligera alternativa del modelo.
- `index-standalone.html` y `PRESS START — Updated Timeline.html`: copias HTML independientes.
- `styles.css` y `script.js`: fuentes separadas de estilos e interacciones del sitio.

**Importante:** el `index.html` principal obtiene el modelo desde `assets/osciloscopio2.glb.gz`. Al publicar, conservá la carpeta `assets` en la raíz del repositorio, junto a `index.html`. No hace falta que el visitante seleccione ni suba el modelo.

## Probar localmente

No abras el HTML con doble clic (`file://`), porque el navegador bloquea las peticiones `fetch()` locales. Abrí esta carpeta en Visual Studio Code y ejecutá **Go Live** con Live Server. Alternativamente, ejecutá `py -m http.server 8000` desde esta carpeta y visitá `http://localhost:8000/index.html`.

## Animación

El modelo original es una malla estática. El visor anima el osciloscopio con un balanceo leve y dibuja la pelota de Tennis for Two sobre el CRT mediante un efecto de shader, siguiendo una trayectoria curva. Respeta la preferencia de movimiento reducido del dispositivo.


3D hardware models: the history scrollytelling viewer loads the oscilloscope, arcade cabinet, Atari, Nintendo NES, PlayStation 1, and PlayStation 3 GLB assets from assets/*.glb.gz. These models rotate continuously while their chapter is active.
