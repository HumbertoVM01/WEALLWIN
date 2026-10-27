# WEALLWIN — 10 experiencias interactivas · Versión corregida v3

Esta versión mantiene la interfaz general limitada estrictamente a #7F7F7F, #000000 y #FFFF00. La ventana de cada experiencia tiene su propia paleta de colores, independiente y diferente de la de las otras nueve experiencias.

**IMPORTANTE: vista previa ≠ juego.** El visor de archivos integrado en la app ChatGPT en iPhone puede impedir que JavaScript se ejecute. Ahora el HTML contiene una **imagen de vista previa integrada** que muestra el contenido de la experiencia incluso cuando el visor bloquea JavaScript. Pero esa imagen no se puede jugar. Para interactuar, publica los HTML en hosting estático (p. ej. Netlify Drop) y abre la URL web con Safari. O abre los HTML locales en un navegador que ejecute scripts locales (algunos iOS viewers no lo hacen).

**Publicación:** extraer este ZIP y subir todos los archivos a Netlify Drop. `index.html` redirige directamente a la primera experiencia. Los controles de la experiencia son exclusivos de la ventana central. El slider inferior abre la siguiente de la secuencia después de un arrastre completo y de confirmar dentro de tres segundos.

**Pruebas:** las experiencias se han renderizado y probado en Chromium. El modo sin JavaScript se ha probado visualmente: muestra una vista estática. No hay backend, registro ni recomendador integrado; la secuencia entre archivos es fija para esta demo. No se requiere conectividad después de servir o cargar los recursos de la página.
