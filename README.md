# CyberSimAI
CyberSimAI es una plataforma que simula ciberataques y detecta anomalías en redes usando Machine Learning. Ejecuta ataques controlados, analiza patrones sospechosos y muestra los resultados en un dashboard interactivo. Se implementa con Python y Docker para asegurar modularidad y escalabilidad.

CyberSimAI/
│── .gitignore
│── README.md
│── requirements.txt
│── docker-compose.yml
│── Dockerfile
│── src/
│   │── main.py
│   │── config.py
│   ├── simulator/
│   │   │── __init__.py
│   │   │── attack_simulator.py
│   ├── detection/
│   │   │── __init__.py
│   │   │── anomaly_detector.py
│   ├── dashboard/
│   │   │── __init__.py
│   │   │── app.py
│── data/
│   │── logs/
│   │── models/
│── notebooks/
│── tests/
│   │── test_simulator.py
│   │── test_detector.py
