# Walker_County_AL_tornado_analysis-1995-2025-
Walker County, AL tornado analysis for the past 30 years. 

Project Objective
This project evaluates tornado risk in Walker County, Alabama to determine whether additional community storm shelters may be needed. The analysis examines tornado frequency, intensity, and casualty risk using historical storm data.

Business Question
Does Walker County, Alabama need additional or larger storm shelters?

Walker County currently has:
23 storm shelters
21 shelters with capacity of ~100 people
2 shelters with capacity of ~300 people

Walker County population:
≈ 64,000 residents

This means shelters can accommodate ~4% of the population.

Data Source

Tornado data was obtained from the
National Oceanic and Atmospheric Administration Storm Events Database.
Population data was obtained from US Census.
Shelter data was obtained from Walker County AL website.

Dataset includes:

Tornado events
Location
Tornado intensity (F / EF scale)
Injuries directly related to a tornado
Deaths directly related to a tornado
Event date and time
Time range analyzed:
1995–2025 (30 Years)

Tools Used:

Python
Pandas
Excel
Tableau
GitHub

Data Preparation:

The raw NOAA storm dataset was cleaned using Python.

Key steps included:
Filtering Alabama events
Filtering Walker County
Filtering tornado events
Changing column names
Standardizing F-scale and EF-scale values
Merging multiple tables
Creating tornado intensity variable
Calculating casualty metrics
Visualizations

Key Findings Between 1995 and 2025:

38 tornadoes occurred in Walker County

Tornado activity shows irregular but recurring patterns

Strong tornadoes (EF2+) occurred multiple times

Several tornadoes resulted in injuries or fatalities


Analysis also shows that:

Probability of injury or death increases with tornado intensity

Tornado events occur most frequently during spring severe weather season, namely the month of April with nearly half of tornadoes in 30 years occurring in this month.


Shelter Capacity Analysis:

Walker County shelter capacity is ≈ 2,700 people

Walker County population is ≈ 64,000 residents

Percentage of population that could be sheltered is only ≈ 4%


Conclusion:

Walker County experiences recurring tornado events, including severe storms capable of causing injuries and fatalities. Given the limited shelter capacity relative to the population, the analysis suggests that additional or expanded community storm shelters may improve public safety during severe weather events.
