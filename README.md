# Fuente de archivos AniCAT para Kodi

Añade **https://anicat-org.github.io/** en Kodi → Gestor de archivos → Añadir fuente.
Después abre Add-ons → Instalar desde un archivo .zip → esa fuente y selecciona
`repository.anicat-1.0.0.zip`. Instala AniCAT desde AniCAT Repository.

`public/` contiene un índice HTML sencillo y el ZIP directamente en la raíz.
El workflow de `anicat-org/repository.anicat` sincroniza esos archivos mediante
una deploy key limitada a este repositorio. Aquí Pages publica únicamente `public/`.
El índice no requiere JavaScript ni redirecciones.

El servicio de actualizaciones sigue en
https://anicat-org.github.io/repository.anicat/ (redirige a https://repo.ani.cat/).
Ese sitio también muestra un índice de archivos; la landing está en `descargar.html`.

`repo.ani.cat` está configurado en Pages de `repository.anicat`, con CNAME DNS
hacia `anicat-org.github.io` y HTTPS. Este sitio mantiene disponible la fuente
alternativa en la dirección original de GitHub. No es necesario mover el dominio.
