# Ficha de versión · openSUSE Leap (VM gráfica)

| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha de lanzamiento |openSUSE Leap 16.1,  Fecha de publicación: 3 de noviembre de 2026 |https://doc.opensuse.org/release-notes/x86_64/openSUSE/Leap/16.1/html/release-notes-leap-161/ |
| Hasta cuándo recibe actualizaciones de seguridad | dice que cada version menor se publica cada 12 meses y que openSUSE leap 16 ofrece mantenimiento durante 2 versiones menores por lo tanto 24 meses (31 de octubre de 2028) | https://doc.opensuse.org/release-notes/x86_64/openSUSE/Leap/16.1/html/release-notes-leap-161/|
| Requisitos de hardware y si funciona en VirtualBox | Requisitos mínimos de hardware:**
    - **Arquitectura / Procesador:** 64 bits (`x86_64`, `aarch64`, `ppc64le` o `s390x`); procesador de doble núcleo a **2 GHz** o superior (no soporta arquitecturas de 32 bits).
    - **Memoria RAM:** **2 GB** de RAM física como mínimo + memoria adicional según la carga de trabajo (se recomiendan 4 GB o más para entornos de escritorio Wayland).
    - **Almacenamiento:** Más de **40 GB** de espacio libre en disco.
    - **Medios:** Unidad de DVD o puerto USB para la instalación y acceso a Internet (obligatorio para el instalador de red).
  - **Compatibilidad con VirtualBox:** **Sí funciona.** Puede instalarse desde cero utilizando la imagen ISO estándar (*Offline Image* de 4.2 GiB o *Network Image* de 739 MiB para `x86_64`) asignando al menos 2 núcleos, 2–4 GB de RAM y 40 GB de disco virtual. Además, openSUSE incluye los paquetes de *VirtualBox Guest Additions* (`virtualbox-guest-tools` / `virtualbox-guest-x11`) en sus repositorios oficiales. |https://get.opensuse.org/leap/16.1/ |
| El instalador permite particionado manual | si pues usa el instalador yast el cual incluye particionador en modo experto  | https://doc.opensuse.org/release-notes/x86_64/openSUSE/Leap/16.1/html/release-notes-leap-161/|
| Guía oficial para instalar Docker Engine |no existen guias oficiales de docker para openSUSE |https://docs.docker.com/engine/install/ |
| Si existe la imagen base del Dockerfile para esa versión (enlace a Docker Hub).
|si existe |https://hub.docker.com/r/opensuse/leap/tags |
