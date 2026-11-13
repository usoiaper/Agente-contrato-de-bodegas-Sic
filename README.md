# Agente de bodegas SIC – Contrato 1077 de 2026

Agente de Claude Code para apoyar la supervisión del Contrato 1077 de 2026 (arrendamiento de las bodegas 10-11, 44 y 48 de la SIC – Documentos Inteligentes S.A.S.).

## Estructura

| Ruta | Contenido |
|---|---|
| `Agente_de_bodegas_sic.md` | Memoria del contrato (se actualiza tras cada cambio importante) |
| `CLAUDE.md` | Instrucciones que Claude Code carga al abrir el repositorio |
| `.claude/agents/agente-bodegas-sic.md` | Definición del agente (reglas, formato, entregables) |
| `.claude/skills/preinforme-recorrido` | Lista de chequeo previa al recorrido |
| `.claude/skills/informe-verificacion` | Informe de verificación mensual |
| `.claude/skills/respuesta-ans` | Respuesta al Cuadro de novedades (ANS) con la Matriz v2 |
| `.claude/skills/actualizar-memoria` | Actualización de la memoria |
| `documentos/` | Documentos fuente |
| `entregables/` | Documentos generados |

## Uso

Abre el repositorio con Claude Code y pide, por ejemplo:

- «Prepara el preinforme del recorrido de noviembre».
- «Revisa el Cuadro de novedades de octubre y proyecta la respuesta de ANS».
- «¿Qué dice el AT sobre los dataloggers?»
- «Actualiza la memoria con lo que hicimos hoy».

También puedes invocar el agente directamente: `@agente-bodegas-sic`.
