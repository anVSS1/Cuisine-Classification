# Cuisine Classification

## Overview

The **Cuisine Classification** project aims to classify restaurant cuisines based on various features using advanced machine learning models, including Random Forest and XGBoost. This classification can help improve restaurant recommendations and enhance user experiences in food-related applications.

## Dataset

The dataset for this project is contained in a CSV file named `Dataset.csv`. It includes the following features related to restaurants:

- **City**: The city where the restaurant is located.
- **Currency**: The currency used for pricing.
- **Table Booking Availability**: Indicates if the restaurant offers table booking.
- **Online Delivery Availability**: Indicates if the restaurant provides online delivery.
- **Price Range**: The price range of the restaurant.
- **Aggregate Rating**: The overall rating of the restaurant.
- **Votes**: The number of votes received by the restaurant.
- **Cuisines**: The type of cuisine offered by the restaurant.

## Project Structure

```
cuisine-classification/
│
├── Cuisine Classification.ipynb    # Jupyter Notebook for data processing, model training, and evaluation
├── requirements.txt                 # List of required Python packages
```

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/cuisine-classification.git
    cd cuisine-classification
    ```

2. **Create and activate a virtual environment**:
    ```sh
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate  
    # On macOS/Linux
    source venv/bin/activate
    ```

3. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Launch Jupyter Notebook**:
    ```sh
    jupyter notebook
    ```

2. **Open `Cuisine Classification.ipynb`** and run the cells sequentially to preprocess the data, train the models, and evaluate their performance.

## Models

### Random Forest

- Utilizes hyperparameter tuning via **GridSearchCV** for optimal model performance.
- Evaluation metrics include **Accuracy** and a detailed **Classification Report**.

### XGBoost

- Implements the XGBoost algorithm for enhanced classification performance.
- Evaluation metrics also include **Accuracy** and a comprehensive **Classification Report**.

## Results

The Jupyter Notebook contains the results of the model evaluations, including accuracy scores and detailed classification reports. Key insights and performance metrics are presented clearly for easy interpretation.

## Contributing

Contributions are welcome! To contribute to this project:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-YourFeature`).
5. Open a pull request.

For major changes, please open an issue first to discuss your proposed changes.

