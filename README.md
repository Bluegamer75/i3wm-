# i3wm-
Hola, a continuacion, os voy a mostrar la configuracion que tengo en mi portatil de i3wm, espero que os guste, soy bastante nuevo aun en linux debido a que llevo menos de un añño utilizandolo pero por ahora no creo que se me de del todo mal. A continuacion os explicare paso a paso los programas que utilizo y los scritps que tengo yo configurados para que los podais replicar si quereis.

# Configuracion de i3
La configuracion por ahora esta muy vacia, no he tocado apenas nada de la configuracion inicial (quitando algun acceso que otro y algun script). Utilizo i3 ocn polybar porque antes de poybar tenia bumbleebe-status pero em cambie a polybar por el amor que le tengo desde hacce ya tiempo. Los programas que yo utlizo que necesitais son rofi, feh y compton. Como editor de codigo tengo o visual studio code o neovim. Dejare las configuraciones necesarias en el repo po si alguno lo necesita.

# Porque i3?
En mi portatil tengo instalado a dia de hoy debian 11 de 32 bits porque mi porcesador por desgracia es de 32 bits. He probado otros entornos de escritorio pero o se me petan o me dan fallos. Pero en el caso de i3 no me esta dando ningun fallo ni se me congela como los demas. I3 es uno de los gestores de ventanas que he usado junto con qtile y bspwm. Es muy facil de utilizar, si tienes alguna duda que como opner alguna cosa lo miras el el manual y se hace en menos de un minuto. La unica pega que tengo es que si le quitas el numero al espaciok de trabajo este se queda inutilizable. 

# Scripts
Los scripts que tengo son muy basicos; por ejempo, un script que me odena todos los archivos de programacion, musica, video e imagenes y los mete en sus respectivas carpetas. Otro que me hace capturas de pantalla y me las envia a la carpeta de Imágenes/Screenshots. Otro con el que arreglo un bug de mi pantalla que hace que saliera en vertical y otro que me cierra la sesion.

# Mi laptop
Specs de mi portatil (muy basica)
-Modelo: Acer One S1003 (300 euros)
-Intel Atom x5-8350 4 cores (sin hilos) a 1,44GHz hasta 1,92GHz (con un voltage de 1 what :OO)
-4GB de RAM DDR3 a 1667mhz 
-50GB Almacenamiento (SD) junto con dualboot de windows10 32 bits de 70GB
-Pantalla de 10 pulgadas a resolucion 1280x800 pixeles
-Puertos: (un solo USB junto con un Micro HDMI y un puerto para cargar el portatil micro USB tipo A)

Por ahora me queda por isntalar los drivers de audio porque no consigo escuchar onidos in siquiera con los ausiculares, pero al principio solo podia estar conectado mediante un adpatador ethernet a internet hasta que me descargue los drivers



# Imagenes de como quedó

Imagen de las terminales con compton, (y i3-gaps y polybar)

![2021-10-12_12-10_1](https://user-images.githubusercontent.com/76869585/136936997-095baf34-db86-4cb5-9e67-b62176ff1d69.png)

Aqui teneis una imagen utilizando neovim 

![2021-10-11_15-50](https://user-images.githubusercontent.com/76869585/136801898-9f2df3cc-7062-4732-82c9-73e598798bc3.png)

Y dicho esto pongamonos con la instalacion

# Instalaciòn
Para empezar tendremos que instalar i3 (en mi caso en debian), para instalarlo utilizaremos sudo apt install i3wm i3status (ya cambiareis la barra en el futuro por otra que os guste) rofi feh neovim xorg. Con esto ya podremos empezar con el manual de instalacion y configuracion.

despues de hacer todos los pasos le dais a startx y os deberia cargar i3, sos saltara que tecla quereis que sea mod en el sistema, podeis ponerlo con la tecla de windows o la tecla de control, y ya estariais en i3, una bonita pantalla negra que tendras que saber como configurar, para abrir una terminal tendreis que darle mod+Enter para despues hacer un cd .config/i3 y usar nano config


