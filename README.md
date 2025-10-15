# MANCHESTER UNITED PLAYER PERFORMANCE ANALYSIS 2024-25 ⚽️
This project provides an in-depth exploratory data analysis (EDA) of Manchester United players' performance using key traditional and advanced football metrics for the 2024-25 season. The analysis aims to identify top performers in terms of goal contributions, assess statistical distributions, and explore correlations between different performance metrics.

## 💾 Dataset Overview
The dataset (man utd data.xlsx) contains various performance statistics for 31 Manchester United players.

Key Columns:
Column	Description
Player	The name of the player.
Positon	The primary playing position (e.g., CAM, RW, ST, CB).
Appearances	Total number of matches played.
Minutes	Total minutes played.
Goals	Total goals scored.
Assist	Total assists made.
Sh90	Shots per 90 minutes.
KP90	Key Passes per 90 minutes.
xG	Expected Goals (cumulative).
xA	Expected Assists (cumulative).
xG90	Expected Goals per 90 minutes.
xA90	Expected Assists per 90 minutes.
G+A	Total Goals + Assists (calculated).
xG+xA	Total Expected Goals + Expected Assists (calculated).

📊 Analysis Highlights
1. Top Performers by Goals and Assists
The analysis confirms the primary contributors to the team's offense:

Top 5 Goalscorers: Bruno Fernandes and Amad Diallo Traore lead the team with 8 goals each.

Top 5 Assist Providers: Bruno Fernandes is the clear creative leader with 10 assists.

2. Overall Production Ranking
By calculating and ranking players by their combined Goals + Assists (G+A) and Expected Goals + Expected Assists (xG+xA), we can assess both actual and expected offensive output.

Top 10 Players by Total Goals + Assists (G+A)
The top 3 actual producers are:

Bruno Fernandes (18) 🥇

Amad Diallo Traore (14) 🥈

Alejandro Garnacho (8) 🥉

Top 10 Players by xG + xA (Expected Production)
The top 3 expected producers are:

Bruno Fernandes (20.12) 🥇

Amad Diallo Traore (9.51) 🥈

Alejandro Garnacho (9.44) 🥉

3. Positional and Performance Metrics
Goals Distribution by Position
A box plot visualizes goal-scoring distribution across different positions:

The RW (Right Winger) position shows the highest median goals, primarily driven by Amad Diallo Traore.

The CAM (Attacking Midfielder) position shows the highest maximum goals, attributed to Bruno Fernandes.

Strikers (ST) have a wide range of goal production, with Rasmus Højlund and Joshua Zirkzee as the main contributors in the sample.

Appearances vs. Minutes Played
A scatter plot illustrates the relationship between appearances and minutes, with color coding by position:

This plot effectively identifies players who are consistent starters (high minutes, high appearances) like André Onana and Noussair Mazraoui, versus those who are fringe players or have been injured (low minutes).

Notably, Bruno Fernandes and André Onana are the only two players exceeding 3000 minutes played.

Performance vs. Expectation (Goals vs. xG)
A scatter plot of Goals vs. xG, with the size of the bubble representing minutes played, helps identify over- and under-performers in front of goal:

Over-performers (Goals > xG): Players above the red Goal = xG line, such as Amad Diallo Traore and Lisandro Martínez, are finishing their chances at a rate higher than expected.

Under-performers (Goals < xG): Players below the red line, notably Alejandro Garnacho and Rasmus Højlund, have converted fewer chances than statistically expected based on the quality of their shots.

4. Correlation of Rate Stats
A correlation heatmap of key "per 90 minutes" (rate) statistics reveals strong relationships:

Metric 1	Metric 2	Correlation	Interpretation
Sh90	xG90	0.99	An extremely strong positive correlation, indicating that players who take more shots per 90 minutes are also getting higher quality chances (higher xG per 90).
KP90	xA90	0.99	An extremely strong positive correlation, meaning players who play more key passes per 90 minutes are creating assists at a higher expected rate (higher xA per 90).
Sh90	KP90	0.78	A strong positive correlation, suggesting that players who are heavily involved in the shooting phase also tend to be highly involved in the chance creation phase.

## 🛠️ Technologies Used
Python: The core language for data analysis.

Pandas: For data loading, manipulation, and cleaning.

NumPy: For numerical operations.

Matplotlib & Seaborn: For data visualization.

Jupyter Notebook: For interactive analysis and documentation.


