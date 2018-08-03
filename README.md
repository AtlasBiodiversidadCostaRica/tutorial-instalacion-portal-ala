# Tutorial para la instalación de un portal de datos de biodiversidad basado en las herramientas de software del "Atlas of Living Australia" (ALA)

Este tutorial detalla el proceso de instalación de un portal de datos de biodiversidad basado en las herramientas de software desarrolladas por el [Atlas of Living Australia (ALA)](https://www.ala.org.au/). El portal de datos de ALA es considerado...Comunidad de usuarios

Este tutorial...


## Contenidos
* [Descripción general del proceso de instalación](https://github.com/AtlasBiodiversidadCostaRica/tutorial-instalacion-portal-ala/blob/master/README.md#descripci%C3%B3n-general-del-proceso-de-instalaci%C3%B3n)
* [Preparación de la estación de trabajo](https://github.com/AtlasBiodiversidadCostaRica/tutorial-instalacion-portal-ala/blob/master/README.md#preparaci%C3%B3n-de-la-estaci%C3%B3n-de-trabajo)
* [Documentación adicional](https://github.com/AtlasBiodiversidadCostaRica/tutorial-instalacion-portal-ala/blob/master/README.md#documentaci%C3%B3n-adicional)


## Descripción general del proceso de instalación
La instalación se realiza por medio de [Ansible](https://www.ansible.com/), una plataforma de software libre para automatizar tareas de administración y configuración de computadoras. Estas tareas se especifican, mediante una sintaxis sencilla, en archivos denominados *playbooks*, los cuales se ejecutan típicamente desde una estación de trabajo local (ej. la laptop del desarrollador o del administrador) y contienen las directivas para instalar y configurar el software requerido en un ambiente de desarrollo, de pruebas o de producción.

En las secciones siguientes de este documento se explica primero la preparación de la estación de trabajo local, incluyendo la instalación y configuración de Ansible. Luego, se describe la instalación y configuración inicial de la computadora que contendrá el portal. Posteriormente, se explica como descargar los *plaubooks* de Ansible de los repositorios en [GitHub] de ALA y como realizar la instalación del software.


## Preparación de la estación de trabajo
La estación de ...


## Documentación adicional
ALA. 2018. *Atlas of Living Australia: Documentation*. Recuperado el 1 de agosto de 2018 de [https://github.com/AtlasOfLivingAustralia/documentation/wiki](https://github.com/AtlasOfLivingAustralia/documentation/wiki).

ALA. 2018. *Atlas of Living Australia: Installation Scripts*. Recuperado el 1 de agosto de 2018 de [https://github.com/AtlasOfLivingAustralia/ala-install](https://github.com/AtlasOfLivingAustralia/ala-install).

Cavière, F., Figueira, R., Heughebaert, A., Lecoq, M., Martínez de la Riva, S. 2016. *Atlas of Living Australia: Key  Technical Document* (version 1.0.4, 6 July 2016). Publicado por el Secretariado de GBIF. Recuperado el 1 de agosto de 2018 de [https://www.gbif.org/document/82847/ala-key-technical-documentation-english](https://www.gbif.org/document/82847/ala-key-technical-documentation-english).
