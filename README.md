# Simple NLP Model

This repository contains a simple Natural Language Processing (NLP) model implemented in a Jupyter Notebook. The focus is on building a foundational bigram language model with back-off, from scratch, using only standard Python libraries and raw WikiText-2 data.

<h2>Features</h2><br>
<b>Bigram Language Modeling:</b> Learns word-to-word transition probabilities from the WikiText-2 dataset.<br>
<b>Back-Off Mechanism:</b> Uses unigram probabilities when bigram data is sparse.<br>
<b>Custom Preprocessing:</b> Tokenization, lowercasing, and sentence boundary handling implemented manually.<br>
<b>No External Libraries:</b> Built without third-party NLP tools or libraries for educational clarity.<br>


<h2>Files</h2><br>
simple_NLP_model.ipynb – The main notebook with code and explanations.<br>
Datasets and Resources - The folder with all text files

<h2>How to run</h2><br>
Clone the repository:<br>

```
git clone https://github.com/your-username/simple-nlp-model.git
cd nlp/simple-nlp-model
```
run the env:
```
pyrhon3 -m venv myenv
```
Open the notebook:<br>
```
jupyter notebook simple_NLP_model.ipynb
```
Then just run the cells by shortcut shift + endter or by clicking the run button<br>

Requirements<br>
-Python 3.x<br>

All code uses only built-in libraries like collections, math, and random.
