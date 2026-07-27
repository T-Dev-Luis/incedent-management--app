# Incident Management App

Sistema de gestión de incidencias técnicas construido con **Angular 20** como
parte de un reto formativo incremental de 30 días para desarrolladores junior.

## Tecnología principal

- Angular 20 (componentes standalone)
- TypeScript en modo estricto
- SCSS
- Angular Router

## Requisitos previos

- Node.js 20 LTS o superior
- npm 10 o superior
- Angular CLI 20 (`npm install -g @angular/cli@20`)

## Instalación

```bash
npm install
```

## Ejecución en ambiente local

```bash
npm start
```

La aplicación quedará disponible en `http://localhost:4200/`.
Se recarga automáticamente al guardar cambios en el código fuente.

## Compilación de producción

```bash
npm run build
```

Los artefactos se generan en `dist/incident-management-app/`.

## Pruebas unitarias

```bash
npm test
```

## Estructura del proyecto (estado actual — Día 1)

```
src/
└─ app/
   ├─ app.component.ts
   ├─ app.component.html
   ├─ app.component.scss
   ├─ app.component.spec.ts
   ├─ app.config.ts
   └─ app.routes.ts
```

La estructura evolucionará día a día durante el reto formativo hasta
incorporar `core/`, `shared/`, `features/incidents/`, `features/authentication/`,
`features/dashboard/` y `layout/`, según lo definido en la guía del reto.

## Estado del reto

| Día | Objetivo                                             | Estado      |
|-----|-------------------------------------------------------|-------------|
| 1   | Preparación del entorno y creación del proyecto      | ✅ Completado |

Ver informes diarios detallados en [`docs/`](./docs).
