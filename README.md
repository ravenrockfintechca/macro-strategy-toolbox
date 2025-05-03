# macro-strategy-toolbox
FORKS OF MACTO TRADING STUFF
macro-strategy-toolbox/
│
├── README.md 项目介绍与模块清单
├── notebooks/ 每个策略的Jupyter演示
│   ├── 01_yield_curve_strategy.ipynb
│   ├── 02_all_weather.ipynb
│   └── ...
│
├── data/ 可接入的 FRED / IMF / Yahoo API 数据处理模板
│
├── strategies/ 核心策略代码
│   ├── yield_curve.py
│   ├── cpi_model.py
│   └── ...
│
├── backtests/ 回测框架（支持 Backtrader / vectorbt）
├── webapp/ 可选 Flask 前端（与你网站打通）
└── ztrader_sync/ 推送更新到 ztrader.ai 的脚本
