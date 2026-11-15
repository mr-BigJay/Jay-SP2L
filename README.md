# Jay-SP2L

Independent working copy of the **SP2L** trading-bot code from [AlirezaSadabadi/PythonTraderBot](https://github.com/AlirezaSadabadi/PythonTraderBot/tree/main/code/SP2L).

## Included
- `SP2L_Advanced_Bot_Optimized.py` — advanced strategy / live trader
- `SP2L_Bot_Basic_Old.py` — simpler reference implementation
- `Meta.py` — MetaTrader 5 execution helper
- `TelegramBot.py` — Telegram messaging helper
- Backtesting notebooks and Python requirements

## Important
This is **not** a Linux-native Bitunix bot. The original trading scripts use the `MetaTrader5` Python package and require a compatible MetaTrader terminal. Do not run scripts connected to a funded trading account until execution, risk limits, credentials, SL/TP and exchange-specific logic have been reviewed. `NewsMonitor` is a separate upstream module and is not included in this initial copy.

The upstream `myenv/` virtual environment, `__pycache__/` compiled files, and `Results/` sample output are deliberately omitted.

## Attribution
Original author: **Alireza Sadabadi**.
Upstream: https://github.com/AlirezaSadabadi/PythonTraderBot

See the included `LICENSE` file for the upstream Apache License, Version 2.0.
