# Hitos y evidencias — Jokxer Collaborators

_Corte documental: 21 de noviembre de 2026._

Los detalles de implementación y resultados de pruebas de seguridad proceden del informe del entorno de desarrollo. La observación de la interfaz procede de una captura del panel privado con una cuenta de prueba. Estas evidencias no equivalen a una auditoría independiente ni a un lanzamiento en producción.

## Fase 1 — Arquitectura y cimentación

**Completada según el informe técnico.**

- Auditoría de la SPA React/TypeScript y su infraestructura existente.
- Definición de módulos, tipos de dominio, permisos y rutas futuras.
- Modelo conceptual de colaboradores, invitaciones, proyectos, recursos, revisión, publicación y notificaciones.
- Documentación de arquitectura, seguridad, integraciones, pruebas y hoja de ruta.
- Build, verificación de tipos y lint reportados sin errores bloqueantes.
- Sin directorio público de colaboradores ni rutas activas en esta fase.

## Fase 2 — Identidades y administración

**Implementada según el informe técnico; comprobaciones de base de datos reportadas como satisfactorias.**

- Perfiles, invitaciones y auditoría con controles de acceso.
- Acceso por invitación y recuperación de cuenta.
- Panel privado de administración y panel básico del colaborador.
- Gestión administrativa de usuarios, invitaciones y auditoría.
- Rutas privadas compatibles con acceso directo, refresh e historial.
- Medidas contra abuso en el formulario de contacto.
- Typecheck, lint y build reportados como correctos.

## Validación operativa observada

- El panel privado del colaborador abrió con una cuenta de prueba activa.
- La captura confirma acceso visual a ese panel, no todos los flujos de invitación ni de correo.
- **Pendiente:** ejecutar la acción de suspensión y confirmar cierre de la sesión existente, bloqueo de reingreso y denegación de operaciones directas.
- Se registró la recepción y activación de una invitación de prueba. La recuperación de acceso por correo y la prueba de suspensión siguen pendientes.

### Flujos de prueba

| Flujo | Estado | Criterio |
|---|---|---|
| Invitar | **Validado en una cuenta de prueba** | Invitación recibida. |
| Activar | **Validado en una cuenta de prueba** | La invitación permitió activar la cuenta. |
| Entrar al panel | **Validado en una cuenta de prueba** | Se observó el panel privado con la cuenta activa. |
| Recuperar acceso por correo | **Pendiente de validar** | Completar la recuperación y verificar el reingreso. |
| Suspender | **Pendiente de validar** | Confirmar cierre de sesión, bloqueo de reingreso y denegación de operaciones protegidas. |

**Indicador: 3 de 5 flujos con evidencia**, corte al 25 de noviembre de 2026. Es el alcance de esta lista de pruebas, no un porcentaje de avance del proyecto ni un lanzamiento a público.

## Publicación

El sitio personal sigue separado del módulo privado. No se publican perfiles de colaboradores, datos de cuenta, tokens, instrucciones privilegiadas ni detalles internos de infraestructura.

[Volver a la vitrina pública](../../README.md#jokxer-collaborators).
