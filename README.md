# ICO-AR-001: Edificio B WebAR

## Incluye
- `index.html`: página WebAR MindAR + A-Frame.
- `assets/EdificioB.glb`: modelo 3D conceptual generado para este prototipo.
- `assets/marcador.png`: marcador de imagen de prueba.
- `assets/QR_ID.png`: QR de identificación del proyecto (no es URL).
- `assets/Code128_ID.png`: código Code 128 de identificación (no es URL).

## Pendiente imprescindible
`assets/targets.mind` todavía NO está incluido. Debe compilarse desde `assets/marcador.png` con el compilador MindAR; sin él no funcionará el image tracking.

## Compilar targets.mind
1. Abrir https://hiukim.github.io/mind-ar-js-doc/tools/compile/ .
2. Cargar `assets/marcador.png` y compilar.
3. Descargar y renombrar el archivo como `targets.mind`.
4. Colocarlo en la carpeta `assets/`.

## Publicar
Subir todos los archivos a la raíz del repositorio GitHub. Settings > Pages > Deploy from a branch > `main` > `/ (root)`.

## Limitaciones verificadas
Modelo y marcador son conceptuales, no cotejados con fotografías reales del Edificio B. Tracking y AR en móvil no se han probado. QR y Code 128 actuales son identificadores, no URL.
