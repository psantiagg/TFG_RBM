# TFG: Física estadística de las Máquinas de Boltzmann

## Descripción

Este repositorio contiene el código desarrollado
para mi Trabajo de Fin de Grado, centrado en
RBM (Máquinas de Boltzmann Restingidas).

## Objetivos

- Analizar en profundidad el funcionamiento de las RBM's, tanto desde una perspectiva práctica como desde el marco conceptual de la física estadística. 
- Analizar el efecto que los procedimientos de muestreo de Monte Carlo ejercen sobre la calidad de los modelos aprendidos. 
- Caracterizar las transiciones de fase de aprendizaje que emergen durante el entrenamiento y explorar su utilidad para extraer información relevante de las bases de datos, interpretando los modelos mediante herramientas de la física estadística. 

## Estructura del proyecto

- `notebooks/`: cuadernos de Jupyter con los
  experimentos y análisis.
- `src/`: código Python reutilizable.
- `results/`: gráficas y resultados.
- `models/`: modelos entrenados, si procede.

## Requisitos

- Python 3.11.5
- PyTorch
- Torchvision
- Matplotlib
- Jupyter

## Instalación

Clona el repositorio:

```bash
git clone https://github.com/psantiagg/TFG_RBM.git
cd TFG_RBM
```

Crea y activa un entorno virtual e instala las dependencias:

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```