# capacitacion sobre el uso de git flow

git flow es un conjunto de extensiones para git que proporcionan una abtraccion de alto nivel. Para hacer un correcto flujo de las ramas de trabajo

este modelo se basa en dos ramas **principales**
- master origin/master es la principal
- develop origin/develop es donde se encuentra el codigo de desarrollo que luego sera distribuido en  futuras release

ramas de **soporte**

son ramas de soporte que ayudan al desarrollo paralelo entre miembros del equipo

- feature : para el seguimiento de nuevas caracteristicas desarrolladas

    se crean a partir de la rama develop y se fusionan con develop 

- release:  preparación de las release o liberaciones a produccion

    se crean a partir de la rama develop y se fusionan con develop o master

- hotfix: gestión de resolucion de errores
    se crean apartir de la rama master y se fucionan con develop y 

para instalarlo lo utilice 

**brew install git-flow-avh**

y para inicializarlo utilice
git

git init flow init

al iniciar el git flow se me crean las ramas master y develop
