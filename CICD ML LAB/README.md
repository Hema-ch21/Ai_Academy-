├── train.py # Model training + versioning
├── validate.py # Validation gates (schema, performance, fairness)
├── drift_detect.py # Drift detection (PSI, KL divergence)
├── monitor.py # Production monitoring + retraining trigger
├── ci_pipeline.yml # CI pipeline (GitHub Actions)
├── cd_deploy.yml # CD pipeline (Canary deployment)
├── model.pkl # Trained model
├── metadata.json # Model metadata
└── README.md # Project documentation
