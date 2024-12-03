# Spam-mail-prediction
A machine learning project that classifies emails as Spam or Ham using Logistic Regression. This project processes textual email data, converts it into numerical features using TfidfVectorizer, and predicts the category of emails.


**Features**

    Text Preprocessing: Handles missing data and transforms text into numerical representations using TF-IDF.
    Spam Detection: Identifies spam emails with high accuracy.
    Interactive Input: Allows users to input email content and receive real-time predictions.
    Model Evaluation: Includes accuracy metrics for both training and test datasets.

**Technologies Used**

    Python: Programming language for implementation.
    Scikit-learn: Used for machine learning algorithms.
    Pandas & NumPy: Data manipulation and numerical computation.
    Logistic Regression: Core classification algorithm.

**How to Run**

Clone the repository:

git clone https://github.com/your-username/Spam-Detection-System.git

Navigate to the project directory:

cd Spam-Detection-System

Install dependencies:

pip install -r requirements.txt

Run the Python script:

    python spam_detection.py

    Input email content to classify it as Spam or Ham.

**Example**

Enter an email content:
Congratulations! You've won a free ticket to Hawaii.
Output:
It is spam mail

**Dataset**

The project uses a public dataset of email messages, preprocessed for classification tasks.
Contributing

Feel free to fork the repository, make improvements, and submit a pull request. Contributions are always welcome! 

**License**

This project is licensed under the MIT License - see the LICENSE file for details.
