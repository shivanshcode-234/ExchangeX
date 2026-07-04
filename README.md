 ⚡ ExchangeX

> A high-performance electronic exchange simulator built from scratch in Python and Next.js.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688)
![Next.js](https://img.shields.io/badge/Next.js-Frontend-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![License](https://img.shields.io/badge/License-MIT-green)

📌 Overview

ExchangeX is a modern electronic exchange simulator designed to demonstrate how real-world financial exchanges process and distribute market data.

The project combines a low-latency matching engine, real-time WebSocket streaming, and a professional TradingView-inspired trading terminal.

Unlike simple stock simulators, ExchangeX focuses on the engineering behind electronic markets.

---

 ✨ Features

- ⚡ High-performance limit order book
- 📈 Real-time market data streaming
- 📊 Live candlestick charts
- 📚 Level II order book
- 💰 Paper trading
- 🌐 WebSocket API
- 🔄 REST API
- 📉 Portfolio tracking
- 📊 Performance analytics
- ⚙️ Market simulator
- 🔥 Replay engine
- 🧪 Stress testing
- 🐳 Docker support



 🏗 Architecture


                    ExchangeX

              Next.js Trading Terminal
                       │
          REST API + WebSocket Gateway
                       │
                  FastAPI Backend
                       │
       ┌───────────────┴───────────────┐
       │                               │
 Matching Engine               Market Simulator
       │                               │
       └───────────────┬───────────────┘
                       │
               Market Data Publisher
                       │
Backend

- Python
- FastAPI
- AsyncIO
- WebSockets
- Uvicorn

Frontend

- Next.js
- TypeScript
- TailwindCSS
- TradingView Lightweight Charts
- Framer Motion

 DevOps

- Docker
- GitHub Actions
- Prometheus
- Grafana



📂 Project Structure

text
ExchangeX/

backend/
frontend/
docs/
docker/
tests/




 🎯 Planned Features

- [x] Limit Order Book
- [x] FIFO Matching Engine
- [ ] Market Orders
- [ ] IOC Orders
- [ ] FOK Orders
- [ ] Portfolio Dashboard
- [ ] Live Charts
- [ ] AI Market Commentary
- [ ] Multi-Exchange Simulation
- [ ] Replay Engine
- [ ] Risk Dashboard


 🚀 Performance Goals

- <100 μs matching latency
- 10,000+ simulated orders/sec
- O(1) order lookup
- FIFO price-time priority
- Real-time WebSocket updates



🎓 Educational Purpose

ExchangeX is built as a learning project to explore:

- Financial market infrastructure
- Low-latency systems
- Data structures & algorithms
- Distributed systems
- Real-time networking
- Software architecture

---

## 📜 License

MIT License
