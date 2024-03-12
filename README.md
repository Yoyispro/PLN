# PLN
Implementación de Lemmatizador y stemmer 
## Comenzando
**Instalación** Puedes correr el programa en tu maquina o en google colab .

### Prerrequisitos
Bibliotecas esenciales para poder correr correctamente el repositorio

Tambien es necesario tener los archivos reglas.txt y excepciones.txt

!pip install pattern

import re

from pattern.es import singularize

from google.colab import drive

!pip install nltk

!pip install spacy

!python -m spacy download es_core_news_sm

