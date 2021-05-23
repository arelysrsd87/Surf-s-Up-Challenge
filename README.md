# Overview of the analysis
W. Avy, your business investor for the Surf n' Shack shop you would like to open in Oahu, Hawaii, asks if you can run some analytics on a data weather set he has from the same island.
## Purpose of the analysis
The purpose of the analysis is to provide W. Avy temperature trends before opening the surf shop. Specifically, temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
# Results
Below are the summary statistics for the June temperatures:

![June summary statistics](https://github.com/arelysrsd87/Surf-s-Up-Challenge/blob/main/Resources/June.png)

Below are the summary statistics for the December temperatures:

![December summary statistics](https://github.com/arelysrsd87/Surf-s-Up-Challenge/blob/main/Resources/December.png)

Three key diferences between June and December are:
- The number of samples was greater for the month of June (1700) than for the month od December (1715).
- June had a higher average temperature (75F) than  December (71F).
- Although the standard deviation is around 3 for both June and December, the month of December has a greater variability on the average temperature becuase the total number of measurements is lower than the month of June.
# Summary
- Because the June sample (1700) was longer than the December sample (1517), a random sampling of 1517 data points in the June sample was taken in order to match sample sizes. A paired t-test was performed and a p-value less than 0.05 was returned, so I can assume that there is a statistically significant difference between the average temperatures in June and December.
- Two additional queries that could be performed for the months of June and December could be: (1) to compare temperature results for these months using the same station, (2) identify the average temperature in June and December at all stations across all available years in the dataset.

