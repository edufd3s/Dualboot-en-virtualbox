# Linux / GParted

**Los requisitos minimos para instalar ubuntu 24.04 son**

-Un monitor con resolución mínima de 1024×768 puntos.

-25 GB de espacio libre en disco.

-Un dispositivo DVD o un puerto USB para el soporte de instalación.

-Procesador de doble núcleo a 2 GHz o superior.

-4 GB de memoria principal (aunque puede funcionar a partir de 1 GB).

· **G-Parted**

  Se descarga desde su web oficial en [SourceForge](https://sourceforge.net/projects/gparted/files/gparted-live-stable/1.6.0-10/gparted-live-1.6.0-10-amd64.iso/download?use_mirror=unlimited)


## Instalacion GParted 

Mientras arranca la maquina pulsamos F2 y booteamos desde gparted, se abrira una ventana en la que podremos seleccionar la particion que queramos

![Gparted](ubuntu/img/edu_gparted_1.png) elegimos la particion grande e instalamos.

## Instalacion Ubuntu

Montamos la iso de ubuntu que hemos descargado desde la pagina oficial y la montamos en la maquina virtual. Para instalarla al iniciar la maquina virtual pulsamos F2
hasta que nos da la opcion.

Instalamos normalmente ubuntu.

## Grub

A partir de ahora cada vez que iniciemos la maquina virtual el menú GNU GRUB aparecerá y nos dará a elegir con que sistema operativo iniciar.
Eso es lo que hace un gestor de arranque.

## MBR y GPT

MBR y GPT son dos tipos de esquemas de particionamiento para discos duros.

-MBR (Master Boot Record): Es un esquema de particionamiento antiguo que soporta hasta 4 particiones primarias y discos de hasta 2 TB. Se encuentra en el primer sector del disco.

-GPT (GUID Partition Table): Es un esquema más moderno que permite un número casi ilimitado de particiones y puede manejar discos mucho más grandes (varios zettabytes). Se utiliza en sistemas UEFI y ofrece mayor redundancia y flexibilidad.

## Las etapas por las que pasa un ordenador desde que se enciende hasta que el sistema operativo esta listo para ser usado.

1. **POST (Power-On Self Test)**: Verificación del hardware por el firmware (BIOS/UEFI).

2. **Carga el Firmware**: Inicializa el firmware y busca del dispositivo de arranque.

3. **Carga el Bootloader**: Localiza y carga el bootloader desde el dispositivo de arranque.

4. **Inicializa del Kernel**: Carga e inicializa el núcleo del sistema operativo.

5. **Carga los Controladores**: Carga los controladores necesarios para el hardware.

6. **Inicia los Servicios y Procesos**: Activa los servicios y procesos del sistema.

7. **Interfaz de Usuario**: Carga la interfaz gráfica de usuario.

8. **El sistema operativo está disponible para el usuario**
