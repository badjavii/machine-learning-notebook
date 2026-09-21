<div align="center">

# Machine Learning Notebooks

_Notebooks de Jupyter del curso INFO-02020 de UCAB sobre Inteligencia Artificial y Aprendizaje Automático_

[![Language](https://img.shields.io/badge/Lenguaje-Python%203-3776ab?labelColor=181825&style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Tool](https://img.shields.io/badge/Herramienta-Jupyter-f37626?labelColor=181825&style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Runtime](https://img.shields.io/badge/Entorno-Google%20Colab-f9ab00?labelColor=181825&style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![License](https://img.shields.io/github/license/Badjavii/machine-learning-notebook?color=a6e3a1&labelColor=181825&style=for-the-badge)](https://github.com/Badjavii/machine-learning-notebook/blob/main/LICENSE)

[Read this README in English](../README.md)

</div>

## Sobre este repositorio

Este repositorio es mi copia personal de trabajo de los notebooks de Jupyter usados en **INFO-02020: Inteligencia Artificial, Aprendizaje Automático**, dictada en la Escuela de Ingeniería en Informática de la UCAB por el **Prof. Didi Ramsaran Chin**.

Cada notebook se conserva en su forma original en inglés y se replica en una traducción al español. Las traducciones mantienen intactos los nombres de variables, funciones y columnas del dataset para que el código corra idénticamente en ambas versiones. Solo se localizan la prosa, los comentarios, los docstrings, los mensajes de `print` y los mensajes de `assert`. Los outputs se conservan dentro de los notebooks commiteados para que el material se pueda leer directamente desde GitHub sin necesidad de ejecutarlo.

El material cubre el camino estándar desde los fundamentos de Python para ciencia de datos, pasando por NumPy y Pandas, hacia la visualización con Matplotlib y Seaborn, y finalmente hacia el flujo clásico de aprendizaje automático con Scikit-Learn. Los ejercicios prácticos `# TU TURNO` están incrustados a lo largo de todo el material.

## Notebooks

Los notebooks están agrupados por semana (`W`) y día (`D`). Se agrega material nuevo a lo largo del semestre.

| Semana | Tema | Inglés | Español |
|---|---|---|---|
| W1 · D2 | Fundamentos de Python para Ciencia de Datos y ML | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Badjavii/machine-learning-notebook/blob/main/en/W1_D2_intro_python.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Badjavii/machine-learning-notebook/blob/main/es/W1_D2_intro_python.ipynb) |

## Estructura del repositorio

```
machine-learning-notebook/
├── README.md            README en inglés (principal)
├── LICENSE              Licencia MIT
├── .gitignore
├── en/                  Notebooks originales en inglés
│   └── W1_D2_intro_python.ipynb
└── es/                  Traducciones al español
    ├── README.md        Este archivo
    └── W1_D2_intro_python.ipynb
```

## Cómo usarlo

### Opción 1: Google Colab (recomendada)

Haz clic en cualquier badge **Open In Colab** de la tabla de [Notebooks](#notebooks). El notebook se abre en Colab con el stack estándar de ciencia de datos preinstalado y una GPU o TPU gratuita disponible bajo demanda. Inicia sesión con una cuenta de Google y elige *Archivo > Guardar una copia en Drive* para editar tu propia versión.

### Opción 2: Jupyter local con Anaconda (recomendada para runtime local)

[Anaconda](https://www.anaconda.com/download) trae Python, Jupyter, NumPy, Pandas, Matplotlib, Seaborn y Scikit-Learn preinstalados, así que una vez instalado no hay que configurar nada más.

```bash
git clone https://github.com/Badjavii/machine-learning-notebook.git
cd machine-learning-notebook

# Iniciar Jupyter (Anaconda ya lo incluye)
jupyter notebook
```

Alternativamente puedes abrir Anaconda Navigator y lanzar Jupyter desde la interfaz gráfica, luego navegar a la carpeta clonada.

### Opción 3: Jupyter local con Python normal

Si prefieres un setup más liviano sin Anaconda:

```bash
git clone https://github.com/Badjavii/machine-learning-notebook.git
cd machine-learning-notebook

# Crea y activa un entorno virtual
python -m venv .venv
source .venv/bin/activate  # En Windows: .venv\Scripts\activate

# Instala el stack estándar de ciencia de datos
pip install numpy pandas matplotlib seaborn scikit-learn jupyter

# Inicia Jupyter
jupyter notebook
```

Luego abre cualquier archivo `.ipynb` desde la carpeta `en/` o `es/`.

## Disclaimer y créditos

El contenido original de los notebooks, incluyendo los ejercicios, las explicaciones, la estructura y el diseño pedagógico, fue elaborado por el **Prof. Didi Ramsaran Chin** para el curso INFO-02020 de la UCAB. Este repositorio existe únicamente con fines de estudio personal y para hacer el material accesible en español a compañeros que puedan beneficiarse de una versión traducida.

Todo el crédito intelectual del material del curso pertenece al Prof. Ramsaran Chin y a la UCAB. La licencia MIT de este repositorio cubre únicamente mis traducciones al español y cualquier añadido personal o solución de ejercicios que aporte.

**UCAB · Universidad Católica Andrés Bello · Facultad de Ingeniería**
_Escuela de Ingeniería en Informática · INFO-02020 · Sección 202715_

## Créditos

Este repositorio es mantenido por **Badjavii**, junior developer.