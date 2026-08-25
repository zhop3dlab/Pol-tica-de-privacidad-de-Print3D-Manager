# Política de privacidad de Print3D Manager

**Última actualización: 25 de agosto de 2026**

Esta política explica qué datos trata Print3D Manager ("la app"), con qué finalidad, y qué opciones tienes. Está escrita para describir exactamente lo que la app hace hoy, no funciones futuras.

## 1. Quién trata los datos

Print3D Manager es una app desarrollada de forma independiente para la gestión de talleres de impresión 3D (costes, impresoras, materiales, proyectos, clientes, presupuestos y facturas).

Contacto: zhop3dlab@gmail.com

## 2. Principio general: la app es local por defecto

Toda la información que introduces (impresoras, materiales, proyectos, clientes, presupuestos, facturas, inventario) se guarda **en tu propio dispositivo** de forma predeterminada. No necesitas crear una cuenta ni tener conexión a internet para usar la app con todas sus funciones principales.

Ningún dato de tu negocio se envía a nuestros servidores ni a terceros salvo que actives voluntariamente la sincronización con la nube (ver sección 3) o mientras se muestra un anuncio (ver sección 5).

## 3. Cuenta y sincronización con la nube (opcional)

Si decides crear una cuenta (con email y contraseña, o con tu cuenta de Google) para guardar tus datos también en la nube y usarlos en más de un dispositivo:

- **Datos de la cuenta**: dirección de email y, si usas Google, el nombre e imagen de perfil asociados a esa cuenta de Google.
- **Datos de tu negocio**: si activas la sincronización, una copia de tus proyectos, clientes, impresoras, materiales, presupuestos y facturas se guarda en una base de datos en la nube (Google Firebase/Firestore), asociada únicamente a tu cuenta y a tu espacio de trabajo. Nadie fuera de tu cuenta puede acceder a esos datos.
- Puedes dejar de usar la nube en cualquier momento y volver a que la app funcione solo en local.
- Puedes **eliminar tu cuenta y todos los datos asociados en la nube** en cualquier momento desde la propia app, en **Más → Cuenta → Eliminar cuenta y datos**. Esta acción es permanente e inmediata.

Usamos Google Firebase (Authentication y Firestore) como proveedor de infraestructura para la cuenta y la nube. Google actúa como encargado del tratamiento de estos datos según sus propias condiciones: <https://firebase.google.com/support/privacy>.

## 4. Datos que nunca salen de tu dispositivo

- **Archivos G-code**: si usas el analizador de G-code, el archivo se lee y analiza enteramente en tu dispositivo. El contenido del archivo nunca se sube a internet ni se comparte con nadie; solo tú ves los datos extraídos (tiempo estimado, gramos, temperaturas).
- **Copias de seguridad locales**: exportar/importar tus datos en un archivo JSON (disponible según tu plan) es una operación completamente local — el archivo se guarda donde tú decidas (por ejemplo, compartiéndolo tú mismo por email o guardándolo en tu almacenamiento).
- **PDFs de presupuestos y facturas**: se generan en tu dispositivo. Compartirlos o descargarlos es una acción tuya explícita; la app no los envía a ningún servidor propio.

## 5. Publicidad

La app muestra anuncios mediante **Google AdMob** a los usuarios del plan gratuito. AdMob puede recoger identificadores de publicidad de tu dispositivo para mostrar anuncios (personalizados o no, según tu configuración de privacidad del sistema operativo) y medir su rendimiento. Este tratamiento lo realiza Google conforme a su propia política de privacidad: <https://policies.google.com/privacy> y su política específica para AdMob: <https://support.google.com/admob/answer/6128543>.

Los usuarios de los planes de pago (Pro y Business) no ven anuncios.

## 6. Qué NO hacemos

- No vendemos tus datos a nadie.
- No accedemos al contenido de tus proyectos, clientes o facturas salvo que tú actives expresamente la sincronización en la nube, y ni siquiera entonces los revisamos manualmente.
- No usamos tus datos de negocio para entrenar modelos de inteligencia artificial.
- No pedimos permisos de cámara, contactos, ubicación ni micrófono — la app no los necesita y no los solicita.

## 7. Tus derechos

Si has creado una cuenta, en cualquier momento puedes:

- **Ver** cuántos datos tienes guardados localmente y en la nube (Más → Cuenta).
- **Descargar** una copia de tus datos en un archivo JSON (según tu plan, Más → Datos).
- **Eliminar** tu cuenta y todos los datos asociados en la nube desde la propia app (Más → Cuenta → Eliminar cuenta y datos).
- **Desinstalar la app** en cualquier momento, lo que elimina todos los datos guardados localmente en tu dispositivo.

Si necesitas ayuda con cualquiera de estos derechos, o tienes alguna duda sobre esta política, contacta con **[tu-email-de-contacto@ejemplo.com]**.

## 8. Menores de edad

La app no está dirigida a menores de edad y no recogemos conscientemente datos de menores.

## 9. Cambios en esta política

Si esta política cambia de forma relevante, se actualizará la fecha al principio del documento. El uso continuado de la app tras un cambio implica la aceptación de la política actualizada.
