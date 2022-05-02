⚠️: Antes de instalar el SO asegurate de tener "Secure Boot" deshabilitado
[¿Como deshabilitar Secure Boot?](https://maxedtech.com/how-to-enable-or-disable-secure-boot/)



1. Descarga la version [2.18p de Rufus](https://github.com/pbatard/rufus/releases/download/v2.18/rufus-2.18p.exe) y abre el programa.
2. Busca un pendrive de 8GB o mas y conectalo a tu PC.
3. Selecciona tu pendrive en el apartado de "Dispositivo".
4. Descarga y selecciona el archivo .ISO (Optical disc image).
5. Selecciona el esquema de particion (MBR o GPT).
6. Deja el sistema de archivos en NTFS. 
7. Dale a "Empezar" y luego espera a que se extraiga la .ISO en tu pendrive, este proceso eliminara TODO lo que tenga dentro el pendrive.
8. Cuando hayas finalizado este proceso presiona las teclas Windows + R y escribe "CMD" una vez dentro de CMD ejecuta el siguiente comando "shutdown.exe -r -o -f -t 00" y deberia iniciarte en el Boot Menu.
9. Selecciona tu pendrive (confirma de que tenga "UEFI" en el nombre) y empezara el programa de Instalacion de Windows.
10. Busca la unidad que tenga el tamaño de tu disco principal con Windows, la mayoria de veces, es el DISCO 0. Selecciona cada particion de esa unidad (ejemplo: Unidad 0 Particion 0/1/2) y eliminalas.
11. Cuando hayas eliminado todas las particiones en tu DISCO principal, veras "UNALLOCATED SPACE", seleccionalo y aplica los cambios (creara un nuevo disco con la cantidad total de espacio), luego presiona Siguiente.
12. El SO iniciara con la instalacion en tu PC.
