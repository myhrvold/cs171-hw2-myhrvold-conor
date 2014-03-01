<b> Contributors </b> – Head of project (project lead), but also perhaps curious users and contributors, as it shows an overall picture who has made the most contributions to the master branch (i.e. total number), displayed also in a time series with when those contributions  occurred, and additionally how many edits have been made (additions/deletions in green/red). This visualization is centered on seeing people.

Data: Commits (w/ contributors attached to them)

How to get w/ API:

Addressing burst of commits: This won't have an adverse effect since you only keep track of cumulative numbers.

<b> Commits Activity </b> – Head of project (project lead), as it shows the number of commits in a time series. This visualization is centered on seeing updates to the code (commits).

Data: Commits (w/ time attached to them)

How to get w/ API:

Addressing burst of commits: 

<b> Code Frequency </b> – Project user/contributor (including the lead), as this visualization is centered on seeing updates to the code (additions/deletions).

Data: Additions/Deletions (w/ time attached to them)

How to get w/ API:

Addressing burst of commits: This would show up as a spike in the chart. If this got to be an issue you could always normalize the additions/deletions by day so you would just look at the ratio.

<b> Punch card </b> – Project manager (possibly the lead), as this visualization shows updates to the code on a shorter time scale of a week. Someone who is in charge of the overall architecture might not need to see this viz, but certainly someone responsible for seeing that weekly deadlines are met, would be interested in this chart to see when most of the work is done during the day.

Data: Commits (w/ time and date attached to them)

How to get w/ API:

Addressing burst of commits: Here, this could be an actual issue since the circle representing the number could overwhelm the rest of the chart. So you'd want to use d3 to fix the maximum size the bubble is, and make sure you print the number (maybe with a symbol showing that the high number will not be to scale relative to the low numbers.)

<b> Pulse of a repository </b> – Project contributors, and anyone who wants to interface with the project, as this visualization is a dashboard of open, closed, and pending issues which are proposed/accepted/rejected changes to the code; not just cosmetic, but also features and functionality.

Data: A combination of commits, 

How to get w/ API:

Addressing burst of commits:
