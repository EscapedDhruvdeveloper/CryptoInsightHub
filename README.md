# CryptoInsightHub

A modern, responsive cryptocurrency tracking and analysis platform built with React.js. Track real-time crypto prices, compare different cryptocurrencies, and manage your personal watchlist with an intuitive user interface.

## 🚀 Features

- **Real-time Cryptocurrency Tracking**: Monitor live prices and market data
- **Interactive Dashboard**: Comprehensive overview of cryptocurrency markets
- **Coin Comparison**: Side-by-side comparison of different cryptocurrencies
- **Personal Watchlist**: Save and track your favorite cryptocurrencies
- **Responsive Design**: Optimized for desktop and mobile devices
- **Custom Cursor Effects**: Enhanced user experience with interactive cursor animations
- **Material-UI Components**: Modern and consistent UI design
- **Chart Visualizations**: Interactive charts powered by Chart.js

## 🛠️ Technologies Used

- **Frontend Framework**: React 18.2.0
- **UI Library**: Material-UI (MUI) 5.11.4
- **Routing**: React Router DOM 6.6.2
- **Charts**: Chart.js 4.2.0 with React Chart.js 2
- **HTTP Client**: Axios 1.2.2
- **Animations**: Framer Motion 8.4.3
- **Notifications**: React Toastify 9.1.1
- **Sharing**: React Web Share 2.0.2
- **Testing**: React Testing Library

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd CryptoInsightHub
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application.

## 🏗️ Project Structure

```
src/
├── components/
│   ├── CoinPage/          # Individual coin detail components
│   ├── Common/            # Reusable UI components
│   ├── ComparePage/       # Cryptocurrency comparison components
│   ├── Dashboard/         # Dashboard-specific components
│   └── LandingPage/       # Home page components
├── pages/
│   ├── Home.js           # Landing page
│   ├── Dashboard.js      # Main dashboard
│   ├── Coin.js           # Individual coin details
│   ├── Compare.js        # Coin comparison page
│   └── Watchlist.js      # Personal watchlist
├── functions/            # Utility functions and API calls
├── assets/              # Static assets (images, icons)
├── App.js               # Main application component
└── index.js             # Application entry point
```

## 🎯 Available Pages

- **Home (`/`)**: Landing page with project overview
- **Dashboard (`/dashboard`)**: Main cryptocurrency tracking interface
- **Coin Details (`/coin/:id`)**: Detailed view of individual cryptocurrencies
- **Compare (`/compare`)**: Side-by-side cryptocurrency comparison
- **Watchlist (`/watchlist`)**: Personal cryptocurrency watchlist

## 📜 Available Scripts

- `npm start`: Runs the app in development mode
- `npm build`: Builds the app for production
- `npm test`: Launches the test runner
- `npm eject`: Ejects from Create React App (one-way operation)
