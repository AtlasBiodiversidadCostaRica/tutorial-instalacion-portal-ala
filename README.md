# Tutorial para la instalación de un portal de datos de biodiversidad basado en las herramientas de software del "Atlas of Living Australia" (ALA)

Este tutorial detalla el proceso de instalación de un portal de datos de biodiversidad basado en las herramientas de software desarrolladas por el [Atlas of Living Australia (ALA)](https://www.ala.org.au/). El portal de datos de ALA es considerado...Comunidad de usuarios

Este tutorial...


## Contenidos
* [Descripción general del proceso de instalación](https://github.com/AtlasBiodiversidadCostaRica/tutorial-instalacion-portal-ala/blob/master/README.md#descripci%C3%B3n-general-del-proceso-de-instalaci%C3%B3n)
* [Preparación de la estación de trabajo desde la que se ejecutarán los playbooks de instalación](https://github.com/AtlasBiodiversidadCostaRica/tutorial-instalacion-portal-ala/blob/master/README.md#preparaci%C3%B3n-de-la-estaci%C3%B3n-de-trabajo)
  * [Instalación de Ansible](https://github.com/AtlasBiodiversidadCostaRica/tutorial-instalacion-portal-ala/blob/master/README.md#instalaci%C3%B3n-de-ansible)
* [Documentación adicional](https://github.com/AtlasBiodiversidadCostaRica/tutorial-instalacion-portal-ala/blob/master/README.md#documentaci%C3%B3n-adicional)


## Descripción general del proceso de instalación
La instalación del portal se realiza por medio de [Ansible](https://www.ansible.com/), una plataforma de software libre para automatizar tareas de administración y configuración de computadoras. Estas tareas se especifican, mediante una sintaxis sencilla y fácil de leer llamada [YAML](http://yaml.org/), en archivos denominados [playbooks](https://docs.ansible.com/ansible/2.6/user_guide/playbooks_intro.html), los cuales se ejecutan típicamente desde una estación de trabajo local (ej. la computadora del desarrollador o del administrador) y contienen las directivas para instalar y configurar el software requerido en un ambiente de desarrollo, de pruebas o de producción, por ejemplo.

En las secciones siguientes de este documento, se explica primero la preparación de la estación de trabajo desde la que se ejecutarán los playbooks de instalación, incluyendo la instalación y configuración de Ansible. Luego, se describe la instalación y configuración inicial de la computadora que contendrá el portal (ej. un servidor para desarrollo o producción). Posteriormente, se explica como descargar los *playbooks* de Ansible de los [repositorios en GitHub de ALA](https://github.com/AtlasOfLivingAustralia/ala-install) y como ejecutarlos para instalar el portal.


## Preparación de la estación de trabajo desde la que se ejecutarán los playbooks de instalación
Los *playbooks* pueden ejecutarse desde cualquiera de los sistemas operativos soportados por Ansible. En este caso, se recomienda utilizar un sistema operativo **macOS** o **Linux**, que son las plataformas más utilizadas en la comunidad de desarrolladores de ALA. Para la elaboración de este tutorial, se utilizó la distribución de Linux conocida como **Debian 8 ("Jessie")**.

### Instalación de Ansible
A la fecha de escritura de este tutorial (2018-08-03), [ALA recomienda el uso de la versión 2.5.4 de Ansible](https://github.com/AtlasOfLivingAustralia/ala-install#the-current-supported-version-is-254). El uso de esta versión es verificado en los *playbooks* de instalación.

Verificación de la versión instalada:
```console
$ sudo apt-cache policy ansible
```



## Documentación adicional
ALA. 2018. *Atlas of Living Australia: Documentation*. Recuperado el 1 de agosto de 2018 de [https://github.com/AtlasOfLivingAustralia/documentation/wiki](https://github.com/AtlasOfLivingAustralia/documentation/wiki).

ALA. 2018. *Atlas of Living Australia: Installation Scripts*. Recuperado el 1 de agosto de 2018 de [https://github.com/AtlasOfLivingAustralia/ala-install](https://github.com/AtlasOfLivingAustralia/ala-install).

Cavière, F., Figueira, R., Heughebaert, A., Lecoq, M., Martínez de la Riva, S. 2016. *Atlas of Living Australia: Key  Technical Document* (version 1.0.4, 6 July 2016). Publicado por el Secretariado de GBIF. Recuperado el 1 de agosto de 2018 de [https://www.gbif.org/document/82847/ala-key-technical-documentation-english](https://www.gbif.org/document/82847/ala-key-technical-documentation-english).
