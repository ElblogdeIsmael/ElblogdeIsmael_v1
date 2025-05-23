# Ejercicios Propuestos Tema 6: Impuesto sobre beneficios


La empresa ALFA, S. L. ha adquirido el 1 de enero del año 2020 una maquinaria por valor de 40.000 €, con una vida útil estimada de 10 años. Según la normativa fiscal, la empresa puede aplicar un coeficiente máximo de amortización del 8%.

Los datos para la contabilización del impuesto sobre el beneficio de las sociedades del ejercicio 2020 son los siguientes: beneficio contable, 60.000 €; deducciones fiscales, 1.000 € y pagos a cuenta del Impuesto de Sociedades, 500 €. Los datos para la contabilización del impuesto sobre el beneficio de sociedades del último ejercicio en el que se producen efectos fiscales de la amortización de la maquinaria son los siguientes: beneficio contable, 40.000 €; deducciones fiscales, 2.000 € y pagos a cuenta del Impuesto de Sociedades, 800 €.

**SE PIDE:** Sabiendo que el tipo de gravamen del Impuesto de Sociedades es del 30%, contabilice las siguientes operaciones:

* Cálculo del impuesto corriente:
  * Debemos de tener en cuenta que en cuanto a a amortización fiscal, esta es como máximo del 8%.

| Año  | Contable (VIDA ÚTIL: 10 AÑOS) | Fiscal (VIDA ÚTIL: 12.5 AÑOS) | Diferencia Liquidación | Signo |
|------|-------------------------------|--------------------------------|------------------------|-------|
| 2020 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2021 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2022 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2023 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2024 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2025 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2026 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2027 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2028 | 4.000,00                     | 3.200,00                      | 800,00                | (+)   |
| 2029 | 0,00                         | 3.200,00                      | -3.200,00             | Ajuste (+) |
| 2030 | 0,00                         | 3.200,00                      | -3.200,00             | Ajuste (+) |
| 2031 | 0,00                         | 3.200,00                      | -3.200,00             | Ajuste (+) |
| 2032 | 0,00                         | 1.600,00                      | -1.600,00             | Ajuste (+) |
| **Total** | **40.000,00**           | **40.000,00**                 |                        |       |

### Nota

---
En los años de reversión (2029-2032), la amortización fiscal (3.200 €) es mayor que la contable (0 €). Esto significa que:

- Contablemente, no hay gasto de amortización.
- Fiscalmente, sí hay gasto de amortización.

Para pasar del Resultado Contable a la Base Imponible Fiscal, debemos restar esos 3.200 € (o 1.600 €) que fiscalmente son deducibles. Esta resta disminuye la Base Imponible Fiscal.

Por lo tanto, la interpretación del "Ajuste (+)" en esos años debería ser que estas diferencias temporarias (ahora deducibles) se están aplicando para reducir la base imponible fiscal y, consecuentemente, el impuesto a pagar. Aunque el número en la columna "Diferencia Liquidación" es negativo (-3.200 €), el efecto en el cálculo de la base imponible es de una deducción fiscal, lo cual es beneficioso para la empresa y por eso se puede considerar un "ajuste positivo" en el sentido de que favorece al contribuyente al reducir la base.

Es crucial entender que, en los primeros años, la empresa está pagando más impuestos de lo que lo haría si aplicara la amortización contable (diferencia temporaria imponible). En los años finales, la empresa pagará menos impuestos gracias a la amortización fiscal pendiente (diferencia temporaria deducible). La tabla parece estar enfocada en cómo estas diferencias afectan la base imponible a lo largo del tiempo, y el "Ajuste (+)" en los años de reversión indica que se está aplicando un beneficio fiscal que reduces la base imponible.

---

<!-- ---
|Cabe destacar que en la práctica la resolución de ejercicios se realiza de manera contraria|
--- -->

| Concepto                                | 2020      | 2032      |
|-----------------------------------------|-----------|-----------|
| Rdo. Ejercicio                          | 60.000,00 | 40.000,00 |
| (+/-) Diferencias Permanentes           | 0,00      | 0,00      |
| (+/-) Diferencias Temporarias (maquina) | 800,00    | -1.600,00 |
| (=) BI Previa                           | 60.800,00 | 38.400,00 |
| (-) Rdos. Negativos años anteriores     | 0,00      | 0,00      |
| (=) Bimponible                          | 60.800,00 | 38.400,00 |
| (x) Tipo Gravamen (30%)                 | 0,30      | 0,30      |
| (=) Cuota Íntegra                       | 18.240,00 | 11.520,00 |
| (-) Deducciones/Bonificaciones          | -1.000,00 | -2.000,00 |
| (=) Cuota Líquida (6300)                | 17.240,00 | 9.520,00  |
| (-) Retenciones y P/Cta (473)           | -500,00   | -800,00   |
| (=) Cuota Diferencial (4752)            | 16.740,00 | 8.720,00  |

Llegado hasta este punto, el impuesto corriente coincide con la cuota líquida y el asiento quedaría de la siguiente manera:
|DEBE|Asiento relativo al impuesto corriente del ejercicio 2020|HABER|
|-------|-------------------------------------------------------------|-------|
|17.240 | 6300. Impuesto corriente. ||
|473 | H.P. retenciones y pagos a cuenta|500|
|4752 | H.P. Acreedora por impuesto de sociedades ||

