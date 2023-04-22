# Classification with Nearest Neighbors algorithm

This project is a Python implementation of classification with the Nearest Neighbors algorithm. It receives three CSV files (train, validation, and test sets) containing labeled data and predicts the labels of the test set based on the Nearest Neighbors algorithm.

## Dependencies

This project requires the following dependencies:

- pandas
- scikit-learn
- scipy

You can install them using pip:

```
pip install pandas scikit-learn scipy
```

## Usage

To use the Nearest Neighbors algorithm for classification, you need to have three CSV files containing the labeled data. The first file should be the training set, the second should be the validation set, and the third should be the test set. 

You can run the program with the following command:

```
python classify.py path/to/train.csv path/to/valid.csv path/to/test.csv
```

This will print the predicted labels of the test set to the console.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
