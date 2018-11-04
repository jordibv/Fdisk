# Fdisk

Fdisk es un software que está para varios sistemas operativos, el cual permite dividir un disco duro, con nombre de partición. La descripción de las particiones se guarda en la tabla de particiones que se localiza en el sector 0 de cada disco.
como funciona?

para crear

vemos todos los discos con Fdisk -l

para elegir el disco duro a editar utilizamos fdisk dev/sda

vemos todas las opciones con la letra m

n : nueva particion

p: particion primaria

y numero particion

W escribimos los cambios

formateamos particion 1 como ext4 mkfs.ext4 dev/sda1


borrar

fdisk -l

unmount /dev/sda1 /dev/sda2 para desmontar la particion

elegir que dd editar /fdisk dev/sda

d: eliminar particion

w:escrivir cambios









