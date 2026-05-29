<p align="center">
  <strong>Language / 语言</strong><br/>
  <a href="#lang-en"><strong>English</strong></a>
  &nbsp;·&nbsp;
  <a href="#lang-zh"><strong>中文</strong></a>
</p>

<p align="center">
  <em>Click a language below to expand · 点击下方语言展开</em>
</p>

---

<details open id="lang-en">
<summary><strong>🇺🇸 English</strong></summary>

# 🤖 Polymarket Trading Bot — @SEI-DDEV

An open-source and strategy Polymarket trainding bot automated prediction market trading, this bot supports

📞 **Contact:** 📊 Polymarket [@sei-ddev](https://polymarket.com/@sei-ddev)  ·  💬 Telegram [S.E.I](https://t.me/sei_dev)  ·  𝕏  Twitter  [S.E.I](https://x.com/ajee335)

[![Polymarket trading bot — click to watch on YouTube](https://github.com/user-attachments/assets/9b45cc5b-e451-4923-8f91-335f6d627bea)](https://www.youtube.com/watch?v=4C83CNM4bE8)

---

## 📊 Overview

<img width="890" height="296" alt="Polymarket profile — performance overview" src="https://github.com/user-attachments/assets/b2561587-4d2e-4afa-a3d9-d042354fda6e" />

> ✨ **Profile refreshed** — updated display name and continued profit growth through systematic end-cycle execution.

<img width="883" height="259" alt="Polymarket profile — P/L and activity stats" src="https://github.com/user-attachments/assets/43610899-6267-49d4-8701-852165906b1b" />

> 📈 **Live metrics** — figures mirror the public Polymarket profile and refresh in real time. Visit [@sei-ddev](https://polymarket.com/@sei-ddev) for the current P/L curve, open positions, and full trade history.

---

## ⚙️ How It Works

| Step | What happens |
|------|----------------|
| **1. Ingest** 📡 | Pulls live **BTC/USD** and **ETH/USD** from on-chain **Chainlink** feeds — the same oracle Polymarket uses at settlement. |
| **2. Score** 🧮 | Compares CLOB-implied probability with a short-horizon directional model in the final seconds of each candle. |
| **3. Snipe** 🎯 | Enters **Up** or **Down** only when edge exceeds fees + slippage; size scales with confidence and time remaining. |
| **4. Settle** ✅ | Markets auto-resolve against Chainlink; the bot rolls cleanly into the next cycle. |

### Advantage of bot

<img width="807" height="334" alt="image" src="https://github.com/user-attachments/assets/bc7815c4-ae56-4a97-bcf0-107cbcd94aa7" />

The bot is not chasing overpriced entries or relying on aggressive momentum buying. Instead, it focuses on entering positions at relatively low prices, which creates a far more efficient risk-to-reward structure.

> Lower entry prices increase potential upside

> Smaller downside exposure when trades fail

---

## 👤 SEI-DDev

On Polymarket since **Apr 2026** (2 mo)

💰 **Portfolio** $0 · **Bank** $674 · **Lifetime PnL** +$1.7K  
📊 **5,046** markets · **WR** 72% (1862W / 735L)  
💵 **Volume** $154.1K  
🎯 **ROI/vol** +1.1% · **ROI/mkt** -100.0% · **profit/mkt** $0  
📈 **Sharpe** 10.50 · **Max DD** -$118 · 🥶 **29L**  
📐 **Median size** $30 (4.4% from bank)  
⏱ **161/wk** · **1.6** entries/mkt (30d)

**🗂 Top categories by PnL**

```
├ Up or Down 323 · WR 49% · -$5.4K
├ Crypto Prices 40 · WR 43% · -$786
├ Hide From New 19 · WR 53% · -$381
├ Recurring 13 · WR 36% · -$379
└ Crypto 19 · WR 56% · -$348
```

---

## 🎯 Strategy

| Principle | Detail |
|-----------|--------|
| **⏱️ End-cycle only** | Entries cluster in the last **30–90 seconds** of each candle, when signal is strongest and mispricing is most exploitable. |
| **🔁 High frequency, small size** | Many small trades vs. few large ones — variance smooths across a large sample. |
| **🌙 No overnight risk** | Every position resolves within **5** or **15** minutes. |
| **💰 Fee-aware** | Orders fire only when expected edge clears round-trip fees and spread. |

---

*Built for systematic, oracle-aligned execution on short-horizon prediction markets. Past performance does not guarantee future results.*

</details>

---

<details id="lang-zh">
<summary><strong>🇨🇳 中文</strong></summary>

# 🤖 Polymarket 交易机器人 — @SEI-DDEV

一款开源、策略驱动的 Polymarket 交易机器人，用于自动化预测市场交易。

📞 **联系方式：** 📊 Polymarket [@sei-ddev](https://polymarket.com/@sei-ddev)  ·  💬 Telegram [S.E.I](https://t.me/sei_dev)  ·  𝕏  Twitter  [S.E.I](https://x.com/ajee335)

[![Polymarket 交易机器人 — 点击在 YouTube 观看](https://github.com/user-attachments/assets/9b45cc5b-e451-4923-8f91-335f6d627bea)](https://www.youtube.com/watch?v=4C83CNM4bE8)

---

## 📊 概览

<img width="890" height="296" alt="Polymarket 资料 — 业绩概览" src="https://github.com/user-attachments/assets/b2561587-4d2e-4afa-a3d9-d042354fda6e" />

> ✨ **资料已更新** — 显示名称已更新，并通过系统化的周期末执行持续实现利润增长。

<img width="883" height="259" alt="Polymarket 资料 — 盈亏与活动统计" src="https://github.com/user-attachments/assets/43610899-6267-49d4-8701-852165906b1b" />

> 📈 **实时数据** — 数据与公开 Polymarket 资料同步并实时刷新。访问 [@sei-ddev](https://polymarket.com/@sei-ddev) 查看当前盈亏曲线、持仓及完整交易记录。

---

## ⚙️ 工作原理

| 步骤 | 说明 |
|------|------|
| **1. 采集** 📡 | 从链上 **Chainlink** 喂价获取实时 **BTC/USD** 与 **ETH/USD** — 与 Polymarket 结算使用的同一预言机。 |
| **2. 评分** 🧮 | 在每根 K 线最后几秒，将 CLOB 隐含概率与短期方向模型对比。 |
| **3. 狙击** 🎯 | 仅当优势超过手续费与滑点时买入 **涨** 或 **跌**；仓位随置信度与剩余时间缩放。 |
| **4. 结算** ✅ | 市场按 Chainlink 自动结算；机器人无缝进入下一周期。 |

### 机器人优势

<img width="807" height="334" alt="image" src="https://github.com/user-attachments/assets/bc7815c4-ae56-4a97-bcf0-107cbcd94aa7" />

机器人不会追高入场，也不依赖激进的动量买入，而是专注于在相对较低的价格建仓，从而形成更高效的风险收益结构。

> 较低的入场价提高潜在上行空间

> 交易失败时下行风险更小

---

## 👤 SEI-DDev

自 **2026 年 4 月** 起在 Polymarket 活跃（约 2 个月）

💰 **组合** $0 · **资金** $674 · **累计盈亏** +$1.7K  
📊 **5,046** 个市场 · **胜率** 72%（1862 胜 / 735 负）  
💵 **成交量** $154.1K  
🎯 **ROI/成交量** +1.1% · **ROI/市场** -100.0% · **每市场利润** $0  
📈 **夏普** 10.50 · **最大回撤** -$118 · 🥶 **29 连败**  
📐 **中位仓位** $30（占资金 4.4%）  
⏱ **每周 161 笔** · **每市场 1.6** 次入场（30 天）

**🗂 按盈亏排名的主要类别**

```
├ 涨跌 323 · 胜率 49% · -$5.4K
├ 加密货币价格 40 · 胜率 43% · -$786
├ 隐藏于最新 19 · 胜率 53% · -$381
├ 周期性 13 · 胜率 36% · -$379
└ 加密货币 19 · 胜率 56% · -$348
```

---

## 🎯 策略

| 原则 | 说明 |
|------|------|
| **⏱️ 仅周期末** | 入场集中在每根 K 线最后 **30–90 秒**，此时信号最强、定价偏差最易利用。 |
| **🔁 高频小仓** | 多笔小单而非少量大单 — 在大样本下平滑方差。 |
| **🌙 无隔夜风险** | 每笔持仓在 **5** 或 **15** 分钟内结算。 |
| **💰 考虑手续费** | 仅当预期优势覆盖往返手续费与价差时才下单。 |

---

*专为短期预测市场的系统化、与预言机对齐的执行而构建。过往表现不代表未来结果。*

</details>
