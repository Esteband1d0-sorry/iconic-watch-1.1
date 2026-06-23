# ICONIC Watch — Web cliente relojería

| Campo | Valor |
|---|---|
| ID | CLI-003 |
| Cliente | Relojería colombiana (ICONIC Watch) |
| Responsable | Esteban |
| Tier | 1 — Web básica |
| Estado | ✅ Desplegado en Railway |
| Setup | €500 |
| Mensualidad | €50/mes |

## Deploy

URL: `https://iconic-watch-11-production.up.railway.app`

Railway autodeploy activo — cada push a `master` redespliega en ~2 min.

## Estructura

```
iconic-watch-1.1/
  web/
    index.html    ← landing ICONIC WATCH — Haute Horlogerie
    logo.svg      ← logo del cliente
  server.js       ← Express server (sirve web/ en $PORT)
  package.json
  railway.toml
```
