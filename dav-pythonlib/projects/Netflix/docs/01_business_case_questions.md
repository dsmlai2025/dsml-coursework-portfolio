
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
- Movie & TV show trends over years
- Seasonality of content
- Favorite actors/directors
- Actor director combinations
- Time to launch movie/tv show
- Type of content preference in different countries
- Distribution of content type by region
- Content duration, rating, genre preferences in different regions
- 

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

### What techniques did you use?
- Categorical col: Mode.
- Mode is used when categorical variable has dominant category
- Numerical col: Mean/Median
- Mean is used on symmetrical distributed dataset. Median is used on skewed dataset
- DateTime: Forward fill, Backward fill
- Pandas: fillna(), SimpleImputer Class
- String functions - split, contains, replace, bins etc
- Univariate, BiVariate, Multivariate analysis

### Insights / Recommendations
1. Content aligned with Drama, Comedy is recommended due to their popularity across various countries and in both TV Shows and Movies
2. TV shows added first month of every year or during July/August months
3. For US audience movie length of 80-120 min are recommended
4. Target the content rating of 14+ for US, India and Mature/R rating for UK
5. Japanse audience consider adding Anime genres and for South Korean audience, Romantic genres
6. When creating content, consider popular actor/director for each country and prioritize those combinations
7. Content should be added within 1 year of release
8. TV shows with 1 season is very popular

### Impact on Business
1. Content Strategy: Identified popular genres, tailored content strategy, leading to increased engagement and retention.
2. Scheduling Optimization: Optimized content release timing, maximizing viewership, and enhancing subscriber satisfaction.
3. Audience Targeting: Refined targeting strategies based on preferred content lengths, ratings, and genres, attracting diverse demographics.
4. Content Localization: Invested in localized content production, considering cultural and regional preferences, strengthening global presence.
