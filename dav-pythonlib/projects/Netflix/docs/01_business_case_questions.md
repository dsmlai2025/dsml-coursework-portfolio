
### Gist of the project
- Delve into the dataset to guide strategic decision-making for content production and identify business growth opportunities across various countries
- Exploration of data, cleaning, transformation and followed by univariate and bivariate analysis
- Influence content strategy and marketing efforts for better targeted customer experience and improved market

### How did you get the data for this project?
- Public avaiable from Kaggle

### Netflix North Star Metric
- Total hours viewed (Hrs viewed per subscriber)

| Metric | Definition | Why It Matters |
|--------|------------|---------------|
| **Total Hours Viewed** | Sum of all watch time across platform | Core value: Entertainment delivered |
| **Hours/User/Month** | Avg viewing time per active subscriber | Engagement + retention proxy |
| **Completion Rate** | % of content watched to completion | Content quality indicator |

### Goal of the project
- Analyze and uncover actionable insights that guides Netflix business in strategic decision making regarding types of TV shows and movies to produce (Increase Watch Time)
- Identify business opportunities for growth in different countries (Increase # of subscribers)
- Retain existing subscription base by tailoring content to their preferences

### General questions that you think would help answer the goals of the project
- Understand the dataset columns
- High level questions
- Which format maximizes hrs viewed?
- Release patterns correlate with binge watching
- What movie genre drives maximum watch time
- Movie trends over years
- Favorite actors/directors
- Time to launch movie/tv show
- Type of content preference in different countries
- Distribution of content type

### How did you approach the project?
- Load the dataset
- Preprocessing
- Initial exploratory analysis
- Visualization
- Insights

### What challenges did you face?
- Nested values in columns
- How did you deal? unnesting them using explode or pivot/stack
- Data inconsistency - missing values, duplicate records
- Why deal with missing records? It can distort analysis and lead to inaccurate conclusions
- ML algos cannot deal with missing values and degrade their model performance
- duplicate records lead to skewed results and waste computation resources

### How techniques did you use?
- Categorical col: Mode.
- Mode is used when categorical variable has dominant category
- Numerical col: Mean/Median
- Mean is used on symmetrical distributed dataset. Median is used on skewed dataset
- DateTime: Forward fill, Backward fill
- Pandas: fillna(), SimpleImputer Class
- String functions - split, contains, replace, bins etc
- Univariate, BiVariate, Multivariate analysis
