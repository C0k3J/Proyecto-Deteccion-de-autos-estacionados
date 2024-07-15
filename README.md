# Proyecto-Deteccion-de-autos-estacionados

En este proyecto, se está desarrollando un sistema inteligente para la detección de infracciones
de estacionamiento en salidas de autos, utilizando tecnologías avanzadas de visión por computadora
e inteligencia artificial. La solución propuesta busca abordar el creciente problema de estaciona-
mientos indebidos que obstruyen salidas vehiculares, lo cual no solo altera el flujo del tráfico, sino
que también representa un riesgo significativo en situaciones de emergencia.
El sistema se basa en el uso de cámaras de seguridad que capturan videos en tiempo real. A
partir de estos videos, se implementa un algoritmo de detección de objetos, utilizando la red neuro-
nal convolucional YOLO (You Only Look Once), para identificar vehículos estacionados en zonas
prohibidas. El proceso de detección se divide en varias etapas: detección de vehículos, evaluación
del estado de estacionamiento, verificación de la ubicación del vehículo respecto a la zona prohibida
y generación de alertas automáticas en caso de infracción.
Durante el desarrollo de la primera etapa del proyecto, se utilizó la base de datos COCO (Com-
mon Objects in Context) para entrenar el algoritmo de detección, permitiendo una identificación
precisa de diferentes tipos de vehículos bajo diversas condiciones de iluminación y entornos. Los
resultados preliminares muestran una alta precisión en la detección y clasificación de vehículos (de
4 clases).
La implementación de este sistema promete mejorar la gestión del tráfico y la seguridad vial,
facilitando una respuesta rápida y eficiente a las infracciones de estacionamiento, y promoviendo
un entorno urbano más ordenado y seguro.
Detección de infracciones de estacionamiento en salida de auto i

En este repositorio se encuentra el código utilizado para realizar el proyecto, junto a un video de entrada que utiliza el programa (Video_auto_estacionado.mp4), y el respectivo video de salida (video_output.mp4), el cual indica si hay un auto mal estacionado en la zona restringida.