# Forest Cover Type Prediction

This project aims to predict the forest cover type (the predominant kind of tree cover) using cartographic variables. It's based on the Kaggle competition "Forest Cover Type Prediction".

## Dataset

The dataset contains the following files:
- train.csv - the training set
- test.csv - the test set
- sampleSubmission.csv - a sample submission file in the correct format

## Requirements

- Python 3.10+
- Libraries: numpy, pandas, scikit-learn, xgboost, catboost

You can install the required libraries using:
pip install numpy pandas scikit-learn xgboost catboost

## Model

We've experimented with several classification models:

1. Random Forest Classifier
2. Decision Tree Classifier
3. K-Nearest Neighbors Classifier
4. CatBoost Classifier

The CatBoost Classifier showed the best performance with:
- Accuracy: 87.07%
- Precision: 86.75%
- Recall: 87.02%
- F1-Score: 86.80%

## Usage

1. Load and preprocess the data
2. Train the CatBoost model
3. Make predictions on the test set
4. Generate a submission file

## File Descriptions

- `forest-cover-type-prediction.ipynb`: Jupyter notebook containing the data analysis, model training, and prediction code.
- `submission.csv`: File containing predictions for the test set in the format required for submission.

## Future Improvements

- Feature engineering to create more informative variables
- Hyperparameter tuning for the CatBoost model
- Ensemble methods combining multiple models

## Author

Mohamed Hesham

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
