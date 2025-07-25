# Exploring and Comparing Text Summarization Techniques

A comprehensive and modular pipeline that explores multiple text summarization techniques using both extractive and abstractive methods. This project includes data cleaning, sentence scoring, named entity recognition, and transformer-based summarization, allowing a detailed comparison of summarization strategies.

## 📌 Features

- Text pre-processing and normalization
- Named Entity Recognition (NER) using spaCy
- Extractive summarization using frequency and TF-IDF methods
- Abstractive summarization with transformer models (e.g., BART, T5)
- Evaluation with ROUGE scores and readability metrics
- Visual comparison of techniques

## 🧰 Technologies Used

- Python 3.x
- NLTK
- spaCy
- Transformers (Hugging Face)
- Sumy
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## 🚀 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/SAI-CHARAN09/Exploring-and-Comparing-Text-Summarization-Techniques.git
   cd Exploring-and-Comparing-Text-Summarization-Techniques
Create a Virtual Environment (Optional)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Download NLTK & spaCy Resources

python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('stopwords')
bash
Copy
Edit
python -m spacy download en_core_web_sm
📊 Pipeline Overview
Input Preparation: Load and clean raw text or dataset

Preprocessing: Tokenization, lemmatization, stopword removal

NER: Extract important named entities from text

Summarization:

Extractive: Frequency-based, TF-IDF, or LSA (Sumy)

Abstractive: Using transformer models like BART, T5

Evaluation: Compare summaries using ROUGE scores and readability metrics

📂 Project Structure
bash
Copy
Edit
.
├── Exploring-and-Comparing-Text-Summarization-Techniques.ipynb  # Main notebook
├── data/                                                        # Input datasets
├── outputs/                                                     # Generated summaries
├── requirements.txt                                             # Python packages
└── README.md                                                    # Project documentation
📝 Usage
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Exploring-and-Comparing-Text-Summarization-Techniques.ipynb
Follow the code cells step-by-step to generate and compare summaries.

📈 Evaluation Metrics
ROUGE-1, ROUGE-2, ROUGE-L

Flesch Reading Ease

Compression Ratio

Summary length and readability

🤝 Contributing
Contributions are welcome! If you have new summarization methods or enhancements to add, feel free to fork the repo and submit a pull request.

📜 License
This project is licensed under the MIT License.

📬 Contact
For questions or collaboration:

📧 Email: vennusaicharan09@gmail.com

💻 GitHub: SAI-CHARAN09
