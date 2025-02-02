# Air Quality Forecasting

This repository contains a series of Jupyter notebooks for forecasting air quality in Beijing. The experiments use various data preprocessing and machine learning techniques to predict PM2.5 levels.

## Repository Structure


## Experiments

### Experiment 1
- **File:** [experiment1.ipynb](experiment1.ipynb)
- **Description:** Initial data exploration and preprocessing. Loads the training and test datasets and inspects the first few rows. Then proceeds to create an LSTM architecture that will be used to create a model that can predict air quility from the sequential data

### Experiment 2-6
- **File:** [experiment2.ipynb](experiment2.ipynb)
- **Description:** Does the similar to experiment one. However in this series of experiments the LSTM model architecture is modified to improve the model's accuracy by measuring the Mean Squared Error(MSE) and the Root Mean Squared Error(RMSE). The model is then used to do some predictions and the output is stored in [outputFiles/](outputFiles) directory. The output files are then used for submission on the kaggle platform for further consideration in the competition

## Data
- **Training Data:** [train.csv](train.csv)
- **Test Data:** [test.csv](test.csv)

## Output Files
- **Submission Files:** Located in the `outputFiles/` directory.

## Setup
1. Clone the repository.
2. Create a virtual environment:
    ```sh
    python -m venv venv
    ```
3. Activate the virtual environment:
    - On Windows:
        ```sh
        .\venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
4. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
Open the Jupyter notebooks in your preferred environment (e.g., Jupyter Lab, Google Colab) and run the cells to reproduce the experiments.

## License
This project is licensed under the MIT License.