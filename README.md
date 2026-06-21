# 🤖 Scylla — Facebook Messenger Chatbot

[![Node.js](https://img.shields.io/badge/Node.js-18+-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT-412991?logo=openai&logoColor=white)](https://openai.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A high-performance Facebook Messenger chatbot powered by OpenAI's GPT models. Built with Node.js, it delivers natural language responses to users through the Facebook Messenger Platform.

## ✨ Highlights

- **GPT-Powered Responses** — Leverages OpenAI API for intelligent, context-aware conversations
- **Facebook Messenger Integration** — Full webhook handling for Messenger Platform events
- **Lightweight & Fast** — Minimal dependencies, quick response times

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Runtime | Node.js 18+ |
| AI/ML | OpenAI API (GPT) |
| Platform | Facebook Messenger Platform |
| Language | JavaScript |

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- OpenAI API Key
- Facebook Page + App (for webhook)

### Installation

```bash
git clone https://github.com/whilmarbitoco/scylla-facebook-bot.git
cd scylla-facebook-bot
npm install
```

### Configuration

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
FB_PAGE_ACCESS_TOKEN=your_page_token
FB_VERIFY_TOKEN=your_verify_token
```

### Run

```bash
npm start
```

## 📡 Architecture

```
User Message → Facebook Webhook → Node.js Server → OpenAI API → Response → Messenger
```

## 📄 License

MIT © [Whilmar Bitoco](https://github.com/whilmarbitoco)
