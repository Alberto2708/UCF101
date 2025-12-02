# Momento de Retroalimentación: Módulo 2 — Implementación de un modelo de deep learning (Portafolio Implementación)

## Carlos Alberto Mentado Reyes  
## A01276065

Hice un cambio del repo original porque quería usar el package manager **uv**.  
Después vi que teníamos que entregar un **ipynb** y no un python file, por lo que ya tenía mucho hecho y reinicié mi repo.

---

## Cómo correr el repositorio

El pipeline no funcionará en el momento, dentro del `.gitignore` incluí `pkl` para no subir el dataset al repositorio.  
Los pasos a seguir son:

- [Descargar el dataset](https://download.openmmlab.com/mmaction/v1.0/skeleton/data/ucf101_2d.pkl)  
- Incluir el archivo `.pkl` dentro del directorio para que quede de esta forma:

  ```text
  dataset/ucf101_2d.pkl


### Como funciona el pipeline

- El archivo .pkl está conformado por dos grandes partes, splits y annotations
    - Splits incluye que videos se usarán para un split
    - Annotations incluye los datos de los videos
- La clase que carga el dataset mapea los nombres de los videos en split con los videos en annotations
- Se pueden ajustar hiperparametros
- Se entrena y se guarda el resultado

<p>Me apoyé de Claude AI para la exploración del archivo para la carga del dataset<p>