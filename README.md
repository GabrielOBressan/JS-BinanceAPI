# JS-BinanceAPI

# Crypto Market Dashboard

A real-time dashboard for cryptocurrency market data visualization, featuring interactive price charts for Bitcoin, Ethereum, Ripple, and Solana.

## 🚀 Features

- Price visualization across different time intervals (24h, 7d, 30d, 6m, 1y)
- Interactive charts using Binance API data
- Responsive and modern interface
- Support for multiple cryptocurrencies (BTC, ETH, XRP, SOL)
- Automatic monetary value formatting
- Informative chart tooltips

## 🛠️ Technologies Used

- Node.js
- Express.js
- Chart.js
- Axios
- Binance API
- HTML5/CSS3
- JavaScript (ES6+)
- Tailwind CSS

## 📋 Prerequisites

- Node.js (version 14.0.0 or higher)
- NPM (version 6.0.0 or higher)

## 🔧 Installation

1. Clone the repository:
git clone https://github.com/your-username/crypto-market-dashboard.git

2. Navigate to the project directory:
cd crypto-market-dashboard

3. Install dependencies:
npm install

4. Start the server:
npm start

5. Access the application at:
http://localhost:3000

## 📦 Dependencies

{
  "dependencies": {
    "express": "^4.17.1",
    "axios": "^0.24.0",
    "chart.js": "^3.7.0"
  }
}

## 🔄 Updating Dependencies

To update all dependencies to their latest versions:
npm update

## 📊 Project Structure

crypto-market-dashboard/
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── models/
│   └── Price.js
├── index.js
├── package.json
└── README.md

## 🖥️ How to Use

1. The home page displays four charts, one for each cryptocurrency
2. Use the time interval selectors to change the visualization:
   - 24h: last 24 hours data
   - 7d: last 7 days data
   - 30d: last 30 days data
   - 6m: last 6 months data
   - 1y: last year data

## ⚙️ Configuration

The project uses Binance's public API to fetch price data. No authentication is required for the endpoints used.

## 🤝 Contributing

1. Fork the project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🎯 Project Status

The project is under active development and open for contributions.

## 🐛 Known Issues

- No known issues at the moment.

## 📫 Contact

Gabriel Bressan - gabrielbressannz@gmail.com

Project Link: [https://github.com/your-username/crypto-market-dashboard](https://github.com/your-username/crypto-market-dashboard)
