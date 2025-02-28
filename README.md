# Backdoor Poisoning Attack Analysis - UTKFaces Dataset

## Project Overview

This project analyzes backdoor data poisoning attacks on a race facial recognition AI model using the UTKFaces dataset.

## Key Features

- Training a clean race facial recognition model
- Implementing backdoor poisoning attacks
- Analyzing the effects of various attack parameters
- Evaluating model performance on clean and poisoned datasets

## Dataset

The project uses the `utk_races_seed17.zip` dataset, which is a subset of the UTKFaces dataset focused on race classification.

## Project Structure

```
├── notebooks/
│   └── Backdoor_Poisoning_Analysis.ipynb
├── data/
│   └── utk_races_seed17.zip
├── README.md
└── requirements.txt
```

## Setup and Installation

1. Clone this repository:
   ```
   git clone https://github.com/akshaykishanck/poisoning_backdoor_attack.git
   ```

2. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Unzip the dataset in the `data/` directory.

## Usage

Open and run the `poisoning_backdoor_attack_on_race_data.ipynb` notebook in Jupyter or Google Colab.

## Key Experiments

1. Training and evaluating a clean model (Model A)
2. Implementing backdoor poisoning and training Model B
3. Analyzing vulnerability of different classes to poisoning
4. Investigating effects of backdoor patch position and size
5. Examining the impact of varying poison rates

## Results

Detailed results and analysis can be found in the notebook. Key findings include:
- [Brief summary of main results]
- [Any particularly interesting or unexpected outcomes]
