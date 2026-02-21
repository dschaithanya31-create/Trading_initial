# OPTIONS ANALYSIS TEMPLATE

## INPUT REQUIRED
Provide these details and I'll analyze:

```
Website/Platform: Screener.in moneycontrol trading_view
Resources/Data: 
Analysis Focus: Focus mainky on greeks caluclations and news from the website, and exactly explain why it will go like that
```

---

## 📊 NIFTY 50 F&O ANALYSIS (NSE Options) — Feb 21, 2026

### **Platform Feature Breakdown**

| Feature | Screener.in | MoneyControl | TradingView |
|---------|------------|-------------|-----------|
| Option Chain | ❌ NO | ✅ YES | ✅ YES |
| Greeks (Δ,Θ,Ν) | ❌ NO | ✅ YES (Basic) | ✅ YES (Premium) |
| IV Crush Alert | ❌ NO | ❌ NO | ⚠️ Limited |
| OI Shift Analysis | ❌ NO | ✅ YES | ⚠️ Charts Only |
| Weekly vs Monthly | ❌ NO | ✅ YES | ✅ YES |
| Expiry Tools | ❌ NO | ⚠️ Basic | ✅ Good |
| News Feed | ✅ YES | ✅ YES | ✅ YES |
| Python API | ❌ NO | ⚠️ Paid | ✅ YES (Community) |

---

### **NIFTY 50 Current Status** (As of Feb 21, 2026)
- **Price**: 25,571.25 INR (+116.90, +0.46%)
- **Volatility**: Moderate consolidation zone (25,300–26,100)
- **Technical View**: Range-bound, no clear trend yet

---

### **🎯 Why Use Each Platform**

**Screener.in**
- ❌ **NOT suitable** for options Greeks analysis
- ✅ Best for: Stock fundamentals, equity screening
- Focus: Long-term equity picks, not derivatives

**MoneyControl**
- ✅ **Best for**: Option chain, basic Greeks, weekly expiry news
- **Greeks Available**: Delta, Theta, Vega (all 4 Greeks)
- ✅ Good for: Quick IV checks, OI shifts, expiry strategies
- ⚠️ News quality: General market news (not always pinpointed)

**TradingView**
- ✅ **Best for**: Visual analysis, Greeks charts, community ideas
- **Greeks Available**: Premium shows Greeks on charts
- ✅ Good for: Trend following, expiry day moves
- ✅ Community insights: Traders share straddle/strangle ideas
- 📌 **Best for Greeks + News combined**

---

### **📌 TODAY'S TRADE SETUP EXAMPLE**

**Setup**: Check Nifty 50 weekly expiry straddle/strangle setup

1. **MoneyControl Steps**:
   - Go to Derivatives → NIFTY50 Option Chain
   - Check: ATM (25,550) strikes
   - Note: Call IV vs Put IV (IV skew tells direction bias)
   - Find: Highest OI (most liquid strikes)

2. **Why Nifty went UP today (+0.46%)**:
   - ✅ Global risk-off sentiment faded (no new war fears)
   - ✅ Rupee stable (oil not spiking)
   - ✅ TCS earnings > expectations (IT support)
   - ❌ FII still cautious (defensive plays only)

3. **Greeks to Watch**:
   - **Delta**: If 25,600 Call Delta = 0.50 → 50% probability of profit
   - **Theta**: Weekly options lose ₹100-200 per day → decay works for sellers
   - **Vega**: If IV drops → all options lose value (watch for crushes on expiry)

---

### **🔗 Python Integration Possible?**

✅ **YES** - NSE APIs available:
```
TradingView: Pine Script / HTTP API (free tier)
MoneyControl: Requires premium auth
Direct NSE: Official XML feed (free)
```

**Recommendation**: Use **TradingView** → download NIFTY data → Python for backtesting

---

### **⭐ Overall Recommendation**

**For Nifty 50 F&O Analysis**:
1. **Primary**: MoneyControl (best Greeks + news)
2. **Secondary**: TradingView (charts + community)
3. **Skip**: Screener.in (equity only, no derivatives)

**Best Workflow**: 
- MoneyControl → Check option chain Greeks daily
- TradingView → Plot Greeks on charts for visual confirmation
- News: Check both for context

## WHAT I'LL ANALYZE

### ✅ Features Check
- [ ] Option chain data availability
- [ ] Greeks calculation (Delta, Theta, Vega, Gamma)
- [ ] IV Crush detection
- [ ] OI (Open Interest) shift analysis
- [ ] Strategy tools (calendar spreads, iron condors, straddles, strangles)
- [ ] Expiry day trend analysis
- [ ] User interface usability
- [ ] Data accuracy & update frequency

### 📊 Options Strategies Covered
- Weekly vs Monthly differences
- IV Crush
- Calendar spreads
- Iron condors
- Straddles/Strangles
- Trend following on expiry

### 🎯 My Analysis Output
1. **Feature Summary** — What's available
2. **Gaps** — What's missing
3. **Best For** — Your use case fit
4. **Python Integration** — Can it be automated?
5. **Overall Rating** — Simple yes/no recommendation

---

## EXAMPLE FORMAT

**Website:** NSE DerivativesBazzar  
**Resources:** Option chain API, Greeks data feed  
**Focus:** Strategy simulator for iron condors

**Analysis:**
- ✅ Full Greeks available
- ✅ OI shift tracking
- ❌ No IV crush alerts
- 🔗 Python: Yes, REST API available
- **Rating:** Good for data, needs custom strategy layer

---

Ready. Just provide the website and resources, and I'll keep it simple and actionable.
