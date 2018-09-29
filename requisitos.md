
# Catálogo de requisitos

| **R01**     | **Datos de usuario**           |
| --------------: | :------------------- |
| **Descripción** | Para cada usuario se pedirán los siguientes datos: - Requeridos: nick, email, contraseña, role - Opcionales: avatar, biografia, web personal, twitter, facebook, google+             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R02**     | **Alta de usuario**           |
| --------------: | :------------------- |
| **Descripción** | Formulario de registro para darse de alta como usuario. El nombre de usuario debe ser único y el email también para poder llevarse a cabo.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R03**     | **Visualizar Perfil de usuario**           |
| --------------: | :------------------- |
| **Descripción** | Muestra el perfil del usuario y los datos relacionados a este             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R04**     | **Modificar Perfil Usuario**           |
| --------------: | :------------------- |
| **Descripción** | Permite cambiar los datos personales y la imagen de usuario             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R05**     | **Iniciar Sesión con usuario**           |
| --------------: | :------------------- |
| **Descripción** | Formulario donde introducir el usuario y la contraseña para acceder a la aplicación.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R06**     | **Cerrar Sesión de usuario**           |
| --------------: | :------------------- |
| **Descripción** | Permite cerrar una sesión abierta en el navegador actual. Automáticamente se volverá al sitio principal.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R07**     | **Check para recordar sesión activa**           |
| --------------: | :------------------- |
| **Descripción** | Permite marcar una casilla en la misma ventana de login para recordar la sesión durante 30 días en el navegador. A los 30 días expirará la sesión y se deberá volver a iniciar.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R08**     | **Avatar de usuario**           |
| --------------: | :------------------- |
| **Descripción** | Cada usuario puede tener un avatar, en caso de no ser seleccionado se otorga el que existe por defecto.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R09**     | **Cambiar contraseña de usuario**           |
| --------------: | :------------------- |
| **Descripción** | Los usuarios pueden cambiar su propia contraseña             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R10**     | **Buscar usuario por nick**           |
| --------------: | :------------------- |
| **Descripción** | Se pueden buscar usuarios por el nick/apodo que usan             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R11**     | **Datos almacenados para ip bloqueadas**           |
| --------------: | :------------------- |
| **Descripción** | Para bloquear una IP se almacenará: - IP - Fecha de bloqueo  Las IP bloqueadas no podrán hacer login ni crear cuentas durante 1 día             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R12**     | **Bloquear acceso a una IP**           |
| --------------: | :------------------- |
| **Descripción** | Bloquear IP tras 10 intentos de login erróneos             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R13**     | **Datos almacenados para usuarios bloqueados**           |
| --------------: | :------------------- |
| **Descripción** | Se almacenarán los siguientes datos: - ID del usuario - Fecha de bloqueo             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R14**     | **Bloquear acceso a un usuario**           |
| --------------: | :------------------- |
| **Descripción** | Los usuarios marcados como bloqueado no podrán volver a iniciar sesión             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R15**     | **Baja de usuario**           |
| --------------: | :------------------- |
| **Descripción** | Formulario simple que permite eliminar una cuenta de usuario. El usuario debe estar dentro de la sesión y verificar contraseña.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R16**     | **Datos almacenados sobre roles**           |
| --------------: | :------------------- |
| **Descripción** | Para cada role se almacenará la siguiente información: - Tipo del role o nombre de este - Descripción             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R17**     | **Crear Roles de usuarios**           |
| --------------: | :------------------- |
| **Descripción** | Crear distintos roles con permisos diferentes para cada usuario: - nuevo → Cuenta recién creada, solo puede rellenar su perfil. - novato → Cuenta creada recientemente pero ha verificado su email. - geekv1 → Ha publicado 10 torrents. Máximo 1 torrent al día. - geekv2 → Ha publicado 50 torrents. Máximo 3 torrents al día. - geekv3 → Ha publicado 100 torrents. Máximo 20 torrents/día. - especial → Designado manualmente por el administrador para colaborar en la administración o moderación del sitio. Puede editar comentarios y torrents de todo el mundo.              |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R18**     | **Crear Rol administrador**           |
| --------------: | :------------------- |
| **Descripción** | El rol administrador designado al usuario “admin” será quien tendrá los máximos permisos de administración del sitio y podrá efectuar cualquier operación en cualquier momento.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R19**     | **Datos almacenado para cada torrent**           |
| --------------: | :------------------- |
| **Descripción** | Para cada torrent se recogerá los siguientes datos: - Licencia  - Categoría (para agruparlos) - Usuario que ha subido el torrent - Título - Resumen - Descripción - Imagen - Ruta hacia el archivo torrent subido - Tamaño del archivo torrent subido - Enlace Magnet del torrent - Password para descomprimir el torrent - Cantidad de descargas - Cantidad de visitas a la ficha del torrent - Fecha de subida - Fecha de modificación             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R20**     | **Crear categorías de torrents**           |
| --------------: | :------------------- |
| **Descripción** | Los torrents tendrán que pertenecer obligatoriamente a una de estas categorías preestablecidas.  Los usuarios no podrán crear más categorías. Las categorías son las siguientes: - Máquinas Virtuales - Libros             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R21**     | **Agregar torrent**           |
| --------------: | :------------------- |
| **Descripción** | Formulario que solicita los datos básicos del torrent y subirlo. Es obligatorio una categoría de torrent y una descripción. En el caso de que el torrent sea idéntico a otro existente en la BD se denegará compartirlo. Se desea conocer: - Nombre - Descripción corta - Descripción larga - Imagen - Quien lo sube - Categoría - Fecha de creación - Tamaño - Compresión - Contraseña (Se desaconseja usar) - Licencia - Suma de verificación del torrent             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R22**     | **Visualizar Torrent**           |
| --------------: | :------------------- |
| **Descripción** | Antes de ser descargado abrir una página dedicada al torrent mostrando información completa sobre este. No podrá eliminarse ni modificarse.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R23**     | **Datos almacenados para cada licencia**           |
| --------------: | :------------------- |
| **Descripción** | Los datos almacenados para las licencias de los torrents son: - Nombre de la licencia - URL hacía el sitio web con la información de la licencia - Imagen             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R24**     | **Sistema de licencias**           |
| --------------: | :------------------- |
| **Descripción** | Implementar sistema de licencias que se muestre al visualizar un torrent, para conocer la licencia que dispone el archivo que vamos a descargar.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R25**     | **Busquedas de torrents**           |
| --------------: | :------------------- |
| **Descripción** | Búsqueda paginada de torrents por categoría y nombre.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R26**     | **Datos almacenados para la descarga de torrents**           |
| --------------: | :------------------- |
| **Descripción** | Las descargas de torrents se almacenarán en la base de datos con la siguiente información: - IP desde la cual se pulsa para descargar - Id del torrent a descargar - Instante de la descarga             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R27**     | **Descargar Torrent**           |
| --------------: | :------------------- |
| **Descripción** | Al pulsar comenzará la descarga del archivo torrent y se registrará esta descarga en la base de datos (tabla con una entrada por cada descarga realizada)             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R28**     | **Añadir imagen a Torrent**           |
| --------------: | :------------------- |
| **Descripción** | Permite subir una imagen para relacionarla con el torrent. Recomendado 300x300px proporciones 1:1 y no superar 500KB             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R29**     | **Generar suma de comprobación al torrent**           |
| --------------: | :------------------- |
| **Descripción** | Auto generar una suma de comprobación al torrent subido. Este dato también será almacenado. Se mostrará cuando se visualice el torrent.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R30**     | **Modificar Torrent**           |
| --------------: | :------------------- |
| **Descripción** | El usuario puede modificar el título, descripción e imagen. También puede eliminar el torrent pero no resubir el archivo torrent.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R31**     | **Mostrar veces que se ha pulsado descargar un torrent**           |
| --------------: | :------------------- |
| **Descripción** | Cada vez que se pulsa un torrent se registra y cuando se visualiza este se muestra la cantidad de veces que se ha descargado.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R32**     | **Almacenar texto del enlace magnet**           |
| --------------: | :------------------- |
| **Descripción** | Almacenar en la Base de Datos el enlace magnet al torrent             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R33**     | **Copiar enlace Magnet al portapapeles**           |
| --------------: | :------------------- |
| **Descripción** | Al pulsar sobre un icono, se copiará automáticamente el enlace al portapapeles del sistema operativo             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R34**     | **Aviso Legal**           |
| --------------: | :------------------- |
| **Descripción** | Vista para mostrar el aviso legal del sitio             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R35**     | **Política de Cookies**           |
| --------------: | :------------------- |
| **Descripción** | Vista para mostrar la política de cookies             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R36**     | **Política de Privacidad**           |
| --------------: | :------------------- |
| **Descripción** | Vista para mostrar las políticas de privacidad             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R37**     | **Cartel sobre cookies y RGPD**           |
| --------------: | :------------------- |
| **Descripción** | Cartel donde se enlazan a las políticas del sitio web y necesita ser aceptado para dar conformidad. Quedará almacenado en una cookie indicando que está aceptado para no volver a mostrarse.  Para ello se investigará algún plugin jquery y se almacenará en el cliente la aceptación del servicio             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R38**     | **Datos de comentario**           |
| --------------: | :------------------- |
| **Descripción** | Datos que almacenará para un comentario: - Usuario que lo redacta - Torrent al que se asocia - Contenido del comentario - Comentario al que se asocia (si procede) - Fecha de creación - Fecha de modificación             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R39**     | **Crear un comentario**           |
| --------------: | :------------------- |
| **Descripción** | En un torrent se puede generar un comentario sobre el mismo.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R40**     | **Modificar Comentario**           |
| --------------: | :------------------- |
| **Descripción** | Permite modificar comentarios propios             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R41**     | **Eliminar Comentario**           |
| --------------: | :------------------- |
| **Descripción** | Funcionalidad para eliminar comentarios por el autor o role administrador             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R42**     | **Los comentarios no pueden superar los 500 caracteres**           |
| --------------: | :------------------- |
| **Descripción** | Los comentarios no pueden extenderse más de 500 caracteres             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R43**     | **Visualizar comentarios asociados a un torrent**           |
| --------------: | :------------------- |
| **Descripción** | Cuando se visualiza un torrent aparecerán debajo del mismo los últimos 10 comentarios realizados             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R44**     | **Solo se permite 1 comentario cada 5 minutos**           |
| --------------: | :------------------- |
| **Descripción** | Un usuario no podrá realizar comentarios seguidos dentro del tiempo indicado (5 minutos)             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R45**     | **Ordenar comentarios**           |
| --------------: | :------------------- |
| **Descripción** | Permite ordenar comentarios por: - Fecha - Usuarios - Importancia según votos             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R46**     | **Datos almacenados para demandar un torrent**           |
| --------------: | :------------------- |
| **Descripción** | Al demandar un torrent se almacenará: - Usuario que lo demanda - Título - Detalles             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R47**     | **Vista para Demandar torrents**           |
| --------------: | :------------------- |
| **Descripción** | Apartado dónde se muestran los torrents demandados, cada demanda permanecerá aquí 30 días y no se mostrará automáticamente pasado ese tiempo.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R48**     | **Demanda de torrent**           |
| --------------: | :------------------- |
| **Descripción** | Permite demandar un torrent específico que aún no haya sido subido a la plataforma             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R49**     | **Datos almacenados para la puntuación de torrents**           |
| --------------: | :------------------- |
| **Descripción** | Se almacenará: - Usuario que vota - Puntuación de 0-10  Si ya había votado, al votar nuevamente se actualizará el valor de la puntuación por la nueva.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R50**     | **Sistema de puntuación de torrents**           |
| --------------: | :------------------- |
| **Descripción** | Se podrá puntuar los torrents en una escala 0-10. Mostrará la media obtenida junto al torrent.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R51**     | **Datos Almacenados sobre reportes de torrents**           |
| --------------: | :------------------- |
| **Descripción** | Al reportar un torrent se almacenará la siguiente información: - Usuario que reporta - Torrent asociado - IP de quien reporta - Título del reporte - Motivo del reporte - Indicación de si ha sido enviado el reporte por email a los administradores - Fecha de creación             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R52**     | **Reportar Torrent **           |
| --------------: | :------------------- |
| **Descripción** | Reportar torrent con uso indebido llevando a un formulario de envío para describir por qué cree que no es correcto.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R53**     | **Vista para torrents reportados**           |
| --------------: | :------------------- |
| **Descripción** | En esta vista solo podrá acceder los roles administrador y especial, se mostrará un listado de los torrents reportados, su descripción y enlace a este.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R54**     | **Descartar o eliminar torrent reportado**           |
| --------------: | :------------------- |
| **Descripción** | En la vista existirá un botón para descartar el reporte o eliminar el material reportado             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R55**     | **Datos sobre reportes de comentarios**           |
| --------------: | :------------------- |
| **Descripción** | Los datos almacenados para los comentarios reportados serán: - Usuario que reporta - Comentario al que se asocia - ip  - Título - Motivo para el reporte - Indicación de si ha sido enviado el reporte por email a los administradores - Fecha de creación             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R56**     | **Reportar Comentario**           |
| --------------: | :------------------- |
| **Descripción** | Un usuario puede marcar un comentario para reportarlo solo una vez. Esto envía una notificación a un administrador/moderador             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v2             |


