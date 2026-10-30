# ⚽ FIFA World Cup Analysis Dashboard | Power BI

## 📌 Project Overview

This project explores FIFA World Cup history through an interactive Microsoft Power BI dashboard, covering 22 tournaments from 1930 to 2022.

The analysis focuses on tournament growth, host nation performance, France's 2018 World Cup victory, the four best-performing teams at Qatar 2022, and Nigeria's historical World Cup performance.

I combined historical tournament records, match-level statistics, FIFA rankings and host nation information, using Power BI and DAX to transform the data into meaningful football insights.

The dashboard contains five analytical pages:

1. Tournament Overview
2. Host Nation Analysis
3. France's Path to Glory – 2018
4. Qatar 2022 Top Four Analysis
5. Nigeria at the World Cup

## 🎯 Project Objectives

- Explore historical FIFA World Cup trends and tournament expansion.
- Examine whether hosting the World Cup is associated with tournament success.
- Analyse France's title-winning performance in 2018.
- Compare pre-tournament FIFA rankings with the final positions of the Qatar 2022 top four.
- Investigate Nigeria's World Cup performance, goals, results and tournament progression.
- Demonstrate the application of DAX, data modelling and interactive visualisations in sports analytics.

## 🛠️ Tools and Skills

**Microsoft Power BI**

- Power BI Desktop
- DAX measures and calculated columns
- Data modelling
- Interactive dashboard development
- KPI development
- Data visualisation
- Football and sports analytics

## 📊 Dashboard Overview

![FIFA World Cup Dashboard](Dashboard_Overview.png)

## 📈 Key Performance Indicators

### Historical World Cup Statistics

| KPI | Value |
|---|---:|
| Total World Cups | 22 |
| Total Matches Played | 964 |
| Total Goals Scored | Approximately 2,720 |
| Participating Countries | 81 |
| Host Nations | 17 |
| Average Goals per Tournament | 123.64 |
| Host Nation World Cup Wins | 6 |
| Host Nation Win Rate | 27.27% |

### France 2018 Performance

| KPI | Value |
|---|---:|
| Goals Scored | 14 |
| Goals Conceded | 6 |
| Matches Won | 6 |
| Goal Difference | +8 |

### Qatar 2022 Top Four

| KPI | Value |
|---|---:|
| Previous Champions Among the Top Four | 2 |
| Average Pre-Tournament FIFA Ranking | 10.25 |
| Best Pre-Tournament Ranking | 3 |
| Lowest-Ranked Top Four Team | 22 |

### Nigeria's World Cup Performance

| KPI | Value |
|---|---:|
| World Cup Appearances | 6 |
| Total Matches Played | 21 |
| Best Tournament Finish | Round of 16 |
| Knockout Stage Qualifications | 3 |

---

## 🔍 Dashboard Analysis and Key Findings

### Page 1: Tournament Overview

This page explores the historical development of the FIFA World Cup, including winners, participating nations, goals scored and tournament expansion.

**Key Findings**

- Brazil remains the most successful World Cup nation, with five titles.
- Total goals scored per tournament have generally increased as the competition expanded.
- The number of participating teams has grown significantly throughout World Cup history.
- The dataset includes 81 participating countries and 17 host nations.
- Hosting the competition does not guarantee a place among the best-performing teams.

**Football Insight**

World Cup success has historically been concentrated among a relatively small group of nations. However, tournament expansion has created more opportunities for countries to compete internationally.

### Page 2: Host Nation Analysis

This page examines whether playing at home provides a meaningful competitive advantage.

I developed a host performance scoring system:

| Score | Tournament Result |
|---|---|
| 5 | Winner |
| 4 | Runner-up |
| 3 | Third place |
| 2 | Fourth place |
| 1 | Outside the top four |

**Key Findings**

