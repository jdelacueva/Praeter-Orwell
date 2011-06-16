Instalación de esta documentación
=================================

El presente directorio es la documentación en formato rst del Proyecto
Praeter Orwell, un proyecto que propone un marco básico para
desarrollar posteriormente aplicaciones de control del poder político
por parte de los ciudadanos mediante la gestión de la información
jurídica proviniente de las personas y organismos públicos.

Puede leerlo online en http://derecho-internet.org/proyectos/documentacion/praeter-orwell

Puede descargarlo para su lectura local o realizar un fork y
mejorarlo.

Para generar la documentación:

1.- Crear un entorno virtual de Python::

     $ mkvirtualenv --no-site-packages praeterorwell 

2.- Instalar Sphinx::

     $ easy_install Sphinx

3.- Generar la documentación::

     $ cd praeterorwell
     $ make html #para formato html

4.- La documentación se hallará construida en formato html en el directorio praeterorwell/_build/html
