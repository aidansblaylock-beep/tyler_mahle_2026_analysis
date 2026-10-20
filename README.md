# Decoding Tyler Mahle: A Mid-Season Pitch-Mix Optimization Study

## Overview
When veteran pitcher Tyler Mahle was traded to the Atlanta Braves at the trade deadline, his season experienced a dramatic turnaround. This project explores the data-driven mechanics behind that resurgence. Moving beyond traditional box scores, this study leverages Python, Statcast pitch-by-pitch tracking data, and a local SQLite database to analyze how a subtle adjustment by the Braves' coaching staff unlocked career-best efficiency.

##Data Sources & Tech Stack
Data Source: MLB Statcast API (extracted via pybaseball).

Languages & Tools: Python (Pandas, NumPy, Matplotlib, Seaborn), SQL (SQLite3).

Environment: Google Colab / Jupyter Notebook.

##Key Findings & Analytical Insights
1. The Core Mechanism: Significant Arsenal Shift
By splitting Mahle's season into his pre-trade stint (San Francisco Giants) and post-trade stint (Atlanta Braves), a clear change in pitch selection emerges:

The Splitter (FS): Mahle’s usage of his splitter jumped dramatically from 24.94% in San Francisco to 39.19% in Atlanta.

The Counter-Balance: To accommodate this heavy reliance on his splitter, he scaled back his cutter (FC) usage from 16.67% down to 11.00% and reduced slider usage.

2. The Whiff Rate Paradox: Volume Over Stuff
A superficial look might assume his splitter became a vastly nastier pitch in Atlanta. However, underlying metrics reveal a deeper truth:

Pre-Trade Splitter Whiff Rate: 26.61%

Post-Trade Splitter Whiff Rate: 27.35%

##The Takeaway: The whiff rate remained nearly identical (a marginal +0.74% change). The true catalyst for his turnaround wasn't an altered physical shape or velocity spike on the pitch; it was strategic volume. By increasing his splitter usage by nearly 15 percentage points, Mahle gave hitters a pitch they consistently struggled to square up much more frequently, keeping opponents off-balance through repetition and sequencing.

##3. Macro-Level Improvements
His average pitch velocity ticked up from 89.2 mph with the Giants to 90.0 mph with the Braves, suggesting a positive bump in adrenaline following the transition to a contender's pitching infrastructure.

##Visualizing the Evolution
Below is a comparison of his pitch mix percentages before and after the trade deadline:

<img width="984" height="584" alt="tyler_mahle_2026_pitch_mix_analysis_visualization" src="https://github.com/user-attachments/assets/e8d860f7-67b6-4131-8a16-1f44e7b9eea9" />
