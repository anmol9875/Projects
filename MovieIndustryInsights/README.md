# Movie Industry Insights Dashboard

## About

Welcome to the **Movie Industry Insights Dashboard**! This project is an interactive analysis of the global film industry, developed using **Power BI**. It highlights financial metrics, genre trends, company performance, and more to provide valuable insights into what drives success in the movie business.


---

## Purpose of the Project

The purpose of this project is to analyze movie data and uncover insights related to:

- Profitability trends over time  
- Genre-based differences in budget, gross, and runtime  
- Top-performing production companies and actors  
- Influence of ratings on movie performance  
- Geographic distribution of movie releases  

This dashboard helps in answering real-world business questions and demonstrates skills in data modeling, transformation, and visualization.

---

## About Data

The dataset used in this project was sourced from [Kaggle - Movies Dataset](https://www.kaggle.com/datasets/danielgrijalvas/movies). It includes comprehensive details about over 7,600 movies including:

| Column     | Description                           |
|------------|---------------------------------------|
| `name`     | Name of the movie                     |
| `rating`   | Movie's rating (PG, R, etc.)          |
| `genre`    | Main genre of the movie               |
| `year`     | Year of release                       |
| `released` | Exact release date                    |
| `score`    | IMDb rating score                     |
| `votes`    | Number of user votes                  |
| `director` | Director of the movie                 |
| `writer`   | Writer(s) of the movie                |
| `star`     | Leading star/actor                    |
| `country`  | Country of release                    |
| `budget`   | Production budget in USD              |
| `gross`    | Gross earnings in USD                 |
| `company`  | Production/distribution company       |
| `runtime`  | Duration of the movie in minutes      |

The data was cleaned and transformed using Power BI’s Power Query and DAX features for better usability in visual analysis.

---

## Feature Engineering

To support more insightful analysis, several custom measures and calculated fields were created, including:

| Field Name               | Description                                                             |
|--------------------------|--------------------------------------------------------------------------|
| `Profit`                 | Calculated as Gross – Budget                                             |
| `Profit Margin %`        | (Profit ÷ Budget) × 100, shows efficiency in spending                    |
| `Avg. Budget`            | Yearly and genre-level budget averages                                   |
| `Avg. Gross`             | Yearly and genre-level gross averages                                    |
| `Total Profit` KPIs      | Aggregated by Genre, Company, Star, and Rating                           |
| `Vote & Runtime Averages`| Genre-level analysis on average runtime and popularity                   |

These engineered fields helped in building precise comparisons and answering detailed analytical questions.

---

## Dashboard Sections

### 1. Summary View  
- Total industry KPIs: Budget, Gross, Profit  
- Highest scoring genres  
- Vote distribution and average runtime by genre  

### 2. Finance View  
- Budget and gross trends over time  
- Profit margin by genre and rating  
- Top-performing stars by profit  
- Most profitable movies  

### 3. Genre Overview  
- Genre count and distribution  
- Financial performance by genre  
- Average runtime and ratings breakdown  

---

## Analysis List

1. **Financial Overview**  
   > Explore industry-wide trends in budget, gross, and profit over time.

2. **Profitability by Genre**  
   > Identify which movie genres bring the highest returns.

3. **Top Companies Analysis**  
   > See how studios like Warner Bros., Universal, and Disney perform financially.

4. **Star Impact on Profit**  
   > Analyze how top actors influence profitability.

5. **Distribution by Rating**  
   > Understand how movie ratings like PG-13 or R affect earnings.

6. **Vote & Runtime Insights**  
   > Examine popularity through vote counts and how runtime varies by genre.

7. **Country-Wise Movie Distribution**  
   > Breakdown of movie releases across global markets.

---

## Business Questions Answered

1. What is the overall trend in movie budget, gross revenue, and profit over time?  
2. Which genres are most profitable and most popular?  
3. How do different movie ratings impact profit margins?  
4. Which companies consistently produce high-grossing movies?  
5. What role do actors play in influencing a movie's profitability?  
6. How are votes and average runtime distributed across genres?  
7. How is the global movie industry distributed by country?

---

## Key Metrics

- **Total Movies Analyzed**: 7,667  
- **Total Budget**: $196B  
- **Total Gross**: $587B  
- **Total Profit**: $365B  
- **Most Profitable Genre**: Action  
- **Top Studios**: Warner Bros., Universal Pictures, Walt Disney  
- **Top Stars by Profit**: Robert Downey Jr., Tom Hanks, Tom Cruise  

---

## Tools Used

- **Power BI Desktop** for dashboard design  
- **Power Query Editor** for data transformation  
- **DAX** for calculated measures and KPIs  
