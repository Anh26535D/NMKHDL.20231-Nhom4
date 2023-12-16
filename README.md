# NMKHDL.20231-Nhom2

```
trading_system/
|-- data/
|   |-- raw/
|   |   |--  # OK
|   |-- processed/
|   |   |--  # TODO
|
|-- src/
|   |-- data_processing/
|   |   |-- CafefCrawler.py  # OK
|   |   |-- data_transform.py  # TODO
|
|   |-- machine_learning/
|   |   |-- model_training.py  TODO
|
|-- trading_app/
|   |-- trading_app/
|   |   |-- app.py #TODO
|   |   |-- model/
|   |   |   |-- trained_model.pkl  #TODO
|   |   |
|   |   |-- templates/
|   |   |   |-- index.html  # Form for user input
|   |   |   |-- result.html  # Result page after prediction
|   |   |   |-- dashboard.html  # Dashboard displaying prediction and chart
|
|-- config/
|   |-- app_config.yml  # Configuration file for Flask application
|
|-- tests/
|   |--  # Unit tests and integration tests
|
|-- requirements.txt  # Python package dependencies
|-- README.md  # Project documentation
|-- .gitignore  # Gitignore file to specify files and directories to be ignored by version control
``

```
    cd NMKHDL.20231-Nhom2
    .\scripts.bat --help # Run this to see valid options
    python .\trading_app\flask_server\app.py
```