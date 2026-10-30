# Amazon Publishing Strategy

A data-backed recommendation to a CEO: which bestselling authors Amazon should back for 2025–2030, and which recent screen titles could be adapted into books.

**Context:** business case · **Author:** Amit Stein

## Data
- 550 Amazon bestsellers, 2009–2019 (name, author, rating, reviews, price, year, genre).
- About 10,000 Netflix titles (year, genre, rating, votes, cast, description).

## Approach
- Data quality checks, cleaning and de-duplication.
- Focus on the dominant genre (non-fiction, 310 of 550 titles) and the top 10 authors by appearances.
- A simple score that weighs how often an author reached the list by their average rating.
- Genre and cast analysis of recent Netflix titles.
- An executive deck with the recommendation, platform KPIs (conversion rate, repeat-customer rate, average basket value) and a clear caveat that the data ends in 2019.

## Recommendation
Back **Gary Chapman**, the **American Psychological Association** and **Rob Elliott**, the three highest-scoring authors.

## Files
- `Final_Amit_Stein.ipynb`: the analysis
- `עמית שטיין.pptx`: the executive presentation (Hebrew)
- `bestsellers with categories.csv`, `n_movies.csv`: the data

**Tools:** Python · pandas · seaborn · matplotlib · PowerPoint
