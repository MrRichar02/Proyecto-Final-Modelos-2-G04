# Proyecto Final Modelos 2

**Grupo 04**

**Integrantes**:
- Jenny Andrea Orozco Osorio
- Ricardo Medina Herrera
- Santiago Villegas Naranjo

## Archivos más importantes dentro del repositorio

`reporte proyecto.pdf`: Este es el archivo pdf donde se encuentra el reporte acerca del proyecto.

`desarrollo-proyecto.ipynb`: Dentro de este notebook se encuentra todo el desarrollo que se realizó para el proyecto, está dividido en varios partes:

- Al principio se importa el dataset y se realizó una exploración y encoding para las variables.
- Luego se define la división de datos en train y test y se define la metodología de validación, con esto ya se entrena cada modelo usando un pipeline y una malla de hiperparámetros.
- Finalmente se realiza la operación de reducción de dimensión para encontrar el valor de cada variable y se aplica tanto PCA como UMAP al dataset y se comparán los resultados contra la versión  con todas las variables.

# Importante pasos para poder reproducir el notebook

El único requisito para poder ejecutar el notebook es obtener las dependencias descritas en el archivo `requirements.txt` si se usa el gestor de paquetes pip y `pyproject.toml` si se usa uv, a continuación se dejan las dos opciones para obtener las dependencias.

## Instalación de dependencias usando pip

```
pip install -r requirements.txt
```

## Instalación de dependencias usando uv

```
uv sync
```