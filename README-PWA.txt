GESTOR DE TURNOS - PWA PILOTO

Cambios de esta versión:
- PWA instalable mediante HTTPS/GitHub Pages.
- Orientación recomendada horizontal, pero NO obligatoria.
- En vertical aparece un aviso breve durante unos segundos y desaparece solo.
- La aplicación sigue funcionando en vertical.
- En teléfono horizontal se aplica una interfaz más compacta.
- El menú Herramientas tiene desplazamiento propio para mostrar todas las opciones.
- Se mantiene Supabase Auth y la sincronización separada por cuenta.

PUBLICACIÓN EN GITHUB PAGES
1. Reemplaza index.html, manifest.json y sw.js por estos archivos.
2. Mantén icon-192.svg e icon-512.svg.
3. GitHub Pages publicará automáticamente el cambio.
4. Si tienes la PWA instalada, ciérrala por completo y vuelve a abrirla para que tome la nueva versión.

NOTA:
El cambio de orientación está en manifest.json con orientation: any. El aviso es informativo y no bloquea la pantalla vertical.
