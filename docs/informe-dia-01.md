# Informe diario - Día 1

## Objetivo de la jornada

Preparar el entorno de desarrollo y comprender la estructura inicial de una
aplicación Angular.

## Actividades realizadas

- Verificación de versiones instaladas de Node.js, npm y Angular CLI.
- Creación del proyecto Angular 20 con enrutamiento (`provideRouter`) y
  estilos SCSS habilitados.
- Habilitación del modo estricto de TypeScript (`strict`, `strictTemplates`,
  `strictInjectionParameters`, `strictInputAccessModifiers`).
- Ejecución de la aplicación en ambiente local (`npm start`).
- Revisión de la estructura generada por el CLI.
- Inicialización del repositorio Git.
- Creación del archivo `README.md` con instrucciones de instalación y
  ejecución.
- Documentación de los comandos principales del proyecto.

## Conceptos aplicados

- Angular CLI y estructura de un proyecto Angular.
- Componentes standalone (`AppComponent` sin `NgModule`).
- Configuración de aplicación (`app.config.ts`) y `provideRouter`.
- Control de versiones con Git.

## Evidencia funcional

`npm start` levanta el servidor de desarrollo en `http://localhost:4200/` y
muestra el título "Sistema de gestión de incidencias técnicas" sin errores en
consola.

## Pruebas ejecutadas

- `npm test`: prueba por defecto de `AppComponent` (creación del componente y
  renderizado del título).

## Dificultades encontradas

_(completar según corresponda en el entorno real de desarrollo)_

## Soluciones aplicadas

_(completar según corresponda)_

## Decisiones técnicas

- Se optó por mantener `app.component.ts` (en vez del nombre corto `app.ts`)
  para alinear el proyecto con la estructura de referencia definida en la
  guía del reto.
- El arreglo de rutas (`app.routes.ts`) se dejó vacío intencionalmente: las
  rutas de negocio (`/incidents`, `/dashboard`, etc.) se incorporan a partir
  del Día 13 según el plan formativo.

## Trabajo pendiente

- Día 2: definición de los modelos de dominio tipados (`Incident`,
  `IncidentStatus`, `IncidentPriority`, `User`).

## Tiempo invertido

Aproximadamente 2 horas.

## Commits relacionados

- `chore(project): initialize Angular incident management application`
