<div style="width: 100%; clear: both;">
  <div style="float: left; width: 50%;">
    <img src="http://www.uoc.edu/portal/_resources/common/imatges/marca_UOC/UOC_Masterbrand.jpg" align="left">
  </div>
  <div style="float: right; width: 50%;">
    <p style="margin: 0; padding-top: 22px; text-align:right;">PRA2 · Tipología y ciclo de vida de los datos</p>
    <p style="margin: 0; text-align:right; padding-button: 100px;">Joshua y Marcos Caballero, Abril 2022</p>
    <p style='color: #105269; font-size: 18px; text-align:right; font-family: verdana'><b>  Máster Ciencia de Datos</b></p>
  </div>
</div>
<div style="width:100%;">&nbsp;</div>

# <b><u> Limpieza y Análisis del dataset "Red Wine Quality" </b></u>

## <b> Introducción </b>
Se desea elaborar un proyecto analítico y usar las herramientas de integración, limpieza, validación y análisis de las mismas.

## <b> Dataset </b>
Enlace al dataset de Kaggle [Red Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

Los dos conjuntos de datos están relacionados con las variantes tintas y blancas del vino portugués "Vinho Verde". Debido a cuestiones de privacidad y logística, sólo se dispone de variables fisicoquímicas (entradas) y sensoriales (la salida) (por ejemplo, no hay datos sobre tipos de uva, marca de vino, precio de venta del vino, etc.).

Estos conjuntos de datos pueden considerarse tareas de clasificación o de regresión. Las clases están ordenadas y no equilibradas (por ejemplo, hay muchos más vinos normales que excelentes o malos).

Traducción realizada con la versión gratuita del traductor www.DeepL.com/Translator

### Descripción
Variables de entrada (basadas en pruebas fisicoquímicas):
1. `acidez fija`:
2. `acidez volátil`:
3. `ácido cítrico`:
4. `azúcar residual`:
5. `cloruros`:
6. `Dióxido de azufre libre`:
7. `Dióxido de azufre total`:
8. `densidad`:
9. `pH`:
10. `sulfatos`:
11. `alcohol`:

Variable de salida (basada en datos sensoriales):
12. `calidad (puntuación entre 0 y 10)`:

## Cómo replicar el entorno
Comandos para ejecutar los crawlers:
```bash
cd carrefour_scrapy
scrapy crawl carrefour -o wines_carrefour.csv

cd vivino_API
python vivino.py
```

### Requerimientos
Python 3.9.7, pip 21.2.4
```bash
Scrapy==2.6.1
pandas==1.4.2
```

## License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/mcaballero99/carrefour_crawler">Wine Crawler</a> by <span property="cc:attributionName">Marcos Caballero </span> is licensed under <a href="http://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"></a></p>
