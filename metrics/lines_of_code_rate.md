Question: How many lines of code are written in a project over the course of time?

## Description
Shows a graph representation of how many lines of code are committed inside a project given a time parameter.

## Objectives
Gives funders insight on not just the activity of an open source project but how much is actually being contributed to it. This will help them make a decision on if the project is worthwhile to begin or continue funding.

## Implementation
Need to get data from Github showing lines of code committed from a start date and end date, then show a graph visualization of this information to show a curve of upward trend, downward trend, or steady trend.

## Filters
Start Date
End Date
Select specific sections of a project

## Visualizations
Show graph representation of metrics gathered. Time on X axis and lines of code commmitted on the Y axis.

## Tools Providing Metric
Github API specifically committs,

## Data Collecting Strategies
Count number of lines of code per each commit in specific section or whole project.

## References
https://developer.github.com/v3/repos/commits/
