# 🎮 BelGames Financial Budgeting & Break-Even Analysis

## 📘 Project Summary

This project models the full-year financial plan of **BelGames**, a company that sells gaming consoles, digital games, and accessories. The analysis covers revenue forecasting, break-even calculations, monthly budgeting, cash collections, purchases, and net profitability. It helps decision-makers understand cost behaviors, profitability, and sustainability across product lines.

---

## 💼 Business Scenario

BelGames sells:
- **Consoles** at $420 per unit  
- **Digital Games** at $65 per unit  
- **Accessories** at $35 per unit  

The company increases unit sales by **5% each month**, and sells **80% for cash and 20% on credit**. Purchases are planned using a **50% ending inventory policy**, and **cash payments are spread 60% immediately and 40% in the following month**. 

---

## 📊 What Was Done

### 1. 📈 Revenue Forecasting
- Calculated expected sales growth each month
- Forecasted monthly and annual revenue by product type
- Applied different price points to units sold to compute total revenue

### 2. 💰 Cash Collections
- Separated cash vs credit sales (80/20 split)
- Included one-month lag for collecting credit sales
- Built a month-by-month cash collection schedule

### 3. 📦 Purchases Budget
- Applied 50% inventory policy for planning next month’s stock
- Used `TRUNC` to round purchase volumes to whole units
- Variable costs per unit:
  - Consoles: $240  
  - Digital Games: $18  
  - Accessories: $18

### 4. 🧾 Income Statement
- Computed Gross Profit = Revenue – Variable Costs
- Subtracted Fixed Monthly Costs ($45,000) to derive Net Profit
- Total Net Profit for the year: **$3.59 million**

### 5. 🧮 Break-Even Analysis
- Used weighted average contribution margin across all 3 products
- Formula: Break-even Units = Fixed Costs ÷ Weighted CM
- BelGames needs to sell **at least 480 units per year** to cover fixed costs

### 6. 💵 Cash Budget
- Integrated operating, investing, and financing activities:
  - Operations: inflow from customers, outflow to suppliers
  - Investing: R&D budgeted at **10% of revenue**
  - Financing: $100,000 raised through share issuance

---

## 🔍 Key Insights

| Metric | Value |
|--------|-------|
| **Annual Revenue** | $5.35 million |
| **Annual Variable Costs** | $1.71 million |
| **Annual Net Profit** | $3.59 million |
| **Break-even Units** | 480 units/year |
| **Cash from Ops** | ~$2.4 million |
| **Cash Ending Balance** | -$2.03 million (due to heavy investment) |

---

## 📂 Project Files

- [📄 Full Excel Financial Model](https://docs.google.com/spreadsheets/d/1rDly-vdYy8z8CE0uhJQAD0nSvSdlgwbD/edit?usp=sharing&ouid=101535771334112261438&rtpof=true&sd=true)
- [📘 Project Report PDF](https://drive.google.com/file/d/1xNFBDO6o4AdnuRbiZ_oL_CeqtfvtiwVB/view?usp=sharing)

---

## 📌 Lessons Learned

- How to integrate **cash budgeting, income statements, and breakeven** into one model
- Importance of inventory planning and credit terms in managing cash flows
- Weighted contribution margins are key to multi-product breakeven
- Investment decisions like R&D have strong impact on net cash balance

---

## 📫 Contact

**Author:** Great Ukachukwu 
**LinkedIn:** www.linkedin.com/in/great-ukachukwu-861b18192  
**GitHub Portfolio:** [github.com/Ug-tech](#)

---
