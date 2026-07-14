# ARIMA del indicador ID19 por CSMC

**Fecha:** 2026-07-13  
**Unidad:** CSMC-mes  
**Modelo:** ARIMA univariado del indicador mensual, sin covariables externas  
**Horizonte:** 2026-06 a 2026-12  

## Resultado operativo

- CSMC unicos armonizados: 268.
- CSMC con ARIMA ajustado: 211.
- CSMC no modelados por continuidad insuficiente: 57.
- Modelos con criterio estricto: 167.
- Modelos con criterio basico solamente: 44.
- Mediana MAE en validacion 2026-01 a 2026-05: 0.1897.
- Mediana RMSE en validacion 2026-01 a 2026-05: 0.2218.

## Conversion a cumplimiento ID19

Resultado principal entre los 211 CSMC con ARIMA ajustado:

- LOGRA: 99 CSMC.
- NO LOGRA por indicador proyectado debajo de la meta: 105 CSMC.
- NO LOGRA por denominador proyectado menor de 30: 7 CSMC.

Por tanto, segun este corte ARIMA, **99 CSMC lograrian y 112 CSMC no lograrian**.

En el universo total de 268 CSMC, 57 quedan como `NO_MODELADO` por continuidad insuficiente y no deben mezclarse con el conteo principal.

## Lectura con IC95%

Entre los 211 CSMC con ARIMA ajustado:

- LOGRA ROBUSTO IC95: 22 CSMC.
- INCIERTO, porque el IC95 cruza la meta: 162 CSMC.
- NO LOGRA ROBUSTO IC95: 20 CSMC.
- NO LOGRA por denominador proyectado menor de 30: 7 CSMC.

Lectura: el conteo puntual es 99 vs 112, pero con IC95% el rango compatible de CSMC que podrian lograr va de 22 a 184. La mayoria queda en zona incierta porque el intervalo cruza la meta.

## Escenario para alcanzar 70%

Para alcanzar 70% de cumplimiento entre los 211 CSMC modelados, se necesitan 148 CSMC que logren la meta. Como el escenario puntual actual tiene 99, faltan 49 CSMC adicionales.

La modificacion operativa recomendada no es cambiar el modelo, sino aumentar el numerador en CSMC cercanos a la meta:

- CSMC adicionales a rescatar: 49.
- Paquetes completos adicionales estimados: 468.
- Mediana de paquetes adicionales por CSMC rescatado: 9.
- Maximo en los 49 priorizados: 18.

Si el objetivo se interpreta como 70% de los 268 CSMC totales, no solo de los modelados, se requieren 188 CSMC que logren la meta. Eso exige 89 CSMC adicionales y 1,512 paquetes completos adicionales, manteniendo como no cumplidores a los no modelados.

## Logro esperado nuevo 30%-50%

Javier propuso una nueva tabla de logro esperado para negociación 2026:

| Denominador anual proyectado | Logro esperado nuevo |
|---|---:|
| 10-39 pacientes | 50% |
| 40-59 pacientes | 45% |
| 60-100 pacientes | 40% |
| 101-150 pacientes | 35% |
| >150 pacientes | 30% |

Con esta regla, el conteo puntual cambia así:

- CSMC que cumplirían con el logro esperado nuevo: 118/211 modelados.
- Porcentaje de cumplimiento entre modelados: 55.9%.
- CSMC necesarios para llegar a 70% entre modelados: 148.
- CSMC adicionales a focalizar: 30.
- Paquetes completos adicionales estimados: 166.
- Mediana de paquetes adicionales por CSMC focalizado: 5.5.
- Máximo en los 30 priorizados: 9.
- CSMC que quedarían bajo el logro esperado nuevo tras rescatar 30: 63.

Lectura estratégica: esta tabla es consistente como "logro esperado nuevo", pero no alcanza 70% por sí sola. Para convertirla en un escenario de 70%, debe acompañarse de una focalización mínima de 30 CSMC.

## Nuevo umbral negociado 20%-40%

Javier propuso un nuevo umbral transitorio para negociación 2026, con piso de denominador desde 10 pacientes:

| Denominador anual proyectado | Nuevo umbral |
|---|---:|
| 10-39 pacientes | 40% |
| 40-59 pacientes | 35% |
| 60-100 pacientes | 30% |
| 101-150 pacientes | 25% |
| >150 pacientes | 20% |

Con esta regla, el conteo puntual cambia así:

- CSMC que cumplirían con el nuevo umbral: 148/211 modelados.
- Porcentaje de cumplimiento entre modelados: 70.1%.
- CSMC adicionales requeridos para alcanzar 70%: 0.
- Paquetes completos adicionales requeridos para alcanzar 70%: 0.
- CSMC que quedan bajo el nuevo umbral: 63.
- CSMC con denominador proyectado menor de 10 entre modelados: 0.

Lectura estratégica: esta regla alcanza el 70% entre CSMC modelados sin rescate adicional. La focalización cambia de "rescatar 14" a "vigilar 63 que todavía quedan bajo el nuevo umbral si se quiere superar o blindar el 70%".

