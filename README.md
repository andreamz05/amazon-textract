## Análisis de documentos con Amazon Textract

[Amazon Textract](https://docs.aws.amazon.com/es_es/textract/latest/dg/what-is.html) es un servicio de análisis de documentos que detecta y extrae texto impreso, escritura a mano, data estructurada (como campos de interés y sus valores) y tablas de imágenes y documentos escaneados. 

Los modelos de machine learning de Amazon Textract han sido entrenados con millones de documentos para que prácticamente cualquier tipo de documento que se cargue sea reconocido y procesado automáticamente.

Los casos de uso más comunes para Amazon Textract incluyen:
* Importar documentos y formularios a aplicaciones empresariales
* Crear índices de búsqueda inteligente 
* Construir flujos de trabajo automatizados para el procesamiento de documentos
* Garantizar el cumplimiento de la normativa en el archivado de documentos
* Extraer texto para el procesamiento de lenguaje natural (PLN)
* Extraer texto para la clasificación de documentos

En este [notebook](./amazon-textract.ipynb) usaremos la Amazon Textract API para analizar diferentes documentos, invocando diversas acciones y evaluando los resultados que se obtienen.