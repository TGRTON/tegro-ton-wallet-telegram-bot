# Tegro Ton Bot

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Aiogram](https://img.shields.io/badge/Aiogram-3.0.0b8-blue)](https://docs.aiogram.dev/en/latest/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100.0-blue)](https://fastapi.tiangolo.com/)
[![Redis](https://img.shields.io/badge/Redis-4.6.0-blue)](https://redis.io/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1.4.23-blue)](https://www.sqlalchemy.org/)
[![httpx](https://img.shields.io/badge/httpx-0.24.1-blue)](https://www.python-httpx.org/)

## Comprehensive Description

**Tegro Ton Bot** is a sophisticated Telegram bot engineered for seamless integration with the innovative Tegro.money payment system and the versatile TON blockchain network. This bot is an exemplar of modern fintech solutions, offering a range of functionalities for both casual users and blockchain enthusiasts. It serves as a gateway for users to engage in various financial transactions, leveraging the security and efficiency of the TON blockchain.

Developed initially as a test assignment, Tegro Ton Bot has evolved into a full-fledged tool for facilitating transactions in the TON ecosystem. Its primary focus is on TGR - a unique token within the TON network. Users can effortlessly purchase TGR, track their balance, and engage in transactions, all within the Telegram interface.

### Enriched Features

- **TGR Purchasing:** Enables users to buy TGR tokens directly through the bot.
- **Balance Inquiries:** Check the current balance of TGR tokens in the user's account.
- **TON Wallet Creation:** Users can create a new wallet specifically for handling TON transactions.
- **TGR Wallet Management:** Apart from TON, the bot also supports the creation and management of TGR wallets.
- **Transaction Tracking:** Monitors and reports transaction activities within the TON network.
- **TON and TGR Transactions:** Facilitates both TON and TGR transactions, ensuring a smooth financial experience.
- **Wallet Balance Checks:** Offers a quick and easy way to verify the balances of both TON and TGR wallets.

### Advanced Technologies

- **Python 3.11:** The backbone of the bot, known for its simplicity and efficiency.
- **Aiogram:** A powerful framework for building dynamic Telegram bots.
- **FastAPI:** Known for its speed and ease of use, this framework is ideal for web application development.
- **Uvicorn:** A lightning-fast ASGI server used to run FastAPI applications.
- **SQLAlchemy & Alembic:** These libraries provide robust database handling and migration capabilities.
- **httpx:** Facilitates efficient HTTP requests within the application.
- **Redis:** An in-memory database that enhances the performance and scalability of the bot.

## Detailed Installation Guide

1. **Telegram Bot Registration:**
   Register your bot on Telegram using @BotFather to obtain your unique token.

2. **Telegram Hook Requirement:**
   The bot requires a public IP for Telegram Hook. For local development or testing, services like [ngrok](https://ngrok.com) can be used.

3. **Environment Setup:**
   Rename '.env.template' to '.env' and populate it with all the necessary environment variables.

4. **TON Network Integration:**
   Download and set up the Ton-Server from [this repository](https://github.com/TGRTON/TON-token-Rest-API) to interact with the TON blockchain.

5. **Payment Gateway Configuration:**
   For processing payments, register your service at [Tegro.money](https://tegro.money).

6. **Bot Launch:**
   Run the bot from the root directory using the following command:

```
uvicorn src.main:app --port=80
```

## Usage

After issuing the /start command, an intuitive menu appears. It allows testing the full functionality of the bot.
