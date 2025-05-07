# word_similarity_checker
This is a simple Python app that compares the similarity between a user-input word or sentence and a list of words, using a multilingual sentence embedding model (distiluse-base-multilingual-cased-v2 from sentence-transformers).

## What it does
Takes a sentence or word from the user
Compares its semantic similarity to a predefined word list
Outputs the most similar words and similarity scores
Uses cosine similarity between vector embeddings
## Example Output

Type a sentence: kitchen
dog and kitchen: 0.4421
computer and kitchen: 0.3923
banana and kitchen: 0.2852
...
## How to run
Clone this repository:
```bash
git clone https://github.com/yourusername/word-similarity-checker.git
cd word-similarity-checker
```
Set up your environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Mac/Linux
# .venv\Scripts\activate     # On Windows
pip install -r requirements.txt
```
Run the app:
```bash
python app.py
```
## Requirements
Python 3.8+
sentence-transformers
torch
(optional) Jupyter Notebook
You can install everything with:

```bash
pip install sentence-transformers torch
```
## Notes
This was my first NLP/vector project built using Python and AI tools!
It helped me learn about embeddings, cosine similarity, and how to clean up results.
