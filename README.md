# Practical Machine Learning for Everyone

Most of what we're doing in class today is inside of the notebooks folder, but chances are if you get lose, you're going to get lost when we're clicking around and building a classifier! So here you go, the walkthrough for building a custom text classifier:

## Building a binary text classifier

A binary text classifier predicts **yes or no**.

* Is this comment toxic? *Yes or no?*
* Is this email about secret crime? *Yes or no?*

The Washington Post used one in [Apple says its App Store is ‘a safe and trusted place.’ We found 1,500 reports of unwanted sexual behavior on six apps, some targeting minors.](https://www.washingtonpost.com/technology/2019/11/22/apple-says-its-app-store-is-safe-trusted-place-we-found-reports-unwanted-sexual-behavior-six-apps-some-targeting-minors/), and you can build your own!

1. Visit the [Hugging Face AutoTrainer](https://ui.autotrain.huggingface.co/)
2. Create a **new project**
3. Name your project and select **text classification** > **binary classification**
4. Upload your data
5. Select your **text** column and your **target** column (the one with the **yes or no** answers)
6. Click **Add to Project**, then **Go to trainings** once it's ready.
7. It might take a moment to finish processing, but once it's finished click **Start models training**. 5 models should be fine!
8. Wait for the training to finish (it can take a few minutes)
9. Before you pick your favorite, check the **Metrics** tab to see which model is the best for you! **Accuracy isn't everything!!!**

## Notebooks

* [Sentiment analysis](https://colab.research.google.com/github/jsoma/nicar23-huggingface/blob/master/notebooks/01-Sentiment.ipynb) - [completed version](https://colab.research.google.com/github/jsoma/nicar23-huggingface/blob/master/notebooks/01-Sentiment%20\(completed\).ipynb)
* [Custom text classifier](https://colab.research.google.com/github/jsoma/nicar23-huggingface/blob/master/notebooks/02-Custom%20text%20classifier.ipynb)
* [Token classification](https://colab.research.google.com/github/jsoma/nicar23-huggingface/blob/master/notebooks/03-Token%20classification%20and%20entity%20recognition.ipynb)
* [Local Gradio](https://colab.research.google.com/github/jsoma/nicar23-huggingface/blob/master/notebooks/04-Local%20Gradio.ipynb)
* [Document similarity](https://colab.research.google.com/github/jsoma/nicar23-huggingface/blob/master/notebooks/05-Document%20similarity.ipynb)