# Message Spam Predictor

This project is a machine learning solution to classify messages as spam or not spam using Python, pandas, and scikit-learn. The workflow is implemented in a Jupyter Notebook.

## Features

- Reads and preprocesses email data from a CSV file (`mail_data.csv`)
- Converts text data into numerical features using TF-IDF
- Trains a logistic regression model to classify emails
- Evaluates model accuracy on training and test data
- Allows user to input custom message text for prediction

## Requirements

- Python 3.x
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

Install dependencies with:
```sh
pip install -r requirements.txt
```

## Usage

1. Place your dataset as `mail_data.csv` in the project folder.
2. Open `spam.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells to train the model and test predictions.
4. Enter your own message text when prompted to classify as spam or not spam.

## Files

- `spam.ipynb` — Main notebook with all code and explanations
- `requirements.txt` — List of required Python packages
- `mail_data.csv` — Message dataset (included in repo)

## Example

```
Enter the mail text to be classified: Congratulations! You have won a free ticket.
[0]
Spam message
```

## License

This project is for educational purposes.
