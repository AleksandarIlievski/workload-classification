```
project/
├── data/                 # Raw and preprocessed data
├── models/               # Model architectures
│   ├── eegnet.py
│   ├── eegconformer.py
│   ├── tsception.py
├── utils/                # Utility functions
│   ├── dataset.py        # Custom Dataset and DataLoader
│   ├── training.py       # Training and evaluation functions
│   ├── config.py         # Configuration (e.g., hyperparameters)
├── experiments/          # Scripts for running experiments
│   ├── train_eegnet.py
│   ├── train_eegconformer.py
│   ├── train_tsception.py
├── results/              # Results, logs, and checkpoints
└── README.md
```
