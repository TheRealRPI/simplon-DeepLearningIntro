# 🧠 Introduction au Deep Learning

> TP pratiques — du perceptron aux réseaux de neurones profonds

[![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://tensorflow.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?logo=jupyter)](https://jupyter.org)

## 📑 Table des matières

- [Description](#-description)
- [Exercices](#-exercices)
- [Prérequis](#-prérequis)
- [Utilisation](#-utilisation)
- [Structure du projet](#-structure-du-projet)
- [Auteurs](#-auteurs)
- [Licence](#-licence)

## 📖 Description

Formation pratique au Deep Learning : **perceptron**, **MLP**, **CNN** et **RNN**.
12 notebooks Jupyter progressifs, du NumPy from scratch à Keras/TensorFlow — chaque exercice existe en 2 versions : la version originale (`exo_*`) et la version PDF corrigée (`exo_pdf_*`).

## 🎯 Exercices

| # | Notebook | Sujet | Compétences |
|---|----------|-------|-------------|
| 1 | `exo_1_perceptron.ipynb` / `exo_pdf_1_perceptron.ipynb` | Perceptron — portes AND/NOR | NumPy, gradient descent, classification binaire |
| 2 | `exo_2_iris.ipynb` / `exo_pdf_2_iris.ipynb` | MLP sur Iris | Keras, MLP, classification multi-classes |
| 3 | `exo_3_cnn_mnist.ipynb` / `exo_pdf_3_cnn_mnist.ipynb` | CNN sur MNIST | Conv2D, MaxPooling, images 28×28 |
| 4 | `exo_4_cnn_fashion_mnist.ipynb` / `exo_pdf_4_cnn_fashion_mnist.ipynb` | CNN sur Fashion-MNIST | CNN, classification 10 classes |
| 5 | `exo_2bis_titanic.ipynb` / `exo_pdf_5_titanic.ipynb` | MLP sur Titanic | Preprocessing, comparaison 4/16/64 neurones |
| 6 | `exo_5_rnn_texte.ipynb` / `exo_pdf_6_rnn_victor-hugo.ipynb` | RNN — génération de texte | RNN/LSTM, NLP, prédiction mot suivant |

## 🔧 Prérequis

- **Python 3.13+**
- **Jupyter Notebook** ou **JupyterLab**
- Bibliothèques : `tensorflow`, `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## 💻 Utilisation

```bash
jupyter notebook
# ou
jupyter lab
```

Ouvrir les notebooks dans `notebook/` dans l'ordre : **1 → 2 → 3 → 4 → 5 → 6** (version PDF corrigée : `exo_pdf_*`)

## 📁 Structure du projet

```
DeepLearningIntro/
├── notebook/               # 12 notebooks Jupyter (6 exercices × 2 versions)
│   ├── exo_1_perceptron.ipynb
│   ├── exo_2_iris.ipynb
│   ├── exo_2bis_titanic.ipynb
│   ├── exo_3_cnn_mnist.ipynb
│   ├── exo_4_cnn_fashion_mnist.ipynb
│   ├── exo_5_rnn_texte.ipynb
│   ├── exo_pdf_1_perceptron.ipynb       # versions corrigées (source PDF)
│   ├── exo_pdf_2_iris.ipynb
│   ├── exo_pdf_3_cnn_mnist.ipynb
│   ├── exo_pdf_4_cnn_fashion_mnist.ipynb
│   ├── exo_pdf_5_titanic.ipynb
│   └── exo_pdf_6_rnn_victor-hugo.ipynb
├── data-sources/           # Textes pour les RNN (exo 5/6)
│   ├── victor-hugo-texts.txt / victor-hugo-titles.txt
│   ├── corpus.txt / bobby.txt / aya.txt / papayou.txt
└── .gitignore
```

## ✍️ Auteurs

[TheRealRPI](https://github.com/TheRealRPI) - 🧙 Sorcier de la Data | Data Engineer en formation - Simplon.co

## 📜 Licence

Projet académique - Simplon.co
