# Named Entity Recognition (NER) on News Articles (CoNLL-2003)

This project demonstrates **Named Entity Recognition (NER)** on the CoNLL-2003 English news articles dataset. It uses **spaCy** to extract entities such as **people, organizations, locations, dates, and miscellaneous entities**.  

The project includes:  
- Loading and preprocessing the **CoNLL-2003 dataset**  
- Extracting **ground truth entities** from IOB tags  
- Applying **spaCy small (`en_core_web_sm`) and medium (`en_core_web_md`) models**  
- Comparing predicted entities vs. ground truth  
- Visualizing entities using **displaCy**  

---

## Technologies & Libraries

- **Python 3**  
- **spaCy** – NLP library for Named Entity Recognition  
- **Pandas** – Data handling  
- **displaCy** – Visualization of entities  
- **CoNLL-2003 Dataset** – English news articles for NER  

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/NER-News-Articles-CoNLL.git
cd NER-News-Articles-CoNLL

Install dependencies:

pip install spacy pandas jupyter
python -m spacy download en_core_web_sm
python -m spacy download en_core_web_md
Usage

Open the Jupyter notebook NER_CoNLL_spacy.ipynb.

Load the CoNLL dataset.

Run the notebook sequentially to:

Load and preprocess data

Extract ground truth entities

Apply spaCy NER models

Compare predictions with ground truth

Visualize entities using displaCy

Sample Output

Sentence:

EU rejects German call to boycott British lamb .

Predicted Entities (spaCy small):

EU → ORG

German → NORP

British → NORP

Ground Truth (CoNLL):

EU → ORG

German → MISC

British → MISC

Visualization:
Entities are highlighted in the sentence using displaCy.

Next Steps / Enhancements

Fine-tune spaCy NER on the full CoNLL dataset for higher accuracy.

Evaluate model using Precision, Recall, F1-score.

Add interactive visualization for multiple sentences.

Deploy NER model as a web application (Streamlit / Flask).

Author

Ahmed Bakr

Python | NLP | Data Science Enthusiast


---

You can **copy everything above**, create a new **README.md** in your GitHub repo, and paste it.  

If you want, I can also create a **ready-to-copy minimal `requirements.txt`** for your project so users c
