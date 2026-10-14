# AppTiendaPOS

Aplicación web del **Punto de Venta TiendaPOS** construida con **Next.js** y la
librería de componentes **shadcn/ui** (Radix). Multitenant, con suscripciones y
consumo de la API `tiendapos-api`. Despliegue en Netlify.

## Stack

- Next.js + TypeScript
- shadcn/ui (Radix UI) + Tailwind CSS
- React Hook Form + Zod (formularios y validación)
- API backend: [`tiendapos-api`](../tiendapos-api) (Laravel)

## Puesta en marcha

```bash
npm install
```

Configura la URL de la API en `.env.local`:

```bash
NEXT_PUBLIC_API_URL=https://tiendapos-api.onrender.com/api/v1
```

```bash
npm run dev
```

## Scripts

| Comando | Descripción |
| --- | --- |
| `npm run dev` | Desarrollo |
| `npm run build` | Build |
| `npm run start` | Servir build |
| `npm run typecheck` | Chequeo de tipos |
| `npm run lint` | Linting |

---

Por [junnior-dev](https://github.com/junnior-dev).
