# Song Request Tool

Version 1.0

Con esta herramienta podras hacer solicitudes en cola de tus seguidores mediante una app web que puedes administrar de manera facil agregando solamente el usuario y la cancion que soliciten, ya que es algo tedioso estar pendiente del chat y anotar las canciones que te soliciten en tus LIVES.

Features:
 - Podras colocar la aplicacion en TikTok Live Studio mediante compartir pantalla.
 - Podras usar tanto una base de datos relacional como una Ficticia para mas facilidad o limitacion de hardware si requieres de menos recursos.
 - Puedes personalizar el texto de la pagina con tus datos de preferencia.

Como lo puedo usar?

1) Decarga el repositorio a tu escritorio
2) Abre cmd y busca la ubicacion del repositorio descargado y escribes el siguiente comando:
    - Ejemplo : cd C:\Users\bajamut12\Desktop\Song Request
3) Ejecuta el comando en la consola cmd :  python -m venv env
4) Luego habilita el entorno virtual creado con el siguiente comando: env\Scripts\activate
3) Luego escribes el siguiente comando: pip install requirements.txt, se van a instalar unas librerias para que pueda funcionar la app o arrojara error
4) Escribe a continuacion el siguiente comando:
    - python main.py
5) Se abrira automaticamente la app, a empezar a usar!

Con esto ya puedes empezar a usarlo de manera facil, ya esta configurado para que puedas usarlo con una base de datos dummy, por lo que no requiere de otros programas pero si tienes mas experiencia
con programacion, puedes adaptarle una base de datos en el archivo data.ini que es donde se almacena la url de conexion al SQL.

ADVERTENCIA: no modificar nada del data.ini si no tienes conocimiento alguno de los valores que deben estar ahi, los unicos valores que puedes cambiar son los de la seccion [INDEX]

Disfrutalo!
