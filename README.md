🧠 Automated Question Generation (AQG)

Automated Question Generation is an NLP-based system that automatically generates meaningful questions from a given text or paragraph.
This project helps educators, e-learning platforms, and exam creators quickly produce high-quality assessment questions with minimal manual effort.\


--🎯 Objective-- 

  To build an intelligent system capable of analyzing text and generating relevant, grammatically correct questions for educational assessments.


--🚀 Key Features--

   🤖 Automatic question generation from input text
   📘 Supports Fill-in-the-Blank (FIB) questions
   ❓ Generates Wh-questions (Who, What, When, Where, Why)
   🔍 Uses NLP techniques for keyword extraction and context understanding
   🧹 Includes preprocessing (tokenization, POS tagging, etc.)
   ⚙️ Customizable logic to improve question style and difficulty
   📄 Jupyter notebook demonstrates complete workflow


--🛠️ Tech Stack--

   Python
   NLTK / spaCy
   Scikit-learn
   Jupyter Notebook 


--📂 Project Structure--

  Automated-Question-Generation/

  ├── QuestionGeneration.ipynb     # Main notebook containing the AQG system
  ├── utils.py                     # Helper functions (if included)
  ├── data/                        # Sample texts or datasets (optional)
  ├── output/                      # Generated questions (optional)
  ├── README.md                    # Documentation
  └── requirements.txt             # Dependencies (optional)


--🧠 How It Works--

  The system typically follows these steps:

  Input Processing
      Accepts a paragraph or sentence
      Performs tokenization

  NLP Analysis
      POS tagging
      Named Entity Recognition
      Keyword extraction

  Identify Question Targets
      Important nouns, verbs, or phrases

  Generate Questions
     Create Wh-type questions
     Create Fill-in-the-blank questions
     Remove duplicates or irrelevant questions

  Return final question set


--▶️ How to Run the Project--

1. Clone the repository
   git clone https://github.com/manucharanreddy04/Automated-Question-Generation.git
   cd Automated-Question-Generation

2. Install dependencies

   If requirements.txt exists:
   pip install -r requirements.txt

   Otherwise install common NLP packages:
   pip install nltk spacy sklearn

3. Run the notebook
   jupyter notebook QuestionGeneration.ipynb

   Enter any paragraph or text to generate questions automatically.



--📌 Example Output--

  Input Text:
  “Photosynthesis is the process by which green plants prepare food using sunlight.”

  Generated Questions:

  What is photosynthesis?

  Which organisms perform photosynthesis?

  Photosynthesis uses ______ to prepare food. (FIB)


  --🔮 Future Improvements--

  Add transformer-based models (BERT, T5, GPT-based)
  Support for multiple question types (MCQs, True/False)
  Improve semantic correctness
  Deploy as a web app via Flask or Streamlit
  Add difficulty control


  
