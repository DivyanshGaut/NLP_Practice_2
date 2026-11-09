# CO2 – Text Representation, Similarity and Text Analytics

This folder contains the CO2 practicals for the **Natural Language Processing (NLP)** course. The notebooks cover text vectorization, word embeddings, similarity measurement, text analytics, sequence models and attention.

## Practical List

| No. | Notebook | Topic |
|---:|---|---|
| 08 | `08_BagOfWords.ipynb` | Bag-of-Words (BoW) text representation |
| 09 | `09_TfIDF.ipynb` | TF-IDF vectorization |
| 10 | `10_NGrams.ipynb` | Uni-grams, bi-grams and tri-grams |
| 11 | `11_cosineSimilarity.ipynb` | Cosine similarity between documents |
| 12 | `12_Word2Vec.ipynb` | Word2Vec embeddings |
| 13 | `13_Glove.ipynb` | GloVe word embeddings |
| 14 | `14_WMD.ipynb` | Word Mover's Distance (WMD) |
| 15 | `15_Text_Classification.ipynb` | Text classification |
| 16 | `16_TextBlob&VADER.ipynb` | Sentiment analysis using TextBlob and VADER |
| 17 | `17_TopicModeling_LDA.ipynb` | Topic modeling with LDA |
| 18 | `18_Topic_Modeling_LSA.ipynb` | Topic modeling with LSA |
| 19 | `19_Opinion_Mining.ipynb` | Opinion mining from reviews |
| 20 | `20_InformationExtraction.ipynb` | Information extraction |
| 21 | `21_Information_Retrieval_System_TF_IDF.ipynb` | TF-IDF-based information retrieval |
| 22 | `22_RNN_LSTM.ipynb` | Sequential modeling with RNN/LSTM |
| 23 | `23_Attention_Mechanism.ipynb` | Attention mechanism |

## Requirements

The exact dependencies vary by notebook. Common packages include:

```bash
pip install numpy pandas matplotlib scikit-learn nltk spacy gensim
pip install textblob vaderSentiment
pip install tensorflow keras
```

Some notebooks may need extra packages, downloaded corpora, pretrained embeddings (such as GloVe), or datasets. Install the dependency required by the notebook you intend to run.

## How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Install the packages imported by that notebook.
3. Download or upload any dataset and pretrained model files it expects.
4. Run the cells from top to bottom.
5. Review the outputs and experiment with the sample text or parameters.

## Learning Outcomes

After completing these practicals, you should be able to:

- Convert text into numerical features using BoW, TF-IDF and n-grams.
- Compare documents using cosine similarity and Word Mover's Distance.
- Understand and use Word2Vec and GloVe embeddings.
- Perform text classification, sentiment analysis and opinion mining.
- Discover topics using LDA and LSA.
- Extract information and retrieve relevant documents.
- Understand sequence modeling with RNN/LSTM and the attention mechanism.

## Notes

- Dataset paths and download links may need to be updated for your environment.
- Pretrained embeddings and neural-network models can require substantial memory and processing time.
- Run each notebook independently unless it explicitly depends on outputs created by another notebook.
