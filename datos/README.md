# Datos del proyecto

El proyecto `atlas_provincias.qgz` busca sus capas en:

```
datos/atlas_provincias.gpkg
```

Este archivo (114 MB) no está incluido en el repositorio porque supera el límite de tamaño de GitHub. Se puede descargar desde la sección **[Releases](../../../releases)** del repositorio.

Una vez descargado, colocarlo en esta carpeta (`datos/`) sin cambiarle el nombre y abrir el proyecto.

## Capas que contiene

| Capa | Descripción | Fuente |
|---|---|---|
| `provincia` | Límites de las 24 jurisdicciones | IGN |
| `area_protegida` | Áreas naturales protegidas (terrestres y marinas) | IGN |
| `vial_nacional` | Red vial nacional | IGN |
| `vial_provincial` | Red vial provincial | IGN |
| `cobertura_atlas` | Capa de cobertura del Atlas (Tierra del Fuego encuadrada en Isla Grande, Isla de los Estados y Malvinas) | Elaboración propia a partir de `provincia` |
| `paises` | Países limítrofes | Mapa base de QGIS |
| `layer_styles` | Estilos de las capas | — |

Sistema de referencia: WGS 84 (EPSG:4326).
