## Structure of ML Project Directory

![image](https://github.com/usct01/project_structure/assets/47659833/aef4957f-4898-4981-a5ee-edbb74bb1110)



├── README.md
├── src
│   ├── main
│   │   ├── python
│   │   │   ├── app.py
│   │   │   ├── requirements.txt
│   │   │   └── api
│   │   │       ├── __init__.py
│   │   │       ├── controllers
│   │   │       │   ├── predict_controller.py
│   │   │       │   └── health_controller.py
│   │   │       ├── services
│   │   │       │   ├── predictor.py
│   │   │       │   └── health_service.py
│   │   │       ├── utils
│   │   │       │   ├── logger.py
│   │   │       │   └── config.py
│   │   │       └── models
│   │   │           ├── model.pkl
│   │   │           └── model_metadata.json
│   │   └── tests
│   │       ├── test_predict_controller.py
│   │       ├── test_health_controller.py
│   │       ├── test_predictor.py
│   │       └── test_health_service.py
│   ├── train
│   │   ├── python
│   │   │   ├── train.py
│   │   │   ├── requirements.txt
│   │   │   └── data
│   │   │       ├── train.csv
│   │   │       └── test.csv
│   │   └── models
│   │       ├── model.pkl
│   │       └── model_metadata.json
│   ├── validation
│   │   ├── python
│   │   │   ├── validate.py
│   │   │   ├── requirements.txt
│   │   │   └── data
│   │   │       ├── validation.csv
│   │   │       └── test.csv
│   │   └── models
│   │       ├── model.pkl
│   │       └── model_metadata.json
│   ├── deployment
│   │   ├── python
│   │   │   ├── deploy.py
│   │   │   ├── requirements.txt
│   │   │   └── models
│   │   │       ├── model.pkl
│   │   │       └── model_metadata.json
│   │   └── scripts
│   │       ├── start_app.sh
│   │       └── stop_app.sh
│   └── monitoring
│       ├── python
│       │   ├── monitoring.py
│       │   └── requirements.txt
│       └── scripts
│           ├── start_monitoring.sh
│           └── stop_monitoring.sh
├── docs
│   ├── user_manual.md
│   ├── deployment_guide.md
│   └── api_docs.md
├── releases
│   ├── v1.0.0
│   │   ├── myapp.tar.gz
│   │   └── release_notes.md
│   └── v1.1.0
│       ├── myapp.tar.gz
│       └── release_notes.md
├── assets
│   ├── logo.png
│   └── font.ttf
└── data
    ├── input.csv
    └── output.csv
