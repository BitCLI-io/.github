<div align="center">
  <img src="https://github.com/BitCLI-io/.github/assets/YOUR_IMAGE_ID_HERE" alt="BitCLI Logo" width="120" />
  <h1>BitCLI — Ultra-Fast Crypto Alerts Engine</h1>
  <p><b>Tick-by-tick order flow, liquidations, and funding rate analytics right in Telegram.</b></p>

  [![Telegram Bot](https://img.shields.io/badge/Telegram-Launch_Bot-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/bitclibot)
  [![Documentation](https://img.shields.io/badge/Docs-docs.bitcli.io-10b981?style=for-the-badge&logo=read-the-docs)](https://docs.bitcli.io)
  [![Website](https://img.shields.io/badge/Website-bitcli.io-151c2c?style=for-the-badge&logo=google-chrome)](https://bitcli.io)
</div>

<br>

## ⚡ About BitCLI

BitCLI is an institutional-grade, **High-Frequency Trading (HFT)** alert engine built in C++. It connects directly to raw L2 WebSockets across Binance, Bybit, and Hyperliquid, evaluating order flow events in under `500ns`.

Instead of a clunky web UI, BitCLI provides a blazing-fast **Command Line Interface (CLI)** directly inside Telegram. 

```bash
# Examples of BitCLI syntax you can type in Telegram:
btc 95k             # Price alert at $95,000
sol 3% 5m           # Velocity alert: ±3% jump within 5 minutes
* vol 15m x3        # Whale radar: Any coin volume spikes 3x over SMA20
* liq z3            # Anomaly radar: Liquidation cascade Z-Score > 3
btc cvd div 15m     # Order flow: Bearish/Bullish CVD divergence
```

## 🛠 Repositories & SDKs

We are building an open ecosystem for algorithmic traders, quants, and AI agents.

- 🤖 **[bitcli-mcp-server](#)** — Official Model Context Protocol (MCP) server. Connect Claude Desktop, Cursor, or your autonomous AI agents directly to our real-time crypto radars.
- 🔗 **[bitcli-tv-webhooks](#)** — Ready-to-use PineScript templates and JSON payloads for routing TradingView signals to Telegram via BitCLI gateway.
- 📦 **[bitcli-python-sdk](#)** *(Coming Soon)* — Official Python wrapper for the BitCLI M2M API.

<br>

<div align="center">
  <i>"Don't chase the candle close. Trade the tick."</i><br>
  Contact: <a href="mailto:team@bitcli.io">team@bitcli.io</a> | B2B & White-Label: <a href="mailto:b2b@bitcli.io">b2b@bitcli.io</a>
</div>
