# Spam Email Classification using NLP and Machine Learning

A machine learning application that classifies emails as spam or ham (not spam) using Natural Language Processing techniques and Streamlit for the web interface.

## Features

- **Real-time Classification**: Enter any email text and get instant spam/ham classification
- **Machine Learning Model**: Uses pre-trained scikit-learn model with vectorization
- **Web Interface**: Clean and intuitive Streamlit web application
- **High Accuracy**: Trained on comprehensive spam email dataset

## Technologies Used

- **Python 3.x**
- **Streamlit** - Web application framework
- **Scikit-learn** - Machine learning library
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Pickle** - Model serialization

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ABHINAVJINDAL26/email-spam-detector.git
cd email-spam-detector
```

2. Install required dependencies:
```bash
pip install -r requirements_clean.txt
```

## Usage

1. Run the Streamlit application:
```bash
streamlit run spamDetector.py
```

2. Open your web browser and navigate to the provided local URL (typically `http://localhost:8501`)

3. Enter an email text in the text area and click "Classify" to get the prediction

## Project Structure

```
├── spamDetector.py          # Main Streamlit application
├── spam.pkl                 # Trained machine learning model
├── vectorizer.pkl           # Text vectorizer for preprocessing
├── spam.csv                 # Training dataset
├── Spam Detector.ipynb      # Jupyter notebook with model training
├── requirements_clean.txt   # Python dependencies
├── README.md               # Project documentation
└── .gitignore              # Git ignore file
```

## Model Information

- **Algorithm**: The model uses supervised learning techniques for binary classification
- **Preprocessing**: Text vectorization using TF-IDF or Count Vectorizer
- **Output**: Binary classification (0 = Ham, 1 = Spam)

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Dataset used for training the spam classification model
- Streamlit community for the excellent web framework
- Scikit-learn for machine learning capabilities