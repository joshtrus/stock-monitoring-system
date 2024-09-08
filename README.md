# stock-monitoring-system

This is a web application that allows users to track stock prices in real time. Users can add stock tickers, view currrent and historical prices. The stock data is obtained using Yahoo Finance API, and the front end dynamically displays the stock information. 

# features
- Add/remove tickers
- View realtime stock information that updates every 30 seconds
- color-coded price changes

# Technologies Used
- Backend: Flask (Python)
- Frontend: HTML, CSS, JavaScript, jQuery
- API: Yahoo Finance API via yfinance library

# Usage
Enter the stock ticker symbol (e.g. AAPL for Apple) in the input field and click "Add". The system will then display the stocks current price and percentage change. The stock prices are updated every 30 seconds. The prices are visually represented by color where green indicates an increase and red a decrease. Click the "remove" button to delete a ticker from the list.

# Screenshots
<img width="1512" alt="Screenshot 2024-09-08 at 11 19 13 AM" src="https://github.com/user-attachments/assets/5dde4788-553c-4cd9-bf8b-1ee9c580f052">

# Future Improvements
- Improve the front end of the website to make more visually appealing
- Give the ability to click on a stock and view more information along with a historical graph
  
