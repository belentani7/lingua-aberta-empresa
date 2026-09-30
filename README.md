# lingua-aberta — Empresa

Convertir lingua-aberta en producto: web usable, precios, pagos y área de cliente.

## Qué es

La capa de **negocio** sobre lingua-aberta, una plataforma de aprendizaje de idiomas con
progresión CEFR y repetición espaciada. Aquí vive lo que hace que sea sostenible: cobros,
plan de negocio y área privada.

## Puesta en marcha

```bash
pnpm install
pnpm dev
```

## Cobros

Requiere `STRIPE_SECRET_KEY` en el entorno de despliegue (Vercel). **Sin la clave, el endpoint
`/api/checkout` responde en modo demo**: así se puede probar el flujo sin cobrar de verdad.

## Estado

Plan de negocio a 90 días. El producto base existe; esto lo convierte en empresa.

## Licencia

Sin licencia declarada.
