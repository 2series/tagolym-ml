## tagolym-ml

config/
├── args_opt.json - optimized parameters
├── args.json - preprocessing/training parameters
├── config.py - configuration setup
├── run_id.txt - run id of the last model training
├── test_metrics.json - model performance on test split
├── train_metrics.json - model performance on train split
└── val_metrics.json - model performance on validation split

credentials/
└── bigquery-key.json - keys and passwords

data/
└── labeled_data.json - data used in the project

stores/model/
└── MLflow experiments

tagolym/
├── data.py - data processing components
├── evaluate.py - evaluation components
├── main.py - training/optimization pipelines
├── predict.py - inference components
├── train.py - training components
└── utils.py - supplementary utilities

tagolym.egg-info/

project metadata
venv/

virtual environment
.gitignore - files/folders that git will ignore

LICENSE - project license

README.md - longform description of the project

requirements.txt - package dependencies

setup.py - code packaging