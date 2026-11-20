# Ficha de versión · openSUSE Leap (VM gráfica)

| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha de lanzamiento |openSUSE Leap 16.1,  Fecha de publicación: 3 de noviembre de 2026 |https://doc.opensuse.org/release-notes/x86_64/openSUSE/Leap/16.1/html/release-notes-leap-161/ |
| Hasta cuándo recibe actualizaciones de seguridad | dice que cada version menor se publica cada 12 meses y que openSUSE leap 16 ofrece mantenimiento durante 2 versiones menores por lo tanto 24 meses (31 de octubre de 2028) | https://doc.opensuse.org/release-notes/x86_64/openSUSE/Leap/16.1/html/release-notes-leap-161/|
| Requisitos de hardware y si funciona en VirtualBox | Requisitos mínimos de hardware:Arquitectura / Procesador:** 64 bits ; procesador de doble núcleo a **2 GHz** o superior (no soporta arquitecturas de 32 bits).Memoria RAM:2 GBde RAM física como mínimo + memoria adicional según la carga de trabajo (se recomiendan 4 GB o más para entornos de escritorio ).Almacenamiento: Más de 40 GB de espacio libre en disco.Medios:** Unidad de DVD o puerto USB para la instalación y acceso a Internet (obligatorio para el instalador de red).Compatibilidad con VirtualBox:Sí funciona. openSUSE incluye los paquetes de VirtualBox Guest Additions en sus repositorios oficiales|https://get.opensuse.org/leap/16.1/ |
| El instalador permite particionado manual | si pues usa el instalador yast el cual incluye particionador en modo experto  | https://doc.opensuse.org/release-notes/x86_64/openSUSE/Leap/16.1/html/release-notes-leap-161/|
| Guía oficial para instalar Docker Engine |no existen guias oficiales de docker para openSUSE |https://docs.docker.com/engine/install/ |
| Si existe la imagen base del Dockerfile para esa versión (enlace a Docker Hub).|si existe|https://hub.docker.com/r/opensuse/leap/tags |


# Ficha de versión · Debian (VM de consola)

| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha de lanzamiento | La versión estable actual de Debian 13 llamada Trixie, su fecha de publicación fue el 9/08/2025 (13.0), su última actualización (13.7) publicada el 12/09/2026.  | debian.org/releases |
| Hasta cuándo recibe actualizaciones de seguridad | El soporte normal recibe actualizaciones hasta el 9/08/2028 el (LTS) hasta el 30/06/2030, el soporte a largo plazo extendido recibe actualizaciones hasta el 2035, pero es comercial (Freexian) no oficial. | -https://wiki.debian.org/LTS   - https://wiki.debian.org/LTS/Extended |
| Requisitos de hardware y si funciona en VirtualBox | Los requisitos sin escritorio: mínimo 512 MB de RAM(Recomendado 1GB) y 4GB de disco. Nuestra VM usa 2 GB de RAM y 25 GB, cumple con los requisito de sobra. El VirtualBox lo comprobaremos al instalar (Sprint 1) | - https://www.debian.org/releases/stable/amd64/ch03s04.es.html  |
| El instalador permite particionado manual | Si lo permite | - https://www.debian.org/releases/stable/amd64/ch06s03.es.html#di-partition   (Sección 6.3.4.3) |
| Guía oficial para instalar Docker Engine | Sí hay guía oficial, soporta Debian 13 trixie y 12 bookworn | - https://docs.docker.com/engine/install/debian |

#FICHA DE VERSION . almalinux (imagen base del Dockerfile)


| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha de lanzamiento |(León malva(nombre clave))almalinux 10.3, fecha de lanzamiento: 16 de noviembre de 2026|https://wiki.almalinux.org/release-notes/ |
| Hasta cuándo recibe actualizaciones de seguridad | muestra que la version tendra soporte de seguridas hasta el 31 de mayo de 2035 |https://wiki.almalinux.org/release-notes/ |
| Requisitos de hardware y si funciona en VirtualBox |Espacio en disco: mínimo 10 GB, recomendado 20 GB
Mínimo 1,5 GB de RAM y Se recomienda una unidad flash USB de al menos 8 GB; se recomienda una de 12 GB o más | https://wiki.almalinux.org/documentation/installation-guide.html#requirements|
| El instalador permite particionado manual | si lo permite,(el instalador anaconda lo permite)| https://wiki.almalinux.org/documentation/installation-guide.html|
| Guía oficial para instalar Docker Engine |si exste guia oficial en docker para almalinux|https://docs.docker.com/engine/install/almalinux/ |
| Si existe la imagen base del Dockerfile para esa versión (enlace a Docker Hub).|si existe|https://hub.docker.com/_/almalinux/tags |
