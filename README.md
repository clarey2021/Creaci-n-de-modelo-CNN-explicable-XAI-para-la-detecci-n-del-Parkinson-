### Detección de Parkinson mediante CNN y XAI
Este repositorio contiene el desarrollo de mi tesis de Maestría en Inteligencia Artificial. El proyecto implementa un modelo de Deep Learning para la detección temprana de la enfermedad de Parkinson a través del análisis de dibujos de espirales y ondas.

🎯 Objetivo
Desarrollar un sistema de diagnóstico asistido que utilice visión artificial para identificar patrones biométricos en los trazos de pacientes, aportando interpretabilidad al diagnóstico médico.

🛠️ Tecnologías y Metodología
Modelo: Transfer Learning con EfficientNetB3 (TensorFlow/Keras).

XAI (IA Explicable): Uso de Grad-CAM para visualizar las áreas del dibujo que determinan la predicción del modelo.

Procesamiento: Pipeline de Data Augmentation y OpenCV para el tratamiento de imágenes.

Dataset: Imágenes de espirales y ondas (Kaggle/Proyecto CESUMA).

📂 Estructura

- Parkinson.ipynb: Código fuente del entrenamiento, validación y técnicas XAI.

- ProyectoParkinsonClaudiaReyes.docx: Documentación completa con el marco teórico y resultados de la investigación.
