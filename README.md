# Stock-sentiment-engine
NLP-powered stock sentiment ranking engine using FMP + LLMs

# Sentiment Stock Analytics

This is a professional-grade software pipeline for analyzing stock sentiment using NLP and real-time news data from Financial Modeling Prep (FMP).

### 📌 Features

1. **Rank all stocks** based on sentiment scores over the last two quarters.
2. **Get historical sentiment** analysis for a given ticker and date range.

### 💡 Technologies

- Python
- FMP API
- TextBlob / VADER / FinBERT (future)
- Pandas, NumPy
- Matplotlib / Seaborn (optional)
- HuggingFace Transformers (later)

### 📂 Coming Modules

- `news_fetcher.py` - Pulls historical news headlines per ticker
- `sentiment_engine.py` - NLP scoring logic (TextBlob first)
- `feature_builder.py` - Aggregates sentiment per ticker/date
- `app.py` - CLI interface for running tasks

### 🔒 API Key
Set your FMP API key in `config.json`:

```json
{
  "FMP_API_KEY": "your_key_here"
}