| **R57**     | **Datos almacenados para votos de comentarios**           |
| --------------: | :------------------- |
| **Descripción** | Cuando se vota un comentario se almacenará: - Usuario - Puntuación del 0-10             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R58**     | **Votar Comentarios**           |
| --------------: | :------------------- |
| **Descripción** | Los comentarios se pueden votar             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R59**     | **Vista para comentarios reportados**           |
| --------------: | :------------------- |
| **Descripción** | En esta vista solo podrá acceder los roles administrador y especial, se mostrará un listado de los comentarios reportados, su descripción y enlace a este.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R60**     | **Descartar o eliminar comentario reportado**           |
| --------------: | :------------------- |
| **Descripción** | En la vista existirá un botón para descartar el reporte o eliminar el material reportado             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R61**     | **Check al enviar un comentario obligando aceptar políticas del sitio y RGPD**           |
| --------------: | :------------------- |
| **Descripción** | Obligar a marcar las políticas del sitio y añadir enlace a ellas junto al check en el formulario para agregar nuevo comentario. Si está logueado ya tiene aceptado y no se mostrará el botón pero si los enlaces.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R62**     | **Mostrar torrents totales de un usuario al ver su perfil**           |
| --------------: | :------------------- |
| **Descripción** | En la vista del usuario muestra la cantidad de torrent totales             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R63**     | **Datos almacenados al registrar accesos a la BD**           |
| --------------: | :------------------- |
| **Descripción** | - ID Del usuario que accede - Instante del acceso             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R64**     | **Registrar accesos en BD**           |
| --------------: | :------------------- |
| **Descripción** | Cada vez que un usuario accede (crea una nueva sesión) al sitio web se registra su dirección ip, usuario y timestamp.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R65**     | **Crear vista de búsqueda avanzada**           |
| --------------: | :------------------- |
| **Descripción** | En este apartado se podrá buscar filtrando por la mayoría de las posibilidades como: rango de puntuación, uploader, categoría…             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R66**     | **Check al crear usuario aceptando políticas del sitio y RGPD**           |
| --------------: | :------------------- |
| **Descripción** | Obligar a marcar las políticas del sitio y añadir enlace a ellas junto al check en el formulario de creación de usuarios             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R67**     | **Mostrar en un lateral torrents mejor valorados**           |
| --------------: | :------------------- |
| **Descripción** | Los 5 torrents con más puntuación se verán en el lateral siendo accesibles con un click             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R68**     | **Mostrar últimos comentarios en lateral**           |
| --------------: | :------------------- |
| **Descripción** | Los 5 últimos comentarios se mostrarán en el menú lateral             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R69**     | **Unificar maquetación de vistas**           |
| --------------: | :------------------- |
| **Descripción** | Estandarizar todas las vistas con la misma maquetación             |
| **Prioridad**   | Importante           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R70**     | **Mostrar usuarios conectados y totales**           |
| --------------: | :------------------- |
| **Descripción** | Se informará de la cantidad de usuarios conectados en la aplicación y de los usuarios totales existentes.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R71**     | **Vista para estadísticas**           |
| --------------: | :------------------- |
| **Descripción** | En esta vista se podrán ver estadísticas para el administrador             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R72**     | **Estadísticas Cantidad de descargas totales**           |
| --------------: | :------------------- |
| **Descripción** | Dibuja en una gráfica el total de descargas de torrents por agregación al mes             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R73**     | **Estadísticas Cantidad de usuarios totales**           |
| --------------: | :------------------- |
| **Descripción** | Dibuja en una gráfica la estadística con la cantidad de usuarios totales por agregación al mes             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R74**     | **Estadísticas Cantidad de torrents totales**           |
| --------------: | :------------------- |
| **Descripción** | Dibuja en una gráfica la estadística con el total de torrent totales por agregación al mes             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R75**     | **Exportar estadísticas a PDF**           |
| --------------: | :------------------- |
| **Descripción** | Estadísticas como la cantidad de usuarios, cantidad de torrents, descargas totales… podrán ser exportadas a un archivo PDF por un administrador             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R76**     | **Superar pruebas de HTML5 y CSS3**           |
| --------------: | :------------------- |
| **Descripción** | Se deberá comprobar que el código supera:  a. Validador para HTML5, CSS3.  b. Nivel de accesibilidad AA.  c. Prueba del seis.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R77**     | **Validar Accesibilidad**           |
| --------------: | :------------------- |
| **Descripción** | Mínimas reglas de accesibilidad cumplida             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R78**     | **Validar Formularios desde Servidor**           |
| --------------: | :------------------- |
| **Descripción** | Validar los formularios recibidos en el servidor sin tener en cuenta si ya se han validado en el usuario/cliente             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R79**     | **Validar Formularios desde Cliente**           |
| --------------: | :------------------- |
| **Descripción** | Validar los formularios antes de ser enviados, por el navegador usuario/cliente             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R80**     | **Utilizar AJAX**           |
| --------------: | :------------------- |
| **Descripción** | Añadir funcionalidades que hagan uso de Ajax             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R81**     | **Utilizar jQuery**           |
| --------------: | :------------------- |
| **Descripción** | Añadir funcionalidades que hagan uso de jQuery             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R82**     | **Manejo de eventos**           |
| --------------: | :------------------- |
| **Descripción** | Interactividad a través de mecanismo de manejo de eventos intuitivos y eficaces.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R83**     | **Uso del DOM**           |
| --------------: | :------------------- |
| **Descripción** | Uso y manipulación de las características del modelo de objetos del documento (DOM).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R84**     | **Uso de mecanismos de almacenamiento**           |
| --------------: | :------------------- |
| **Descripción** | Uso de mecanismos de almacenamiento en el lado del cliente.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R85**     | **Plugins Jquery**           |
| --------------: | :------------------- |
| **Descripción** | Incluir al menos un plugin no trabajado en clase.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R86**     | **PHP 7.1**           |
| --------------: | :------------------- |
| **Descripción** | Usar PHP 7.1             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R87**     | **Yii2 Framework**           |
| --------------: | :------------------- |
| **Descripción** | Usar Yii2 Framework versión 2.0.10 o superior.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R88**     | **PostgreSQL**           |
| --------------: | :------------------- |
| **Descripción** | Usar PostgreSQL versión 9.6 o superior.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R89**     | **Uso de Heroku**           |
| --------------: | :------------------- |
| **Descripción** | Despliegue de la apliación en la plataforma Heroku.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R90**     | **Uso de Codeception**           |
| --------------: | :------------------- |
| **Descripción** | Pruebas funcionales con Codeception.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R91**     | **Uso de Code Climate**           |
| --------------: | :------------------- |
| **Descripción** | Estilo y mantenibilidad del código fuente validados por Code Climate.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R92**     | **Escalabilidad de la aplicación**           |
| --------------: | :------------------- |
| **Descripción** | La aplicación ha de ser escalable             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R93**     | **Estructura en HTML5**           |
| --------------: | :------------------- |
| **Descripción** | Para estructurar el contenido se utilizarán las etiquetas semánticas de HTML5.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R94**     | **Presentación con CSS3**           |
| --------------: | :------------------- |
| **Descripción** | Todo lo relacionado con la presentación se trabajará mediante CSS3.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R95**     | **Diseño flexible**           |
| --------------: | :------------------- |
| **Descripción** | El diseño será flexible             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R96**     | **Incluir Animaciones**           |
| --------------: | :------------------- |
| **Descripción** | Existirán transiciones, transformaciones, animaciones y contenido multimedia.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R97**     | **Incluir Microdatos**           |
| --------------: | :------------------- |
| **Descripción** | Uso de microdatos.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R98**     | **Diseño apto para diferentes resoluciones**           |
| --------------: | :------------------- |
| **Descripción** | Implementar el diseño para resoluciones grandes y pequeñas.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R99**     | **Registro de usuario**           |
| --------------: | :------------------- |
| **Descripción** | La aplicación permitirá el registro de usuarios.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R100**     | **Visualizar maquetación en distintos navegadores web**           |
| --------------: | :------------------- |
| **Descripción** | Comprobar que cada elemento se encuentra en el lugar que corresponde al ser visualizado en distintos navegadores             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R101**     | **Visualizar diseño en distintos navegadores web**           |
| --------------: | :------------------- |
| **Descripción** | Comprobar que la visualización de la aplicación es aceptable en distintos navegadores conocidos y más utilizados como: - Firefox - Firefox-ESR - Chromium - Chrome - Safari - Opera - Epyphany - Falkon - Google Browser (Android)             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R102**     | **Desplegar Aplicación en local**           |
| --------------: | :------------------- |
| **Descripción** | Desplegar la aplicación en local simulando produción (sin desarrollo para probarla y someterla a tests)             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R103**     | **Desplegar la aplicación en  host**           |
| --------------: | :------------------- |
| **Descripción** | Realizar el despliegue en un Host:   a. Utilizando algún servicio gratuito de hosting como los vistos en clase.  b. Instalar / configurar o solicitar el software necesario para desplegar el proyecto.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R104**     | **Incidencias en GitHub**           |
| --------------: | :------------------- |
| **Descripción** | Cada requisito se definirá en github como un issue             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R105**     | **Código Fuente en GitHub**           |
| --------------: | :------------------- |
| **Descripción** | El código fuente será publicado en GitHub             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R106**     | **Estilo de código Yii2**           |
| --------------: | :------------------- |
| **Descripción** | Estilo del código según las normas internas de Yii2 para el código y para las plantillas.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R107**     | **Tres lanzamientos**           |
| --------------: | :------------------- |
| **Descripción** | Tres lanzamientos (releases) etiquetados en el repositorio como v1, v2 y v3.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R108**     | **README en el directorio raíz**           |
| --------------: | :------------------- |
| **Descripción** | README.md en el directorio raíz con la descripción principal del proyecto.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R109**     | **Documentación en Github Pages**           |
| --------------: | :------------------- |
| **Descripción** | Documentación generada con yii2-apidoc y publicada en Github Pages a partir del contenido del directorio /docs:  a. Contenido:    i. Guía general    ii. API  b. Formato: Github flavored Markdown (fuente) y HTML (resultado).  c. Usar script publicar_doc.sh contenido en la raíz del proyecto.  d. Opciona: conversión a PDF             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R110**     | **Solucionar todas las incidencias**           |
| --------------: | :------------------- |
| **Descripción** | Administración y resolución de todas las incidencias notificadas en Github.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R111**     | **Usar etiquetas e hitos**           |
| --------------: | :------------------- |
| **Descripción** | Usar etiquetas e hitos:  a. Etiquetas: mínimo, importante, opcional (además de las ya existentes).  b. Hitos: v1, v2, v3 (con fechas de entrega aproximadas).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R112**     | **Versión más estable en la rama master**           |
| --------------: | :------------------- |
| **Descripción** | La rama master debe reflejar en todo momento el estado más estable de la aplicación, de manera que:  a. La rama master no debe contener bugs conocidos.  b. El desarrollo deberá hacerse en otras ramas creadas a tal efecto (una distinta por cada funcionalidad) y se irán combinando con la master una vez que se haya implementado la funcionalidad correspondiente.  c. Cada rama debe ir asociada con una incidencia. El nombre de la rama debe empezar por el número de la incidencia correspondiente (p. ej. 17-login).  d. La release actual en Heroku corresponderá siempre con el último commit de la rama master (usar los deploys automáticos de Heroku conectando la aplicación de Heroku con la rama master de Github).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R113**     | **Usar Waffle**           |
| --------------: | :------------------- |
| **Descripción** | Usar Waffle para la gestión general del proyecto.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R114**     | **Iteraciones**           |
| --------------: | :------------------- |
| **Descripción** | Al final de cada iteración:  a. Se realiza el lanzamiento que toque (v1, v2 o v3), etiquetando el commit correspondiente con el hito adecuado.  b. Se actualiza y publica la documentación.  c. Al final del Proyecto, se tiene que cumplir lo siguiente:    i. Todas las incidencias cerradas con su debida justificación.    ii. En el backlog sólo pueden quedar tarjetas con prioridad opcional.    iii. El lanzamiento v3 desplegado en la nube.    iv. La documentación correctamente actualizada y publicada.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R115**     | **Formularios largos paginados**           |
| --------------: | :------------------- |
| **Descripción** | Los formularios con demasiados campos serán paginados para mostrar pocos campos en cada paso             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R116**     | **Interfaz Publicar resúmenes en redes sociales**           |
| --------------: | :------------------- |
| **Descripción** | Mediante esta interfaz se mandará la información para ser publicada en todas las redes sociales disponibles a la vez             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R117**     | **Asociar con API Twitter para crear bot automatizado**           |
| --------------: | :------------------- |
| **Descripción** | Asociar con la API de twitter para desarrolladores e integrar con un bot la aplicación de forma que cada cierto tiempo publique automáticamente un resumen de la actividad: - Últimas subidas → enlace y titulos más descargados - Lo más descargado del mes → enlace y títulos             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R118**     | **Asociar con API Telegram para crear bot automatizado**           |
| --------------: | :------------------- |
| **Descripción** | Asociar con la API de telegram para crear un bot que publique en un canal de forma automatizada resúmenes de nuevos torrents o torrents más descargados cada cierto tiempo.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R119**     | **Integrar torrents en trackers**           |
| --------------: | :------------------- |
| **Descripción** | Decirle a trackers importantes que existe cada torrent almacenado en el sitio             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R120**     | **Login Google+**           |
| --------------: | :------------------- |
| **Descripción** | Permite acceder a la aplicación mediante cuenta de Google+             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R121**     | **Login Facebook**           |
| --------------: | :------------------- |
| **Descripción** | Permite acceder a la aplicación mediante cuenta de Facebook             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R122**     | **Bloquear posibles torrents peligrosos**           |
| --------------: | :------------------- |
| **Descripción** | Detectar si el archivo que hace referencia el torrent es peligroso o incumple las políticas del sitio. En principio esto es difícil de lograr y se filtrará extensiones para bloquear formatos de vídeo y binarios como: mp4,avi,flv,bat,exe…             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R123**     | **Almacenar cantidad de semillas**           |
| --------------: | :------------------- |
| **Descripción** | Se almacena la cantidad de usuarios que comparten el recurso torrent.  Para actualizar este valor primero comprobará que lleva más de un día desde la última comprobación, como esto valores estarán guardados (ultima comprobación de seed y cantidad de seed) en la misma tabla de torrents no genera esfuerzo extra.  La comprobación de semillas se llevará a cabo cuando un usuario acceda a visualizar el torrent para su descarga, de forma que no se hará constantemente ni tampoco sobre torrents que nadie use.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R124**     | **Enviar estadísticas por email**           |
| --------------: | :------------------- |
| **Descripción** | Las estadísticas serán enviadas mensualmente por email o manualmente pulsando sobre dicha acción             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R125**     | **Visita interactiva guiada para nuevos usuarios**           |
| --------------: | :------------------- |
| **Descripción** | Cuando un nuevo usuario es creado se le mostrará mediante una visita guiada como funciona la aplicación de forma interactiva resaltando cada apartado y describiendo su funcionamineto.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R126**     | **Datos almacenados para temas de usuario**           |
| --------------: | :------------------- |
| **Descripción** | - Nombre del tema (será el nombre de la clase CSS) - Descripción del esquema de colores             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R127**     | **Selector de temas**           |
| --------------: | :------------------- |
| **Descripción** | Permitir cambiar tema en la configuración de usuario             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R128**     | **Vista para configurar usuario**           |
| --------------: | :------------------- |
| **Descripción** | En esta vista se puede seleccionar preferencias del usuario, es independiente al perfil personal del usuario y contempla opciones de uso sobre la plataforma y no personales. Entre estas selecciones estará el tema estético y la visita guiada             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R129**     | **Confirmar cuenta email del usuario**           |
| --------------: | :------------------- |
| **Descripción** | Cuando un usuario es dado de alta podrá acceder a la aplicación pero no compartir contenido ni comentarios hasta verificar el email introducido.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R130**     | **Restablecer contraseña por email**           |
| --------------: | :------------------- |
| **Descripción** | Añadir opción por si se olvida la contraseña que permita recuperarla a través de un correo.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R131**     | **Confirmar Baja de usuario por email**           |
| --------------: | :------------------- |
| **Descripción** | Se enviará un correo de confirmación para autenticar al usuario además de haber pedido con anterioridad la contraseña.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R132**     | **Cuando un usuario es borrado recibe un correo**           |
| --------------: | :------------------- |
| **Descripción** | Envía correo al usuario cuando este se borra             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R133**     | **Enviar emails con noticias**           |
| --------------: | :------------------- |
| **Descripción** | Permite enviar emails a los suscritos en la aplicación             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R134**     | **Darse de baja a los emails**           |
| --------------: | :------------------- |
| **Descripción** | Posibilidad de continuar con la cuenta permitiendo elegir si recibe noticias o emails de administración             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R135**     | **Reportar torrent caído.**           |
| --------------: | :------------------- |
| **Descripción** | El reporte llegará a los administradores y moderadores. Además también llegará al usuario que subió en un principio el torrent.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R136**     | **Exportar estadísticas a CSV**           |
| --------------: | :------------------- |
| **Descripción** | Estadísticas como la cantidad de usuarios, cantidad de torrents, descargas totales… podrán ser exportadas a un archivo CSV por un administrador             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R137**     | **Exportar BD de torrents en plano**           |
| --------------: | :------------------- |
| **Descripción** | Permite al administrador exportar la BD completa en texto plano             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R138**     | **Exportar BD de torrents en CSV**           |
| --------------: | :------------------- |
| **Descripción** | Permite al administrador exportar la BD completa en formato CSV             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R139**     | **Traducción a inglés**           |
| --------------: | :------------------- |
| **Descripción** | La aplicación podrá traducir los textos a inglés y recordará la selección mediante almacenamiento en cliente.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R140**     | **Google analytics**           |
| --------------: | :------------------- |
| **Descripción** | Se agregará a google analytics el sitio web y tendrá un código de seguimiento para recabar información y estadísticas.             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |



