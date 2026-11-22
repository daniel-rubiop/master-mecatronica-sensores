# Sensores y Actuadores para Maquinaria · Máster en Mecatrónica (UVigo)

Material del trabajo de selección de sensórica de la asignatura *Sensores y Actuadores para Maquinaria* del Máster en Mecatrónica de la Universidade de Vigo (curso 2026/2027).

## Grupo 4 · Estuches y latas de conserva

Simulador 3D a escala de la estación que inspecciona en línea los estuches de sardinas en tomate de dos clientes (ALVA y CALVO). Comprueba que hay lata, que la lata no es corta, que tiene tapa, que las solapas están pegadas y que el cliente y el formato son los correctos.

**Abrir el simulador:** https://daniel-rubiop.github.io/master-mecatronica-sensores/estuches-latas/

Funciona en cualquier navegador, en ordenador o en móvil, sin instalar nada. La página lleva incluida la librería 3D (Three.js r128, licencia MIT), así que también se puede descargar el archivo `estuches-latas/index.html` y abrirlo sin conexión.

En el simulador se puede:

- recorrer la estación por fases, con el sensor activo y su zona de detección resaltados;
- provocar defectos (sin lata, lata corta, sin tapa, solapa levantada, cliente erróneo) y ver qué sensor los detecta y cómo se rechazan;
- ver la lata dentro del estuche (rayos X) y una vista explosionada con todos los sensores alrededor de un único estuche.

### Autores

- José Cruz Vizcaíno
- Daniel Rubio Prego
- Alberto Souto Outeiral
- Alberto Souto Quintas
- Kevin Jorge Viera González

## Estructura

| Ruta | Contenido |
|---|---|
| `index.html` | Página de inicio con el enlace a cada trabajo |
| `estuches-latas/index.html` | Simulador 3D del Grupo 4 (archivo autónomo) |

La web se publica con GitHub Pages desde la rama `main`. Cualquier cambio que se suba a `estuches-latas/index.html` se refleja en el mismo enlace al cabo de un minuto o dos.
