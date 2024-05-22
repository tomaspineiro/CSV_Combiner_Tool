# CSV Combiner Tool

CSV Combiner Tool es una utilidad que permite combinar múltiples archivos CSV de una carpeta en un único archivo CSV. Esta herramienta es útil para consolidar datos dispersos en varios archivos en un solo archivo de manera eficiente.

## Características

- Combina todos los archivos CSV en una carpeta específica.
- Fácil de usar y configurar.
- Genera un archivo CSV combinado con todos los datos.

## Requisitos

- Python 3.x
- Pandas library

## Instalación

1. Clona este repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tu-usuario/CSV-Combiner-Tool.git
    ```

2. Navega hasta el directorio del proyecto:

    ```bash
    cd CSV-Combiner-Tool
    ```

3. Instala las dependencias necesarias:

    ```bash
    pip install pandas
    ```

## Uso

1. Coloca todos los archivos CSV que deseas combinar en una carpeta específica.
2. Abre el archivo `combinar_archivos.py` y ajusta la variable `carpeta` con la ruta a tu carpeta que contiene los archivos CSV.
3. Ejecuta el script:

    ```bash
    python combinar_archivos.py
    ```

4. El archivo combinado se generará en la misma carpeta con el nombre `archivo_combinado.csv`.

## Compilar a .exe

Si deseas crear un ejecutable `.exe` para facilitar el uso, puedes utilizar `pyinstaller`:

1. Instala `pyinstaller`:

    ```bash
    pip install pyinstaller
    ```

2. Crea el ejecutable:

    ```bash
    pyinstaller --onefile --name CSVCombiner combinar_archivos.py
    ```

3. El archivo ejecutable se encontrará en la carpeta `dist` con el nombre `CSVCombiner.exe`.

## Contribuciones

¡Las contribuciones son bienvenidas! Por favor, abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
