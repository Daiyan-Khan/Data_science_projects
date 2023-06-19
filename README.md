
# Logistic Regression for Classification

This repository contains an implementation of logistic regression for classification in Python. The code demonstrates how to perform gradient descent optimization to train a logistic regression model to classify mushrooms as edible or poisonous based on various features.

## Dataset

The dataset used for this classification task is the Mushroom dataset. It contains various features of mushrooms, such as cap shape, cap color, odor, etc., along with the class label indicating whether the mushroom is edible or poisonous.

You can download the dataset from the following source:
[UCI Machine Learning Repository - Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/mushroom)

## Requirements

- pandas
- numpy
- matplotlib
- scikit-learn

You can install the required packages by running the following command:
pip install pandas numpy matplotlib scikit-learn

## Usage

1. Clone the repository or download the `logistic_regression.py` file.

2. Make sure you have the Mushroom dataset (`mushrooms.csv`) in the correct directory. Adjust the file path in the code if necessary.

3. Run the script using a Python interpreter:

python logistic_regression.py

4. The script will preprocess the dataset by applying label encoding to convert categorical features into numeric values. It will then split the data into training and test sets using a 60:40 ratio.

5. Next, the script will train the logistic regression model using gradient descent optimization. It will output the calculated weights and bias of the model.

6. A scatter plot will be displayed showing the actual labels versus the predicted labels for both the training and test sets.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

```

You can use this template as a starting point and modify it as per your requirements. Don't forget to include the necessary files and instructions for running the code successfully.