- Host nations won 6 of the 22 tournaments analysed.
- The host nation win rate was 27.27%.
- Most hosts did not finish among the top four.
- Qatar's 2022 host performance score was 1, below the historical average.
- Host country performances vary considerably across tournaments.

**Football Insight**

Home advantage may provide benefits such as crowd support and familiarity with local conditions, but it does not guarantee tournament success. Team quality, preparation and competitive strength remain important.

### Page 3: France's Path to Glory – 2018

This page examines France's successful 2018 World Cup campaign through match results, goals scored, goals conceded and comparisons with other World Cup champions.

**Key Findings**

- France scored 14 goals and conceded 6.
- The team recorded 6 wins and 1 draw.
- France remained unbeaten throughout the tournament.
- France scored four goals against Argentina in the Round of 16 and four against Croatia in the final.
- Its final goal difference was +8.

I also developed DAX measures to compare goals scored and conceded by World Cup champions across different tournaments.

**Football Insight**

France's 2018 campaign demonstrates the importance of consistency, attacking effectiveness and sufficient defensive stability in winning major tournaments.

**Important Analytical Decision**

My initial plan was to analyse Argentina's 2022 championship campaign. However, the available 2022 match dataset did not contain the complete home and away goal fields required for detailed match analysis.

Rather than make assumptions or present unreliable calculations, I redirected the analysis to France's 2018 campaign, for which complete match-level goal data was available.

This decision reflects the importance of data quality and adapting analytical questions to available evidence.

### Page 4: Qatar 2022 Top Four Analysis

This page compares the four best-performing countries at the Qatar 2022 World Cup using their pre-tournament FIFA rankings, final positions, knockout progression and previous World Cup titles.

| Country | Pre-Tournament Ranking | Final Position |
|---|---:|---:|
| Argentina | 3 | 1 |
| France | 4 | 2 |
| Croatia | 12 | 3 |
| Morocco | 22 | 4 |

**Key Findings**

- Argentina and France were among the highest-ranked teams before the tournament.
- Croatia finished third despite entering the tournament ranked 12th.
- Morocco achieved fourth place despite being ranked 22nd.
- Argentina and France had each won two World Cup titles before Qatar 2022.
- Croatia and Morocco had never won the competition before the tournament.

**Football Insight**

FIFA rankings provide useful information about team strength but do not fully determine tournament outcomes.

Morocco was a particularly notable example, reaching the semi-finals and finishing fourth despite entering the tournament ranked 22nd.

**Important Analytical Decision**

I originally intended to classify all 32 participating countries as overachievers or underperformers.

However, inconsistent team names and stage information across the available datasets made it difficult to calculate each team's furthest progression reliably.

I therefore refined the analysis to focus on the four highest-finishing teams, allowing a more accurate comparison using available ranking and final-position data.

### Page 5: Nigeria at the World Cup 🇳🇬

This page provides a dedicated analysis of Nigeria's World Cup history, including participation, match outcomes, goals scored, goals conceded and knockout-stage progression.

**Tournament Progression**

Nigeria reached the Round of 16 in:

- 1994
- 1998
- 2014

Nigeria exited at the group stage in:

- 2002
- 2010
- 2018

**Overall Match Record**

| Result | Matches |
|---|---:|
| Wins | 6 |
| Draws | 3 |
| Losses | 12 |
| Total | 21 |

**World Cup Win Rate by Tournament**

| Year | Win Rate |
|---|---:|
| 1994 | 50% |
| 1998 | 50% |
| 2002 | 0% |
| 2010 | 0% |
| 2014 | 25% |
| 2018 | 33% |

**Key Findings**

- Nigeria participated in six World Cups between 1994 and 2018.
- The country's best finish remains the Round of 16.
- Nigeria achieved its highest tournament win rates in 1994 and 1998.
- Nigeria scored seven goals and conceded four in the 1994 tournament.
- In 1998, Nigeria won two of its four matches.

**Football Insight**

Nigeria has demonstrated the ability to progress beyond the group stage but has struggled to consistently reach the later stages of the competition.

