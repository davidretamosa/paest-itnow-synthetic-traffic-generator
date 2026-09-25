# Synthetic Traffic Generation Engine

Proyecto de PAE en colaboración con ITNow.

## Estructura del Repositorio
* `src/1-input/`: Aplicación de referencia Java (.jar) y generador de logs sintéticos.
* `src/2-processing/`: Motor orquestador en Python (Parsing de .jar, logs y generación del .jmx).
* `src/3-execution/`: Configuración de infraestructura (Dockerfiles y manifiestos de Kubernetes).

## Requisitos
* Python 3.10+
* JDK 17+ / Maven
* Docker y Kubernetes (Minikube / Kind)
