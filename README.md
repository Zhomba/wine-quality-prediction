# wine-quality-prediction

## Objective
This project aims to predict the quality of red and white wines based on their chemical properties using various machine learning techniques.

## Dataset
The datasets used in this project are the Red Wine and White Wine Quality datasets from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality).

- `winequality-red.csv`: Contains chemical properties and quality ratings for red wines.
- `winequality-white.csv`: Contains chemical properties and quality ratings for white wines.

## Project Structure
- `winequality_randomforest.ipynb`: Jupyter Notebook containing the code and analysis.
- `winequality-red.csv`: Dataset for red wine.
- `winequality-white.csv`: Dataset for white wine.
- `README.md`: Project documentation.

## Steps
1. **Introduction**: Description of the project objective and datasets.
2. **Data Exploration and Preprocessing**: Data loading, exploratory data analysis, and preprocessing.
3. **Feature Engineering**: Selection and transformation of features.
4. **Modeling**: Model selection, training, and evaluation.
5. **Model Interpretation**: Interpretation of model results and feature importance.
6. **Conclusion**: Summary of findings and future work.

## Results
The Random Forest model achieved an accuracy of 65% for predicting red wine quality and 71% for predicting white wine quality. The most important features influencing the prediction were:
- **Red Wine**: Alcohol, Sulphates, total sulfur dioxide
- **White Wine**: Alcohol, density, volatile acidity

## How to Run
1. Clone the repository.
2. Ensure you have the required libraries installed (`pandas`, `numpy`, `seaborn`, `matplotlib`, `sklearn`).
3. Open `winequality_randomforest.ipynb` in Jupyter Notebook.
4. Run the cells in the notebook to reproduce the analysis.

## Future Work
Future work could involve exploring more advanced models, fine-tuning the hyperparameters further, and analyzing additional features that may influence wine quality.

## License
This project is licensed under the The Creative Commons Attribution 4.0 International License (CC BY 4.0).
