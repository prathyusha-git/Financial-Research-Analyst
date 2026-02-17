# 📊 NVIDIA FY2025 Financial Research & Data Verification

## 🔍 Research Question
**What drove NVIDIA’s explosive FY2025 performance, and is it financially sustainable?**

---

## 🏢 Company
NVIDIA Corporation (NVDA)

## 👩‍💻 Analyst
Prathyusha

## 📅 Date
16 Feb 2026

---

## 🎯 Objective

This project demonstrates structured financial research using **primary SEC filings only** (Form 10-K and Form 10-Q).

Goals:
- Extract financial data directly from audited and unaudited filings
- Validate fiscal year alignment
- Perform structured financial extraction
- Apply ratio-based analytical evaluation
- Document methodology for reproducibility
- Evaluate financial sustainability

✅ No third-party aggregation platforms (Yahoo Finance, Bloomberg, etc.) were used.

---

## 📚 Data Sources

| Filing | Period | Purpose | Status |
|--------|--------|----------|--------|
| Form 10-K | Fiscal Year Ended Jan 26, 2025 | Full-year baseline | Audited |
| Form 10-Q | Quarter Ended Oct 27, 2024 | Momentum & run-rate validation | Unaudited |

All filings sourced directly from **SEC EDGAR**.

---

## 🧮 Key Financial Highlights (FY2025 – 10-K)

- Revenue: **$130.5B**
- Gross Profit: **$97.9B**
- Operating Income: **$81.5B**
- Net Income: **$72.9B**
- Gross Margin: **75.0%**
- Operating Margin: **62.4%**
- Net Margin: **55.8%**

---

## 🚀 What Drove FY2025 Explosion?

### 1️⃣ Revenue Growth

Revenue more than doubled YoY.

\[
Revenue\ Growth = \frac{FY25 - FY24}{FY24} = 114\%
\]

### 2️⃣ AI Segment Concentration

- Compute & Networking Revenue: **$116.2B**
- Total Revenue: **$130.5B**

\[
Segment\ Share = \frac{116.2}{130.5} \approx 89\%
\]

👉 AI/Data Center demand was the dominant driver.

---

### 3️⃣ Margin Expansion

\[
Gross\ Margin = \frac{Gross\ Profit}{Revenue} = 75\%
\]

High ASP AI accelerators significantly expanded margins.

---

### 4️⃣ Operating Leverage

\[
Operating\ Margin = \frac{Operating\ Income}{Revenue} = 62.4\%
\]

Revenue doubled while operating expenses grew slower — confirming scalability.

---

## 📊 DuPont ROE Decomposition

\[
ROE = Net\ Margin \times Asset\ Turnover \times Equity\ Multiplier
\]

- Net Margin: **55.8%**
- Asset Turnover: **1.17**
- Equity Multiplier: **1.41**

\[
ROE \approx 0.558 \times 1.17 \times 1.41 \approx 92\%
\]

🔎 ROE is profitability-driven, not leverage-driven.

---

## 💰 Cash Flow Sustainability (10-Q – 9 Months)

- Operating Cash Flow: **$47.0B**
- CapEx: **$2.8B**

\[
Free\ Cash\ Flow = OCF - CapEx \approx 44B
\]

\[
FCF\ Margin = \frac{FCF}{Revenue} \approx 48.5\%
\]

Strong earnings quality and cash backing.

---

## ⚖ Financial Sustainability Assessment

| Pillar | Status |
|--------|--------|
| Profitability | Strong |
| Cash Flow | Strong |
| Leverage | Low Risk |
| Revenue Diversification | Moderate Risk |

---

## ⚠ Key Risk Factors

- 89% revenue concentration in AI Compute
- AI demand cyclicality
- Export controls & regulatory exposure
- Competitive pressure in accelerators

---

## 📌 Conclusion

NVIDIA’s FY2025 performance was driven primarily by:
- AI/Data Center demand
- High ASP GPU acceleration
- Margin expansion
- Operating leverage
- Strong capital efficiency

Financial sustainability appears strong due to:
- High free cash flow conversion
- Low leverage
- Profitability-led ROE

However, growth remains strategically concentrated in the AI demand cycle.

---

## 🛠 Methodology

- All data extracted manually from:
  - Consolidated Statements of Income
  - Consolidated Balance Sheets
  - Segment Reporting Notes
  - Fiscal Year Disclosure Section
- Cross-verified fiscal year alignment between 10-K and 10-Q
- All numbers reported in millions USD unless stated otherwise

---

## 📁 Project Structure

```text
📂 NVIDIA-Financial-Research
 ├── NVIDIA_FY2025_Financial_Research_Memo.pdf
 ├── 10K_FY2025.pdf
 ├── 10Q_Q3_FY2025.pdf
 └── README.md
