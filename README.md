[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/reinagraham/cancer-variant-dataset-machine-learning-using-r)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-39729E?logo=quarto&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

# Machine Learning for Cancer Variant Pathogenicity Classification

A reproducible machine learning workflow using **R** to classify cancer-related genetic variants according to their clinical significance through statistical modelling, Random Forest, and model evaluation.

### **Kaggle Notebook**
https://www.kaggle.com/code/reinagraham/cancer-variant-dataset-machine-learning-using-r

### Quarto html version
https://reinasdatastudio.github.io/cancer-variant-machine-learning/cancer-variant-dataset-machine-learning.html

## Overview

This project explores the application of supervised machine learning to classify cancer-related genetic variants using a publicly available genomics dataset.

The objective was to compare traditional statistical modelling with machine learning approaches while demonstrating a reproducible workflow for data preprocessing, exploratory data analysis, model development, and evaluation. Particular emphasis was placed on understanding the impact of class imbalance and selecting appropriate evaluation metrics for healthcare datasets.

This project was originally developed as a **Kaggle Notebook** and has been migrated to GitHub as part of my healthcare data science portfolio.

## Key Features

* Reproducible machine learning workflow using R
* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Logistic Regression (GLM)
* Random Forest classification
* Class imbalance assessment
* Model comparison and evaluation

## Technologies

* R
* tidyverse
* randomForest
* ggplot2
* Quarto *(or Kaggle Notebook, depending on the final repository structure)*

## Repository Structure

- cancer-variant-machine-learning.qmd
- README.md
- data/

## Results

The project compares Logistic Regression and Random Forest models for classifying pathogenic genetic variants. The analysis highlights the challenges of class imbalance in healthcare datasets and demonstrates why model evaluation should consider precision, recall, and class-specific performance rather than overall accuracy alone.

## Disclaimer

This project uses a publicly available educational dataset and is intended to demonstrate reproducible machine learning workflows for healthcare data analysis. It should not be used for clinical decision-making.

## Author

**Reina Kaino**

Former Pharmacist | Data Scientist | System Engineer

**Website**
https://reinasdatastudio.github.io/webpage/

&ensp;

---
&ensp;

# 機械学習によるがん関連遺伝子変異の病原性予測

## 概要

本プロジェクトでは、公開されているがんゲノムデータを用いて、機械学習による遺伝子変異の病原性分類を行いました。

ロジスティック回帰分析とRandom Forestを比較しながら、データ前処理、探索的データ解析（EDA）、モデル構築、性能評価までを再現可能なワークフローとして実装しています。また、医療データで重要となるクラス不均衡がモデル性能に与える影響についても評価しました。

本プロジェクトは、**Kaggle Notebook**として作成した内容を、ポートフォリオの一部としてGitHubへ移行したものです。

**Kaggle Notebook**
https://www.kaggle.com/code/reinagraham/cancer-variant-dataset-machine-learning-using-r

**Quarto html バージョン**

## 主な内容

* Rを用いた再現可能な機械学習ワークフロー
* データ前処理・クリーニング
* 探索的データ解析（EDA）
* ロジスティック回帰分析
* Random Forest
* クラス不均衡の評価
* モデル比較・性能評価

## 使用技術

* R
* tidyverse
* randomForest
* ggplot2
* Quarto（またはKaggle Notebook）

## ディレクトリ構成

- cancer-variant-machine-learning.qmd
- README.md
- data/

## 解析結果

ロジスティック回帰分析とRandom Forestを比較し、クラス不均衡が存在する医療データでは、単純な正解率だけでなく、適合率（Precision）、再現率（Recall）、クラスごとの性能を評価することの重要性を確認しました。

## 注意事項

本プロジェクトでは公開されている教育用データセットを使用しています。解析内容は、医療データに対する機械学習ワークフローを学習・実践することを目的としており、臨床利用を目的としたものではありません。

## 作成者

**戒能 伶奈**

元薬剤師｜データサイエンティスト

**Website**
https://reinasdatastudio.github.io/webpage/
