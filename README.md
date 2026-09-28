# PostitME · Rendimiento 1.0.2

Versión 1.0.2 (3). Se conservan el corcho, las notas clay 3D, las 12 posiciones y las vistas 1–6 y 7–12.

Web: https://uncafeconmane.github.io/postitme-premium/

Aplicación: https://uncafeconmane.github.io/postitme-premium/app/

- El JavaScript inicial pasa de 4.733.048 a 3.850.131 bytes; el módulo PDF se carga al exportar y se incluye en la instalación offline.
- La instalación offline descarga un solo motor gráfico: 12,75 MiB en Chromium o 14,07 MiB con el motor completo, frente a 19,6 MiB. Tamaños sin compresión.
- Con 1.000 notas, la prueba del tablero pasa de 58 recorridos de colección a 2 al abrir; cambiar de vista o página no repite el filtrado.
- Textura estática aislada, dibujo por lotes, vistas previas de texto limitadas sin modificar las notas, miniaturas y animaciones más ligeras.
- 36 pruebas Flutter aprobadas; ocho páginas públicas y 109 enlaces internos comprobados; pruebas de ambos motores offline, PDF diferido, navegación, aislamiento de datos y actualización fallida.

La web permanece en modo local, sin cuentas, pagos, analítica ni sincronización remota activa. Las notas existentes conservan su formato y cifrado. Para recibir una actualización pendiente, cerrar todas las pestañas y ventanas instaladas de PostitME y volver a abrir. No borrar los datos del navegador.

Las cifras de tamaño y recorridos no son mediciones de FPS ni de velocidad en móviles físicos. Cámara, micrófono, biometría, notificaciones y Safari/iOS requieren pruebas en dispositivos reales. La aplicación iOS necesita compilación y firma en macOS.
