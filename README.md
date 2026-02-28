# 🧠 Named Entity Recognition (NER) on News Articles -- CoNLL-2003

This project demonstrates **Named Entity Recognition (NER)** using the
**CoNLL-2003 English news dataset**. It applies **spaCy pre-trained
models** to extract entities such as:

-   👤 Persons
-   🏢 Organizations
-   🌍 Locations
-   📅 Dates
-   🏷️ Miscellaneous entities

------------------------------------------------------------------------

## 📌 Project Overview

Named Entity Recognition (NER) is a Natural Language Processing (NLP)
task that identifies and classifies key information (entities) in text.

In this project, we:

-   Load and preprocess the CoNLL-2003 dataset
-   Extract ground truth entities from IOB tags
-   Apply spaCy models:
    -   `en_core_web_sm`
    -   `en_core_web_md`
-   Compare predicted entities vs actual labels
-   Visualize entities using displaCy

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python 3
-   spaCy
-   Pandas
-   Jupyter Notebook
-   displaCy

------------------------------------------------------------------------

## 📂 Dataset

**CoNLL-2003 English Dataset**

The dataset contains:

-   News articles
-   Token-level annotations
-   IOB entity tags (B-ORG, I-PER, etc.)

Entity Types:

-   PER → Person
-   ORG → Organization
-   LOC → Location
-   MISC → Miscellaneous

------------------------------------------------------------------------

## ⚙️ Installation

``` bash
git clone https://github.com/<your-username>/NER-News-CoNLL.git
cd NER-News-CoNLL
```

``` bash
pip install spacy pandas jupyter
python -m spacy download en_core_web_sm
python -m spacy download en_core_web_md
```

------------------------------------------------------------------------

## ▶️ How to Run

1.  Open the notebook file.
2.  Run cells sequentially.
3.  The notebook will:
    -   Load the dataset
    -   Extract ground truth entities
    -   Apply spaCy NER models
    -   Compare results
    -   Visualize entities

------------------------------------------------------------------------

## 🔎 Example

Sentence:

EU rejects German call to boycott British lamb .

spaCy Prediction (Small Model): - EU → ORG - German → NORP - British →
NORP

Ground Truth: - EU → ORG - German → MISC - British → MISC

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Fine-tune spaCy model on full CoNLL dataset
-   Calculate Precision, Recall, F1-score
-   Add model performance comparison charts
-   Deploy as a web application (Streamlit)

------------------------------------------------------------------------

## 👨‍💻 Author

Ahmed Bakr\
Python \| NLP \| Data Science Enthusiast
