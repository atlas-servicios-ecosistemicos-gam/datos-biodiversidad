# Datos de biodiversidad

## Biodiversidad
### GAM

```shell
cd gam

# ASP - Corredores biológicos
ogr2ogr -f GeoJSON -nln asp_corredores_gam -t_srs EPSG:4326 -makevalid asp_corredores_gam.geojson asp_corrdedores_gam.shp
```
