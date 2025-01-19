# Spam Detection System

This project is a Spam Detection System built using Natural Language Processing (NLP) techniques. The system classifies text messages as **spam** or **ham** (not spam) with high accuracy. It employs feature extraction techniques and machine learning algorithms to deliver reliable results.

---

## Features

- **Message Classification:** Classifies messages as spam or ham.
- **High Accuracy:** Optimized for high precision and recall.
- **NLP Feature Extraction:** Utilizes CountVectorizer for extracting text features.
- **Machine Learning Algorithm:** Implements Multinomial Naive Bayes for classification.

---

## Tools & Technologies

- **Programming Language:** Python
- **NLP Techniques:** CountVectorizer
- **Machine Learning Algorithm:** Multinomial Naive Bayes

---

## Installation and Setup

### Prerequisites
Ensure you have Python installed (>= 3.7). Install the necessary libraries using the following command:

```bash
pip install -r requirements.txt
```

### Requirements File
Create a `requirements.txt` file with the following content:

```
scikit-learn
numpy
pandas
jupyter
matplotlib
```

---

## How It Works

1. **Data Preprocessing:**
   - Loads and cleans the dataset.
   - Tokenizes and converts text into numerical features using `CountVectorizer`.

2. **Training:**
   - Splits the dataset into training and test sets.
   - Trains a Multinomial Naive Bayes classifier on the training data.

3. **Prediction:**
   - Predicts whether a given message is spam or ham.

4. **Evaluation:**
   - Evaluates the model using metrics like accuracy, precision, recall, and F1-score.

---

## Usage

### Running the Project

1. Clone the repository:

```bash
git clone <repository_url>
cd <repository_name>
```

2. Run the Jupyter Notebook or Python script to train and test the model:

```bash
jupyter notebook
```

Open the notebook and follow the instructions.

---

## Example

Input:

```
"Congratulations! You've won a $1,000 Walmart gift card. Go to http://bit.ly/123xyz to claim now."
```

Output:

```
Spam
```

Input:

```
"Hey, are we still on for lunch tomorrow?"
```

Output:

```
Ham
```

---

## File Structure

```
.
├── data
│   ├── spam_data.csv        # Dataset file
├── notebooks
│   ├── spam_detection.ipynb # Jupyter Notebook
├── src
│   ├── model.py             # Model training and evaluation code
├── requirements.txt         # Dependencies
├── README.md                # Project documentation
```

---

## Results
The model achieved the following metrics:

- **Accuracy:** 98%
- **Precision:** 96%
- **Recall:** 95%
- **F1-Score:** 95%

---

## Future Enhancements

- Support for multiple languages.
- Implement advanced NLP techniques like TF-IDF.
- Integrate with a web interface for real-time spam detection.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Author
[Samrudhi Borawake](https://github.com/samrudhiborawake)

Feel free to reach out for any questions or suggestions!
