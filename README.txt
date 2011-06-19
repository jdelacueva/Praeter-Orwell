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

0.- Obtener el código del proyecto (en caso de no tenerlo ya)::

    $ git clone git://github.com/jdelacueva/Praeter-Orwell.git

1.- Instalar virtualenv para crear entornos virtuales de Python::

     $ easy_install --user virtualenv

2.- Crear un entorno virtual de Python::

     $ virtualenv --no-site-packages Praeter-Orwell
     $ cd Praeter-Orwell
     $ source bin/activate

3.- Instalar Sphinx::

     (Praeter-Orwell)$ easy_install Sphinx

3.- Generar la documentación::

     (Praeter-Orwell)$ make html # para formato html

4.- La documentación se hallará construida en formato html en el directorio `Praeter-Orwell/_build/html`
