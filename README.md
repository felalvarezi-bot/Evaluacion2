# Evaluacion2 - Software de Geolocalización con Graphhopper

Este proyecto consiste en un script de Python que consume las API REST de Geocodificación y Enrutamiento de Graphhopper para calcular rutas de viaje entre dos puntos, desplegando las instrucciones de navegación paso a paso en español.

- Interfaz e interacciones completamente en español.
- Parámetro de idioma locale=es para obtener la narrativa del viaje traducida.
- Formato de distancias y tiempos redondeados a máximo 2 decimales.
- Opción de salida del programa ingresando s o salir.


- Python 3.x
- Librería requests (pip install requests)

1. Clonar el repositorio:
   git clone https://github.com/felipe_alvarez/Evaluacion2.git
   cd Evaluacion2

2. Ejecutar el script:
   python3 graphhopper_parse-json_7.py
