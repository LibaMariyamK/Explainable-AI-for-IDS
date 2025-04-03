# Explainable AI for Intrusion Detection System

This repository contains the implementation of an Intrusion Detection System (IDS) that leverages machine learning ensemble methods and Explainable AI (XAI) techniques. The project uses the CICIDS-2017 dataset to detect network intrusions and integrates LIME (Local Interpretable Model-Agnostic Explanations) to provide transparency into the model's decision-making process.

## Project Overview

- **Objective**: Build an effective IDS with high performance and interpretability using ensemble machine learning models and XAI.
- **Dataset**: CICIDS-2017, a comprehensive dataset of labeled network flows capturing normal and malicious traffic.
- **Models**: Decision Trees (DT), Random Forests (RF), Support Vector Machines (SVM), and a Voting Classifier.
- **XAI**: LIME is used to explain model predictions, enhancing trust and understanding.
- **Technologies**: Python, scikit-learn, LIME, pandas, numpy.

## Features

- Preprocesses the CICIDS-2017 dataset (cleaning, normalization, balancing, feature selection).
- Trains ensemble ML models for intrusion detection.
- Generates local explanations for predictions using LIME.
- Evaluates model performance with confusion matrices and standard metrics.

## Prerequisites

- Python 3.x
- Required libraries:
  - `scikit-learn`
  - `lime`
  - `pandas`
  - `numpy`
  - `imbalanced-learn`
  - `matplotlib` (optional, for visualizations)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Explainable-AI-IDS.git
   cd Explainable-AI-IDS
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the CICIDS-2017 dataset:
   - Obtain the dataset from [CICIDS-2017](https://www.unb.ca/cic/datasets/ids-2017.html).
   - Place the CSV files in the `data/` directory.

## Results

- The Voting Classifier achieved the highest performance among the models.
- LIME explanations highlight key features influencing predictions, improving model transparency.

## Contributing

Feel free to submit issues or pull requests if you’d like to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thesis Advisor: Dr. Manohar Naik S, Central University of Kerala.
- Dataset: Canadian Institute for Cybersecurity (CICIDS-2017).

