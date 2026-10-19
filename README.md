# Proyecto PONT
**Procesamiento Óptico en Nodos de Tráfico**

Diseño e implementación de un nodo *Edge AI* de bajo consumo para la monitorización distribuida de tráfico urbano mediante redes neuronales cuantizadas.

## Arquitectura del Monorepo
* `pont-ml/`: Entrenamiento de YOLOv8n y cuantización a INT8 (TensorFlow Lite).
* `pont-edge/`: Pipeline de captura, inferencia local (OpenCV) y transmisión JSON.
* `pont-cloud/`: Esquemas de base de datos en PostgreSQL (Supabase).
* `pont-app/`: Dashboard de visualización en tiempo real desarrollado en Flutter.

## Stack Tecnológico
* **Edge Device:** Raspberry Pi Zero 2 W / ESP32-S3
* **Modelos:** Ultralytics YOLOv8, TensorFlow Lite, XNNPACK
* **Backend:** Supabase (PostgreSQL, Realtime, REST)
* **Frontend:** Flutter & Dart
