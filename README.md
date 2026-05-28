#   IMDB_Movie_Analysis-PowerBI

## Table of Contents 

*  Project Overview
*  Data Source
*   Tools
*   Data Preparation
*   Exploratory Data Analysis
*   Insights
*   Dashboard<br>

### Project Overview

* An interactive Power BI dashboard designed to analyze historical movie data, exploring trends across box office revenues, critical ratings, and the most influential actors and directors in cinema history.
* This Dashboard is designed to analyze a historical dataset of 1,000 films. The project transitions seamlessly from a high-level macroeconomic overview of the film industry to a highly granular, individual movie performance tracker. It serves as a comprehensive tool for exploring historical trends, understanding demographic market reach, and identifying the key drivers behind cinematic success from 1920 to 2020.

  
### Data Source

Movies Data : The primary dataset is used for this analysis is the " IMDB_Movies_Data. xlsx", which contains a historical dataset of 1,000 films for exploring historical trends, understanding demographic market reach, and identifying the key drivers behind cinematic success from 1920 to 2020.

### Tools

* PowerBI - Creating Dashboard, Data Visualization
* Power Query Editor - Data Cleaning
* Data Analysis Expressions (DAX) - Creating Measure and Parameters

### Project Dashboard includes :- 
  
  *  Sheet 1: Home
  *   Sheet 2 : Summary
  *   Sheet 3 : Movie Details<br>

### Data Preparation
In the initial data preparation phase, we performed the following tasks:

  1. Data loading and inspection.
  2. Handling missing values.
  3. Data cleaning and formatting

### Exploratory Data Analysis
EDA involved exploring the Movies data to answer key questions, such as:

1. Which directors and actors have the highest volume of highly-rated films in this dataset?
2. How does box office revenue trend historically, and which specific years generated major financial breakthroughs?
3. What is the market distribution look like when segmenting movies by age certifications (e.g., U, A, UA)?
4. Do genres with the highest volume of films (e.g., Drama) also pull in the highest overall ratings?

### Insights

#### Summary
In summary Page contains insights are as follows:

#### 1] Key Performance Indicators (KPIs) 

The dashboard tracks high-level summary metrics across the dataset:
*   Total Directors: 548 unique filmmakers.
*   Total Genres: 202 unique genre combinations/categories.
*   Average Votes per Movie: ~273.69K votes, showcasing audience engagement.
*   Average Gross Revenue: $68.03M per movie.
*   Average Rating: 7.95/10, indicating a curated or highly-rated selection of films.
*   Average Meta Score: 77.98/100, reflecting critical consensus.

#### 2] Advanced Search & Hierarchical Breakdown (Decomposition Tree)
*   Located on the left, this section utilizes a *Decomposition Tree* visual. It allows users to break down the total volume of movies (Count of Genre: 1000) by specific paths: Genre ➡️ Director ➡️ Movie Title. 
*   It currently showcases a filtered deep-dive into specific directors like Richard Linklater and Peter Bogdanovich alongside their notable films (e.g., the Before trilogy).

#### 3] Top 5 Movies by Gross Revenue
*   A treemap highlighting the highest-earning blockbusters in the dataset. 
*   Dominating the box office metrics are massive franchises like Star Wars: Episode VII - The Force Awakens ($937M), Avengers: Endgame ($858M), Avatar ($761M), and Avengers: Infinity War ($679M).

#### 4] Industry Powerhouses 
*   *Top Actors by Movies:* Ranks the most prolific actors in the dataset. *Tom Hanks* leads with 12 movies, closely followed by industry veterans like *Robert De Niro* (11), *Al Pacino* (10), and *Clint Eastwood* (10).
*   *Top Directors by Movies:* Tracks the directors with the highest film count in this dataset. Legendary filmmaker *Alfred Hitchcock* tops the list with 14 films, followed by *Steven Spielberg* (13) and *Hayao Miyazaki* (11).

#### 5] Historical Gross Revenue Trends
*   A historical timeline spanning from *1920 to 2020* that tracks financial growth in the film industry.
*   Features a dynamic insight header highlighting a major milestone: *"Highest Gross is generated in the year 2009"* (largely driven by the release of Avatar), with a visible exponential spike in revenue moving into the 2000s and 2010s.


#### Movie Details
In Movie Details Page contains insights are as follows:

#### 1]. Dynamic Movie Profile Card (Detailed Drilldown)
*   *Interactive Selection:* Features a *Title* slicer at the top left (currently showing "A Man for All Seasons"). Selecting a movie dynamically populates a comprehensive metadata profile card.
*   *Key Details Captured:* 
    *   *Core Metadata:* Director (Fred Zinnemann), Genre (Biography, Drama, History), Runtime (120 min), and Release Year (1966).
    *   *Financials & Reception:* Box Office Gross ($28.35M), IMDb Rating (7.70), Total Votes (31K), and Metacritic Score (72.00).
    *   *Narrative Context:* Includes a dynamic text box rendering the movie's official plot description.
    *   *Cast Details:* Dynamically lists the main starring actors (e.g., Paul Scofield, Wendy Hiller, Robert Shaw, Leo McKern).

#### 2]. Certificate Distribution
*   A *Funnel Chart* illustrating the volume of movies across different film certifications and age ratings.
*   The breakdown highlights market distribution, showing that *U* (175 movies), *A* (146 movies), and *UA* (101 movies) represent the bulk of the dataset, tapering down into niche ratings like PG-13, PG, and Approved.

#### 3]. Industry Genre Analysis 
*   *Top Genres by Total Movies:* A horizontal bar chart identifying *Drama* as the single most dominant genre with 85 entries, followed by hybrid genres like Drama, Romance (37) and Comedy, Drama (35).
*   *Top Genres by Total Rating:* A column chart that shifts the perspective from volume to performance, tracking which genres pull in the highest cumulative user ratings. Pure *Drama* leads significantly here as well (678 total rating points).

#### 4]. Historical Audience Engagement
*   *Top Movies by Total Votes:* Tracks the sheer volume of audience engagement through global vote counts.
*   Cinematic masterpieces dominate this visual, with *The Shawshank Redemption* and *The Dark Knight* leading the pack at an incredible *2,343K* and *2,303K* votes respectively, followed closely by Inception (2,067K) and Fight Club (1,855K).


### Dashboard

#### Home Page
<img width="1314" height="735" alt="Screenshot 2026-05-29 002512" src="https://github.com/user-attachments/assets/e5f36737-795f-4090-a441-49ae45d35d6b" />


#### Summary 
<img width="1332" height="744" alt="Screenshot 2026-05-29 002544" src="https://github.com/user-attachments/assets/ec3b2524-574b-4901-9992-b739f54278e5" />

#### Movie Details
<img width="1332" height="743" alt="Screenshot 2026-05-29 002618" src="https://github.com/user-attachments/assets/eb22ebe5-a856-4eb4-895e-daa573423118" />





