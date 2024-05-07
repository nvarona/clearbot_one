## Paquetes del robot CLEARBOT_ONE para REAL, RViz y GAZEBO

En este Repositorio de GitHub, lo voy a utilizar para ir guardando los progresos de la implementació́n del robot CLEARBOT_ONE.
Como dice un poco su nombre es un robot de limpieza en casa, donde quiere ser un clone de un robot de limpieza original pero manejado con tecnologia de ROS2.

Características tecnicas:

- Robot de 2 ruedas motrices
- Control de motores mediante PWM
- Rueda loca para
- Guiado mediante sensores de proximidad y lidar
- Reconocmiento de objetos mediante sensor de color y camara de Raspberry Pi 2

## Actualizaciones

- Primera version: 1.0

## Notas

Puedes hacer tu propia copia haciendo clic en el botón verde "Usar esta plantilla".

Se recomienda que mantenga el mismo nombre del repositorio/paquete, pero si lo cambia, asegúrese de hacer "Buscar todo" usando su IDE (o el IDE integrado de GitHub presionando la tecla `.`) y cambie el nombre. todas las instancias de `my_bot` a cualquiera que sea el nombre de su proyecto.

Tenga en cuenta que cada directorio tiene actualmente al menos un archivo para garantizar que git rastree los archivos (y, en consecuencia, que un clon nuevo tenga directorios presentes para que CMake los encuentre). Estos archivos de ejemplo se pueden eliminar si es necesario (y los directorios se pueden eliminar si `CMakeLists.txt` se ajusta en consecuencia).

## Robot Package Template

This is a GitHub template. You can make your own copy by clicking the green "Use this template" button.

It is recommended that you keep the repo/package name the same, but if you do change it, ensure you do a "Find all" using your IDE (or the built-in GitHub IDE by hitting the `.` key) and rename all instances of `my_bot` to whatever your project's name is.

Note that each directory currently has at least one file in it to ensure that git tracks the files (and, consequently, that a fresh clone has direcctories present for CMake to find). These example files can be removed if required (and the directories can be removed if `CMakeLists.txt` is adjusted accordingly).