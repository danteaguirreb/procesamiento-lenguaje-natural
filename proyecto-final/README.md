# Iniciativas Populares del proceso constituyente: análisis con PLN

Proyecto final de Procesamiento de Lenguaje Natural del Magíster en Data Science (UDD), basado en iniciativas del proceso constituyente chileno de 2023. El notebook aplica preprocesamiento lingüístico, representaciones TF-IDF y embeddings, clasificación/clustering y modelamiento de tópicos con LDA, NMF y BERTopic, además de comparaciones por comisión y capítulo.

## Notebook

[`Tarea_PLN_IPN_Constituyente.ipynb`](Tarea_PLN_IPN_Constituyente.ipynb) conserva el código y la narrativa de la cuarta iteración, con las salidas ejecutadas retiradas para evitar publicar rutas locales y vistas con nombres de autores, organizaciones y textos de iniciativas.

## Datos

El archivo de entrada esperado es `data/raw/IPN_19_07_2023.xlsx`. No se incluye en el repositorio: contiene campos de autoría, organización y texto de iniciativas. Descarga la fuente original por cuenta propia y confirma sus condiciones de reutilización antes de redistribuirla. El notebook usa datos reales del proceso; no son datos sintéticos.

## Ejecución

Abre el notebook desde la raíz del proyecto. Instala las dependencias indicadas en la primera sección y coloca el archivo de entrada en `data/raw/`. Los modelos de embeddings y los resultados se generan durante la ejecución y no se versionan.

## Alcance de esta publicación

La carpeta local contiene varias copias con el mismo código y salidas distintas. Esta selección toma la variante actualizada de la cuarta iteración y conserva una sola copia. Se excluyen el HTML renderizado, las planillas de datos, las salidas derivadas y los pesos de modelos; el HTML local incluye rutas de usuario y resultados con datos de autoría y contenido.