Its 1994 and 1998 performances provide useful historical reference points for investigating the factors associated with stronger tournament outcomes.

---

## 🎛️ Interactive Dashboard Features

The dashboard includes several features that allow users to explore the World Cup data dynamically.

**Year Filter**

Allows users to explore individual World Cup tournaments.

**Host Country Filter**

Allows comparisons of tournaments hosted by different countries.

**Interactive Visual Filtering**

Selecting a chart element updates related visualisations on the same page.

For example, selecting Nigeria's 1998 win-rate bar filters the corresponding match-results chart to show the team's results from that tournament.

These interactions allow users to move from broad historical trends to specific teams, years and performances.

## 🧮 DAX and Data Modelling

DAX played an important role in transforming raw World Cup records into meaningful performance indicators.

### Examples of DAX Measures

- Total World Cups
- Total Matches
- Total Goals
- Average Goals per Tournament
- Host Nation Wins
- Host Win Rate
- France Goals Scored and Conceded
- France Goal Difference
- World Cup Champion Goals Scored
- World Cup Champion Goals Conceded
- Previous World Cup Titles
- Nigeria Goals Scored and Conceded
- Nigeria Win Rate

### Examples of Calculated Columns

- Host Performance Score
- Host Won
- France Match Result
- France Match Order
- Top Four Team
- Final Position
- Knockout Stage Score
- Nigeria Match Result

These calculations helped classify individual matches, measure national team performance, compare tournament outcomes and develop dynamic KPIs.

## 💡 Recommendations and Opportunities for Further Analysis

**1. Improve Match-Level Data Coverage**

Future analysis should include richer match statistics such as possession, shots, expected goals, bookings and player-level performance.

**2. Combine FIFA Rankings with Tournament Outcomes**

Ranking information could be used alongside tournament results to evaluate which national teams outperform or underperform expectations.

**3. Investigate Host Advantage More Deeply**

Additional variables such as crowd support, climate, travel requirements and historical team strength could help explain differences in host nation performance.

**4. Improve Comparisons Between World Cup Champions**

Goals per match would provide a more comparable measure of attacking output because World Cup formats and match totals have changed over time.

**5. Investigate Nigeria's Tournament Consistency**

Further analysis could examine Nigeria's group-stage performances, defensive stability, squad characteristics and match outcomes against stronger opponents.

**6. Strengthen Data Preparation**

Standardising country and team names across datasets would make it easier to combine records and develop more comprehensive analyses.

**7. Extend the Dashboard**

Future versions could incorporate player-level statistics and additional World Cup tournaments, including the 2026 competition once complete and validated data becomes available.

## 🧠 Skills Demonstrated

Through this project, I demonstrated my ability to:

- Develop multi-page Power BI dashboards.
- Create DAX measures and calculated columns.
- Transform historical sports data into meaningful KPIs.
- Compare football performance across countries and tournaments.
- Work around data quality and completeness limitations.
- Design interactive visualisations.
- Communicate football insights through data storytelling.
- Translate analysis into practical research questions and recommendations.


## 🏁 Conclusion

This project demonstrates how Power BI can be used to explore football history and identify meaningful performance patterns.

Across 22 FIFA World Cups, the analysis highlights the growth of international football, the limited relationship between hosting and winning, the importance of tournament consistency, and the differences between pre-tournament expectations and actual results.

From France's unbeaten 2018 campaign to Morocco's remarkable performance in Qatar 2022 and Nigeria's historical World Cup journey, the dashboard presents several perspectives on international football performance.

Beyond the visualisations, the project strengthened my practical experience with DAX, data modelling, analytical decision-making, dashboard design and sports data storytelling.

## 👤 Author

**Olanipekun Joshua Tijesuni**

Data Analyst | Researcher | Data Analyst

Passionate about applying data analytics to football, agriculture and real-world decision-making.
