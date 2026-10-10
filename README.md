
# 📞 Call Center Performance Dashboard — Power BI

![Dashboard Preview](screenshots/02_overview.png)

## 📌 Project Overview
An end-to-end Power BI analytics solution built to monitor and improve 
call center operations across multiple projects and agents. The dashboard 
tracks real-time KPIs, daily trends, agent performance, and forecast 
accuracy — enabling data-driven staffing and coaching decisions.

---

## 🎯 Key KPIs Tracked
| Metric | Description |
|---|---|
| Service Level | % of calls answered within threshold |
| Handle Rate | % of offered calls successfully handled |
| Abandoned Ratio | % of callers who hung up before being served |
| ASA | Average Speed of Answer (seconds) |
| Accuracy Ratio | Quality/resolution rate of handled calls |

---

## 📊 Dashboard Pages
| Page | Purpose |
|---|---|
| 🏠 Home | Navigation hub |
| 📈 Overview | High-level KPIs, project comparison, top agents |
| 📅 Day Over Day | Period-over-period trend analysis |
| 👤 Agent Details | Individual agent performance drill-down |
| 📉 Abandon Analysis | Abandoned call patterns by day |
| 🔮 Forecasting | Forecasted vs. actual call volume gap |
| 🎯 Target Tracking | Live progress toward operational target |

---

## ⚙️ Power BI Features Used
- **Custom DAX Measures** — Period-over-period growth rates, dynamic KPIs
- **Decomposition Tree** — Root cause analysis for call volume
- **Dynamic Titles** — Context-aware visuals that update with slicers
- **Top N Ranking** — Identifies top-performing agents automatically
- **Combo Charts** — Overlays volume and quality metrics
- **Gauge Visual** — Real-time target achievement indicator
- **Navigation Buttons** — Custom home page for seamless UX
- **Slicers** — Filter by Day, Month, and Project across all pages

---

## 🛠️ Data Preparation
- Cleaned and structured raw call log data
- Built a custom Date Table for time intelligence functions
- Created relationships between fact and dimension tables
- Applied data transformations in Power Query (M language)

---

## 💡 Business Recommendations
1. **Proactive staffing** — High abandonment clusters on specific days;
   schedule additional agents before the spike, not after.
2. **Targeted coaching** — Use agent drill-downs to identify who has
   high ASA or low handle rates and coach individually.
3. **Forecast recalibration** — Where actual calls consistently exceed
   forecast, tighten planning assumptions or add a buffer capacity.

---

## 📸 Screenshots
### Overview
![Overview](screenshots/02_overview.png)

### Day Over Day
![Day Over Day](screenshots/03_day_over_day.png)

### Agent Details
![Agent Details](screenshots/04_agent_details.png)

---

## 🚀 How to Use
1. Download `dashboard/sallah.pbix`
2. Open with **Power BI Desktop** (free download from Microsoft)
3. If prompted, reconnect the data source to your own dataset
4. Use the slicers to filter by month, day, or project

---

## 👤 Author
**[Your Name]**  
[LinkedIn Profile URL] | [Email]
