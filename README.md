# Torneos CoD Mobile

Comunidad de torneos pagos de **Call of Duty Mobile** (Battle Royale en sala privada) con pago por kill, premios al top 3 y un moderador al que todos cazan.

> Estado: **fase de definición** (13/10/2026). Todavía no hay nada operando.

## Qué hay en este repositorio

| Ruta | Para qué sirve |
|---|---|
| `index.html` | Página web del briefing: formulario de preguntas + simulador de rentabilidad. Es lo que publica Vercel. |
| `docs/00-resumen-del-negocio.md` | Qué es el negocio, cómo funciona y quién hace qué. |
| `docs/01-analisis-y-riesgos.md` | Opinión objetiva: lo que puede salir bien, lo que puede salir mal y cómo prevenirlo. |
| `docs/02-numeros-y-rentabilidad.md` | Cálculos base: margen por torneo, punto de equilibrio, sensibilidad. |
| `docs/03-plan-de-accion.md` | Lista de tareas por fases, con casillas para ir marcando. |
| `docs/04-bitacora-de-decisiones.md` | Registro de cada decisión tomada, con fecha y motivo. |

## Cómo usar la página

1. Abre el enlace de Vercel (o `index.html` en el navegador).
2. Responde las preguntas. Se guardan **solo en tu navegador**: cada socio tiene sus propias respuestas.
3. Al terminar, toca **Copiar respuestas** y pégalas en el chat con Claude para generar el plan de acción definitivo.

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
