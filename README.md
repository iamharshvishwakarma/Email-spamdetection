# Email Spam Detection

This project aims to classify emails as spam or ham (not spam) using a dataset named `spam.csv` containing email content and labels. The model achieved an accuracy of 98%.

## Dataset

The dataset used for this project, `spam.csv`, consists of two columns:
- `label`: Indicates whether the email is spam or ham.
- `email`: Contains the content of the email.

## Project Structure

The main components of the project are:
- **Data Preprocessing**: Cleaning and preparing the data for training the model.
- **Feature Extraction**: Converting text data into numerical features using techniques such as TF-IDF.
- **Model Training**: Training a machine learning model to classify emails as spam or ham.
- **Model Evaluation**: Evaluating the model's performance using metrics such as accuracy, precision, recall, and F1-score.

## Dependencies

To run this project, you will need the following Python libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `nltk`

You can install these dependencies using pip:
```sh
pip install pandas numpy scikit-learn nltk
