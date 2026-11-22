# Contenido de Eternal Launcher

Esta carpeta es lo que el launcher descarga al abrirse (noticias, imágenes de fondo y logo).
Cualquier cambio que hagas aquí aparece en TODAS tus PCs sin recompilar ni reinstalar.

## Qué se puede cambiar en config.json
- **news**: lista de noticias (id, title, summary, date y `url` opcional que abre un enlace). Lista vacía `[]` = panel oculto.
- **newsTitle**: título del panel de noticias.
- **background.image**: fondo del menú principal. Nombre de archivo de esta carpeta o enlace https. `""` = sin fondo.
- **background.opacity**: de 0 (invisible) a 1 (completo). Recomendado entre 0.15 y 0.3.
- **background.scope**: `"home"` (solo menú principal) o `"all"` (todas las pantallas).
- **background.blur**: desenfoque en píxeles (0 a 40).
- **splash.image / splash.opacity**: fondo de la pantalla de carga.
- **logo**: logo que se muestra dentro del launcher (barra de título y pantalla de carga). `""` = el que trae incluido.

## Cuándo se ven los cambios
- GitHub tarda unos 5 minutos en publicar un archivo nuevo.
- El launcher revisa al abrirse y cada 10 minutos. Noticias, fondo del menú y logo cambian solos.
- La pantalla de carga usa lo último descargado, así que ve el cambio en el siguiente arranque.

## Lo que NO se puede cambiar desde aquí (requiere recompilar)
El icono del .exe, del instalador y de la barra de tareas, y cualquier cambio de código o de textos del programa.

## Importante
Este repositorio debe ser PÚBLICO. No pongas aquí datos privados.
