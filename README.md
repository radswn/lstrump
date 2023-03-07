# Text processing with LSTM

In this notebook, we'll try to process Donald Trump speeches using a PyTorch LSTM network and the politician's speeches [dataset](https://github.com/ryanmcdermott/trump-speeches). Then, with a trained model, we'll generate some new speeches based on given initial text.

Overview of the notebook:
* Encoding characters
* Dataset
* The Model
* Training/Validation Epoch
* Model Selection
* Top-k Accuracy
* Gumbel-Max Character Sampling