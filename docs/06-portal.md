# Portal de jugadores · especificación

*Borrador 13/10/2026*

## Para qué

Que todo pase por la página, desde el teléfono, y que se sienta un producto "top":

- El jugador crea su usuario.
- Se verifica una sola vez.
- Se inscribe en cada torneo con su captura de pago.
- Ve sus cupos y sus referidos.

El equipo aprueba con un toque. Telegram queda solo para la comunidad y los avisos.

## Lo que ve el jugador

| Pantalla | Qué hace |
|---|---|
| Registro | Nombre, teléfono, usuario de Activision, foto de cédula, datos de pago móvil para cobrar premios, código de referido (opcional). |
| Estado de verificación | "En revisión" → "Verificado" (cuando ya está en el clan). |
| Próximos torneos | Fecha, hora, inscritos / cupo, escalón de premios actual ("¡faltan 6 para premios ×2!"). |
| Inscribirme | Subir captura del pago móvil o Binance + número de referencia. O usar un cupo gratis. |
| Mis cupos | Cupos gratis disponibles (por referidos o por desconexión al inicio) y su origen. |
| Mis referidos | Su código, a quién invitó y cuántos cupos ganó. |
| Reglamento | Siempre a mano. |

## Lo que ve el equipo (panel admin)

| Pantalla | Qué hace |
|---|---|
| Verificaciones | Ver la cédula, aprobar o rechazar. La foto se borra después de aprobar. |
| Pagos por aprobar | Captura + referencia → aprobar o rechazar con un toque. |
| Torneo en curso | Lista de inscritos aprobados, ID de la sala para enviar, cierre de inscripción. |
| Resultados | Cargar kills por jugador y top 3 → calcula cuánto pagarle a cada uno y lo marca como pagado. |
| Cupos | Dar un cupo manual (ej. desconexión al inicio). |
| Reportes | Ingresos, kills pagadas, premios, ganancia por torneo y por mes. |

## Reglas que el portal aplica solo

- Solo jugadores verificados pueden inscribirse.
- Cupo mínimo y máximo por torneo; la inscripción se cierra cuando se llena la sala o 1 hora antes.
- Premios por escalón según inscritos aprobados (×1, ×2, ×3, ×4).
- Referido: cuando el invitado juega su primer torneo pago, el que lo invitó recibe un cupo gratis.
- Jugadores baneados no pueden inscribirse hasta que se cumpla la sanción.

## Tecnología propuesta

- **Vercel** para la página (ya lo usan).
- **Supabase** (plan gratis) para usuarios, base de datos y fotos.
- Inicio de sesión con número de teléfono o correo.
- Fotos de cédula en almacenamiento privado; solo el equipo puede verlas.

## Fases

1. **v1 (antes del piloto):** registro, verificación, torneos, inscripción con captura, aprobación, resultados y pagos.
2. **v2 (lanzamiento):** cupos, referidos, escalón en vivo, reportes.
3. **v3 (escala):** torneos grandes, clasificatorios, pagos internacionales por Binance.
