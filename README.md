# Fuente de archivos AniCAT para Kodi

Añade **https://anicat-org.github.io/** en Kodi → Gestor de archivos → Añadir fuente.
Después abre Add-ons → Instalar desde un archivo .zip → esa fuente y selecciona
`repository.anicat-1.0.0.zip`. Instala AniCAT desde AniCAT Repository.

`public/` contiene un índice HTML sencillo y el ZIP directamente en la raíz.
El workflow de `anicat-org/repository.anicat` sincroniza esos archivos mediante
una deploy key limitada a este repositorio. Aquí Pages publica únicamente `public/`.
El índice no requiere JavaScript ni redirecciones.

La landing y el servicio de actualizaciones siguen en
https://anicat-org.github.io/repository.anicat/.

El futuro dominio `repo.ani.cat` debe configurarse en este sitio raíz, con un
CNAME DNS hacia `anicat-org.github.io` y HTTPS en Pages. El dominio no está activado.
Al migrar, también hay que revisar las URL del repositorio instalable y las
redirecciones de los sitios de proyecto antes de publicar una nueva versión.
