# Plan Maestro público · Jokxer.dev y Jokxer Collaborators

[Inicio](README.md) · [Jokxer.dev](https://jokxer.dev/) · [Hitos de Collaborators](docs/jokxer-collaborators/MILESTONES.md) · [Hoja de ruta](docs/jokxer-collaborators/ROADMAP.md)

## Propósito y alcance

Construir un portafolio web que conecte mi trabajo, intereses y proyectos, y preparar un espacio para que colaboradores invitados presenten su propio trabajo con revisión previa. Esta vitrina explica las decisiones y la evidencia sin distribuir la implementación privada ni ofrecer acceso a cuentas de prueba.

## Estado actual

**Corte documental:** 26 de noviembre de 2026. Jokxer.dev está publicado y permanece en Bolt. Collaborators sigue cerrado al público. Están documentados **3 de 5 flujos de prueba**: invitación, activación y acceso al panel. Recuperación por correo y suspensión quedan por comprobar.

## Historia y decisiones por fase

| Fase | Qué hice | Resultado y límite |
|---|---|---|
| Portafolio web | Reuní las secciones Personal, Profesional, Gamer, Fútbol y Contacto, con navegación adaptable y un estilo distinto por área. | Sitio público; el módulo privado no forma parte de la navegación pública. |
| Contacto y SEO | Integré un formulario con correo transaccional y preparé señales para buscadores, como metadatos y sitemap. | No se publican métricas de tráfico ni se supone que toda la web esté indexada. |
| Identidad de Collaborators | Diseñé la invitación como entrada al panel, sin autorregistro. | Una cuenta de prueba recibió y activó la invitación y entró al panel. |
| Edición y revisión | Definí la secuencia de perfil, portafolio, revisión y publicación. | Son entregas futuras. No se muestran perfiles públicos de colaboradores. |

## Tecnologías y para qué las uso

| Tecnología | Uso en el proyecto |
|---|---|
| React, TypeScript, Vite y Tailwind CSS | Construir la interfaz, mantener componentes y adaptar el diseño a distintas pantallas. |
| Bolt | Alojar Jokxer.dev y aprovechar la infraestructura gestionada del proyecto. |
| Cloudflare | Gestionar el dominio y sus registros DNS; no se presenta como el proveedor de hosting de Jokxer.dev. |
| Google Search Console | Dar seguimiento a la presencia de Jokxer.dev en la búsqueda de Google y revisar señales de indexación y sitemap. |
| Resend | Enviar correo del formulario y las invitaciones de Collaborators; la entrega de una invitación fue documentada. |

Tailscale se utiliza en la [infraestructura privada de HomeLab](https://github.com/jokxer8/Jokxer-HomeLab-Overview/blob/main/PLAN-MAESTRO.md), no para visitar el portafolio ni iniciar sesión como colaborador.

## Resultados y evidencia

- [Jokxer.dev](https://jokxer.dev/): acceso al portafolio público.
- [Hitos y pruebas](docs/jokxer-collaborators/MILESTONES.md#flujos-de-prueba): 3 de 5 flujos con evidencia acotada. Este indicador no es un porcentaje de desarrollo ni un lanzamiento.
- [Arquitectura](docs/jokxer-collaborators/ARCHITECTURE.md) y [seguridad](docs/jokxer-collaborators/SECURITY.md): diseño y límites del módulo.

## Pendientes priorizados y próximos hitos

1. **Cerrar pruebas de acceso.** Documentar recuperación y suspensión con cuentas de prueba antes de abrir nuevas funciones.
2. **Desarrollar perfiles y portafolios.** Verificar edición por el titular y privacidad de los recursos.
3. **Habilitar revisión editorial.** Probar borrador, aprobación y reversión antes de publicar un perfil.
4. **Preparar el lanzamiento controlado.** Comprobar avisos, accesibilidad y calidad; decidir visibilidad después de la revisión.

## Sugerencias

- Publicar un hito cuando haya un resultado comprobable y enlazar su evidencia.
- Revisar el portafolio en móvil y con teclado antes de añadir nuevas vistas.
