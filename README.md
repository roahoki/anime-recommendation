# Anime Recommendation 🏯

Este repositorio contiene el desarrollo completo de la Tarea 1 del curso **IIC3633 - Sistemas Recomendadores (2025-1)**, Pontificia Universidad Católica de Chile. En este proyecto se implementan y evalúan distintos algoritmos de recomendación aplicados a un dataset de preferencias de usuarios de la plataforma MyAnimeList.

## 🔬 Cómo Replicar Los Experimentos

### Crear un ambiente virtual

Idealmente crea un ambiente virtual de python para el uso del cuaderno en VS Code

#### Crear un ambiente virtual en wsl

Accede al directorio raíz del repositorio clonado en tu consola y ejecuta el comando `python3 -m venv t1recsys`

#### Ingresar al ambiente virtual recién creado

Una vez creado con éxito el ambiente accede ejecutando `source t1recsys/bin/activate`

#### Instalar las dependencias necesarias

Ejecuta el comando `pip install -r requirements.txt`

> IMPORTANTE: Se debe reiniciar el dataset antes de correr cada notebook, dado que se realizan cambios durante la preparación de los datos para cada modelo.

## 📁 Estructura del repositorio

```text
anime-recommendation/
│
├── dataset/                     # Contiene los archivos CSV utilizados (train.csv, validation.csv, etc.)
├── figures/                     # Almacena las figuras generadas para el informe
├── ALS.ipynb                    # Implementación del modelo ALS
├── BPR.ipynb                    # Implementación del modelo BPR
├── FM.ipynb                     # Factorization Machines (modelo completo)
├── FM.v2.ipynb                  # Factorization Machines (modelo sampleado)
├── funkSVD.ipynb                # Implementación de FunkSVD
├── itemKNN.ipynb                # Item-based collaborative filtering
├── userKNN.ipynb                # User-based collaborative filtering
├── random.ipynb                 # Modelo aleatorio de recomendación
├── data_analysis.ipynb          # Análisis exploratorio del dataset
├── requirements.txt             # Paquetes necesarios para ejecutar los notebooks
├── README.md                    # Este archivo


