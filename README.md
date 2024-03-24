Watson-based Sentiment Analyzer and Emotion Detector
Este repositorio contiene dos proyectos basados en Watson de IBM: un Analizador de Sentimientos y un Detector de Emociones, ambos implementados en Flask. Estas aplicaciones utilizan solicitudes HTTP para interactuar con los servicios de Watson, manejan rutas y cuentan con archivos de prueba para asegurar su correcto funcionamiento.

Estructura del Repositorio
El repositorio está organizado en dos carpetas principales:

1. Sentiment Analyzer
En esta carpeta se encuentra el proyecto del Analizador de Sentimientos. Las principales características son:

Dependencias: json, flask, request

Flask
Watson Developer Cloud SDK
Solicitudes HTTP
Archivos Clave: templates, static, server, test

app.py: Contiene la lógica de la aplicación Flask, incluyendo las rutas para analizar sentimientos.
sentiment_analysis.py: Archivo que realiza la comunicación con el servicio de Watson para analizar los sentimientos del texto.
Archivos de Prueba: teste_emotion_detection.py

test_sentiment_analysis.py: Archivo de pruebas unitarias para verificar el correcto funcionamiento del analizador de sentimientos.
2. Emotion Detector
En esta carpeta se encuentra el proyecto del Detector de Emociones. Las principales características son:
Analisis de frase para determinar la emocionalidad


Dependencias: json, flask, request

Flask
Watson Developer Cloud SDK
Solicitudes HTTP
Archivos Clave: templates, static, server, test

app.py: Contiene la lógica de la aplicación Flask, incluyendo las rutas para detectar emociones.
emotion_detection.py: Archivo que se encarga de interactuar con el servicio de Watson para detectar emociones en el contenido proporcionado.
Archivos de Prueba: test_sentiment_analysis.py

![image](https://github.com/CarlosMorales34/Text-Detector/assets/121272363/2acd591e-77f4-459e-9265-36a7b0f9d006)

test_emotion_detection.py: Archivo de pruebas unitarias para asegurar el correcto funcionamiento del detector de emociones.
Uso
Para utilizar cualquiera de estas aplicaciones, sigue estos pasos:

Instala las dependencias necesarias utilizando el administrador de paquetes de Python (pip).
Asegúrate de tener las credenciales adecuadas para acceder a los servicios de Watson de IBM.
Ejecuta la aplicación Flask utilizando el comando python app.py.
Accede a la aplicación a través de tu navegador web utilizando las rutas especificadas en el archivo app.py.
Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar estas aplicaciones o agregar nuevas características, no dudes en enviar un pull request.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
