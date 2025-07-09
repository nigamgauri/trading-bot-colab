# Trading Bot – Binance Futures Testnet  
**Candidate:** Gauri Nigam  
**Email:** nigamgauri24@gmail.com  

This project is a simplified trading bot built in Python using the Binance Futures Testnet. It was designed as part of a technical assignment to demonstrate basic automation of trading actions like placing market, limit, and stop-limit orders.

---

## What the Bot Does

- Connects to the Binance Futures Testnet using your API credentials  
- Lets you place **market**, **limit**, or **stop-limit** orders  
- Supports both **buy** and **sell** sides  
- Accepts user input via simple command-line prompts  
- Handles errors and logs order details automatically

---

## How to Use It (on Google Colab)

1. Run the first cell to install required libraries (`python-binance`)
2. Run the next cell to define the `BasicBot` class
3. Enter your Binance **Testnet API key and secret** (not your real one!)
4. Follow the command-line prompts to place an order:
   - Choose order type
   - Enter pair, side, quantity, and price (if needed)
5. You'll get order details in the output and logs in `bot.log`
