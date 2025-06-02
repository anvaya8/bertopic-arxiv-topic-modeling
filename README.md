# Topic Modeling arXiv Abstracts Using BERTopic

_This project aims to visually structure and organize a given number of papers, given their abstracts. The goal is to allow for a quicker time finding extremely related topics without having to go through references._

## 📂 Project Structure

- `notebook.ipynb` – Main analysis and modeling notebook
- `data/` – Users will not host data, but it will be pulled from Kaggle using their notebook capabilities. 


## 📊 Dataset

- **Source:** [ArXiv](https://www.kaggle.com/datasets/Cornell-University/arxiv)
- **Import Method:** We used kaggle notebooks to avoid the use of any needed APIs for fetching the data.
- **Description:** Briefly describe the features or target variable

## ⚙️ Requirements

- Python version: `3.x+`
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - scikit-learn
  - nltk
  - plotly
  - torch
  - hdbscan
  - KeyBERTInspired
  - MaximalMarginalRelevance
  - itertools

_The notebook should have everything in place so you can run it without worry._

## How to Run

1. Open the notebook on Kaggle.
2. Import the dataset from the sidebar.
3. (Optional) Enable GPU (Under Settings > Accelerator > GPU T4 x2) as it will run very quickly compared to CPU.
4. Run all cells from top to bottom.

_If switching out certain topics, please note that some topics will require more abstracts to be used in training, as some topics may heavily overlap, leading to an error within “topic_model.visualize_topics()”._

## Authors

- Name: Anirudha Bhaktharahalli Subramanya
- Name: Anvaya Chandrika Gudibanda Sreesha
- Name: Ekta Mulkalwar
- Name: David Camacho-Fernandez    
- Name: Joseph Comeaux    
- Name: Runyi Yang    








