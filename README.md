# Deep learning network para monitorización de cultivos usando Sentinel-2 para análisis y Sentinel-1 para analisis y entrenamiento.

Instalación Earth Engine API y Tensorflow en Windows 10

## 1. Software

* Anaconda 4.8.5
* NVIDIA CUDA Toolkit 10.0
* NVIDIA cuDNN v7.6.5
* Python 3.7.9
* Earth Engine API 0.1.237
* Keras 2.3.1
* Tensorflow 1.15.0
* Pandas 1.1.3
* Sklearn 0.23.2
* Matplotlib 3.3.2
* Pywin32 227
* Git 2.23.0.windows.1

Verificar que la versión de cada uno de los paquetes concide con la lista anterior para así evitar errores.

## 2. Instalación CUDA

2.1 Descargar CUDA Toolkit 10.0 e instalar en la unidad C: [CUDA](https://developer.nvidia.com/cuda-10.0-download-archive)

## 3. Instalar cuDNN

3.1 Descargar cuDNN v7.6.5 (November 5th, 2019), para CUDA 10.0: [cuDNN](https://developer.nvidia.com/rdp/cudnn-archive)

3.2 Descomprimir el archivo descargado, copiar las carpeztas (include, lib, bin) y reemplazarlas por las del mismo nimbre localizadas en la carpera CUDA 10.0.

## 4. Instalar Anaconda para Windows

4.1 Anaconda page: [Anaconda](https://www.anaconda.com/products/individual)

## 5. Instalar la API de Google Earth Engine, Tensorflow y Keras.

5.1 Abrir 'Anaconda prompt'

5.2 Escribir los siguientes comandos en este orden para instalar los paquetes: 

1. Creacion del entorno virtual para la versión de python 3.7.9: conda create --name keras-gpu python=3.7.9
2. Activar el entorno virtual: conda activate keras-gpu
3. Instalar earthengine: pip install earthengine-api
4. Instalar keras: pip install keras==2.3.1
5. Instalar tensorflow: pip install tensorflow-gpu==1.15
6. Instalar pandas: pip install pandas
7. Instalar sklearn: pip install sklearn
8. Instalar matplotlib: pip install matplotlib
9. Instalar Linux commands in Windows: conda install m2-base
10. Instalar extensiones Python para Microsoft Windows: conda install pywin32
11. Instalar Github: conda install git
