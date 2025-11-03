# 🔄 Cross-Asset Momentum Contagion Research

## 🎯 Business Impact
**Machine Learning detection of shock propagation across asset classes** - identifying how movements in one asset class spill over to others in real-time for improved risk management.

## 📊 Research Highlights

### Strong Relationships Discovered
- **SPX ↔ NDX: 0.973** (Near-perfect tech-broad market comovement)
- **SPX ↔ VIX: -0.820** (Strong inverse - stocks down = volatility up)
- **DXY ↔ GC1: -0.410** (Dollar-Gold inverse relationship)

### Contagion Pathways Mapped
1. **Equity Shock** -> Volatility Spike -> Global Risk-Off
2. **Dollar Strength** -> Commodity Weakness -> Inflation Expectations  
3. **Oil Shock** -> Growth Concerns -> Equity Outflows

## 🛠️ Technical Implementation

### Data & Methodology
- **7 Asset Classes**: SPX, NDX, VIX, TLT, DXY, CL1, GC1
- **Analysis**: Rolling correlations, regime analysis, shock propagation
- **Framework**: Python, pandas, matplotlib, statsmodels

### Key Features
- **Real-time correlation monitoring**
- **Crisis period detection** 
- **Shock impact simulation**
- **Portfolio implications analysis**

## 🚀 Quick Start

```bash
# Install dependencies
pip install yfinance pandas matplotlib seaborn statsmodels

# Run analysis
python contagion_fixed.py