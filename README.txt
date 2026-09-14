FOKUS — PWA de enfoque y progreso
=================================

INCLUYE:
- Pantalla de apertura con FOKUS y el estilo del logo proporcionado.
- Pomodoro 25/5, pausa/reinicio y modo Enfoque.
- Registro local del tiempo de enfoque.
- Tareas Kanban: Por hacer / En proceso / Hecho.
- Rastreador de hábitos con rachas.
- Energía 1–5 con sugerencia de tipo de tarea.
- Vision board textual (base preparada para ampliar a imágenes/video).
- Diario de 3 micro-victorias.
- Barra de progreso acumulativo.
- Auditoría semanal básica.
- Atajo N para crear una tarea/idea.
- PWA instalable en computadora.
- Funcionamiento offline mediante Service Worker.
- Datos guardados localmente en el navegador.

INSTALACIÓN EN LA COMPUTADORA:
1. La PWA necesita servirse por HTTPS o localhost para que Service Worker e instalación funcionen.
2. Para probar localmente, abre una terminal en esta carpeta y ejecuta:
   python -m http.server 8000
3. Abre http://localhost:8000
4. En Chrome/Edge usa el icono de instalación de la barra de direcciones o el botón "Instalar FOKUS".
5. Para publicar y poder instalarla desde cualquier computador, sube la carpeta a un hosting HTTPS (por ejemplo, GitHub Pages, Netlify o Vercel).

NOTA:
Esta es una V1 funcional sin servidor. La sincronización en nube/Background Sync real requiere añadir un backend y autenticación. La Web Share API puede añadirse como siguiente módulo.
