# Números y rentabilidad

*Cálculo base al 13/10/2026 · Tasa BCV: Bs 876,80 por USD*

## Supuestos

- Modo **solo**, sin redespliegue: cada jugador muere como máximo una vez.
- En una sala con *n* jugadores pagos más el moderador, hay *n* muertes (todos menos el ganador).
- No todas las muertes son kills de un jugador: zona, caídas y vehículos no se pagan. Caso esperado: **80 %** de las muertes son kills.
- Premios fijos: top 3 ($22) + bono del moderador ($10) = **$32 = Bs 28.058**.
- Moderador sin pago (por ahora).

## Margen por jugador

| Caso | Fórmula | Margen por jugador |
|---|---|---|
| Esperado (80 % kills) | 3.000 − 2.000 × 0,8 | **Bs 1.400** |
| Peor caso (100 % kills) | 3.000 − 2.000 | **Bs 1.000** |

## Punto de equilibrio

| Caso | Cálculo | Jugadores mínimos |
|---|---|---|
| Esperado | 28.058 ÷ 1.400 | **21** |
| Peor caso | 28.058 ÷ 1.000 | **29** |

## Escenarios por torneo (caso esperado)

| Jugadores | Ingreso | Kills pagadas | Premios fijos | Margen | Margen en USD |
|---|---|---|---|---|---|
| 20 | Bs 60.000 | Bs 32.000 | Bs 28.058 | Bs −58 | ≈ $0 |
| 30 | Bs 90.000 | Bs 48.000 | Bs 28.058 | Bs 13.942 | $15,90 |
| 49 | Bs 147.000 | Bs 78.000 | Bs 28.058 | Bs 40.942 | $46,70 |
| 75 | Bs 225.000 | Bs 120.000 | Bs 28.058 | Bs 76.942 | $87,75 |
| 99 | Bs 297.000 | Bs 158.000 | Bs 28.058 | Bs 110.942 | $126,53 |

*Kills redondeadas al entero más cercano (ej.: 49 × 0,8 = 39 kills).*

## Proyección mensual (1 torneo diario, 26 días)

| Jugadores promedio | Margen mensual aprox. |
|---|---|
| 30 | $413 |
| 49 | $1.214 |
| 75 | $2.282 |

Antes de costos: publicidad, pago al moderador, comisiones bancarias, datos móviles y el tiempo del equipo.

## Lo que más mueve el resultado

1. **Cupo:** cada jugador extra suma ~Bs 1.400.
2. **Redespliegue:** si se permite, el peor caso puede pasar a pérdida.
3. **Tasa BCV:** si la entrada queda fija en Bs y el dólar sube, los premios en USD cuestan más cada semana.
4. **Pago al moderador:** cada $5 por torneo sube el equilibrio en unos 3 jugadores.

## Ojo con la licencia

Si Activision aprueba el torneo con la condición de que la inscripción no financie premios, este modelo hay que rediseñarlo. Ver `01-analisis-y-riesgos.md`, riesgo 1.

El simulador de la página (`index.html`, sección 00) permite cambiar todos estos valores.
