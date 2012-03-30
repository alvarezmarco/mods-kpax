# MODS ELGG PARA KPAX

Estos modulos son necessarios para el correcto funcionamiento de kpax en la plataforma elgg

# Requisitos

Para un correcto funcionamiento se necesita:

mysql 5

php5

Y tener instalado la plataforma elgg (http://elgg.org/download.php)

# Instalación

Nos descargamos los modulos:

    git checkout o nos lo descargamos 
    
Como podeis ver tiene la estructura de ficheros /elgg/etc... eso quiere decir que lo teneis que copiar en la carpeta mod de la plataforma elgg

    copiar todo el contenido a la carpeta mod de elgg

# CONFIGURACION

Una vez teneis puesto el contenido a la carpeta mod,s los teneis que activar. Para activar teneis que ir a administración de la plataforma elgg y activar los diferentes plugins.

Cuando los tengais instalados teneis que generar las key,s para poder interactuar entre los servicios y los plugins.

os diriguis:
    api administration

Aqui os pedira poner un nombre, poneis kpax, os dara dos valores public key y private key. La que usareis es la public key, la private la utiliza el propio elgg.

Ahora teneis que ir al archivo : 
    /www/elgg/mods/kpax/lib/kpaxSrv.php y modificar la linia donde aparece $apikey = ... y modificar por el valor que has obtenido.

Una vez teneis esto configurado ya podeis utilizar los plugins elgg utilizando vuestro servicio kpax


# INCIDENCIAS

Si tenéis alguna incidencia no dudéis enviar un correo a vuestro responsable

# LICENSE

Universitat Oberta de catalunya