# Torneos CoD Mobile

Comunidad de torneos pagos de **Call of Duty Mobile** (Battle Royale en sala privada) con pago por kill, premios al top 3 y un moderador al que todos cazan.

> Estado: **fase de definición** (13/10/2026). Todavía no hay nada operando.

**Socios:** Oswaldo Farias (cuentas, pagos, banco, legal) · Marcos (operativo, redes, diseño, publicidad y moderación).

## Qué hay en este repositorio

| Ruta | Para qué sirve |
|---|---|
| `index.html` | App para el teléfono con 3 pestañas: **Calculadora** (ganancia por partida y por mes), **Plan** (tareas por socio) y **Acuerdos** (reglas y decisiones). Es lo que publica Vercel. |
| `docs/00-resumen-del-negocio.md` | Qué es el negocio, cómo funciona y quién hace qué. |
| `docs/01-analisis-y-riesgos.md` | Opinión objetiva: lo que puede salir bien, lo que puede salir mal y cómo prevenirlo. |
| `docs/02-numeros-y-rentabilidad.md` | Cálculos base: margen por torneo, punto de equilibrio, sensibilidad. |
| `docs/03-plan-de-accion.md` | Lista de tareas por fases, con casillas para ir marcando. |
| `docs/04-bitacora-de-decisiones.md` | Registro de cada decisión tomada, con fecha y motivo. |
| `docs/05-definiciones.md` | Todas las respuestas de definición del negocio. |
| `docs/06-portal.md` | Especificación del portal de jugadores (registro, inscripción, cupos, referidos). |
| `docs/07-ideas-futuras.md` | Ideas registradas para más adelante. |

## Cómo usar la página

1. Abre el enlace de Vercel en el teléfono. Tip: "Agregar a pantalla de inicio" para usarla como app.
2. **Calculadora:** mueve la cantidad de jugadores y las partidas al mes. En *Ajustes* cambias entrada, kill, premios y tasa BCV.
3. **Plan:** marca las tareas listas. Filtra por Oswaldo o Marcos.
4. **Acuerdos:** todo lo decidido hasta ahora (formato, dinero, moderador, inscripción, reglas, equipo). Enlace directo: `…vercel.app/#acuerdos`.
5. Las marcas se guardan **solo en ese teléfono**. Toca **Copiar avance** y pégalo en el chat con Claude para mantener el plan al día.

Las preguntas de definición del negocio se responden en el chat, no en la página.

## Publicar en Vercel (una sola vez)

1. Entra a [vercel.com](https://vercel.com) con tu cuenta de GitHub.
2. **Add New → Project** → elige el repositorio `torneos` → **Import**.
3. Framework Preset: **Other**. No hace falta build command ni output directory.
4. **Deploy**. Cada `git push` a `main` actualiza la página sola.
5. Comparte el enlace `*.vercel.app` con tu socio.

## Subir cambios desde la PC

```bash
cd C:\Users\foswa\Documents\torneos
git add .
git commit -m "Describe el cambio"
git push
```
