# Sysarmy salary surveys 

The current repository aims to help understand the evolution of salaries in technology for the region (Argentina mainly, and Latin America).  The datasets were taken from Sysarmy's blog, they do the surveys (survey takers and companies are anonymous) and share publicly the results.

## Notebooks / Dashboards

https://github.com/gerardobort/sysarmy-data/blob/master/notebooks

## Sources

https://sysarmy.com.ar/blog

https://www.bloomberg.com

Inspired on the analysis made by @fernandezpablo85 (dataset `2016.02`), published in the SysArmy blog.

## Contributing

Contributions are welcome! in the shape of Pull Requests more than Issues.  Except for corrections, if you have any new analysis you want to add, please add your own IPython notebook inside the `notebooks/` folder and datasets inside `data/`, and send me a PR!

## Datasets

### Salaries

| Period  | Path             | URL                                                                                                         |
|---------|------------------|-------------------------------------------------------------------------------------------------------------|
| 2014.02 | data/2014.02.csv | https://drive.google.com/open?id=0B7UapTwn9AahWkdEWnltRjUwVjQ                                               |
| 2015.01 | data/2015.01.csv | https://drive.google.com/open?id=0B7UapTwn9AahSHl1aGNfTlNrYWc                                               |
| 2016.01 | data/2016.01.csv | https://drive.google.com/open?id=0B7UapTwn9AahLTJmSE5zOUQ0aGc                                               |
| 2016.02 | data/2016.02/    | https://drive.google.com/open?id=0B7UapTwn9AahUGtySFBjdHBCcWs                                               |
| 2017.01 | data/2017.01/    | https://docs.google.com/spreadsheets/d/1diZG7ruHJ4OgO2-tbnO-ZnhjxjOnYjMVSxl7I-4LT54/edit#gid=1424918437     |
| 2017.02 | data/2017.02/    | https://docs.google.com/spreadsheets/d/1f1CAmzbVtoL66IwXJWEf0Mn-QbMNGZIoCQ_b1HB-91E                         |
| 2018.01 | data/2018.01/    | https://docs.google.com/spreadsheets/d/1OcOGeYEsI-iIO_QNfl_8avUK2ifg9wRFUly-f-c1CJM/edit#gid=2144425141     |

### Argentine Peso `AR$` currency over time

| Period  | Path                 | URL                                                                                                     |
|---------|----------------------|---------------------------------------------------------------------------------------------------------|
| 5Y      | data/usdars-cur.json | https://www.bloomberg.com/markets/api/bulk-time-series/price/USDARS%3ACUR?timeFrame=5_YEAR              |

### Available data per Dataset (structure)

### 2014.02

* Timestamp
* Tengo
* Trabajo en
* Años de experiencia
* Años en el puesto actual
* Trabajo de
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tenés guardias?
* Cuánto te pagan por guardia (AR$)
* Salario bruto mensual (AR$)
* Cómo creés que está tu sueldo
* Beneficios

### 2015.01

* Timestamp
* Tengo
* Trabajo en
* Años de experiencia
* Años en el puesto actual
* Trabajo de
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tenés guardias ?
* Cuánto te pagan por guardia (AR$)
* Porcentaje, bruto o neto?
* Salario bruto mensual (AR$)
* Cómo creés que está tu sueldo hoy en día
* Cómo creés que está tu sueldo con respecto a como estaba hace 6 meses
* Cambiaste de empresa en los últimos 6 meses?
* Cuál fue el principal motivo de cambio?
* Beneficios
* Tuviste algún aumento de sueldo en los últimos 6 meses?
* Qué porcentaje?

### 2016.01

* Timestamp
* Soy
* Tengo
* Trabajo en
* Años de experiencia
* Años en el puesto actual
* Trabajo de
* Tecnologías que utilizás
* Tecnologías que utilizás
* Automation o funcional?
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tenés guardias?
* Cuánto cobrás por guardia (AR$)
* Porcentaje, bruto o neto?
* Tipo de contrato
* Salario mensual (AR$)
* Bruto o neto?
* Qué tan conforme estás con tu sueldo?
* Cómo creés que está tu sueldo con respecto a Julio 2015
* Recibís algún tipo de bono
* A qué está atado el bono
* Tuviste ajustes por inflación en 2015?
* De qué % fue el ajuste anual?
* Cantidad de empleados
* Cambiaste de empresa en los últimos 6 meses?
* Cuál fue el principal motivo de cambio?
* Beneficios extra

