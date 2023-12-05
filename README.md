# team_VN_Stock_Portfolio_Suggestion_Engine

CMPE_285_Stock_Portfolio_Suggestion_Engine

# Stock Portfolio Suggestion Engine

## Project Description

The Stock Portfolio Suggestion Engine employs diverse investment strategies, including ethical investing, value investing, growth investing, index investing, and quality investing. It recommends optimal investment options by considering the user's input of the investment amount. The user interface displays a comprehensive report of the suggested stock portfolio, delivering a smooth and detailed experience.

### Features

1. User inputs the investment amount in USD (Minimum: $5000 USD).
2. Users can choose one or two investment strategies from the following options:
   - Ethical Investing
   - Growth Investing
   - Index Investing
   - Quality Investing
   - Value Investing
3. The engine assigns specific stocks or ETFs for the selected investment strategy. For example:
4. Index Investing strategy could map to ETFs like:
   - Vanguard Total Stock Market ETF (VTI)
   - iShares Core MSCI Total Intl Stk (IXUS)
   - iShares Core 10+ Year USD Bond (ILTB)
5. Ethical Investing strategy might map to individual stocks like:
   - Apple (AAPL)
   - Adobe (ADBE)
   - Nestle (NSRGY)
6. Each strategy corresponds to at least three different stocks or ETFs.
7. The suggestion engine provides:
   - The selected stocks based on inputted strategies.
   - Allocation of funds to purchase the suggested stocks.
   - A weekly trend of the portfolio value, including a 5-day history.
   - Real-time values of the overall portfolio (updated regularly).
   - A weekly trend of the portfolio value, including a 5-day history.

### Technologies Utilized

- HTML5
- CSS3
- Bootstrap
- JavaScript
- Node.js
- Ant Design
- Flask
- Python
- React
- Heroku
- REST
- IEX Stock API
- TradingView Market Overview Widget

### Running the Frontend

1. Navigate to the `frontend` directory:

   ```zsh
   cd frontend
   ```

2. Install the required dependencies:

   ```zsh
   npm install
   export NODE_OPTIONS=--openssl-legacy-provider
   ```

3. Start the React app:

   ```zsh
   npm start
   ```

   The frontend should be accessible at http://localhost:3000.

Open your web browser and visit http://localhost:3000 to interact with the Stock Portfolio Suggestion Engine.

### Running the Backend

1. Navigate to the `backend` directory:

   ```zsh
   cd backend
   ```

2. Install the required dependencies:

   ```zsh
   pip install -r requirements.txt
   python3 -m pip install --upgrade urllib3
   python3 -m pip install --upgrade Flask
   python3 -m pip install --upgrade Flask-Cors
   python3 -m pip install --upgrade itsdangerous
   python3 -m pip install --upgrade Jinja2
   python3 -m pip install --upgrade MarkupSafe
   python3 -m pip install --upgrade Werkzeug
   python3 -m pip install --upgrade requests
   ```

3. Run the Flask app:

   ```zsh
   python stock-suggestion-server.py
   ```

   The backend server should be running at http://127.0.0.1:5000

### Team Members

- Vani Vineela Aremanda - 016131284
- Lakshmi Sri Nitya Sunkara - 017459390
