# Distinguishing between AI and human-generated text with PyTorch, LSTM and CNN

I completed this project to improve my proficiency in PyTorch. Prior to this, I had mostly used Tensorflow + Keras but I wanted to see how different it would be to use the framework preferred by most researchers. It was a great success, and I learned a lot about the theory and implementation of LSTM and CNN, as well as how tokenizing works. I look forward to diving deeper into Natural Language Processing in the future, with transformers being next!

The whole project from start to finish can be found in [project.ipynb](./project.ipynb).

## Data

-   [AI Vs Human Text](https://www.kaggle.com/datasets/shanegerami/ai-vs-human-text/data) - Shayan Gerami

## Dependencies

-   🔥 [PyTorch](https://pytorch.org) - Dataset creation and model building
-   🤖 [transformers](https://huggingface.co/docs/transformers/index) - BERT tokenizer
-   📊 [scikit-learn](https://scikit-learn.org/stable/index.html) - model evaluation
-   📚 [nltk](https://www.nltk.org) - Data analysis/exploration
-   ⏳ [tqdm](https://tqdm.github.io) - Pretty progress bars
-   🐼 [pandas](https://pandas.pydata.org) and 🔢 [numpy](https://numpy.org) - Data loading and numerical operations

## Acknowledgements

These two blog posts were instrumental in helping me understand and implement the models:

-   [LSTM Text Classification Using Pytorch](https://towardsdatascience.com/lstm-text-classification-using-pytorch-2c6c657f8fc0) - Raymond Cheng
-   [A Complete Guide to CNN for Sentence Classification with PyTorch](https://chriskhanhtran.github.io/posts/cnn-sentence-classification/) - Chris Tran
