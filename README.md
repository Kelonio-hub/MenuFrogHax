# MenuFrogHax
Método de hackeo para Nintendo 3Ds/2Ds

SINOPSIS

El siguiente proceso de Modificación de 3Ds es un híbrido entre Menuhax67 [https://github.com/zoogie/menuhax67] y Frogtool [https://github.com/zoogie/Frogtool],
ambas creaciones de Zoogie y es a él a quien deben atribuirse todos lo méritos. Yo, Kelonio, únicamente he unido piezas para que esta fusión fuera posible. 
Agradecer, también, a Felix64 por ayudarme a recopilar los archivos y a testearlos. 

Este proceso sirve para todas las consolas, en especial para aquellas que tienen los gatillos rotos y no pueden acceder al Modo Recovery en los procesos de Pichaxx o USM. 

REQUISITOS
1. Consola sin modificación boot9 o a9lh de cualquier modelo y región.
2. Tarjeta Sd formateada en FAT32
3. Archivo Movable.sed [se obtiene mediante el minado de Fuerza Bruta: https://seedminer.hacks.guide/]   
4. Archivo F00D43D5 [se obtiene tras la ejecución del Movable con el programa TADmuffinPC (se encuentra en el directorio de Menuhax67)]
5. Archivo bb3.bin (se encuentra en el directorio de Menuhax67)
6. Launcher.dat REGIONAL (se encuentra en el directorio de Menuhax67)
7. Boot.nds (https://github.com/zoogie/b9sTool/releases)
8. Frogminer.3dsx (https://github.com/zoogie/Frogtool)
9. Carpeta Private de Frogminer (https://github.com/zoogie/Frogminer/releases/tag/v1.0)
10. frogcert.bin (este archivo costará encontrarlo debido a su licencia)
11. Archivos hack variados (boot.firm de luma, payload de godmode9, FBI...) 

PROCEDIMIENTO
1. Configurar un personaje MII, apuntar el código y acudir al REQUISITO 2 para obtener el MOVABLE.sed
2. Obtener el archivo F00D43D5 tras la conversión con TADmuffinPC. Meter dicho archivo en la siguiente ruta: sd/Nintendo3Ds/ID1/ID0/Nintendo DSiWare
3. Meter en la raiz de la Tarjeta Sd los archivos de los REQUISITOS 5,6,7,9,10,11. Introducir también el Movable.sed.
4. Introducir el archivo Frogminer.3dsx en la ruta sd/3ds
5. Introducir la Tarjeta Sd en la consola y acudir a Configuración de la consola/Gestión de Datos/DSi Ware/Tarjeta SD. Se flasheará y estaremos en el menú de Bannerbomb3.
6. Activar la opción de Hax, y esperar al reinicio. Al reiniciar acudir al comando de Tema [casita superior izquierda] se flasheará y estaremos en el HBL. 
7. Ejecutar Frogminer.3dsx, dejar que carge. Elegir la opción de Injet y, al finalizar, la opción de Boot. Entraremos, por tanto, a Flipnote Studio. 
8. Realizar la siguiente guía de pasos sobre Flipnote Studio https://zoogie.github.io/web/flipnote_directions/
9. Al finalizar los pasos estaremos ante b9sTool, tendremos que darle a la opción de Install.
10. La consola se reiniciará y ejecutará el boot.firm (el de luma o el de godmode9, según convenga). 
11. Tan solo faltaría instalar el FBI, recuperar el Modo Descarga nds y crear la NAND.
