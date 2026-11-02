# PRESS START — actualización de modelos 3D

Este paquete actualiza el `index.html` y agrega cinco modelos 3D optimizados. Conserva los modelos anteriores ya presentes en `assets/`.

## Ubicación en la línea de tiempo

- Etapa 06 — WORLDS CONNECT (2001–2005): PlayStation 2 (`ps2.glb.gz`). Se corrigió su ubicación: ya no aparece en “DETAILS GET SHARPER”.
- Etapa 07 — DETAILS GET SHARPER (2005–2010): PC gamer (`pc.glb.gz`), como representación visual de la era de mayor fidelidad gráfica.
- Etapa 08 — A MORE CONNECTED ERA (2011–2015): PlayStation 4 (`ps4.glb.gz`).
- Etapa 09 — NEW WAYS TO PLAY (2016–2020): visor de realidad virtual (`vr.glb.gz`).
- Etapa 10 — SPEED MEETS DETAIL (2020–2023): Xbox Series X (`xboxx.glb.gz`).
- Etapa 11 — THE NEXT FRONTIER (2024+): inteligencia artificial (`ia.glb.gz`).

Las primeras cinco etapas usan los modelos existentes: osciloscopio, arcade, Atari, NES y PlayStation 1.

## Cómo actualizar GitHub

1. Descomprimí este ZIP.
2. En el repositorio `press-start1`, elegí **Add file → Upload files**.
3. Arrastrá `index.html` y los cinco archivos nuevos de la carpeta `assets/`. No borres los modelos anteriores.
4. Hacé clic en **Commit changes**.
5. Vercel generará una publicación nueva.

Los cinco modelos se optimizaron con texturas JPEG de 512 px, geometría cuantizada y compresión gzip. El visor interpreta los atributos normalizados para mantener su escala y encuadre.
