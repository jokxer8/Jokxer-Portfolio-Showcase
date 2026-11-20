# Arquitectura conceptual

Jokxer Collaborators se desarrolla como **módulo integrado** en el portafolio existente [jokxer.dev](https://jokxer.dev/), no como sustituto de la web ni como servicio empresarial independiente.

```text
jokxer.dev
├── Secciones personales y profesionales existentes (se conservan)
└── Jokxer Collaborators (módulo en desarrollo)
    ├── Experiencia pública: perfiles/contenidos aprobados (futura)
    ├── Área privada del colaborador
    └── Área privada de administración
         │
         ├── Identidad y autorización
         ├── Datos y operaciones de colaboración
         ├── Revisión y aprobación editorial (futura)
         └── Notificaciones transaccionales
```

## Diseño

1. **Presentación:** componentes React compatibles con la identidad visual existente.
2. **Identidad y permisos:** aprovisionamiento administrativo; controles de sesión y privilegios.
3. **Datos:** Bolt Database, con aislamiento de información según rol/propiedad.
4. **Contenido:** proyectos, repositorios y archivos, planificados para fases posteriores.
5. **Publicación:** separación entre el estado de la revisión y la versión visible.
6. **Integraciones:** correo transaccional con Resend y enlaces de repositorios externos.

## Regla editorial

Los cambios de los colaboradores no aparecerán automáticamente en el sitio público. El administrador debe poder revisar cada nueva versión, ajustar su contenido y aprobarla. La versión pública vigente permanecerá sin cambios hasta que una nueva versión sea autorizada.

La capa de gestión de contenidos y el flujo editorial todavía forman parte de la hoja de ruta, **no de la funcionalidad operativa validada**.

## Límites

- No exponer servicios domésticos o privados como requisito de operación de la web.
- No convertir enlaces a repositorios en permisos sobre repositorios ajenos.
- No aceptar código subido para ejecución automática.
- Evitar servicios de pago adicionales y migraciones innecesarias.

Este documento refleja un diseño de alto nivel; deliberadamente omite secretos e instrucciones de acceso privilegiado.
