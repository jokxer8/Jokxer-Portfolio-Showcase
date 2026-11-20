# Jokxer Collaborators — registro público de desarrollo

> **Estado al 20 de noviembre de 2026:** Fase 1 documentada; Fase 2 implementada según el informe del entorno de desarrollo, **pendiente de validación operativa**. No se presenta como una plataforma abierta ni disponible para colaboradores.

**Jokxer Collaborators** es un módulo en desarrollo de [jokxer.dev](https://jokxer.dev/) que permitirá a colaboradores autorizados administrar pequeños portafolios profesionales sin editar código. El propietario conserva la facultad de revisar, corregir y aprobar las publicaciones antes de hacerlas públicas.

## Qué problema busca resolver

Unificar la presentación del trabajo colaborativo —proyectos, repositorios, diseños, documentación y planificación— en una experiencia profesional coherente, con responsabilidades y autorías claras.

## Principios

- **Acceso cerrado:** solo el administrador crea cuentas; no hay autorregistro de colaboradores.
- **Control editorial:** el colaborador propone cambios y el administrador autoriza cada publicación.
- **Versionado:** el contenido aprobado se mantiene visible mientras una nueva versión espera revisión.
- **Seguridad y privacidad:** aislamiento por usuario, controles en backend y datos, archivos privados antes de aprobarse.
- **Evolución gradual:** preservar las secciones existentes de jokxer.dev; cero inversión adicional en esta etapa.
- **Documentación verificable:** diferenciar código implementado, pruebas ejecutadas y validaciones pendientes.

## Tecnología y ecosistema

| Componente | Uso |
| --- | --- |
| React, TypeScript, Vite y Tailwind CSS | Interfaz de la web existente |
| Bolt Database | Identidades y datos del módulo |
| Resend | Notificaciones transaccionales previstas/integradas |
| Cloudflare | Dominio e infraestructura DNS existente |
| GitHub | Documentación pública y seguimiento |
| Google Search Console | Visibilidad de contenido aprobado en etapas posteriores |
| NAS y Tailscale | Infraestructura **privada**, no expuesta a colaboradores |

Los componentes e integraciones se describen a nivel general. Las configuraciones internas, secretos y datos de usuarios no se publican.

## Avance documentado

| Fase | Alcance | Estado |
| --- | --- | --- |
| 1 | Auditoría, arquitectura, contratos, rutas previstas y documentación | **Completada según informe técnico** |
| 2 | Base de datos, autenticación, invitaciones, paneles y control de acceso | **Implementación informada; validación operativa pendiente** |
| 3 | Perfiles profesionales y edición visual | Pendiente |
| 4 | Proyectos, repositorios y recursos | Pendiente |
| 5 | Moderación, versiones y publicaciones | Pendiente |
| 6 | Notificaciones e integración ampliada | Pendiente |
| 7 | Seguridad integral, pruebas y optimización | Pendiente |
| 8 | Lanzamiento controlado y SEO | Pendiente |

La Fase 2 incluye en su informe migraciones, controles de acceso y rutas privadas, además de compilación, verificación de tipos y lint. **Todavía faltan pruebas con una cuenta administrativa real y confirmación de entrega de correos.** No se publican detalles de acceso ni procedimientos privilegiados.

## Lecturas

- [Bitácora de hitos](MILESTONES.md)
- [Visión arquitectónica](ARCHITECTURE.md)
- [Seguridad y publicación](SECURITY.md)
- [Hoja de ruta](ROADMAP.md)
- [Registro de cambios](CHANGELOG.md)

## Alcance del repositorio

Este espacio es una **vitrina documental pública** del progreso del desarrollo, no un repositorio de credenciales, respaldos de base de datos ni código de producción. La aplicación sigue integrada en el proyecto original de [jokxer.dev](https://jokxer.dev/).

Desarrollado como proyecto personal de ingeniería de software por [Jokxer](https://github.com/jokxer8).
