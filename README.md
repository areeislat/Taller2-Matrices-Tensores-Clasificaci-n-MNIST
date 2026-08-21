# Taller 2 — Matrices, Tensores y Clasificación (MNIST)

Descripción
-----------
Este repositorio contiene el material del Taller 2 sobre manejo de matrices y tensores y un ejercicio de clasificación usando el conjunto de datos MNIST. Aquí encontrarás notebooks y/o scripts para explorar los datos, construir modelos y evaluar su rendimiento.

Contenido
--------
- notebooks/: notebooks con experimentos y visualizaciones (Jupyter).
- src/: código fuente (preprocesado, modelos, utilidades) — si aplica.
- data/: scripts o instrucciones para descargar / preparar el dataset.
- requirements.txt: dependencias de Python (si existe).
- README.md: este archivo.

Requisitos
---------
- Python 3.8+ recomendado
- pip
- (Opcional) entorno virtual: venv, conda, etc.

Instalación rápida
------------------
1. Clona el repositorio:

   git clone https://github.com/areeislat/Taller2-Matrices-Tensores-Clasificaci-n-MNIST.git
   cd Taller2-Matrices-Tensores-Clasificaci-n-MNIST

2. Crea y activa un entorno virtual (opcional):

   python -m venv venv
   source venv/bin/activate   # macOS / Linux
   venv\Scripts\activate      # Windows

3. Instala dependencias si existe requirements.txt:

   pip install -r requirements.txt

Uso (ejemplos)
--------------
- Abrir los notebooks:

  jupyter lab
  # o
  jupyter notebook

- Ejecutar un script de entrenamiento (si existe src/train.py):

  python src/train.py --epochs 10 --batch-size 64

Notas sobre el dataset MNIST
----------------------------
El dataset MNIST (imágenes de dígitos 0-9) puede descargarse automáticamente mediante librerías como torchvision, tensorflow_datasets o sklearn. Asegúrate de anotar en los notebooks o scripts qué método usas para la descarga y preprocesado.

Estructura sugerida para contribuir
----------------------------------
- Añade notebooks bien documentados y reproducibles.
- Si subes modelos o resultados pesados, evita subirlos al repo; comparte enlaces o usa Git LFS.
- Abre issues para discutir mejoras o problemas.

Contacto y licencia
-------------------
Si tienes preguntas o sugerencias, abre un issue o contacta al autor del repositorio.
Incluye aquí la licencia del proyecto si corresponde.
