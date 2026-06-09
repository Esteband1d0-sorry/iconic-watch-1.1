# CLI-003 — Relojería

| Campo | Valor |
|---|---|
| ID | CLI-003 |
| Cliente | Relojería colombiana (nombre real por confirmar) |
| Responsable | Gabo |
| Tier | 1 — Web básica |
| Estado | ⛔ Bloqueado — leer sección STOP antes de continuar |
| Setup | €500 |
| Mensualidad | €50/mes |

## STOP — Aclarar esto antes de tocar nada

El cliente vende relojes traídos de Colombia. Antes de personalizar esta web y conectar Stripe, confirmar con el cliente:

**¿Los relojes son de marca propia o son réplicas de marcas conocidas (Rolex, Omega, Casio, etc.)?**

- Si son **marca propia o multimarca con distribución legítima** → seguir adelante normalmente
- Si son **réplicas AAA** → no se puede hacer tienda online en España. Venderlas online es ilegal (Ley de Marcas), cierra la cuenta de Stripe y puede conllevar sanciones. Alejandro tiene que hablar con el cliente antes de continuar.

Hasta que esto esté aclarado, no se despliega ni se conecta pasarela de pago.

## Contenido actual

```
relojeria/
  web/
    index.html    ← landing "KRONOS – Relojes de Autor" (plantilla, no personalizada)
```
