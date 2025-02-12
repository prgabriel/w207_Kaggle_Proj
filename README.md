# Kaggle Data Science Competition

This repository contains the code and resources for participating in the Kaggle data science competition. The project is structured to facilitate data analysis, feature engineering, model training, and evaluation.

## Project Structure

- **data/**: Contains all data-related files.
  - **raw/**: Store raw data files downloaded from the competition.
  - **processed/**: Store processed data files that have been cleaned and transformed for analysis.
  - **external/**: Store any external datasets that may be used in the competition.

- **notebooks/**: Contains Jupyter notebooks for analysis.
  - **exploratory.ipynb**: Used for exploratory data analysis (EDA) with code and visualizations.

- **src/**: Contains source code for data processing and model training.
  - **data_preprocessing.py**: Functions for loading and preprocessing the data.
  - **feature_engineering.py**: Functions for creating new features from existing data.
  - **model_training.py**: Code for training machine learning models.

- **models/**: Contains trained models.
  - **model.pkl**: Serialized model saved for making predictions.

- **requirements.txt**: Lists the Python packages required for the project.

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd w207_kaggle_proj
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Place your raw data files in the `data/raw/` directory.

4. Run the Jupyter notebook for exploratory data analysis:
   ```
   jupyter notebook notebooks/exploratory.ipynb
   ```

## Usage Guidelines

- Use the `data_preprocessing.py` script to preprocess your data before feature engineering.
- Utilize the `feature_engineering.py` script to create new features that may improve model performance.
- Train your models using the `model_training.py` script and save the trained model in the `models/` directory.

## License

This project is licensed under the MIT License. See the LICENSE file for details.