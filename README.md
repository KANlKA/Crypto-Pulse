Crypto Pulse - Real-Time Cryptocurrency Dashboard
Crypto Pulse Dashboard

Overview
Crypto Pulse is a modern, real-time cryptocurrency dashboard that provides live price updates, market trends, and comprehensive coin data. Built with WebSocket technology, it connects directly to Binance's API to deliver instant price updates without page refreshes.

Features
Real-time Price Updates: Live streaming of cryptocurrency prices via WebSocket

Interactive Charts: Beautiful, animated price charts for top cryptocurrencies

Market Overview: Comprehensive table showing price, volume, and market cap

Smart Filtering: Filter coins by gainers, losers, or view all

Search Functionality: Quickly find specific coins

Responsive Design: Works on desktop and mobile devices

Visual Indicators: Color-coded price changes and animations

Technologies Used
Frontend: HTML5, CSS3, JavaScript

UI Framework: Tailwind CSS

Charts: Chart.js

Icons: Font Awesome

Real-time Data: Binance WebSocket API

Font: Inter (Google Fonts)

Installation
No installation required! Simply open the index.html file in any modern web browser.

For development purposes:

Clone this repository

Open index.html in your browser

The dashboard will automatically connect to Binance's WebSocket API

Usage
Connect to WebSocket: Click the "Connect" button to establish a real-time connection

View Market Data: The dashboard will display live price data for major cryptocurrencies

Filter View:

Click "All" to see all coins

Click "Gainers" to see only coins with positive 24h change

Click "Losers" to see only coins with negative 24h change

Search: Type in the search box to filter coins by name

Featured Coins: View detailed price charts for BTC, ETH, BNB, and SOL

Customization
To add or remove coins from the market table:

Edit the marketCoins array in the JavaScript section

Add/remove objects following the format:

javascript
{ symbol: 'COINUSDT', name: 'Coin Name', logo: 'logo-name' }
