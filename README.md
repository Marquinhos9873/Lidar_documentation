# Lidar_documentation

Visores interactivos (HTML autocontenido, Plotly) generados por el pipeline de fusión
LiDAR + cámara sobre el dataset **UAVScenes** (escena AMvalley, mapas DJI Terra, LiDAR Livox Avia).

Cada archivo es la salida `10_visor_interactivo_lidar_imagen` de un intervalo de vuelo:
la nube de puntos del mapa global proyectada en la cámara y coloreada con el RGB
fotográfico (colorización inversa), navegable en el navegador.

## Contenido

| Archivo | Intervalo de origen |
|---|---|
| `10_visor_interactivo_lidar_imagen.html` | `Int_1` |
| `2_1_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt1` |
| `2_2_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt2` |
| `2_3_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt3` |
| `2_4_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt4` |
| `2_5_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt5` |
| `2_6_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt6` |
| `2_7_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt7` |
| `2_8_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt8` |
| `2_9_10_visor_interactivo_lidar_imagen.html` | `Int_2_pt9` |

## Uso

Cada `.html` es autocontenido (~22 MB, incluye Plotly y los datos embebidos).
Descárgalo y ábrelo en el navegador; no requiere servidor ni dependencias.

> Nota: la nube visualizada está submuestreada (máx. ~30 000–50 000 vértices) para
> evitar el colapso de memoria de la pestaña; los `.ply` exportados en el proyecto
> conservan el 100 % de la densidad.
