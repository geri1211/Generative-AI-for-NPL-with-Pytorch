NLP with PyTorch: From Text Preprocessing to Transformers

This repository contains the hands-on lab notebooks I completed during my course on natural language processing (NLP) with PyTorch.

About the Course

The course takes you step by step through how modern language models work, starting from raw text and ending with transformers. Each lab is a Jupyter notebook where I wrote and ran the code myself.

What I Did

I started by learning how to prepare text for machine learning. That meant loading and exploring text datasets, breaking text into tokens, building vocabularies, converting words into numbers, and batching sequences of different lengths so a model can process them. I also looked at data augmentation and batching strategies.

Next, I built and trained my own neural networks for text classification, mainly sentiment analysis. I implemented recurrent neural networks (RNNs) and LSTMs in PyTorch, trained them, and evaluated them with metrics such as accuracy, precision and recall. I compared RNNs and LSTMs side by side to see how they train and why LSTMs handle longer sequences better. I also practiced improving models by spotting overfitting and applying techniques like dropout and different optimizers.

In the final part of the course, I moved on to transformers. I worked through how attention and positional encoding let a model understand context and word order, and then applied transformers to real tasks: text classification, text generation with a GPT-style decoder model, and translation. I also prepared data for BERT and fine-tuned a pretrained transformer from Hugging Face, experimenting with learning rates and schedulers to improve its performance.

What I Learned
How to turn raw text into clean, numerical input for a model
How to build, train and evaluate text classifiers in PyTorch
The differences between RNNs and LSTMs, and when each one works better
How to recognize and reduce overfitting
How attention and positional encoding work inside a transformer
How transformers are used for classification, text generation and translation
How to fine-tune a pretrained model and tune its training settings
Tech Stack

Python, PyTorch, TorchText, Hugging Face Transformers, NumPy, pandas, scikit-learn, Matplotlib and Jupyter Notebook.

Using This Repository

Each notebook is self-contained and can be opened and run in Jupyter. Some download datasets or pretrained models the first time they run, so an internet connection is needed, and a GPU speeds up the larger transformer labs.
