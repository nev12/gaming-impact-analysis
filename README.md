# EXPLAROTARY ANALYSIS OF GAMING IMPACT ON WORK PERFORMANCE

## 1. Problem Statement and Key Questions

This analysis explores how daily gaming habits affect work or academic performance. Specifically, it aims to answer:
- Why does gaming negatively impact some individuals?
- Are certain types of games more likely to be associated with negative outcomes?
- How can gaming habits be adjusted to reduce negative impacts and promote a more balanced approach?

## 2. Dataset Description

For this project the data that is used is 'Gaming Hours vs Academia & Work Performance' from Kaggle :
https://www.kaggle.com/datasets/prince7489/gaming-hours-vs-academic-and-work-performance

This dataset contains various parameters related to the type of impact gaming has on work performance. It includes features that can be evaluated such as:
- Game Type the user is mostly playing
- Daily Gaming hours
- Sleep hours
- Productivity and Performance scores

This data allows us to explore how different gaming patterns and game types may influence overall performance, and to identify behaviors associated with positive, negative and neutral impact.

## 3. Analysis / Approach

Methodes that were used for analysis of the data are:

1. **Data Cleaning** - for data cleaning, even though the data was already pretty clean, some things still had to be done, like:
   - removing duplicates
   - fixing inonsistent values
   - standardizing text
   - handling missing data
    
2. **Exploratory Data Analysis (EDA)** - uncoverring patterns, relationships and key insights by using:
   - filtering
   - aggregate functions
   - groupby
   - subsets
  
3. **Visualizations** - for better understanding what was found with EDA with the help of:
   - pies
   - bars
   - subsets of two pies so that they can be viewed at the same time
   - plots

## 4. Visuals

With the folowing pie charts, we can clearly see the percentage of people playing different game types from each impact group:

![percentage of games played by each group](https://github.com/nev12/gaming-impact-analysis/blob/main/images/game_types.png)

However the time people spend playing Strategy games is shorter than what people spend on Action games:

![action vs strategy games](https://github.com/nev12/gaming-impact-analysis/blob/main/images/action_vs_strategy.png)


## 5. Conclusion

- **Performance Impact Distribution:** Most people stayed neutral, while there is not big of a difference between the amount of negative and positive impact groups.

- **Playing Hours:** After taking a closer look into each group, one parameter always stands out, and that is gaming hours.
Negative group has even up to 4x more daily gaming hours than the positive group.

- **Game Type Preferences:** Types of games played by these groups differ, positive group mostly plays Strategy games, while the negative one usually prefers Action games.
However, the main difference is again the time spent playing. Most people play Action games for longer than Strategy games.
Since 16.5% of positive group still plays Action games, it shows that they are not necessarily bad.

- **Key Takeaway:** Gaming can have a positive impact if played in moderation. Excessive daily gaming, rather than the type of game,
is the main factor associated with negative performance. Adjusting gaming habits to moderate levels can help reduce negative effects and promote a more balanced lifestyle.
