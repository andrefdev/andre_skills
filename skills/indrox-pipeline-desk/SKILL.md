---
name: Indrox pipeline desk
description: >-
  Higienizar pipeline en Indrox CRM: deals stale, next step+fecha, motivo de
  pérdida; reportes mínimos para forecast real.
---
# Indrox pipeline desk

Adaptado de B2B RevOps Skills (MIT, Rutger Katz / Neon Triforce) v1.8.1.

## Cuándo usar

Revisión semanal de pipeline, forecast dudoso, "oportunidades zombie", o al preparar 1:1 comercial. Trigger: "pipeline", "higiene CRM", "stale", "forecast".

## Reglas duras (kit)

- Sistema: **Indrox CRM** (conector user-Indrox CRM-xai). Etapas alineadas a funnels kit (Core / Zentral) y GR-VTA / GR-DEM.
- Todo deal abierto exige **próximo paso + fecha**. Sin eso = no forecastable.
- Motivo de pérdida obligatorio al cerrar (alimenta C&V / revival).
- No usar benchmarks externos como claim al cliente. No inflar montos con descuentos inventados.
- Pricing en deals Zentral = D.3; Core = valor/alcance, no horas.

## Higiene mínima (semanal)

1. **Stale** — sin actividad logueada:
   - Discovery/Meet: ~7 días
   - Demo / TechBrain en curso: ~10–14 días
   - Propuesta / negociación: ~5–7 días  
   Calibrar al ciclo local; flag en CRM + tarea al owner.
2. **Close date vencida** — confirmar nueva fecha o cerrar; contar pushes.
3. **Next step** vacío o genérico ("seguir") → corregir a verbo + dueño + fecha.
4. **Etapa vs evidencia** — contrastar con skill **Indrox deal gates** (MEDDIC); bajar o matar si la etapa miente.
5. **Loss reason** — al Closed Lost: clase útil (timing, fit, precio/alcance, competitor, ghost, sin autoridad…). Evitar "otro" vacío.

## Reportes mínimos (Indrox CRM)

- Pipeline por marca (Core vs Zentral) y etapa.
- Deals stale / overdue close date (target: pocos).
- Win-loss con motivos (últimos 90 días).
- Aging: deals >2× ciclo típico del movimiento.
- Activaciones pendientes (Zentral) y TechBrain abiertos sin decisión.

## Ritual

| Cadencia | Qué |
| :---- | :---- |
| Semanal | Exception list: stale + below-gate + sin next step |
| Mensual | Scrub: bajar/kill; alinear montos a D.3/alcance |
| Trimestral | Pool revival (skill lost revival) |

## Qué NO hacer

- Dashboard bonito sin higiene de campos.
- Dejar propuestas eternas en "negociando".
- Contar free-trial/pilots fantasmas como pipeline ponderado igual que deals con criterios escritos.

## Handoff

- Evidencia débil → **Indrox deal gates**.
- Ciclo lento → **Indrox deal velocity**.
- Cerrados → **Indrox lost revival**.
- Falta discovery → **Indrox discovery**.
