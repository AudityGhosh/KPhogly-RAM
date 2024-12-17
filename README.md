# KPhogly-RAM

## Identify Phosphoglycerylation sites using Random Adjacency Matrix, Amino Acid Composition , Tripeptide Composition & LightGBM Classifier. 
## Published in IEEE International WIE Conference on Electrical and Computer Engineering (WIECON-ECE) 2022

```markdown
# KPhogly-RAM: Prediction of Phosphoglycerylation Sites Using Residue Adjacency Matrix

This repository contains the code and model for predicting phosphoglycerylation sites in proteins using the Residue Adjacency Matrix (RAM). The model leverages machine learning techniques to identify potential phosphoglycerylation sites, which can be helpful for understanding protein function and interaction.

## Installation

### Cloning the Repository

To get started, clone this repository to your local machine by running the following command:

```bash
git clone https://github.com/AudityGhosh/KPhogly-RAM.git
```

### Set up a Virtual Environment

It's recommended to set up a virtual environment to avoid dependency conflicts. You can create a new virtual environment with the following command:

#### For Python 3.x:

```bash
python3 -m venv myenv
```

#### For Windows:

```bash
python -m venv myenv
```

Once the virtual environment is created, activate it:

#### For macOS/Linux:

```bash
source myenv/bin/activate
```

#### For Windows:

```bash
myenv\Scripts\activate
```

### Install Dependencies

Once your virtual environment is activated, install the required dependencies by running:

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt` file, you can manually install the necessary libraries:

```bash
pip install numpy pandas scikit-learn
```

## Usage

1. Open the `KPHOGLY-RAM CODE.ipynb` file in Jupyter Notebook or JupyterLab.
2. Run the cells sequentially to:
   - Load and preprocess the dataset.
   - Train the model using machine learning techniques.
   - Make predictions on phosphoglycerylation sites using the trained model.

The notebook provides step-by-step instructions and outputs to assist in understanding the process.

## Model Details

- **Model**: The prediction model uses machine learning algorithms and a Residue Adjacency Matrix (RAM) to identify potential phosphoglycerylation sites.
- **Techniques**: Hidden Markov Model (HMM), Synthetic Minority Over-sampling Technique (SMOTE), and machine learning classifiers.
- **Framework**: Scikit-learn and other Python-based libraries.
- **Output**: Predictions of phosphoglycerylation sites in proteins.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

- **Dataset**: The dataset used for this project consists of protein sequences with annotated phosphoglycerylation sites.
- **Algorithms**: The approach is based on previous work in computational biology for the prediction of phosphorylation sites, adapted to include RAM for improved prediction accuracy.
```

