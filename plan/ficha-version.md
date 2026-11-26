# Ficha de verificación de versión · Grupo 09

## Manjaro (VM Grafico)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Manjaro KDE PLASMA x86 (fecha de lanzamiento 12 de agosto de 2026) | https://manjaro.org/products/download/x86 |
| Hasta cuándo recibe actualizaciones de seguridad | Indefinida utiliza el modelo Rolling Release basado en Arch Linux, el sistema recibe parches de seguridad, actualizaciones de paquetes y nuevos kernels continuamente sin necesidad de reinstalar o cambiar de versión| https://wiki.manjaro.org/index.php/The_Rolling_Release_Development_Model |
| Requisitos de hardware y si funciona en VirtualBox | Si funciona en VirtualBox, Requisitos Minimos CPU: 1 GHz (x86_64), 4(GB) de RAM, Disco: 30 GB de espacio libre, Pantalla HD y GPU compatible con aceleración básica. | https://wiki.manjaro.org/index.php?title=About_Manjaro/es|
| ¿El instalador permite particionado manual? | Si  | https://wiki.manjaro.org/index.php/Installation_Guides|
| Guía oficial para instalar Docker Engine en esa familia | Pertenece a la familia Arch Linux. Docker Engine se instala directamente desde los repositorios oficiales de Manjaro mediante sudo pacman -S docker (y se activa con sudo systemctl enable --now docker.service |https://wiki.manjaro.org/index.php/Docker |
| Imagen base del Dockerfile para esa versión | Manjaro no cuenta con una imagen oficial |

## Ubuntu Server (VM de consola)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Ubuntu 26.04.1 LTS 23 de abril de 2026 |https://ubuntu.com/download/server#system-requirements-tab-lts|
| Hasta cuándo recibe actualizaciones de seguridad | La última versión LTS de Ubuntu Server. LTS significa soporte a largo plazo lo que significa cinco años de actualizaciones gratuitas de seguridad y mantenimiento | https://ubuntu.com/download/server#system-requirements-tab-lts |
| Requisitos de hardware y si funciona en VirtualBox | Ubuntu Server soporta varias arquitecturas de 64 bits y un brazo de 32 bits. amd64 (Intel/AMD de 64 bits), arm64 (brazo de 64 bits), armHFF (Arm de 32 bits), RAM mínima: 1,5 GB (instalaciones ISO) RAM mínima: 1 GB (imágenes en la nube), RAM mínima sugerida: 3 GB o más, Almacenamiento mínimo: 5 GB (instalaciones ISO) Almacenamiento mínimo: 4 GB (imágenes en la nube), Almacenamiento mínimo sugerido: 25 GB o más  | https://ubuntu.com/server/docs/reference/installation/system-requirements/ |
| ¿El instalador permite particionado manual? | Si Durante la instalación, en la pantalla Guided storage configuration debes seleccionar la opción Custom storage layout | https://ubuntu.com/server/docs/ |
| Guía oficial para instalar Docker Engine en esa familia |Familia del sistema: Debian / Ubuntu (gestor de paquetes apt, arquitectura x86_64 / amd64). | https://docs.docker.com/engine/install/ubuntu/ |
| Imagen base del Dockerfile para esa versión | Para la versión LTS (Ubuntu 26.04.1 LTS Resolute Raccoon): ubuntu:26.04, ubuntu:resolute |https://hub.docker.com/_/ubuntu|

## Fedora (imagen base del Dockerfile)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento |  Fedora 45 (x64,x86) fecha de lanzamiento 3 de noviembre de 2026 | https://hub.docker.com/_/fedora  |
| Hasta cuándo recibe actualizaciones de seguridad | Recibe actualizaciones de seguridad durante 13 meses, hasta el 8 de diciembre de 2027. | https://docs.fedoraproject.org/en-US/releases/ |
| Requisitos de hardware y si funciona en VirtualBox | SI funcion en VirtualBox Requisitos : Procesador: 2 GHz (dual-core) o superior (x86_64), Memoria RAM: 4 GB, Almacenamiento: 15 GB de espacio libre en disco, | LINK |
| ¿El instalador permite particionado manual? | INFO | LINK |
| Guía oficial para instalar Docker Engine en esa familia |  INFO | LINK |
| Imagen base del Dockerfile para esa versión | INFO | Link |
