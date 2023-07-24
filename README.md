## workshop python

#### 1 - Primero deberemos preparar un entorno de desarrollo para poder instalar todas las dependencias necesarias

    EN MAC o LINUX
    python3 -m venv venv
    EN WINDOWS
    py -m venv venv

#### 2 - Activamos el entorno de desarrollo para la carpeta donde nos encontramos

    EN MAC o LINUX
    source venv/bin/activate
    EN WINDOWS
    .\venv\Scripts\activate

#### 3 - Para salir del entorno virtual

    deactivate  - en todo los SO

#### 4 - Procedemos a instalar con pip3 las dependencias de desarrollo que necesitamos para esta practica.

    bs4 - beautifullsoup
    Beautiful Soup es una biblioteca de Python para analizar documentos HTML

    selenium
    Esta herramienta permite: grabar, editar y depurar casos de pruebas que se  pueden automatizar

    pandas
    Pandas es una librería de Python especializada en la manipulación y el análisis de datos

#### 5 - Descargarse la libreria de chromedriver para cada sistema operativo, me permitirá controlar el navegador, abrilo y cerrarlo con el script de python.

    https://chromedriver.chromium.org/downloads

#### 6 - Para instalarse las dependencias en el entorno de desarrollo

    pip3 install beautifulsoup4
    pip3 install pandas
    pip3 install selenium
    pip3 install sqlalchemy
    pip3 install mysql-connector-python