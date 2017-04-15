# Weight-converter

Modulo que convierte medidas de kilogramos a libras y viceversa.

## Descripcion de la conversion

* Las conversiones disponibles son las siguientes:
  * De kilogramos a libras.
  * De libras a kilogramos.
* Se pueden convertir varias medidas a la vez.

## Instalacion

```
npm install @bladelizard/weight-converter
```

## Uso

```
import { kgToPounds, poundsToKg } from '@bladelizard/weight-converter'

kgToPounds(1) // 2.20462
kgToPounds(2.5) // 5.51155
kgToPounds(5) // 11.0231
kgToPounds(1, 2.5, 5) // [2.20462, 5.51155, 11.0231]

poundsToKg(1) // 0.453592
poundsToKg(2.5) // 1.13398
poundsToKg(5) // 2.26796
poundsToKg(1, 2.5, 5) // [0.453592, 1.13398, 2.26796]
```

## Creditos
- [Gabriel Nunez](https://twitter.com/@bladelizzard)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
