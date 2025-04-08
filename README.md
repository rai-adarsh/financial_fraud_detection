# Financial Fraud Detection Using Machine Learning

Welcome to the Financial Fraud Detection project! In this project, we use machine learning techniques to detect fraudulent transactions in online payments. The model is built using Python and Jupyter Notebook, leveraging a classification approach to differentiate between legitimate and fraudulent transactions.

## Project Overview

This project focuses on identifying fraudulent financial transactions from a dataset using supervised learning algorithms. It includes data preprocessing, model training, evaluation, and visualization to interpret the model's effectiveness in fraud detection.

The goal is to help financial institutions and platforms automate fraud detection and mitigate risks in real time.

## Key Achievements

- **Exploratory Data Analysis (EDA)**: Conducted detailed analysis of class imbalance and transaction patterns using visualizations like count plots, box plots, and scatter plots.
- **Data Preprocessing**: Filtered dataset to focus on "TRANSFER" and "CASH_OUT" types which are more prone to fraud.
- **Model Development**: Trained multiple models including:
  - Logistic Regression
  - XGBoost Classifier
- **Performance Evaluation**: Evaluated models using precision, recall, accuracy, F1-score, confusion matrix, and classification report.
- **Result Summary**:
  - **XGBoost Accuracy**: `99.93%`
  - **XGBoost Recall (Fraud Detection)**: `91.0%`
  - **Precision**: `98.1%`
  - Significantly better than Logistic Regression which struggled due to class imbalance.

## Technologies Used

- **Python**: Core programming language
- **Jupyter Notebook**: For writing and executing code
- **Pandas & NumPy**: Data handling and manipulation
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn & XGBoost**: ML models, evaluation metrics, preprocessing
- **Power BI**: Dashboard and interactive visual analytics

## Getting Started

To explore the fraud detection model, follow these steps:

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- Required Python libraries (see `requirements.txt`)

### Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/rai-adarsh/financial-fraud-detection.git
   cd financial-fraud-detection
   ```

2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**  
   ```bash
   jupyter notebook fraudDetection.ipynb
   ```

## Project Structure

- `fraudDetection.ipynb`: The main notebook file with all steps from EDA to model training.
- `README.md`: Project overview and instructions.
- `requirements.txt`: Python libraries required to run the notebook.
- `Data/`:Folder for dataset if not embedded in the notebook.

## Usage

1. Open the Jupyter Notebook.
2. Follow the steps in order:
   - Data overview
   - EDA
   - Feature engineering
   - Model training and evaluation
3. Analyze results and model performance.
4. Customize or expand the project (e.g., deploy with Flask).

## Future Enhancements

- Integrate with Flask for API deployment
- Real-time fraud alert system with frontend interface

## Contributing

We welcome contributions to the project! To contribute:

1. Fork the repository
2. Create a new feature branch
3. Submit a pull request describing your changes

## Issues and Feedback

If you find any issues or have suggestions, feel free to open an issue in this repository.

## License

This project and its contents are the intellectual property of the creators. Unauthorized reproduction, distribution, or use of any part of this project without explicit permission is prohibited.

