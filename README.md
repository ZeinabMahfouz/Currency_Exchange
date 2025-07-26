# 💱 Exchange Rate Checker using ExchangeRate-API

This Python script fetches real-time currency exchange rates using the [ExchangeRate-API](https://www.exchangerate-api.com/). It allows you to input a base currency and a target currency and returns the latest exchange rate along with the last updated time.

---

## 🚀 Features

- Real-time exchange rate lookup between any two currencies
- Supports all standard 3-letter currency codes (USD, EUR, GBP, INR, JPY, etc.)
- Shows the date and time of the last update
- Graceful handling of invalid input and API errors

---

## 🖥️ Example Output

Enter the base currency (e.g., USD): USD
Enter the target currency (e.g., EUR): EUR

💱 Exchange rate from USD to EUR: 0.89
📅 Last updated: Wed, 24 Jul 2025 00:00:01 +0000

yaml
Copy
Edit

---

## ⚙️ Requirements

- Python 3.x
- `requests` library

Install the required library:

```bash
pip install requests
🔑 API Key Setup
To use this script, you’ll need a free API key from ExchangeRate-API:

Sign up and get your API key from https://www.exchangerate-api.com/

Replace the API key in the script:

python
Copy
Edit
api_key = "your-api-key-here"
📄 How to Use
Clone this repository or copy the script file.

Make sure your API key is inserted correctly.

Run the script:

bash
Copy
Edit
🧠 Notes
The script uses the /pair/{base}/{target} endpoint for simplicity and speed.

Handles errors like invalid currency codes, bad API keys, or network issues.
🙏 Acknowledgements
ExchangeRate-API for their powerful and simple API service.
