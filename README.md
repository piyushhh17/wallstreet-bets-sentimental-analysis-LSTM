# 💬 WallStreetBets Sentiment Analysis using LSTM

An AI-driven sentiment analysis tool built to scan and analyze posts from Reddit's r/wallstreetbets community. The project leverages a Long Short-Term Memory (LSTM) neural network to determine the emotional tone of posts and identify stocks being discussed positively in real-time.

---

## 📌 Highlights

- 🤖 **Deep Learning Powered**: LSTM-based sentiment classification with 92% accuracy.
- 📊 **Data-Driven**: Analyzes Reddit posts and matches them with stock market data.
- 📦 **End-to-End Pipeline**: From raw Reddit text to stock sentiment insights.
- 🌐 **Web Visualizations**: Static HTML pages showing results and analysis.
- 🧠 **Highly Customizable**: Extendable to real-time feeds or other financial communities.

---

## 🧠 Technologies Used

| Domain       | Tools & Libraries                                      |
|--------------|--------------------------------------------------------|
| Programming  | Python                                                 |
| Deep Learning| TensorFlow, Keras                                      |
| Data Handling| Pandas, NumPy                                          |
| Visualization| Matplotlib                                             |
| Storage      | MongoDB                                                |
| Interface    | Jupyter Notebook, HTML                                 |

---

## 📁 Folder Structure

```
wallstreet-bets-sentimental-analysis-LSTM/
│
├── WallStreetBets Sentiment Analysis Final.ipynb  # Main notebook
├── reddit_wsb.csv                                 # Dataset from Reddit
├── stock_data.csv                                 # Related stock info
├── database.sqlite                                # Local database
├── index.html                                     # Visualization dashboard
├── stock_info.html                                # Stock-specific insights
├── Accuracy plot.jpg                              # Model accuracy plot
├── Loss plot.jpg                                  # Model training loss
├── reddit.png                                     # UI asset
├── stocks.png                                     # UI asset
└── README.md                                      # This file
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/piyushhh17/wallstreet-bets-sentimental-analysis-LSTM.git
cd wallstreet-bets-sentimental-analysis-LSTM
```

### 2. Set up your environment

```bash
pip install tensorflow keras pandas numpy matplotlib
```

### 3. Run the notebook

Launch the Jupyter Notebook:

```bash
jupyter notebook WallStreetBets\ Sentiment\ Analysis\ Final.ipynb
```

Follow the steps in the notebook to preprocess data, train the model, and view results.

---

## 📈 Project Results

- ✅ Achieved **92% accuracy** in classifying sentiment (positive/negative).
- 📉 Loss stabilized after ~5 epochs.
- 📊 Plotted metrics and results saved as images for quick reference.

---

## 🚀 Future Directions

- ⏱️ Real-time Reddit feed processing using PRAW or Pushshift API.
- 🌍 Deploy a web dashboard to explore trending tickers.
- 🧪 Explore sentiment correlation with actual stock movement.
- 📲 Mobile integration for alerts on bullish stocks from WSB.

---

## 🧾 License

This project is licensed under the MIT License. Feel free to fork and modify.

---

## 🙋‍♂️ About the Author

**Piyush Kaushal**  
📧 piyushkaushal17@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/piyushhh17/)  
🐙 [GitHub](https://github.com/piyushhh17)

---

> ⭐ If you found this useful, star the repo and share it with fellow devs!
