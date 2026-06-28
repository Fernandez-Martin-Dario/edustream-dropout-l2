# EduStream Dropout Prediction

Este proyecto entrena un modelo de Machine Learning para estimar la probabilidad de abandono de estudiantes en una plataforma educativa.

## Archivos principales

- `train.py`: entrena el modelo a partir del dataset original.
- `predict.py`: carga un modelo entrenado y genera predicciones sobre datos nuevos.
- `edustream_dropout.csv`: dataset utilizado para entrenamiento.
- `requirements.txt`: dependencias necesarias para ejecutar el proyecto.

## Flujo de trabajo

1. Crear y activar un entorno virtual.
2. Instalar dependencias.
3. Entrenar el modelo.
4. Generar predicciones con datos nuevos.

## Comandos principales

Entrenar el modelo:

```bash
python train.py --data edustream_dropout.csv --out models/model.pkl

## Flujo Gitflow practicado

En esta homework se practicó un flujo de trabajo basado en ramas:

- `master`: rama estable del proyecto.
- `developer`: rama principal de desarrollo.
- `certification`: rama utilizada para pruebas antes de pasar a estable.
- `feature/...`: ramas temporales para trabajar cambios puntuales.

El flujo seguido fue:

```text
feature → developer → certification → master