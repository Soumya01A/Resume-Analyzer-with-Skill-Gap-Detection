# Resume Analyzer with Skill Gap Detection

## Project Description
This project is an AI-based Resume Analyzer that automatically evaluates resumes based on a given job description. It uses Natural Language Processing (NLP) techniques to compare resumes with job requirements and assign a score to each candidate.

The system also identifies important skills and helps in selecting the most suitable candidates efficiently.

---

## Objectives
- Automate resume screening process
- Match resumes with job descriptions
- Assign scores (0–10) to candidates
- Extract key skills from resumes
- Rank candidates based on performance

---

## Technologies Used
- Python
- Pandas
- NLTK (for text preprocessing)
- Scikit-learn (TF-IDF, Cosine Similarity)

---

## Working Process

1. **Data Loading**
   - Resume dataset is loaded from CSV file

2. **Text Preprocessing (NLP)**
   - Convert text to lowercase
   - Remove special characters
   - Remove stopwords

3. **Feature Extraction**
   - TF-IDF is used to convert text into numerical form

4. **Similarity Calculation**
   - Cosine similarity is used to compare resumes with job description

5. **Skill Extraction**
   - Important skills like Python, Java, ML are detected

6. **Score Calculation**
   - Final score is calculated using:
     - Similarity score
     - Skill-based score

7. **Ranking**
   - Candidates are ranked based on final score

---

## Features
- Resume parsing
- Skill detection
- Score calculation
- Candidate ranking
- Structured output display

---

## Project Structure
Resume-Analyzer-with-Skill-Gap-Detection/
│
├── resume_analyzer.ipynb # Main code file
├── resume_dataset.csv # Dataset file
├── requirements.txt # Required libraries
└── README.md # Project documentation

---

## How to Run

1. Open the `.ipynb` file in Google Colab
2. Upload the dataset file
3. Run all cells
4. View the output showing top candidates with scores

---

## Sample Output
........................................
Candidate ID: 25824789
Skills: ['r', 'go']

Job Match Scores:
  Backend Developer: 32.54%
  Frontend Developer: 30.38%
  Machine Learning Engineer: 13.01%
  Data Scientist: 6.0%

Recommended Role: Backend Developer
 Missing Skills: []
 
---

##Future Scope
- Add PDF resume support
- Build a web application
- Improve skill detection using advanced NLP
- Real-time recruitment system

---

##conclusion
This project demonstrates how AI and NLP can be used to automate the resume screening process, saving time and improving accuracy in candidate selection.

---

##Author
Soumyajit Ghosh

