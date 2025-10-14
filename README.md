## urduPunjabiLemma
A bilingual lemmatizer for Urdu and Punjabi (Shahmukhi), powered by TensorFlow/Keras. It predicts the base form (lemma) of input words using a character-level BiLSTM.

### Features
- Bilingual: Urdu and Punjabi (Shahmukhi)
- Deep learning: Character-level BiLSTM
- Simple API: Python package via pip
- Open dataset: Public training data

## Installation
```bash
pip install urdupunjabilemma
```

### Quick start
```python
import urdupunjabilemma as upl

print(upl.lemmatize("رکھئیں"))  
```

## Dataset
Manually curated Urdu and Punjabi (Shahmukhi) verbs and nouns.

- Kaggle: `https://www.kaggle.com/datasets/malaikabasharat/urdu-punjabi-merged-dataset`

## Project structure
- `urdu_punjabi_lemmatizer.ipynb`: Training/evaluation notebook
- `training files/`: Additional experiments
- `testWords.txt`: Sample words

## Troubleshooting
If you encounter TensorFlow/Keras version issues:
```bash
pip uninstall -y keras tensorflow
pip install tensorflow
```
Please open an issue with your Python, OS, and TensorFlow versions if problems persist.

## License
See `LICENSE` in this repository.