## Cuadro resumen

| **Requisito** | **Prioridad** | **Tipo** | **Complejidad** | **Entrega** |
| :------------ | :-----------: | :------: | :-------------: | :---------: |
| (**R01**) Datos de usuario | Importante | Información | Fácil | v1 |
| (**R02**) Alta de usuario | Importante | Funcional | Fácil | v1 |
| (**R03**) Visualizar Perfil de usuario | Importante | Funcional | Fácil | v1 |
| (**R04**) Modificar Perfil Usuario | Importante | Funcional | Fácil | v1 |
| (**R05**) Iniciar Sesión con usuario | Importante | Funcional | Fácil | v1 |
| (**R06**) Cerrar Sesión de usuario | Importante | Funcional | Fácil | v1 |
| (**R07**) Check para recordar sesión activa | Importante | Funcional | Fácil | v1 |
| (**R08**) Avatar de usuario | Importante | Funcional | Fácil | v1 |
| (**R09**) Cambiar contraseña de usuario | Importante | Funcional | Fácil | v1 |
| (**R10**) Buscar usuario por nick | Importante | Funcional | Fácil | v1 |
| (**R11**) Datos almacenados para ip bloqueadas | Importante | Información | Media | v1 |
| (**R12**) Bloquear acceso a una IP | Importante | Funcional | Media | v1 |
| (**R13**) Datos almacenados para usuarios bloqueados | Importante | Información | Fácil | v1 |
| (**R14**) Bloquear acceso a un usuario | Importante | Funcional | Media | v1 |
| (**R15**) Baja de usuario | Importante | Funcional | Fácil | v1 |
| (**R16**) Datos almacenados sobre roles | Importante | Información | Fácil | v1 |
| (**R17**) Crear Roles de usuarios | Importante | Funcional | Media | v1 |
| (**R18**) Crear Rol administrador | Importante | Funcional | Media | v1 |
| (**R19**) Datos almacenado para cada torrent | Importante | Información | Fácil | v1 |
| (**R20**) Crear categorías de torrents | Importante | Funcional | Fácil | v1 |
| (**R21**) Agregar torrent | Importante | Funcional | Fácil | v1 |
| (**R22**) Visualizar Torrent | Importante | Funcional | Fácil | v1 |
| (**R23**) Datos almacenados para cada licencia | Importante | Información | Fácil | v1 |
| (**R24**) Sistema de licencias | Importante | Funcional | Fácil | v1 |
| (**R25**) Busquedas de torrents | Importante | Funcional | Fácil | v1 |
| (**R26**) Datos almacenados para la descarga de torrents | Importante | Información | Fácil | v1 |
| (**R27**) Descargar Torrent | Importante | Funcional | Fácil | v1 |
| (**R28**) Añadir imagen a Torrent | Importante | Funcional | Fácil | v1 |
| (**R29**) Generar suma de comprobación al torrent | Importante | Funcional | Media | v1 |
| (**R30**) Modificar Torrent | Importante | Funcional | Fácil | v1 |
| (**R31**) Mostrar veces que se ha pulsado descargar un torrent | Importante | Funcional | Fácil | v1 |
| (**R32**) Almacenar texto del enlace magnet | Importante | Funcional | Fácil | v1 |
| (**R33**) Copiar enlace Magnet al portapapeles | Importante | Funcional | Media | v1 |
| (**R34**) Aviso Legal | Importante | Funcional | Fácil | v2 |
| (**R35**) Política de Cookies | Importante | Funcional | Fácil | v2 |
| (**R36**) Política de Privacidad | Importante | Funcional | Fácil | v2 |
| (**R37**) Cartel sobre cookies y RGPD | Importante | Funcional | Fácil | v2 |
| (**R38**) Datos de comentario | Importante | Información | Fácil | v2 |
| (**R39**) Crear un comentario | Importante | Funcional | Media | v2 |
| (**R40**) Modificar Comentario | Importante | Funcional | Fácil | v2 |
| (**R41**) Eliminar Comentario | Importante | Funcional | Media | v2 |
| (**R42**) Los comentarios no pueden superar los 500 caracteres | Importante | Información | Fácil | v2 |
| (**R43**) Visualizar comentarios asociados a un torrent | Importante | Funcional | Fácil | v2 |
| (**R44**) Solo se permite 1 comentario cada 5 minutos | Importante | Funcional | Fácil | v2 |
| (**R45**) Ordenar comentarios | Importante | Funcional | Media | v2 |
| (**R46**) Datos almacenados para demandar un torrent | Importante | Información | Fácil | v2 |
| (**R47**) Vista para Demandar torrents | Importante | Funcional | Fácil | v2 |
| (**R48**) Demanda de torrent | Importante | Funcional | Media | v2 |
| (**R49**) Datos almacenados para la puntuación de torrents | Importante | Información | Fácil | v2 |
| (**R50**) Sistema de puntuación de torrents | Importante | Funcional | Fácil | v2 |
| (**R51**) Datos Almacenados sobre reportes de torrents | Importante | Información | Fácil | v2 |
| (**R52**) Reportar Torrent  | Importante | Funcional | Media | v2 |
| (**R53**) Vista para torrents reportados | Importante | Funcional | Media | v2 |
| (**R54**) Descartar o eliminar torrent reportado | Importante | Funcional | Media | v2 |
| (**R55**) Datos sobre reportes de comentarios | Importante | Información | Fácil | v2 |
| (**R56**) Reportar Comentario | Importante | Funcional | Difícil | v2 |
| (**R57**) Datos almacenados para votos de comentarios | Importante | Información | Fácil | v2 |
| (**R58**) Votar Comentarios | Importante | Funcional | Media | v2 |
| (**R59**) Vista para comentarios reportados | Importante | Funcional | Media | v2 |
| (**R60**) Descartar o eliminar comentario reportado | Importante | Funcional | Fácil | v2 |
| (**R61**) Check al enviar un comentario obligando aceptar políticas del sitio y RGPD | Importante | Funcional | Fácil | v2 |
| (**R62**) Mostrar torrents totales de un usuario al ver su perfil | Importante | Funcional | Fácil | v2 |
| (**R63**) Datos almacenados al registrar accesos a la BD | Importante | Información | Fácil | v3 |
| (**R64**) Registrar accesos en BD | Importante | Funcional | Media | v3 |
| (**R65**) Crear vista de búsqueda avanzada | Importante | Funcional | Media | v3 |
| (**R66**) Check al crear usuario aceptando políticas del sitio y RGPD | Importante | Funcional | Fácil | v3 |
| (**R67**) Mostrar en un lateral torrents mejor valorados | Importante | Funcional | Fácil | v3 |
| (**R68**) Mostrar últimos comentarios en lateral | Importante | Funcional | Fácil | v3 |
| (**R69**) Unificar maquetación de vistas | Importante | Técnico | Media | v3 |
| (**R70**) Mostrar usuarios conectados y totales | Importante | Funcional | Media | v3 |
| (**R71**) Vista para estadísticas | Importante | Funcional | Difícil | v3 |
| (**R72**) Estadísticas Cantidad de descargas totales | Importante | Funcional | Fácil | v3 |
| (**R73**) Estadísticas Cantidad de usuarios totales | Importante | Funcional | Fácil | v3 |
| (**R74**) Estadísticas Cantidad de torrents totales | Importante | Funcional | Fácil | v3 |
| (**R75**) Exportar estadísticas a PDF | Importante | Funcional | Media | v3 |
| (**R76**) Superar pruebas de HTML5 y CSS3 | Mínimo | Técnico | Media | v3 |
| (**R77**) Validar Accesibilidad | Mínimo | Técnico | Media | v3 |
| (**R78**) Validar Formularios desde Servidor | Mínimo | Técnico | Media | v3 |
| (**R79**) Validar Formularios desde Cliente | Mínimo | Técnico | Media | v3 |
| (**R80**) Utilizar AJAX | Mínimo | Técnico | Media | v3 |
| (**R81**) Utilizar jQuery | Mínimo | Técnico | Media | v3 |
| (**R82**) Manejo de eventos | Mínimo | Técnico | Media | v3 |
| (**R83**) Uso del DOM | Mínimo | Técnico | Media | v3 |
| (**R84**) Uso de mecanismos de almacenamiento | Mínimo | Técnico | Media | v3 |
| (**R85**) Plugins Jquery | Mínimo | Técnico | Media | v3 |
| (**R86**) PHP 7.1 | Mínimo | Técnico | Media | v3 |
| (**R87**) Yii2 Framework | Mínimo | Técnico | Media | v3 |
| (**R88**) PostgreSQL | Mínimo | Técnico | Media | v3 |
| (**R89**) Uso de Heroku | Mínimo | Técnico | Media | v3 |
| (**R90**) Uso de Codeception | Mínimo | Técnico | Media | v3 |
| (**R91**) Uso de Code Climate | Mínimo | Técnico | Media | v3 |
| (**R92**) Escalabilidad de la aplicación | Mínimo | Técnico | Media | v3 |
| (**R93**) Estructura en HTML5 | Mínimo | Técnico | Media | v3 |
| (**R94**) Presentación con CSS3 | Mínimo | Técnico | Media | v3 |
| (**R95**) Diseño flexible | Mínimo | Técnico | Media | v3 |
| (**R96**) Incluir Animaciones | Mínimo | Técnico | Media | v3 |
| (**R97**) Incluir Microdatos | Mínimo | Técnico | Media | v3 |
| (**R98**) Diseño apto para diferentes resoluciones | Mínimo | Técnico | Media | v3 |
| (**R99**) Registro de usuario | Mínimo | Técnico | Media | v3 |
| (**R100**) Visualizar maquetación en distintos navegadores web | Mínimo | Técnico | Media | v3 |
| (**R101**) Visualizar diseño en distintos navegadores web | Mínimo | Técnico | Media | v3 |
| (**R102**) Desplegar Aplicación en local | Mínimo | Técnico | Fácil | v3 |
| (**R103**) Desplegar la aplicación en  host | Mínimo | Técnico | Fácil | v3 |
| (**R104**) Incidencias en GitHub | Mínimo | Técnico | Fácil | v3 |
| (**R105**) Código Fuente en GitHub | Mínimo | Técnico | Fácil | v3 |
| (**R106**) Estilo de código Yii2 | Mínimo | Técnico | Fácil | v3 |
| (**R107**) Tres lanzamientos | Mínimo | Técnico | Fácil | v3 |
| (**R108**) README en el directorio raíz | Mínimo | Técnico | Fácil | v3 |
| (**R109**) Documentación en Github Pages | Mínimo | Técnico | Fácil | v3 |
| (**R110**) Solucionar todas las incidencias | Mínimo | Técnico | Fácil | v3 |
| (**R111**) Usar etiquetas e hitos | Mínimo | Técnico | Fácil | v3 |
| (**R112**) Versión más estable en la rama master | Mínimo | Técnico | Fácil | v3 |
| (**R113**) Usar Waffle | Mínimo | Técnico | Fácil | v3 |
| (**R114**) Iteraciones | Mínimo | Técnico | Fácil | v3 |
| (**R115**) Formularios largos paginados | Opcional | Funcional | Media | v3 |
| (**R116**) Interfaz Publicar resúmenes en redes sociales | Opcional | Funcional | Media | v3 |
| (**R117**) Asociar con API Twitter para crear bot automatizado | Opcional | Funcional | Media | v3 |
| (**R118**) Asociar con API Telegram para crear bot automatizado | Opcional | Funcional | Media | v3 |
| (**R119**) Integrar torrents en trackers | Opcional | Funcional | Difícil | v3 |
| (**R120**) Login Google+ | Opcional | Funcional | Difícil | v3 |
| (**R121**) Login Facebook | Opcional | Funcional | Difícil | v3 |
| (**R122**) Bloquear posibles torrents peligrosos | Opcional | Funcional | Difícil | v3 |
| (**R123**) Almacenar cantidad de semillas | Opcional | Funcional | Difícil | v3 |
| (**R124**) Enviar estadísticas por email | Opcional | Funcional | Difícil | v3 |
| (**R125**) Visita interactiva guiada para nuevos usuarios | Opcional | Funcional | Difícil | v3 |
| (**R126**) Datos almacenados para temas de usuario | Opcional | Funcional | Fácil | v3 |
| (**R127**) Selector de temas | Opcional | Funcional | Media | v3 |
| (**R128**) Vista para configurar usuario | Opcional | Funcional | Media | v3 |
| (**R129**) Confirmar cuenta email del usuario | Opcional | Funcional | Difícil | v3 |
| (**R130**) Restablecer contraseña por email | Opcional | Funcional | Difícil | v3 |
| (**R131**) Confirmar Baja de usuario por email | Opcional | Funcional | Media | v3 |
| (**R132**) Cuando un usuario es borrado recibe un correo | Opcional | Funcional | Difícil | v3 |
| (**R133**) Enviar emails con noticias | Opcional | Funcional | Difícil | v3 |
| (**R134**) Darse de baja a los emails | Opcional | Funcional | Difícil | v3 |
| (**R135**) Reportar torrent caído. | Opcional | Funcional | Fácil | v3 |
| (**R136**) Exportar estadísticas a CSV | Opcional | Funcional | Media | v3 |
| (**R137**) Exportar BD de torrents en plano | Opcional | Funcional | Media | v3 |
| (**R138**) Exportar BD de torrents en CSV | Opcional | Funcional | Media | v3 |
| (**R139**) Traducción a inglés | Opcional | Funcional | Media | v3 |
| (**R140**) Google analytics | Opcional | Funcional | Media | v3 |
