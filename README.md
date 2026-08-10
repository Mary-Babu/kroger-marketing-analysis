# Kroger Marketing Spend Analysis

Python · pandas · Matplotlib · Seaborn · EDA

End-to-end exploratory data analysis on Kroger's real marketing dataset — uncovering spend patterns across tactics, platforms, campaigns, and time.

## Business Problem

Kroger's marketing team needed to understand how spend was actually distributed across tactics, platforms, and campaigns, and whether that allocation still made sense or was just "what we did last year."

## Questions I Asked

- Which tactics and platforms are absorbing the most budget, and which the least?
- Is the gap between top and bottom tactics a deliberate strategy or drift?
- Which specific campaigns anchor the spend, and does that match their scale?
- How does spend move month to month, are there seasonal patterns worth planning around?

## Key Findings

- Digital Media Offsite was the highest-spend tactic at $3,033,685 — over 12,000x more than the lowest tactic (Traditional/Outdoor at $250)
- Top campaign: Iced Platform Launch at $1,077,500
- Lowest campaign: Clamato Lent at $2,700
- Budget is heavily concentrated in digital channels — traditional media plays a minimal role

## Insight

Digital Media Offsite absorbed $3,033,685, over 12,000x the lowest tactic (Traditional/Outdoor at $250). That's not a rounding difference, it means the budget has consolidated almost entirely into one tactic. This dataset only tracks spend, not conversions, so the honest read is: we know where the money's concentrated, not yet whether that concentration is earning its keep.

## Recommendation

Before renewing next year's budget at the same split, run a performance review specifically on Digital Media Offsite, since a 90%+ share in one tactic means results are effectively a bet on that one channel holding up. If performance data isn't tracked at this granularity yet, that's the next dataset to build.

## Impact

If Digital Media Offsite underperforms even slightly, the whole budget's ROI moves with it, there's no diversification to cushion the dip. If it's genuinely outperforming, the $250 Traditional/Outdoor line may be too small to be worth keeping at all, freeing that budget to test a second channel.

## What This Project Does

- Data Cleaning: Removed $ symbols, standardized dates, extracted month periods
- Tactic Analysis: Ranked all marketing tactics by total spend
- Platform Analysis: Identified highest and lowest spend platforms
- Campaign Analysis: Surfaced top and bottom performing campaigns
- Trend Analysis: Plotted monthly spend trends over time

## Tools Used

- Python — core analysis
- pandas — data cleaning and aggregation
- Matplotlib and Seaborn — bar charts and trend line visualizations
- Jupyter Notebook — development environment

## Skills Demonstrated

Exploratory Data Analysis · Data Cleaning · Python · pandas · Seaborn · Matplotlib · Data Visualization · Statistical Analysis · Business Recommendations

## Visualizations

### Tactic Analysis
<img width="946" height="657" alt="Tactic analysis" src="https://github.com/user-attachments/assets/7f968c5e-b1a4-4fa7-beb6-4e7064e6d86d" />

### Platform Analysis
<img width="1006" height="655" alt="Platform Analysis" src="https://github.com/user-attachments/assets/3f7db6d6-727d-4800-8f0e-21d64d27dc9c" />

### Campaign Analysis
<img width="818" height="550" alt="Campaign Analysis" src="https://github.com/user-attachments/assets/e141c678-c312-4de6-b69c-5888a0926fa6" />

### Monthly Trend Analysis
<img width="785" height="433" alt="Monthly Trend Analysis" src="https://github.com/user-attachments/assets/257945b2-0d05-4794-a636-b0f3e3c8ebbc" />
