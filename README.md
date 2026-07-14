# Anglo-v-Glencore
A comparision between a pure-mining entity vs a a diversified resources player
# Anglo vs. Glencore: Liquidity & Margin Shock Stress Testing

### The Premise: Pure-Play Miner vs. Diversified Trader
This project explores the fundamental differences in liquidity management and crisis survival between two distinct resource sector business models. 

Why compare Anglo American and Glencore? Because their financial DNA is completely different during a market crash:
*   **The Pure-Mining Entity (Anglo American):** Operates with a traditional, unhedged cash flow model. Their liquidity needs are relatively straightforward and predictable, but they are highly exposed to direct commodity price drops. 
*   **The Diversified Resources Player (Glencore):** Operates a massive physical trading arm backed by derivatives. While this hedges their price risk, it exposes them to massive, sudden margin calls during extreme market volatility. They survive not just on cash, but on massive buffers of Readily Marketable Inventories (RMI).

This model stress-tests both structures to see how their "survival capacity" holds up when credit squeezes and margin calls hit simultaneously. 

I did a similar project focusing on Anglo Aemrican's 2025 liquidity and copper scenario analysis, as a result, in the Power BI dashboard for this specific project I decided to focus on Glencore when visualizing their liquidity position, but the market shock scenario applies to both, for Anglo American, you can find their liquidity forecast here - https://github.com/Harridinho-art/Anglo-13-week-liquidity-model

---

### Project Scope & Data
*   **13-Week Liquidity Models:** Baseline Q1 and Q2 cash flow forecasts built for both entities.
*   **Margin Shock Stress Test:** A modeled scenario simulating a 50% credit squeeze and severe derivative margin drain (specifically targeting Glencore's trading arm).
*   **Interactive War Room Dashboard:** A Power BI front-end designed to visualize the exact moment of maximum liquidity pain (Week 4) and the composition of their respective emergency safety nets.

---

### A Note on the Baseline Figures
The 13-week liquidity figures in this model are simulated proxies. Because granular, week-by-week internal treasury data is not publicly available, the baseline cash inflows and outflows were derived directly from the entities' 2025 Annual Reports. 

Specifically, the annual **Net Cash from Operating Activities** and **Capital Expenditures** were extracted from the Cash Flow Statements and divided by 52 to establish a linear weekly run-rate. While this provides a structurally sound baseline to execute the margin shock stress test, it is a linear proxy and does not account for intra-quarter working capital seasonality.




### Python Workspace & Modeling
Below are the behind-the-scenes views of the Python workspace used to draft the initial 13-week liquidity frameworks for Q1 & Q2. 

<img width="1902" height="1018" alt="Screenshot 2026-07-10 195637" src="https://github.com/user-attachments/assets/99fe66d3-22fb-4ce3-981a-9778e00e73b0" />



<img width="1902" height="1017" alt="Screenshot 2026-07-10 200216" src="https://github.com/user-attachments/assets/6d2d8471-85b4-4e10-9325-a9acdcbeae95" />


---

### Repository Contents
*   https://github.com/Harridinho-art/Anglo-v-Glencore/blob/main/Anglo%20v%20Glencore.pbix  - The final interactive Power BI dashboard.
<img width="1758" height="886" alt="Screenshot 2026-07-13 193821" src="https://github.com/user-attachments/assets/fdb20158-b1fc-4ce5-b249-bc38f47c33b7" />

*   [Treasury_Liquidity_Framework.xlsx](https://github.com/user-attachments/files/30000252/Treasury_Liquidity_Framework.xlsx) - The raw data sets, baseline models, and margin shock parameters.
*  [Anglo A-annual-report-full-2025.pdf](https://github.com/user-attachments/files/30000273/Anglo.A-annual-report-full-2025.pdf)
*    [GLEN-2025-Annual-Report.pdf](https://github.com/user-attachments/files/30000293/GLEN-2025-Annual-Report.pdf)
