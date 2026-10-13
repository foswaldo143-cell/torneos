# Números y rentabilidad

*Cálculo al 13/10/2026 · Tasa BCV: Bs 876,80 por USD*

## Supuesto (peor caso para la caja)

Queda **un solo jugador en pie** y todos los demás mueren por kill de otro jugador: con *n* jugadores se pagan **n − 1 kills**. El moderador no paga entrada y se asume que lo eliminan (se paga el bono). Por eso no hace falta un tope de kills: el total nunca pasa de n − 1, sin importar quién las haga.

## Montos

- Entrada: **Bs 3.000** · Pago por kill: **Bs 2.000** (fijos en bolívares).
- Bono por eliminar al moderador: **$10** (Bs 8.768).
- Premios top 3 por escalón (se pagan en Bs a tasa BCV):

| Inscritos | Multiplicador | 1.º | 2.º | 3.º |
|---|---|---|---|---|
| Menos de 50 | ×1 | $5 | $3 | $2 |
| 50 a 74 | ×2 | $10 | $6 | $4 |
| 75 a 99 | ×3 | $15 | $9 | $6 |
| 100 (sala llena) | ×4 | $20 | $12 | $8 |

## Fórmula

```
Ganancia = n × 3.000 − (n − 1) × 2.000 − (premios del escalón + bono) × tasa BCV
```

- Cada jugador extra suma **Bs 1.000**.
- Punto de equilibrio: **16 jugadores** (con bono de $9 bajaría a 15).

## Ganancia por partida

| Jugadores | Ganancia | En USD |
|---|---|---|
| 15 | Bs −536 | −$0,61 |
| 16 | Bs 464 | $0,53 |
| 25 | Bs 9.464 | $10,79 |
| 49 | Bs 33.464 | $38,17 |
| 50 | Bs 25.696 | $29,31 |
| 75 | Bs 41.928 | $47,82 |
| 99 | Bs 65.928 | $75,19 |
| 100 | Bs 58.160 | $66,33 |

Ojo: al pasar a un escalón nuevo la ganancia baja un poco (49 deja más que 50). Es intencional: el premio más grande es el gancho para llenar la sala.

## Proyección mensual (32 partidas: lunes a jueves + sábado + domingo)

| Jugadores por partida | Ganancia al mes |
|---|---|
| 25 | Bs 302.848 · ~$345 |
| 50 | Bs 822.272 · ~$938 |
| 100 | Bs 1.861.120 · ~$2.123 |

Antes de publicidad ($150–200 al mes), comisiones bancarias y datos.

## Cuidado con la inflación

Los montos están fijos en bolívares, pero los premios se piensan en dólares. Revisar cada mes y subir entrada y kill de forma proporcional cuando el dólar suba mucho.

La calculadora de la página permite cambiar todos estos valores.
