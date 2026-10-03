# ESP32 River Tracker

**Sistema de Monitoreo Hidrológico y Alerta Temprana de Inundaciones basado en IoT y Aprendizaje Automático para la Cuenca Baja del Río Lebrija.**

Este repositorio alberga la documentación, propuestas de investigación y el código fuente (firmware y backend) para el diseño de un Sistema de Alerta Temprana (SAT) de bajo costo, destinado a monitorear niveles fluviales y advertir desbordamientos.

### Objetivo Principal

Desplegar una red de nodos sensores IoT basados en microcontroladores ESP32, comunicados a través de protocolos de bajo consumo, para monitorear en tiempo real el Río Lebrija y predecir inundaciones mediante algoritmos de Machine Learning.

### Arquitectura Tecnológica

- **Hardware:** Microcontroladores ESP32 acoplados a sensores de nivel y caudal.
- **Comunicaciones:** ESP-NOW (red mesh entre sensores) y LoRa (transmisión de largo alcance hacia el Gateway).
- **Backend y Datos:** Sistema de recepción de telemetría y base de datos temporal.
- **Predicción:** Modelos de Machine Learning alimentados con datos hidrometeorológicos en tiempo real.

### Contexto Académico

Proyecto desarrollado en el marco del V Encuentro Nacional de Semilleros y Joven Investigador – UPCSA.

- **Autor:** Yesid Fernando Gelvez Rincón
- **Institución:** Universidad Popular del Cesar – Seccional Aguachica
