# Jokxer Collaborators — registro público de desarrollo

> **Corte: 21 de noviembre de 2026.** La Fase 2 está implementada según el informe técnico. Se observó el panel privado con una cuenta de prueba activa. La prueba operativa de suspensión sigue pendiente. El módulo no está abierto al público.

**Jokxer Collaborators** es un módulo privado en desarrollo dentro de [jokxer.dev](https://jokxer.dev/) para que colaboradores invitados gestionen un perfil profesional. La administración controla las cuentas. Las herramientas para proyectos, recursos, revisión editorial y publicación pública pertenecen a fases futuras.

## Principios

- Acceso cerrado por invitación; no existe autorregistro.
- Controles de autorización en servidor y base de datos.
- Revisión administrativa antes de cualquier publicación futura.
- Proteger datos y sesiones de las cuentas.
- Mantener el sitio existente y usar infraestructura disponible, sin inversión adicional en esta etapa.
- Diferenciar implementación informada de pruebas realmente ejecutadas.

## Componentes

| Componente | Uso |
| --- | --- |
| React, TypeScript, Vite y Tailwind CSS | Interfaz del portafolio y del módulo privado |
| Bolt Database | Identidad y datos del módulo |
| Resend | Envío de una invitación de prueba registrado; recuperación por correo sin validar |
| Cloudflare | Dominio e infraestructura DNS existente |
| GitHub | Código privado y documentación pública selectiva |
| Google Search Console | Posible uso futuro para contenido aprobado |
| NAS y Tailscale | Infraestructura privada, fuera del acceso de colaboradores |

## Estado

| Alcance | Estado al corte |
| --- | --- |
| Fase 1: auditoría y arquitectura | Completada según documentación |
| Fase 2: identidad, invitaciones, paneles y controles de datos | Implementada según informe técnico |
| Acceso al panel privado con cuenta de prueba | Observado visualmente |
| Prueba operativa de suspensión y bloqueo de sesión | **Pendiente** |
| Invitación de prueba | Recibida y activada; no valida la recuperación por correo |
| Perfiles, proyectos, recursos y aprobación editorial | Fases futuras |
| Publicación pública y SEO de perfiles | No habilitados |

Las comprobaciones reportadas de acceso a base de datos, typecheck, lint y build fueron satisfactorias. La observación del panel confirma que esa pantalla abrió con una cuenta de prueba; no prueba por sí sola todos los flujos de autenticación ni la suspensión.

## Documentos

- [Hitos y evidencias](MILESTONES.md)
- [Arquitectura](ARCHITECTURE.md)
- [Seguridad y privacidad](SECURITY.md)
- [Hoja de ruta](ROADMAP.md)
- [Registro de cambios](CHANGELOG.md)

Este repositorio es una vitrina documental. No contiene código de producción, secretos, instrucciones privilegiadas ni datos privados de colaboradores.
