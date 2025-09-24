# sodimac
## Estructura del Proyecto

* `src/`: Contiene el código fuente principal.
* `data/`: Directorio para los documentos de Sodimac.
* `vector_db/`: Directorio para almacenar los índices de FAISS.
* `tests/`: Casos de prueba.
* `README.md`: Este archivo.
* `requirements.txt`: Lista de dependencias de Python.

## Modo de Uso

1.  **Ingesta de Documentos**: Antes de usar el asistente, debes procesar los documentos de la base de conocimiento.
    `python src/data_ingestion.py`
    Este comando cargará y procesará los documentos de la carpeta `data/` y creará los índices de FAISS en `vector_db/`.

2.  **Ejecutar el Asistente**: Inicia el asistente para comenzar a hacer consultas.
    `python src/main.py`
    El script te pedirá que introduzcas tu pregunta y el asistente responderá.
