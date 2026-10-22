# ZendaFit

[← Volver al portafolio](https://github.com/Jegalvan95)

**Plataforma para entrenadores y nutricionistas independientes**  
Origen académico · Versión 0.2.0 · En desarrollo

## Objetivo

Centralizar la gestión de clientes, la preparación de planes y el seguimiento de progreso, separando la información de cada relación profesional-cliente.

## Funcionalidades implementadas

- Invitaciones y relaciones entre profesionales y clientes.
- Fichas de clientes, notas privadas y agenda de revisiones.
- Rutinas y planes alimenticios en texto o con editores estructurados.
- Borradores, publicación explícita, versiones y plantillas reutilizables.
- Registro de medidas, gráfica de peso y resúmenes descriptivos.
- Permisos comprobados en el servidor y separación de espacios personales y profesionales.
- Asistente con contexto acotado, límites e historial, preparado para integrar un proveedor.

## Tecnologías

React, TypeScript y Vite para la interfaz; Fastify para la API; PGlite para persistencia local, migraciones SQL y Vitest. El proyecto incluye un adaptador para PostgreSQL de servidor, cuya conexión requiere validación en un destino autorizado.

## Evidencia y estado

El repositorio contiene una aplicación local ejecutable. La documentación registra una validación de 72 pruebas en 10 archivos, comprobación de tipos y compilación. Esos resultados corresponden a la validación documentada del proyecto; no se ejecutaron de nuevo para publicar esta ficha.

El acceso web con cuentas reales, el proveedor de IA, el despliegue comercial y la revisión visual de los nuevos formularios siguen pendientes. Las pruebas del asistente usan un adaptador ficticio; no acreditan respuestas de un proveedor real.

## Disponibilidad

Esta ficha es pública y el código permanece privado. No hay una demo pública verificada en esta revisión. Los datos de desarrollo son ficticios y la plataforma no se presenta como un servicio de recomendaciones clínicas automáticas.

*Ficha actualizada el 22 de octubre de 2026 a partir del código y la documentación del proyecto.*
