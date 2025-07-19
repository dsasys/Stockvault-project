# 🚀 StockVault - Smart Trading Platform

[![Node.js](https://img.shields.io/badge/Node.js-18.x-green.svg)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.x-blue.svg)](https://expressjs.com/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-orange.svg)](https://www.mysql.com/)


> **Your Gateway to Smart Trading** - A comprehensive stock trading platform with real-time portfolio management, interactive charts, and AI-powered assistance.

## 📋 Table of Contents

- [✨ Features](#-features)
- [🛠️ Technology Stack](#️-technology-stack)
- [🚀 Quick Start](#-quick-start)
- [📱 Platform Support](#-platform-support)
- [🎯 Key Features](#-key-features)
- [🤖 AI Assistant](#-ai-assistant)
- [📊 Dashboard Analytics](#-dashboard-analytics)
- [🔧 Installation](#-installation)
- [⚙️ Configuration](#️-configuration)
- [📱 Mobile Support](#-mobile-support)


## ✨ Features

### 🎯 Core Trading Features
- **Real-time Stock Trading** - Buy and sell stocks with live market data
- **Portfolio Management** - Track your investments with detailed analytics
- **Wallet System** - Secure deposit and withdrawal functionality
- **Transaction History** - Complete audit trail of all trading activities
- **Performance Tracking** - Real-time profit/loss calculations

### 🎨 User Experience
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Modern UI/UX** - Beautiful gradient designs and smooth animations
- **Interactive Charts** - Visual representation of stock performance
- **Dark/Light Mode** - Customizable theme preferences
- **Accessibility** - WCAG compliant design

### 🤖 AI-Powered Assistance
- **Smart Chatbot** - 30+ comprehensive FAQ responses
- **Natural Language Processing** - Understands various question formats
- **Drag-to-Identify** - Interactive preset question buttons
- **Mobile-Optimized** - Touch gestures and swipe support
- **24/7 Support** - Always available help system

## 🛠️ Technology Stack

### Backend
- **Node.js** - Server-side JavaScript runtime
- **Express.js** - Web application framework
- **MySQL** - Relational database management
- **EJS** - Template engine for dynamic views

### Frontend
- **HTML5/CSS3** - Modern web standards
- **JavaScript (ES6+)** - Client-side functionality
- **Font Awesome** - Icon library
- **Responsive Design** - Mobile-first approach

### Database
- **MySQL 8.0** - Primary database
- **Optimized Schema** - Efficient data structure
- **Transaction Support** - ACID compliance

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher)
- MySQL (v8.0 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/stockvault.git
   cd stockvault
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up database**
   ```bash
   # Create database
   mysql -u root -p
   CREATE DATABASE stockvault;
   
   # Import schema
   mysql -u root -p stockvault < db/schema.sql
   ```

4. **Configure environment**
   ```bash
   # Copy example config
   cp .env.example .env
   
   # Edit configuration
   nano .env
   ```

5. **Start the application**
   ```bash
   npm start
   ```

6. **Access the platform**
   ```
   http://localhost:3000
   ```

## 📱 Platform Support

### 🌐 Web Application
- **Desktop Browsers** - Chrome, Firefox, Safari, Edge
- **Tablet Support** - iPad, Android tablets
- **Mobile Browsers** - iOS Safari, Chrome Mobile
- **PWA Ready** - Installable web app

### 📱 Mobile Features
- **Touch Gestures** - Swipe, tap, and drag support
- **Responsive Design** - Adaptive layouts for all screen sizes
- **Mobile Chatbot** - Optimized for touch interaction
- **Offline Capability** - Basic functionality without internet

## 🎯 Key Features

### 📊 Dashboard Analytics
- **Portfolio Overview** - Total value, profit/loss, performance metrics
- **Top Performers** - Best performing stocks in your portfolio
- **Market Trends** - Real-time market data and insights
- **Quick Actions** - Fast access to common trading functions

### 💼 Portfolio Management
- **Holdings Display** - All your current stock positions
- **Performance Tracking** - Individual and overall returns
- **Risk Analysis** - Portfolio diversification metrics
- **Transaction History** - Complete trading record

### 💰 Wallet System
- **Secure Deposits** - Add funds to your trading account
- **Withdrawal Support** - Cash out your profits
- **Balance Tracking** - Real-time account balance
- **Transaction Logs** - Detailed financial history

### 📈 Stock Trading
- **Real-time Prices** - Live market data integration
- **Buy/Sell Orders** - Simple and intuitive trading interface
- **Stock Search** - Find stocks by name or symbol
- **Market Analysis** - Price charts and technical indicators

## 🤖 AI Assistant

### 💬 Smart Chatbot Features
- **30+ FAQ Responses** - Comprehensive trading knowledge base
- **Natural Language** - Understands various question formats
- **Quick Buttons** - Instant access to common questions
- **Mobile Optimized** - Touch-friendly interface

### 🎯 Question Categories
- **Trading Basics** - How to buy/sell stocks
- **Portfolio Management** - Understanding your investments
- **Wallet Operations** - Deposits, withdrawals, balance
- **Market Knowledge** - Trading terms and concepts
- **Risk Management** - Investment safety and diversification

### 📱 Mobile Support
- **Touch Gestures** - Swipe to close, tap to interact
- **Drag-to-Identify** - Interactive preset question buttons
- **Auto-focus** - Smart input field management
- **Gesture Controls** - Swipe down to close chat

## 📊 Dashboard Analytics

### 📈 Performance Metrics
- **Total Portfolio Value** - Real-time calculation
- **Profit/Loss Tracking** - Individual and overall P/L
- **Return Percentage** - Performance relative to investment
- **Daily Changes** - 24-hour performance tracking

### 🎯 Portfolio Insights
- **Top Performers** - Best performing stocks
- **Risk Assessment** - Portfolio diversification analysis
- **Market Comparison** - Performance vs market indices
- **Trend Analysis** - Historical performance patterns

## 🔧 Installation

### Detailed Setup Instructions

1. **System Requirements**
   ```bash
   # Check Node.js version
   node --version  # Should be 18.x or higher
   
   # Check npm version
   npm --version   # Should be 8.x or higher
   ```

2. **Database Setup**
   ```sql
   -- Create database
   CREATE DATABASE stockvault CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
   
   -- Create user (optional)
   CREATE USER 'stockvault_user'@'localhost' IDENTIFIED BY 'your_password';
   GRANT ALL PRIVILEGES ON stockvault.* TO 'stockvault_user'@'localhost';
   FLUSH PRIVILEGES;
   ```

3. **Environment Configuration**
   ```env
   # Database Configuration
   DB_HOST=localhost
   DB_USER=stockvault_user
   DB_PASSWORD=your_password
   DB_NAME=stockvault
   DB_PORT=3306
   
   # Application Configuration
   PORT=3000
   NODE_ENV=development
   SESSION_SECRET=your_session_secret
   
   # File Upload Configuration
   UPLOAD_PATH=public/uploads
   MAX_FILE_SIZE=5242880
   ```

4. **Dependencies Installation**
   ```bash
   # Install production dependencies
   npm install --production
   
   # Install development dependencies (optional)
   npm install --dev
   ```

## ⚙️ Configuration

### Database Configuration
```javascript
// Database connection settings
const dbConfig = {
  host: process.env.DB_HOST || 'localhost',
  user: process.env.DB_USER || 'root',
  password: process.env.DB_PASSWORD || '',
  database: process.env.DB_NAME || 'stockvault',
  port: process.env.DB_PORT || 3306,
  charset: 'utf8mb4'
};
```

### Security Settings
```javascript
// Session configuration
app.use(session({
  secret: process.env.SESSION_SECRET || 'stockvault_secret',
  resave: false,
  saveUninitialized: false,
  cookie: { secure: process.env.NODE_ENV === 'production' }
}));
```

## 📱 Mobile Support

### Responsive Design Features
- **Mobile-First Approach** - Designed for mobile devices first
- **Touch Optimization** - Large touch targets and gesture support
- **Adaptive Layouts** - Flexible grids and responsive components
- **Performance Optimized** - Fast loading on mobile networks

### Mobile-Specific Features
- **Swipe Gestures** - Navigate with touch gestures
- **Touch Feedback** - Visual feedback for all interactions
- **Mobile Chatbot** - Optimized for touch interaction
- **Offline Support** - Basic functionality without internet

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow the existing code style
- Add tests for new features
- Update documentation as needed
- Ensure mobile compatibility



## 🙏 Acknowledgments

- **Font Awesome** - For the beautiful icons
- **Express.js Community** - For the excellent framework
- **MySQL Community** - For the reliable database
- **Open Source Contributors** - For inspiration and support

---

