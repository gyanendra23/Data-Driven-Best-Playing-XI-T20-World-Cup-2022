# Data-Driven-Best-Playing-XI-T20-World-Cup-2022
📌 Project Overview

This project builds a data-driven Best XI for the T20 World Cup 2022 using match & player performance metrics — no bias, only numbers. I used role-specific benchmarks (batting, finishing, all-round, pace & spin bowling metrics) to identify the most impactful performers of the tournament and visualized the selection process in a Power BI dashboard.

The goal: show how analytics can support objective player selection and reveal high-impact players who may be overlooked by reputation alone.

🔎 Selection Criteria (Role-Specific Benchmarks)

Openers
Bat Avg > 30 ∧ SR > 140 ∧ Boundary% > 50 ∧ Played > 3 ∧ Position 1–2

Middle Order
Bat Avg > 40 ∧ SR > 125 ∧ Avg Balls Faced > 20 ∧ Position 3–5 ∧ Played > 3

Finishers
Bat Avg > 25 ∧ SR > 130 ∧ Avg Balls Faced > 12 ∧ Position ≥ 6 ∧ Played > 3

Spin All-Rounders
Batting: Bat Avg > 15 ∧ SR > 140
Bowling: Bowled > 2 innings ∧ Econ < 7 ∧ Bowling SR < 20 ∧ Position ≥ 7

Fast Bowlers
Bowled > 4 innings ∧ Econ < 7 ∧ Bowling SR < 16 ∧ Bowling Avg < 20

Benchmarks were chosen to reflect role expectations in high-impact T20 cricket (controlled economy for bowlers, strike rate + boundary contribution for batters, and minimum participation to avoid noise).

🧾 Final XI & Key Impact Stats

Openers

Jos Buttler — Avg 45.0 | SR 144.23 | Boundary% 57.14

Quinton de Kock — SR 161.04 | Boundary% 75.81

Middle Order

Virat Kohli — 296 Runs | Avg 98.67 | SR 136.41

Suryakumar Yadav — SR 189.68 | Avg Balls Faced 21.0

Glenn Phillips — 201 Runs | Avg 40.2 | SR 158.26

Finisher

Hardik Pandya — Avg 32.0 | SR 132.0 | (Also bowling/impact value)

Spin All-Rounders

Rashid Khan — 11 Wickets | SR 18.0 | Econ 6.42 | Bat SR 143.5

Mitchell Santner — 9 Wickets | Econ 6.45 | Bat SR 141.2

Fast Bowlers

Anrich Nortje — 11 Wickets | Bowling SR 9.55 | Econ 5.37

Lungi Ngidi — 10 Wickets | Bowling SR 12.0 | Econ 7.16

Haris Rauf — 8 Wickets | Bowling SR 18.0 | Econ 7.04

💡 Key Takeaway

Numbers don’t lie — objective, role-aware metrics highlight impact players beyond mere reputation. This approach helps selectors make transparent, defensible decisions and discover under-the-radar performers.

👨‍💻 Tools & Techniques

Power BI — interactive dashboard & visual storytelling (PBIX included)

CSV — cleaned tournament & player performance dataset

SQL / Pandas (optional) — filtering & preprocessing before visualization

Metrics used — average, strike rate, boundary %, balls faced, wickets, economy, bowling strike rate, etc.

📷 Dashboard Screenshots

The repository includes 6 screenshots showing the analysis, filters, role filters, selection logic, and final XI visuals:












(Ensure the PNG filenames in your repo match the links above.)

📂 Project Structure
📁 T20-Best-XI-Analytics
│── README.md
│── T20_BestXI.pbix
│── t20_wc_2022_players.csv
│── 🖼 T20_BestXI_1.png
│── 🖼 T20_BestXI_2.png
│── 🖼 T20_BestXI_3.png
│── 🖼 T20_BestXI_4.png
│── 🖼 T20_BestXI_5.png
│── 🖼 T20_BestXI_6.png

🚀 How to Use

Clone the repo:

git clone https://github.com/gyanendra23/T20-Best-XI-Analytics.git


Open T20_BestXI.pbix in Power BI Desktop to interact with the full dashboard.

Or open t20_wc_2022_players.csv in your preferred tool to reproduce and extend the analysis.

Filters available: role, team, innings played, minimum matches, strike rate / economy thresholds, and custom benchmark sliders.

🎯 Use Cases

🎯 Selectors / Team Analysts — objective shortlist for player selection

📈 Performance Analysts — find high-impact players for scouting & recruitment

🧑‍🎓 Students & Portfolio Builders — learn role-based metric design and storytelling

📰 Content Creators — create data-backed sports analysis articles

📜 License

MIT License — feel free to reuse with attribution.

👤 Author

Gyanendra Maurya
📧 gkmaurya2306@gmail.com

💻 GitHub: gyanendra23

🔗 LinkedIn: www.linkedin.com/in/gyanendra-maurya-494205348

