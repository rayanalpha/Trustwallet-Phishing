# Trust Wallet Phishing Bot
# Contact : https://t.me/ExclusiveCoder

A comprehensive Telegram Phishing bot for Trust Wallet in multiple languages.

## ✨ Features

### 🎯 Core Functionality
- **Interactive Menu System** with inline keyboards
- **Multi-language Support** (11 languages)
- **Real-time Cryptocurrency Prices** via CoinGecko API
- **Educational Center** with comprehensive guides
- **FAQ System** with common questions
- **News & Updates** section
- **Wallet Creation Guide**
- **App Download Links** (iOS & Android)

### 🎨 User Experience
- **Media Integration** (GIFs and images)
- **Media Caching** for better performance
- **Error Handling** with fallback messages
- **Responsive Design** for all devices

## 🌐 Supported Languages

| Language | Code | Flag |
|----------|------|------|
| English | `en` | 🇬🇧 |
| Persian | `fa` | 🇮🇷 |
| Arabic | `ar` | 🇸🇦 |
| Turkish | `tr` | 🇹🇷 |
| Russian | `ru` | 🇷🇺 |
| Spanish | `es` | 🇪🇸 |
| Portuguese | `pt` | 🇵🇹 |
| Chinese | `zh` | 🇨🇳 |
| Japanese | `ja` | 🇯🇵 |
| Korean | `ko` | 🇰🇷 |
| Italian | `it` | 🇮🇹 |

### Interactive Features
- **Connect Wallet** - Guide users to connect their wallet
- **Create Wallet** - Step-by-step wallet creation guide
- **Crypto Prices** - Real-time cryptocurrency prices
- **Education Center** - Comprehensive learning materials
- **FAQ** - Frequently asked questions
- **Language Selection** - Change bot language
- **News & Updates** - Latest Trust Wallet news

## 🔌 API Integration

### CoinGecko API
The bot integrates with CoinGecko API to fetch real-time cryptocurrency prices:
- **Endpoint**: `https://api.coingecko.com/api/v3/simple/price`
- **Features**: Price, 24h change, market cap
- **Update Frequency**: On-demand (user-triggered)

### Error Handling
- API timeout handling (10 seconds)
- Fallback messages for API failures
- Graceful degradation when services are unavailable