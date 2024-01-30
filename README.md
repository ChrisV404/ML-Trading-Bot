A trading bot that uses machine learning to gauge the market. The ML algorithm receives news information and calculates a sentiment using NLP to create a buy or sell order.

### Steps
1. Create a virtual environment `conda create -n trader python=3.10`
2. Activate it `conda activate trader`
3. Install initial deps `pip install lumibot timedelta alpaca-trade-api`
4. Install transformers and friends `pip install torch torchvision torchaudio transformers`
5. Update the API_KEY and API_SECRET with values from your Alpaca account
6. Run the bot `python tradingbot.py`


(All credit to Nick Renotte)
