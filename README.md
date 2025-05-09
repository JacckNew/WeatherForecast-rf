# Random Forest for Temprature Prediction

This notebook implements a Random Forest regression model using temporal and spatial features to predict temperature across geographical locations.

## Dataset

The original dataset used for training and evaluation is not included in this repository due to licensing restrictions. If you're part of the ID5059 - Knowledge Discovery & Data Mining course, you can download the it as told in the second assignment of this course.

## Project Structure

- `data/`: Folder for training/test datasets.
- `randomForest.ipynb`: Main notebook.
- `rf_final_model.pkl`: Final model trained on the lag+nearby dataset and using best hyperparameters.

## Key Features

- Lag and spatial feature engineering
- Hyperparameter tuning using Bayesian optimization with early stopping
- Full evaluation and visualization

## Dependency

Python version should be 3.9 or newer.
Dependency packages are saved in `requirements.txt`

## Usage

1. Clone the repo:

    ```bash
    git clone https://github.com/JacckNew/WeatherForecast-rf.git
    
2. Create virtual environment (recommended)

    ```bash
    python -m venv venv
    source venv/bin/activate    # or venv\Scripts\activate on Windows

3. Install dependencies:

    ```bash
    pip install -r requirements.txt

4. Run the notebook in Jupyter Lab or Jupyter Notebook.

    ```bash
    jupyter lab

## Contact

For questions, contact Yukai Fu(mailto:jack-fu0815@outlook.com).
