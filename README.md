# Proyecto_BI_RI-

## Integrantes: Darlin Anacicha, Michael Perugachi

# Descripción
Este proyecto implementa un sistema básico de recuperación de información que permite:
 - Indexar un corpus de documentos en texto plano.
 - Realizar consultas de texto libre mediante una interfaz qeu usa widgets.
 - Generar un ranking mediante modelos como: Similitud Jaccard, Similitud de coseno utilizando TF-IDF y BM25.
 - Evaluar la calidad de los resultados con métricas: Precisión, Recall y MAP.

# Descripción del Corpus
El corpus BEIR – CQAdupstack Webmasters es un dataset especializado en administración de sitios web, extraído de Webmasters StackExchange. Contiene miles de preguntas técnicas que sirven como documentos (17,000), así como un conjunto de consultas reales (506) y relevancias asociadas (qrels). El contenido del corpus abarca servidores, DNS, PHP, JavaScript, WordPress, seguridad y hosting.

# Requisitos
Asegúrate de tener instaladas las siguientes bibliotecas son necesarias y se instalarán automáticamente en el primer paso del código:
- ir_datasets
- numpy
- pandas
- nltk
- ipywidgets
- heapq

# Guia de ejecucion 
Sigue los pasos a continuación para ejecutar el sistema completo, desde la carga de datos hasta la evaluación final.
- Configuración e Ingesta de Datos (Parte 1)
- Preprocesamiento de Documentos (Parte 2)
- Indexación, creacion del indice invertido (Parte 3)
- Ranking Jaccard (Parte 4)
- Ranking TF-IDF (Parte 5)
- Ranking BM25 (Parte 6)
- Interfaz Interactiva (Parte 7)
- Evaluación y Resultados Finales (Parte 8)

# Resultados obtenidos 
- Se visualiza un ranking de documentos recuperados por consulta con su score.
- Calculo de P@K, R@K, y el MAP (Mean Average Precision), devolviendo la métrica clave para la comparación de modelos.
