# 🧮 Discounted Cash Flow (DCF) Valuation: Coca-Cola vs. Market Price  
*How I used Python to uncover a 38% valuation gap – perfect for breaking into finance roles.*

## 🔍 Executive Summary  
- **Project Goal**: Built a DCF model from scratch to value Coca-Cola (NYSE: KO).  
- **Key Finding**: Calculated intrinsic value of **$38.90/share** vs. $68.50 market price.  
- **Why It Matters**: Demonstrates core valuation skills for investment banking and equity research. 

## 🛠️ Technical Highlights  
```python
# Sample code snippet showing core calculation
terminal_value = (final_fcf * (1 + growth_rate)) / (wacc - growth_rate)
