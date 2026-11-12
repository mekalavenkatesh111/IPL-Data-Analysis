# IPL Data Analysis (2008-2024)

Analysis of 1095 IPL matches using Python, Pandas and Matplotlib.

## What I did
- Cleaned the data: filled missing winners with "No result" and merged renamed teams (Delhi Daredevils → Delhi Capitals, Kings XI Punjab → Punjab Kings, etc.)
- Found the teams with the most wins
- Analysed toss decisions (field vs bat) and whether winning the toss helps
- Found the top Player of the Match award winners
- Counted matches per season

## Key findings
- Mumbai Indians won the most matches (144), then CSK (138) and KKR (131)
- Teams chose to field first in 704 matches and bat first in 391
- The toss winner won only about 51% of matches, so the toss gives a very small advantage
- AB de Villiers has the most Player of the Match awards (25)

## Tools used
Python, Pandas, Matplotlib, Google Colab

## How to run
1. Open `ipl_data_analysis.ipynb` in Google Colab
2. Upload `matches.csv` to Colab
3. Click Runtime → Run all
