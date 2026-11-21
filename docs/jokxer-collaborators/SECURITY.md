# Seguridad, privacidad y alcance público

La seguridad forma parte de los criterios de aceptación del módulo.

## Políticas del proyecto

- Las cuentas se crean por invitación administrativa; no hay autorregistro.
- Administración y colaborador tienen funciones separadas.
- La autorización se comprueba en servidor y base de datos.
- Los borradores y archivos futuros permanecerán privados hasta aprobación.
- No se ejecuta código enviado por usuarios.
- Las acciones administrativas relevantes se registran.
- No se publican claves, tokens, respaldos, configuraciones internas ni datos personales.
- El NAS y la red privada no forman parte del acceso de colaboradores.

## Estado de verificación al 21 de noviembre de 2026

El informe técnico registra pruebas de RLS/grants y bloqueos de acceso no autorizado, además de typecheck, lint y build correctos. Se observó visualmente el panel privado con una cuenta de prueba activa.

**Pendiente de prueba operativa:** suspender una cuenta de prueba y confirmar que la sesión existente se cierra, que el reingreso queda bloqueado y que las operaciones protegidas también se deniegan desde solicitudes directas. La entrega real del correo transaccional tampoco cuenta con confirmación documentada.

No interpretar la implementación informada como certificación de seguridad ni como autorización para abrir el módulo al público.

## Reporte responsable

No publicar vulnerabilidades explotables, secretos ni datos de colaboradores en issues públicos. Reportar hallazgos sensibles mediante un canal privado con el propietario.

## Privacidad y publicación

Este repositorio comunica el propósito, el avance general y las limitaciones. Los perfiles de colaboradores solo podrán publicarse tras completar las fases correspondientes, obtener consentimiento y recibir aprobación administrativa.
