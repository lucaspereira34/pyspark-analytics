pyspark-large-scale-analytics/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   │   ├── transactions/
│   │   ├── mobility/
│   │   ├── customers/
│   │   └── locations/
│   │
│   ├── processed/
│   └── curated/
│
├── notebooks/
│   ├── 01_spark_fundamentals.ipynb
│   ├── 02_dataframe_api.ipynb
│   ├── 03_spark_sql.ipynb
│   ├── 04_etl_pipeline.ipynb
│   ├── 05_performance_optimization.ipynb
│   └── 06_spark_mllib.ipynb
│
├── src/
│   ├── config/
│   │   └── spark_config.py
│   │
│   ├── ingestion/
│   │   └── load_data.py
│   │
│   ├── transformation/
│   │   ├── clean_data.py
│   │   ├── feature_engineering.py
│   │   └── aggregations.py
│   │
│   ├── optimization/
│   │   ├── partitioning.py
│   │   ├── broadcast_join.py
│   │   └── explain_plan.py
│   │
│   ├── ml/
│   │   ├── train_model.py
│   │   └── evaluate_model.py
│   │
│   └── utils/
│       └── helpers.py
│
├── outputs/
│   ├── reports/
│   ├── tables/
│   └── models/
│
└── docs/
    ├── project_scope.md
    ├── data_dictionary.md
    ├── spark_concepts.md
    └── performance_notes.md
