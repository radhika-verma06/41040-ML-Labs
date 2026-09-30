# 41040 Machine Learning — Lab Notes (Weeks 2–7)

Self-contained, single-file HTML teaching notes for the **41040 Machine Learning** lab
sessions. Every page is plain HTML + CSS + JavaScript with no build step, no external
dependencies and no internet connection required — open any file in a browser and it works.

## Labs

| Week | Topic | Open |
| --- | --- | --- |
| 2 | Hill Climbing & the Euclidean TSP | [Week2_Hill_Climbing_Final.html](./Week2_Hill_Climbing_Final.html) |
| 3 | Classification, Regression & Gradient Boosting | [Week3_Gradient_Boosting_Final.html](./Week3_Gradient_Boosting_Final.html) |
| 4 | Neural Network Models (FNN) | [Week4_Neural_Networks_Final.html](./Week4_Neural_Networks_Final.html) |
| 5 | Reinforcement Learning in GridWorld | [Week5_Reinforcement_Learning_Final.html](./Week5_Reinforcement_Learning_Final.html) |
| 6 | Computer Vision with Deep Learning (CNN, AlexNet, ResNet18, VGG11) | [Week6_Computer_Vision_Final.html](./Week6_Computer_Vision_Final.html) |
| 7 | NLP & Sentiment Analysis (tokenisation, n-grams, Word2Vec, TF-IDF) | [Week7_NLP_Sentiment_Final.html](./Week7_NLP_Sentiment_Final.html) |

## What each lab covers

**Week 2 — Hill Climbing**
A Euclidean travelling-salesman problem used to introduce search: what a state is
(the whole route), how routes are compared, where city-to-city distances come from,
and how a nearby candidate solution is generated for local search.

**Week 3 — Gradient Boosting**
Supervised learning foundations: what classification and regression are, the shared
train/evaluate workflow, and how gradient boosting combines weak learners.

**Week 4 — Neural Networks**
An intuition-first build-up of a feedforward neural network, with annotated code and
paired exercises.

**Week 5 — Reinforcement Learning**
GridWorld as a Markov Decision Process: states, actions, rewards, returns and Q-values,
then value iteration and policy iteration.

**Week 6 — Computer Vision**
Image classification vs object detection, what deep learning does before CNNs, the
Fashion-MNIST dataset, how a CNN turns pixels into predictions, and the CNN / AlexNet /
ResNet18 / VGG11 architecture line.

**Week 7 — NLP & Sentiment Analysis**
The NLP pipeline from raw text to sentiment: tokenisation, n-grams, Word2Vec and word
embeddings, TF-IDF, and a sentiment classifier.

## Usage

```bash
# just open in a browser
open Week2_Hill_Climbing_Final.html
```

Or from a clone of this repository:

```bash
git clone https://github.com/radhika-verma06/41040-ML-Labs.git
cd 41040-ML-Labs
open Week2_Hill_Climbing_Final.html
```

> **Note:** the repository folder is named `Week1_to_Week7_Final_HTMLs`, but only
> Weeks 2–7 are present — there is no Week 1 file in this set.

## Contents

```
.
├── README.md
├── .gitignore
├── Week2_Hill_Climbing_Final.html
├── Week3_Gradient_Boosting_Final.html
├── Week4_Neural_Networks_Final.html
├── Week5_Reinforcement_Learning_Final.html
├── Week6_Computer_Vision_Final.html
└── Week7_NLP_Sentiment_Final.html
```

## Author

[Radhika Verma](https://github.com/radhika-verma06)