## Escenario negociado con valor umbral

Si para el cierre 2026 se negocia usar el `valor umbral` como meta transitoria, el cumplimiento puntual sube de 99 a 134 CSMC entre los 211 modelados.

Para llegar a 70% entre modelados bajo este criterio se requieren 148 CSMC que cumplan. Por tanto, faltan 14 CSMC adicionales, focalizados por menor brecha al umbral.

- CSMC que cumplirían usando umbral: 134.
- CSMC adicionales a focalizar: 14.
- Paquetes completos adicionales estimados: 44.
- Mediana de paquetes adicionales por CSMC focalizado: 3.
- Máximo en los 14 priorizados: 5.

Lectura estratégica: este escenario no modifica la ficha oficial ni la meta esperada; sirve como argumento de negociación para una meta transitoria 2026 basada en el umbral y una focalización operativa mínima.

## Armonizacion de nombres

La llave canonica es `renaes` de 8 digitos. El nombre del CSMC se trata como etiqueta.

- 264 CSMC quedaron con un solo nombre limpio.
- 4 CSMC tuvieron variantes de nombre y fueron resueltos por `renaes`.

Los cuatro casos con variantes fueron:

| RENAES | Nombre canonico | Variantes |
|---|---|---|
| 00021228 | CENTRO DE SALUD MENTAL COMUNITARIA DRA. FRIDA ALAYZA COSSIO | con/sin `TRUJILLO` |
| 00026345 | CENTRO DE SALUD MENTAL COMUNITARIO MAEICH MUCHIK | con/sin `MOCHE` |
| 00031810 | CENTRO DE SALUD MENTAL COMUNITARIO I 3 - CONTAMANA | variante `CENTRO DE SALUD MENTAL COMUNITARIO - CONTAMANA` |
| 00034214 | CENTRO DE SALUD MENTAL COMUNITARIO FORTALECIENDO VIDAS | con/sin punto final |

## Criterios de inclusion ARIMA

- **Basico:** al menos 18 meses observados, al menos 12 meses consecutivos y dato en 2026-05.
- **Estricto:** al menos 24 meses observados, al menos 18 meses consecutivos y dato en 2026-05.

## Especificacion

- Transformacion: `logit(indicador)` con epsilon 0.005 para mantener predicciones entre 0 y 1.
- Grid: `p = 0..2`, `d = 0..1`, `q = 0..2`.
- Seleccion: minimo AIC.
- Validacion: entrenamiento 2024-01 a 2025-12 y comparacion contra 2026-01 a 2026-05 cuando existia dato observado.

## Supuesto de conversion

El denominador anual 2026 se proyecto como:

`denominador observado enero-mayo + 7 x promedio mensual observado enero-mayo`.

El numerador anual 2026 se proyecto como:

`numerador observado enero-mayo + suma(denominador mensual proyectado x indicador mensual ARIMA)`.

## Limite importante

No hay DNI para deduplicar personas entre meses; este corte usa un acumulado operativo mensual proyectado. Es suficiente para responder la pregunta de conteo segun ARIMA, pero debe rotularse como pronostico operativo, no como medicion final oficial.

## Archivos principales

- `arima_indicator_csmc_forecasts.xlsx`
- `arima_indicator_dec2026_summary.csv`
- `arima_indicator_forecast_2026_jun_dec.csv`
- `arima_indicator_models_by_csmc.csv`
- `arima_indicator_series_inputs.csv`
- `csmc_name_crosswalk.csv`
- `arima_id19_compliance_forecast.xlsx`
- `arima_id19_compliance_by_csmc.csv`
- `arima_id19_compliance_by_region.csv`
- `id19_csmc_arima_findings.html`
- `arima_id19_compliance_ci95_by_csmc.csv`
- `arima_id19_compliance_ci95_summary.csv`
- `scenario_70pct_rescue_by_csmc.csv`
- `scenario_70pct_summary.csv`
- `scenario_threshold_transitory_by_csmc.csv`
- `scenario_threshold_rescue_by_csmc.csv`
- `scenario_threshold_rescue_14_by_csmc.csv`
- `scenario_threshold_summary.csv`
- `scenario_threshold_by_region.csv`
- `scenario_custom_threshold_by_csmc.csv`
- `scenario_custom_threshold_by_region.csv`
- `scenario_custom_threshold_focus_by_csmc.csv`
- `scenario_custom_threshold_focus_selected_by_csmc.csv`
- `scenario_custom_threshold_summary.csv`
- `scenario_custom_threshold_focus_by_region.csv`
- `scenario_new_expected_by_csmc.csv`
- `scenario_new_expected_by_region.csv`
- `scenario_new_expected_focus_by_csmc.csv`
- `scenario_new_expected_focus_30_by_csmc.csv`
- `scenario_new_expected_summary.csv`
- `scenario_new_expected_focus_by_region.csv`
