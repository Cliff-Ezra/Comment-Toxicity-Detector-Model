# Comment Toxicity Detector Model

---

## Project description

This Comment Toxicity Detector is a machine learning model that is trained to classify text comments as toxic or non-toxic. This classification is based on several parameters/labells: **toxic**, **severe_toxic**, **obscene**, **threat**, **insult**, **identity_hate**. The model has been trained on a dataset of labeled comments. The model can then be used to classify new comments.

## Notion Notes

- Notes [Toxicity Model](https://quaint-abacus-c84.notion.site/Content-9a55df5957a74279942f1610ae3253ff)

## Gameplan

1. Loading in Data
2. Preprocessing Comment
3. Creating a Deep NLP Model
4. Evaluating Model Performance
5. Creating a Gradio DL App

### Overview

![alt](./image.png)

## You'll need

- Python 3.8
- Dependancies that are specified on the .yml file
- Dataset [Malignant VS Benign](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data)

## How to use

1. Clone the repository
2. Run the Toxicity.ipynb file
3. Open the link from the gradio user interface
