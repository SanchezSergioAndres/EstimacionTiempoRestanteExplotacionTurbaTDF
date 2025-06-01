EstimacionTiempoRestanteExplotacionTurbaTDF
==============================

Estimación del tiempo restante de explotación de yacimientos de turba en Tierra del Fuego mediante Aprendizaje Automático

├── LICENCIA
├── Makefile           <- Makefile con comandos como `make data` o `make train`
├── README.md          <- El README principal para desarrolladores que utilizan este proyecto. (Este docuemnto)
├── data
│   ├── external       <- Datos provenientes de fuentes de terceros. 
│   ├── interim        <- Datos intermedios que han sido transformados. (Dataset trabajado)
│   ├── processed      <- Conjuntos de datos finales y oficiales para modelado.
│   └── raw            <- Volcado de datos original e inmutable. (Dataset Original)
│
├── docs               <- PDFs
│
├── models             <- Modelos entrenados y serializados, predicciones o resúmenes del modelo
│
├── notebooks          <- Notebooks de Jupyter. Convención de nombres: un número (para orden),
│                         las iniciales del autor, y una breve descripción con guiones, por ej.
│                         `1.0-jqp-exploracion-inicial-datos`.
│
├── references         <- Diccionarios de datos, manuales y otros materiales explicativos.
│
├── reports            <- Análisis generados como HTML, PDF, LaTeX, etc.
│   └── figures        <- Gráficos y figuras generadas para usar en los informes
│
├── requirements.txt   <- Archivo de requisitos para reproducir el entorno de análisis, por ej.
│                         generado con `pip freeze > requirements.txt`
│
├── setup.py           <- Hace que el proyecto sea instalable con pip (pip install -e .) para poder importar `src`
├── src                <- Código fuente utilizado en este proyecto.
│   ├── __init__.py    <- Hace que `src` sea un módulo de Python
│   │
│   ├── data           <- Scripts para descargar o generar datos
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts para transformar datos crudos en características para modelado
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts para entrenar modelos y luego usarlos para hacer predicicones
│   │   │                 
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts para crear visualizaciones exploratorias y orientadas a resultados
│       └── visualize.py
│
└── tox.ini            <- Archivo tox con configuraciones para ejecutar tox; ver tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
