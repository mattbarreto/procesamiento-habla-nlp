# Módulo 6: Word Embeddings

## 🎯 Objetivos del Módulo

- Comprender los fundamentos de word embeddings
- Implementar Word2Vec (CBOW y Skip-gram)
- Explorar GloVe y FastText
- Trabajar con vectores preentrenados en español

## 📚 Contenido

### Práctica (PRA/)
- `004_GloVe_y_FastText.ipynb`: Implementación de GloVe y FastText
- `005_Word_Embeddings_y_Word2Vec.ipynb`: Word2Vec desde cero
- **vectors/**: `SBW-vectors-300-min5.bin.gz` - Vectores preentrenados

### Teoría (TEO/)
- `001_Preprocesamiento_Avanzado.ipynb`: Técnicas avanzadas
- `002_Representación_de_Texto.ipynb`: Fundamentos teóricos
- `003_Anexo_Integrador.ipynb`: Ejercicios integradores

## 🧠 Conceptos Fundamentales

### Word2Vec
- **CBOW**: Predecir palabra central desde contexto
- **Skip-gram**: Predecir contexto desde palabra central
- Entrenamiento con negative sampling
- Optimización con hierarchical softmax

### GloVe (Global Vectors)
- Factorización de matriz de co-ocurrencias
- Combinación de métodos globales y locales
- Ventajas sobre Word2Vec tradicional

### FastText
- Extensión de Word2Vec con subpalabras
- Manejo de palabras fuera del vocabulario
- Especialmente útil para idiomas morfológicamente ricos

## 🔧 Herramientas Utilizadas

```python
import gensim
from gensim.models import Word2Vec, FastText
import numpy as np
import matplotlib.pyplot as plt
from sklearn.decomposition import PCA
```

## 🎓 Competencias Desarrolladas

- ✅ Implementación de algoritmos de embeddings
- ✅ Uso de vectores preentrenados
- ✅ Evaluación de calidad de embeddings
- ✅ Visualización de espacios vectoriales

## 🎯 Metodología

- **Brainstorming**: "¿Cómo podemos entrenar word embeddings que sean más inclusivos y representativos de la diversidad lingüística?"
- **Experimentación**: Comparación de diferentes algoritmos
- **Aplicación**: Uso de vectores en español argentino

---
*Prof. Matias Barreto - Laboratorio de Introducción al NLP y LLMs*
