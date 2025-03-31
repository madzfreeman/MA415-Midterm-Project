# USDA NASS Strawberry Production: California vs. Florida (2020-2023)

## Executive Summary
This report analyzes strawberry production in California and Florida from 2020-2023 based on the USDA NASS data, comparing organic and conventional production methods. California dominates in production volume while Florida achieves higher conventional prices. Organic production represents a growing opportunity in both states despite limited organic production currently.

## Production Volume Comparison
California maintains a 3:1 production advantage over Florida, producing 42,700 units versus Florida's 14,100 units in 2023. This ratio is even more emphasized in organic production with a 6:1 ratio in 2021. California has increased production from 37,600 units in 2020 to 42,700 in 2023, while Florida grew from 11,700 to 14,100 units. Organic production remains limited in both states, with California dedicating 4,228 acres and Florida only 704 acres to organic strawberries.

## Market Performance
California's organic strawberry sales reached $156.6 million compared to Florida's $9.2 million, with total organic sales across the study period totaling $351.5 million. Conventional strawberries show opposite pricing patterns between states, with Florida consistently asking higher prices than California. In 2022, Florida achieved $169 per unit versus California's $108. Florida prices have been seen fluctuating more dramatically (from $139 in 2020 to $169 in 2022) than California's ($93 to $125).

## Chemical Usage and Processing
California employs significantly higher volumes of key fungicides: Captan (85,688 lbs vs. 27,931 lbs), Thiram (36,594 lbs vs. 25,468 lbs), and Cyprodinil (4,174 lbs vs. 1,536 lbs). The USDA data shows 11,251 units of organic strawberries were processed while no conventional strawberries were processed at all. This could mean either missing data or that organic and conventional strawberries are sold through different channels.

## State Comparisons
California benefits from mass production benefits, organic market leadership, and stable pricing, though it faces challenges with lower per-unit prices and higher chemical requirements. Florida leverages seasonal timing advantages for premium pricing and has achieved faster growth (20.5% vs. California's 13.6%), despite its smaller scale and limited organic presence.

## Methodology
This analysis used R with data from USDA NASS, California Department of Pesticide Regulation, and Florida Department of Agriculture. Analytical methods included time series decomposition, ratio analysis, and data visualization techniques.

## References
California Department of Pesticide Regulation for chemical usage record
Florida Department of Agriculture for state-specific production benchmarks
USDA NASS (National Agricultural Statistics Service) for production and acreage data

Grolemund, G., & Wickham, H. (2011). Dates and Times Made Easy with lubridate. Journal of Statistical Software, 40(3).
Applied for enabling accurate yearly comparisons between 2020-2023.

Healy, K. (2018). Data Visualization: A Practical Introduction. Princeton University Press.
Helped the development of comparative visualizations (California-Florida production disparities and organic vs. conventional price differences).

Van Buuren, S. (2018). Flexible Imputation of Missing Data (2nd ed.). Chapman & Hall.
Helped determine next steps for missing values when analyzing conventional strawberry processing where there were gaps in data reporting.

Venables, W. N., & Ripley, B. D. (2002). Modern Applied Statistics with S (4th ed.). Springer.
Calculating production ratios and significance in the 3:1 California-Florida volume relationship.

Wickham, H. (2014). Tidy Data. Journal of Statistical Software, 59(10).
Guided to find ways to structure production data when reshaping chemical usage records.

Wickham, H. (2016). ggplot2: Elegant Graphics for Data Analysis (2nd ed.). Springer-Verlag.
Helped with all visualizations, especially the time-series plots showing price fluctuations between 2020-2023.

Wickham, H. (2020). Grouping. In Advanced R (2nd ed.). Chapman & Hall.
Used in state and production type (organic vs. conventional) grouping.

Wickham, H., & Girlich, M. (2022). tidyr: Tidy Messy Data. R package version 1.2.0.
Used frequently for reshaping strawberry production data to create different visualization and analysis approaches throughout.

Wickham, H., François, R., Henry, L., & Müller, K. (2023). dplyr: A Grammar of Data Manipulation. R package version 1.1.0.
Package used throughout the entire strawberry production analysis.

Xie, Y. (2023). knitr: A General-Purpose Package for Dynamic Report Generation in R. R package version 1.43.
Enabled integration of code and analysis results in producing the final report.
