# DanSolutions — módulo de licencias (demostración)

Abre `index.html` con Live Server de VS Code y entra con cualquier correo válido y contraseña de prueba.

## Funciones
- Alta de empresas con límite de sucursales y vencimiento.
- Edición y renovación de licencias desde la sección **Licencias**.
- Estado **Vigente**, **Vencida** o **Deshabilitada**; acceso operativo o de **solo lectura** indicado en pantalla.
- No permite configurar un límite inferior al número de sucursales existente.
- Los datos de demostración se guardan en `localStorage` del navegador.

## IMPORTANTE
Esta versión es solo un prototipo local: no existe autenticación, base de datos ni bloqueo real de operaciones. El modo de solo lectura es una **indicación visual**, no un control de seguridad. Antes de usarlo con negocios reales, implementar Supabase Auth, políticas RLS, funciones transaccionales que comprueben licencias en servidor y auditoría. No publiques datos reales en este prototipo.

## Próximo paso
Definir y aplicar migraciones PostgreSQL para empresas, sucursales y licencias, más RLS y funciones protegidas.
