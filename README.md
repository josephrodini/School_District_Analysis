
# PyCitySchools Challenge

This project constitutes the Module 4 Challenge for the Data Analytics and Visualization Boot Camp.

## Overview of the School District Analysis

### Purpose

This analysis was performed to help Maria determine performance of all the schools in a district across reading and math assessments. In particular, there were a number of specific analyses Maria requested: An overall district summary, top and bottom performing schools, grade-level analyses, results by school spending, results by school size, and results by school type. Further complicating matters, reading and math grades for Thomas High School ninth graders may have been altered. As such, two separate analyses were performed, with and without Thomas freshmen.

### Challenges to the Analysis

There was the aforementioned anomaly for the Thomas 9th graders that required an entire second set of analyses. In addition, data cleaning had to be performed as student name data contained unnecessary prefixes and suffixes that had to be removed.

## Results

### Differeces in metrics due to Thomas data

- School Summary

First of all, no data was more affected that the data for Thomas High School itself. See [the data with ninth grade included](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Thomas_Original.PNG) and [the data with ninth grade excluded](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Thomas_Updated.PNG). The percentages went from under 70% to over 90%. The anomalous data was really dragging the school's performance down.

- District Summary

The overall district summary hardly changed from the [original analysis](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/DistrictSummary_Original.PNG) to [the updated one](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/DistrictSummary_Updated.PNG), as one high school's ninth graders are just a tiny subset of the overall population.

- Top and bottom performing schools

While Thomas High School [was not present in the original top performing schools](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Top_Original.PNG), it [shot up to second place in the updated analyses](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Top_Updated.PNG). The bottom performing schools showed no changed between [original](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Bottom_Original.PNG) and [updated](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Bottom_Updated.PNG).

- Average math by grade

As expected, the only change in the average math passing rate per grade chart from [the original analysis](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/MathbyGrade_Original.PNG) to [the updated one](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/MathbyGrade_Updated.PNG) was the absence of scores from Thomas 9th graders.

- Average reading by grade

This same change was also present in the average reading passing rate per grade charts between [original](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/ReadingbyGrade_Original.PNG) and [updated](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/ReadingbyGrade_Updated.PNG).

- Scores by spending, scores by size, and scores by type

Results for scores by spending, scores by size, and scores by type hardly changed between the two analyses. In fact, when the data is rounded, the figures seem identical for all three measures between the two analyses. See [spending figures original](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Spending_Original.PNG) and [spending figures updated](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Spending_Updated.PNG), [size figures original](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Size_Original.PNG) and [size figures updated](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Size_Updated.PNG), and [type figures original](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Type_Original.PNG) and [type figures updated](https://github.com/josephrodini/School_District_Analysis/blob/main/Resources/Type_Updated.PNG).


### Limitations

We do not know if other data in the dataset is suspect like the data for Thomas ninth graders. Further inquiry is warranted.

## Summary

### Four Changes to the Analysis

After the reading and math scores for the ninth grade at Thomas High School were replaced with NaNs, we can see a few changes:
1. The overall pass rate for Thomas High dramatically increased.
2. Thomas High jumped up to second place in the district passing rankings.
3. The district summary hardly changed.
4. There were minute changes to the spending results, size results, and type results.

It was worth rerunning the analyses to see the overall changes.

