### Programa ejecuciones por tiempo

El **schedule** permite desencadenar un flujo de trabajo para poder ejecutar a horas UTC.

La sintaxis de cron tiene cinco campos **"*"**
y **cada campo representa una unidad de tiempo**

- El primer * representa los minutos
- El segundo * representa las horas
- El tercer * representa los dias del mes
- El cuarto * representa el mes (1 -12 o ENE - DIC)
- El quinto * representa los dias de la semana
(0 - 6 o DOM - SAB)

EJEMPLO :
cada domingo a las 3:00

```yml
on:
  schedule:
    - cron:  '0 3 * * SUN'
```

<hr>