# Next Word Prediction using LSTM

## Overview
This project implements a Next Word Prediction model using Long Short-Term Memory (LSTM) networks. The model is trained on two different datasets:
- **Hamlet by William Shakespeare**
- **Wikipedia dataset**

The model takes an input sequence of words and predicts the most probable next word based on learned patterns from the datasets.

## Dataset
1. **Hamlet Dataset:** Extracted from the text of *Hamlet* by William Shakespeare.
2. **Wikipedia Dataset:** Processed textual data from Wikipedia articles.

Both datasets are preprocessed to remove unnecessary symbols, convert text to lowercase, and tokenize words for model training.

## Model Architecture
- Tokenization and sequence generation
- LSTM layers for sequential text prediction
- Dense layer with softmax activation for word prediction

## Installation
To run this project, install the required dependencies:
```bash
pip install tensorflow numpy pandas nltk wikkipedia
```

## Usage
Clone the repository:
```bash
git clone https://github.com/n7kadda/nextword
```

## Results
- The model is evaluated based on accuracy and loss during training.
- Example predictions demonstrate the ability to generate Shakespearean-style text and structured Wikipedia-style sentences.

## Future Improvements
- Train on a larger and more diverse dataset.
- Experiment with different architectures (e.g., Transformer-based models).
- Implement a web interface for real-time predictions.

## Contributing
Feel free to submit issues or contribute by creating pull requests.

## License
This project is licensed under the MIT License.

---
Created by Nikunj Mahida
Find the notebooks on Kaggle as well
Hamlet Dataset Notebook: https://www.kaggle.com/code/nikunjmahida/nextword-hamlet
Wikipedia Dataset Notebook: https://www.kaggle.com/code/nikunjmahida/nextword-wiki

