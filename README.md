# 🚀 Crypto-Predict: Deep Learning & Sentiment Analysis

### **The Intersection of Quantitative Finance and AI**
This repository implements an end-to-end pipeline for forecasting Cryptocurrency prices by fusing **Historical Market Data** with **Real-Time Social Sentiment**. By bridging these two data streams, the project achieves higher predictive accuracy than traditional time-series models.

---

## 💡 Key Features
* **Hybrid Data Fusion:** Combines market metrics with Twitter/Reddit sentiment scores.
* **Feature Engineering:** Implements RSI, MACD, and Signal Lines for technical context.
* **Sentiment Intelligence:** Uses VaderSentiment to quantify market "Fear and Greed."
* **Advanced Model Suite:** Compares 10+ architectures including Bi-LSTMs and GRUs.
* **Professional Visualization:** Interactive performance tracking using Plotly and Seaborn.

---

## 🧠 Model Performance
This project benchmarks multiple deep learning architectures to identify the most robust predictor.

| Model Architecture | BTC Accuracy | ETH Accuracy |
| :--- | :---: | :---: |
| **GRU (Top Performer)** | **97.23%** | **96.47%** |
| **LSTM** | 96.34% | 95.74% |
| **CNN-BiLSTM Hybrid** | 93.42% | 94.56% |
| **RNN** | 93.31% | 96.16% |
| **Transformer-LSTM** | 80.04% | 80.37% |

---

## 🛠️ Tech Stack & Future Hiring Skills
This project demonstrates expertise in high-demand domains for AI Engineering and Quant roles:

* **Deep Learning:** Design and tuning of Gated Recurrent Units (GRU) and 1D-CNNs.
* **Natural Language Processing:** Text preprocessing, tokenization, and sentiment polarity.
* **Time-Series Analysis:** Multi-index handling, feature scaling, and rolling windows.
* **Data Storytelling:** Creating actionable insights through complex data visualization.
* **Financial Engineering:** Deep understanding of market volatility and momentum.

---

## 📂 Project Structure
* `Crypto_Analysis.ipynb` — Main research & model development
* `Bitcoin_tweets.csv` — Raw sentiment data (Twitter)
* `SEthB.csv` — Community sentiment data (Ethereum)
* `models/` — Deployment-ready .h5 and .keras files

---

## 🚀 Getting Started

### **Installation**
`pip install yfinance tensorflow pandas numpy matplotlib seaborn textblob vaderSentiment plotly`

### **Usage**
1. **Clone the project:** `git clone https://github.com/Sakshid9/Crypto-prediction-using-deep-learning-and-sentiment-analysis.git`
2. **Execute:** Open `Crypto_Analysis.ipynb` in Google Colab or Jupyter Notebook.
3. **Data:** The pipeline uses `yfinance` to fetch live data automatically.

---

## 📈 Future Roadmap
* **Real-time Deployment:** Integrating FastAPI for a live prediction dashboard.
* **Transformer Optimization:** Fine-tuning BERT for nuanced crypto-slang sentiment.
* **RL Agent:** Implementing Reinforcement Learning for automated trade execution.

---

*Developed by [Sakshid9](https://github.com/Sakshid9)*
