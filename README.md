# Nubra Python SDK Examples

This repository contains **runnable, production-style examples** demonstrating how to use the **Nubra Python SDK** for Trading and Market Data APIs.

All examples use the official Nubra Python SDK and are designed to be:
- Execution-grade
- Easy to extend
- Identical across UAT and LIVE environments

---

## Examples Included

### Python SDK

- Authentication (TOTP, environment-based login)
- Place, modify, and cancel orders
- Basket & multi-order execution
- Market data (LTP, OHLC, historical data)
- Margin and risk calculations

> These examples focus on **SDK-first usage** and abstract away raw REST handling.

---

## Prerequisites

- Python **3.9+**
- Nubra API credentials
- Nubra Python SDK installed

---

## Documentation

- **Python SDK Docs**  
  https://nubra.io/products/api/docs/python-sdk/

- **Full API Documentation**  
  https://nubra.io/products/api/docs/

---

## Notes

- Examples default to **UAT** for safe testing  
- Switch to `NubraEnv.PROD` for live trading
- Each folder contains standalone, copy-paste-ready scripts