Vemos que el último año con amortización fiscal es el 2032.

|DEBE|Asiento relativo al impuesto corriente del último ejercicio con efectos fiscales de la amortización de la maquinaria|HABER|
|-------|-------------------------------------------------------------|-------|
|9.520 | 6300. Impuesto corriente. ||
|473 | H.P. retenciones y pagos a cuenta|800|
|4752 | H.P. Acreedora por impuesto de sociedades |8.720|

En cuanto al impuesto diferido, vemos que a finales del 2032 tenemos una diferencia temporaria negativa, por ende, 1.600 x 30% = 480
<!-- |DEBE|Asiento relativo al impuesto diferido del último ejercicio con efectos fiscales de la amortización de la maquinaria|HABER|
|-------|-------------------------------------------------------------|-------|
|||| -->
```
Asiento relativo al impuesto diferido del último ejercicio con efectos fiscales de la amortización de la maquinaria

480 6301. Impuesto diferido 
    a 474 Activo por diferencias temporarias deducibles

```

## Ejercicio Propuesto 2

La empresa C, S.L. ha obtenido un Resultado antes de impuestos de 100.000 € en el año 2022. Se tiene la siguiente información adicional:

1. El 5/3/20x22 le impusieron una sanción tributaria por importe de 500 €.
2. El 30/6/20x22 adquirió un elemento de transporte por 30.000 € y vida útil 3 años. La sociedad se acoge a libertad de amortización deduciéndose la mitad en el año 20x22 y la otra mitad en el año 20x23.
3. La sociedad tiene una Base Imponible negativa del ejercicio 2021 de 20.000 €, que contabilizó el año anterior.
4. La sociedad tiene derecho a una deducción fiscal de 4.000 €.
5. Las Retenciones y pagos a cuenta realizados durante el año 20x22 es de 60.000 €.

Sabiendo que el tipo impositivo es del 25%, **SE PIDE:** Contabilizar el 31/12/20x22.

* Asiento 31 de dic de 2022. Impuesto corriente del ejercicio 2022

| AÑO  | CONTABLE | FISCAL   | DIFERENCIA (Contable - Fiscal) | SIGNO/TIPO |
|------|----------|----------|-------------------------------|------------|
| 2022 | 5.000,00 | 15.000,00 | -10.000,00                   | (-)        |
| 2023 | 10.000,00 | 15.000,00 | -5.000,00                    | (-)        |
| 2024 | 10.000,00 | 0,00      | 10.000,00                    | Ajuste (-) |
| 2025 | 5.000,00  | 0,00      | 5.000,00                     | Ajuste (-) |

| AÑO  | CONTABLE | FISCAL | DIFERENCIA (Contable - Fiscal) | SIGNO/TIPO |
|------|----------|--------|-------------------------------|------------|
| 2022 | 500,00   | 0,00   | 500,00                        | (+)        |

```
100.000 + 500 -10.000 = BI PREVIA = 90.500
BI PREVIA - 20.000 = 70.500 = BI
BI X TIPO DE GRAVAMEN = BI X 0,25 = CUOTA ÍNTEGRA = 17.625 = CI
CI - DEDUCCIONES Y BONIFICACIONES = CI - 4.000 = 13.625 = CUOTA LÍQUIDA (impuesto corriente)

13.625 (6300) impuesto corriente 
    a 
    473 H.P retenciones y pagos a cuenta 60.000
    H.P Deudora por devolución de impuestos 46.375

```

* 31/12/2022 Diferencia del ejercicio 2022 referente a la sanción

```
Al ser una multa, corresponde con una diferencia PERMANENTE, la cual no genera asiento contable.

NPAC
```

* 31/12/2022 Diferencia del ejercicio 2022 TEMPORARIA de la libertad de amortización

```
Viendo la tabla, vemos que la diferencia de lo contable y fiscal = 10.000

10.000 x 0,25 = 2.500

2.500 (6301) Impuesto diferido 
    a
    (479) Pasivo por diferencias temporarias imponibles 2.500

¿Por que se usa aquí la cuenta de pasivo?

Una diferencia temporaria que genera un ahorro fiscal en el presente (Base Imponible actual más baja) pero que resultará en un mayor pago de impuestos en el futuro (Base Imponible futura más alta) es una diferencia temporaria imponible.
Las diferencias temporarias imponibles dan lugar al reconocimiento de un Pasivo por Impuesto Diferido (cuenta 479). Este pasivo representa la obligación que tiene la empresa de pagar más impuestos en el futuro debido a la reversión de esta diferencia temporal.

En resumen, se usa un pasivo porque la libertad de amortización te permite pagar menos impuestos ahora (ahorro fiscal), pero te obliga a pagar más en el futuro cuando esa diferencia se compense.
```

* 31/12/2022 Diferencia temporaria de la base imponible negativa

```
Aquí se refiere a la del año anterior, que recordemos que era 20.000, por ende nos queda: 20.000 x 0,25 = 5.000 = z

z (6301) Impuesto diferido 
    a
    (4745) Crédito por Pérdidas a compensar del ejercicio z 

```




