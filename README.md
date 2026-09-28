# PostitME

Aplicación de notas adhesivas digitales, con tablero 4×3 y vistas ampliadas de seis notas. Esta entrega funciona en modo local: sin registro, sincronización remota, publicidad ni analítica incorporada.

## Web de prueba

Este repositorio contiene [la web/PWA compilada](PostitME_PWA.zip) preparada para GitHub Pages. La publicación se realiza con un workflow manual y sin permisos de escritura sobre el código.

Los textos incluyen aviso legal, condiciones, privacidad y política de almacenamiento local. Contacto indicado por el titular del proyecto: +34 692 225 392. Falta incorporar la identificación legal completa del titular; la web se presenta como versión de prueba y no se declara un cumplimiento legal íntegro.

El paquete contiene únicamente archivos públicos del sitio. No incluye notas de usuarios, contraseñas, claves de firma Android ni credenciales administrativas.

## Verificaciones

- Compilación web release y análisis Flutter aprobados.
- 30 pruebas Flutter aprobadas.
- 116 enlaces internos del sitio comprobados.
- Recursos locales y comportamiento del service worker comprobados automáticamente, incluida la exclusión de peticiones de autenticación y escritura.

El funcionamiento con cámara, micrófono, notificaciones y biometría necesita validación en dispositivos reales. La PWA requiere una primera descarga completa con conexión para abrir sin internet. Exporta copias antes de borrar datos del navegador.