### 2016.02

* Soy
* Tengo
* Argentina
* Años de experiencia
* Años en el puesto actual
* Trabajo de
* Tecnologías que utilizás
* Tecnologías que utilizás
* Automation o funcional?
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tenés guardias?
* Cuánto cobrás por guardia (en tu moneda local)
* Porcentaje, bruto o neto?
* Tipo de contrato
* Salario mensual (en tu moneda local)
* Bruto o neto?
* Qué tan conforme estás con tu sueldo?
* Cómo creés que está tu sueldo con respecto a Enero 2016
* Recibís algún tipo de bono
* A qué está atado el bono
* Tuviste ajustes por inflación este año?
* De qué % fue el ajuste?
* Cantidad de empleados
* Cambiaste de empresa en los últimos 6 meses?
* Cuál fue el principal motivo de cambio?
* Beneficios extra

### 2017.01

* Soy
* Tengo
* Argentina
* Años de experiencia
* Años en el puesto actual
* Trabajo de
* Gente a cargo?
* Cuánta?
* Tecnologías que utilizás
* Tecnologías que utilizás
* Automation o funcional?
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tenés guardias?
* Cuánto cobrás por guardia (en tu moneda local)
* Porcentaje, bruto o neto?
* Tipo de contrato
* Salario mensual (en tu moneda local)
* Bruto o neto?
* Qué tan conforme estás con tu sueldo?
* Cómo creés que está tu sueldo con respecto a Julio 2016
* Recibís algún tipo de bono
* A qué está atado el bono
* Tuviste ajustes por inflación en 2016?
* De qué % fue el ajuste?
* Cantidad de empleados
* Cambiaste de empresa en los últimos 6 meses?
* Cuál fue el principal motivo de cambio?
* Beneficios extra

### 2017.02

* Me identifico
* Tengo
* Argentina
* Años de experiencia
* Años en el puesto actual
* ¿Gente a cargo?
* ¿Cuánta?
* Trabajo de
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tecnologías que utilizás
* Automation o funcional?
* Tecnologías que utilizás
* Tecnologías que utilizás
* ¿Tenés guardias?
* Cuánto cobrás por guardia (en tu moneda local)
* ¿Porcentaje, bruto o neto?
* Tipo de contrato
* Salario mensual (en tu moneda local)
* ¿Bruto o neto?
* ¿Qué tan conforme estás con tu sueldo?
* Cómo creés que está tu sueldo con respecto a Enero 2017
* Recibís algún tipo de bono
* A qué está atado el bono
* ¿Tuviste ajustes por inflación en 2017?
* ¿De qué % fue el ajuste?
* Cantidad de empleados
* ¿Cambiaste de empresa en los últimos 6 meses?
* ¿Cuál fue el principal motivo de cambio?
* Beneficios extra

### 2018.01

* Me identifico
* Tengo
* Argentina
* Años de experiencia
* Años en el puesto actual
* ¿Gente a cargo?
* ¿Cuánta?
* Nivel de estudios alcanzado
* Estado
* Carrera
* Realizaste cursos de especialización
* Trabajo de
* Tecnologías que utilizás
* Tecnologías que utilizás
* Tecnologías que utilizás
* Automation o funcional?
* Tecnologías que utilizás
* Tecnologías que utilizás
* ¿Tenés guardias?
* Cuánto cobrás por guardia (en tu moneda local)
* "¿Porcentaje, bruto o neto?"
* Tipo de contrato
* Salario mensual (en tu moneda local)
* ¿Bruto o neto?
* ¿Qué tan conforme estás con tu sueldo?
* Cómo creés que está tu sueldo con respecto a julio 2017
* Recibís algún tipo de bono
* A qué está atado el bono
* ¿Tuviste ajustes por inflación en 2017?
* ¿De qué % fue el ajuste?
* Cantidad de empleados
* ¿Cambiaste de empresa en los últimos 6 meses?
* ¿Cuál fue el principal motivo de cambio?
* Beneficios extra
