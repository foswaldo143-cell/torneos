# Números y rentabilidad

*Cálculo base al 13/10/2026 · Tasa BCV: Bs 876,80 por USD*

## Supuesto principal (peor caso para la caja)

Queda **un solo jugador en pie** y todos los demás mueren por kill de otro jugador. Con *n* jugadores pagos se pagan **n − 1 kills**. El moderador entra aparte, no paga entrada y se asume que lo eliminan (se paga el bono).

En la práctica algunas muertes son por zona o caídas, así que la ganancia real será un poco mayor.

## Fórmula

```
Ganancia = n × entrada − (n − 1) × pago por kill − (premios top 3 + bono moderador) × tasa BCV
```

Con los montos actuales: entrada Bs 3.000, kill Bs 2.000, premios $22 + bono $10 = $32 (Bs 28.058).

- Cada jugador extra suma **Bs 1.000**.
- Punto de equilibrio: **27 jugadores**.

## Ganancia por partida

| Jugadores | Entradas | Kills pagadas | Premios + bono | Ganancia | En USD |
|---|---|---|---|---|---|
| 20 | Bs 60.000 | Bs 38.000 | Bs 28.058 | Bs −6.058 | −$6,91 |
| 27 | Bs 81.000 | Bs 52.000 | Bs 28.058 | Bs 942 | $1,07 |
| 30 | Bs 90.000 | Bs 58.000 | Bs 28.058 | Bs 3.942 | $4,50 |
| 49 | Bs 147.000 | Bs 96.000 | Bs 28.058 | Bs 22.942 | $26,17 |
| 75 | Bs 225.000 | Bs 148.000 | Bs 28.058 | Bs 48.942 | $55,82 |
| 99 | Bs 297.000 | Bs 196.000 | Bs 28.058 | Bs 72.942 | $83,19 |

## Proyección mensual (con 49 jugadores por partida)

| Partidas al mes | Ganancia aprox. |
|---|---|
| 8 (fines de semana) | $209 |
| 20 (días hábiles) | $523 |
| 30 (1 diaria) | $785 |
| 60 (2 diarias) | $1.570 |

Antes de publicidad, pago al moderador, comisiones bancarias y datos móviles.

## Lo que más mueve el resultado

1. **Cupo:** por debajo de 27 jugadores se pierde.
2. **Margen por jugador:** con Bs 1.000 es estrecho. Subir la entrada a Bs 3.500 o bajar el kill a Bs 1.800 cambia mucho el punto de equilibrio.
3. **Tasa BCV:** los premios están en dólares; si la entrada queda fija en Bs y el dólar sube, la ganancia baja.
4. **Pago al moderador:** cada $5 por partida sube el equilibrio en unos 5 jugadores.

## Ojo con la licencia

Si Activision aprueba el torneo con la condición de que la inscripción no financie premios, este modelo hay que rediseñarlo. Ver `01-analisis-y-riesgos.md`, riesgo 1.

La calculadora de la página permite cambiar todos estos valores.
