# 基於雙向長短期記憶網路(BiLSTM)之情感分析預測

[![Python](https://img.shields.io/badge/Python-3-3776AB)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)](https://jupyter.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00)](https://www.tensorflow.org/)

## 專案描述

使用雙向長短期記憶網路 (BiLSTM) 對 Twitter 文本進行情感分析預測。

## 資料集

[Kaggle - Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

### 前處理

- 只使用 `Positive`、`Negative`、`Neutral`
- 移除 `Irrelevant`

## 設備

- Google Colab CPU

## 技術資訊

| 項目 | 說明 |
|------|------|
| **語言** | Python |
| **環境** | Jupyter Notebook / Google Colab |
| **模型** | BiLSTM (雙向長短期記憶網路) |

## 專案結構

```
BiLSTM_Sentiment-Analysis/
├── BiLSTM_Sentiment_Analysis.ipynb   # Jupyter Notebook 主程式
└── README.md
```
