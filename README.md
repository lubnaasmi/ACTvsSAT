
The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for each test):
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry.

### Problem Statement

- Finding out the correlation between ACT and SAT participation rate 2017.

---

### Datasets




* [`act_2017.csv`](./data/act_2017.csv): 2017 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))

* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state


### Data Dictionary


|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|string|SAT2017,ACT2017  |State from which ACT & SAT datas was collected|
|sat_part|float|SAT2017|Participation rate in SAT 2017|
|sat_math|integer|SAT2017|Average math mark scored in SAT 2017|
|sat_total|integer|SAT2017|Average total mark scored in SAT 2017|
|sat_erw|integer|SAT2017|Average Evidence BAsed read and write mark scored in SAT 2017|
|act_part|float|ACT2017|Participation rate in ACT 2017|
|act_eng|float|ACT2017|Average english mark scored in ACT 2017|
|act_math|float|ACT2017|Average math mark scored in ACT 2017|
|act_read|float|ACT2017|Average Evidence BAsed read and write mark scored in ACT 2017|
|act_sci|float|ACT2017|Average Science scored in ACT 2017|
|act_comp|float|ACT2017|Average composite scored in ACT 2017|

### Conclusions and Recommendations

## Conclusions:

For the year 2017: 
 - more states prefered ACT over SAT. 
 - 17 states with max 100% participation in ACT. 
 - 4 states with max 100% participation in SAT. 
 - The minimum participation rate was 8% in ACT and 2% in SAT.

## Recommendations

- I recommend that the authorities should focus to raise SAT participation rates.
- Some states have low participation rate in both ACT and SAT,authorities should focus on these states to make 100% participation.
- Authorities should focus more on students scored low to increse total score.
