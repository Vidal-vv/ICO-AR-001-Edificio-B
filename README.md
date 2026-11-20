# ICO-AR-001 — Edificio B en Realidad Aumentada

Prototipo WebAR MindAR + A-Frame que intenta mostrar el modelo conceptual al reconocer una imagen.

## Contenido
- `index.html`: página WebAR.
- `assets/EdificioB.glb`: modelo 3D conceptual.
- `assets/marcador.png`: marcador de referencia.
- `assets/targets.mind`: archivo recibido y validado estructuralmente (MindAR v2, 1 target, 1200x900 px).
- `assets/QR_ID.png` y `assets/Code128_ID.png`: códigos identificadores preliminares.

## Publicación
Sube los archivos conservando `assets/`. Activa GitHub Pages desde rama `main`, carpeta root. El sitio necesita HTTPS y permisos de cámara.

## Verificación / limitaciones
El archivo `targets.mind` fue revisado estructuralmente. No se verificó que el target corresponda visualmente al marcador PNG ni se probó el tracking en móvil. El modelo es conceptual y no es una réplica exacta comprobada del edificio real.
