About Dataset
Context
Formula 1 (a.k.a. F1 or Formula One) is the highest class of single-seater auto racing sanctioned by the Fédération Internationale de l'Automobile
(FIA) and owned by the Formula One Group. The FIA Formula One World Championship has been one of the premier forms of racing around the world since 
its inaugural season in 1950. The word "formula" in the name refers to the set of rules to which all participants' cars must conform. A Formula One 
season consists of a series of races, known as Grands Prix, which take place worldwide on purpose-built circuits and on public roads.

Content
The dataset consists of all information on the Formula 1 races, drivers, constructors, qualifying, circuits, lap times, pit stops, championships from 
1950 till the latest 2023 season.

Acknowledgements
The data is compiled from http://ergast.com/mrd/

With the amount of data being captured, analyzed and used to design, build and drive the Formula 1 cars is astounding. It is a global sport being 
followed by millions of people worldwide and it is very fascinating to see drivers pushing their limit in these vehicles to become the fastest racers 
in the world!

Formula 1 Exploratory Data Analysis (EDA) Project
Objective:

Gain insights into the world of Formula 1 racing by exploring a comprehensive dataset spanning 1950 to 2023.
Uncover patterns and trends in driver performance, constructor success, race results, and other factors that influence the sport.
Prepare the data for further analysis, such as predictive modeling or building dashboards for fans and analysts.
Description:

This project utilizes Python libraries like Pandas, Seaborn, and Matplotlib to conduct an in-depth exploration of the Formula 1 dataset. 
Here's a breakdown of the key steps involved:

Data Loading and Cleaning:
      Load various dataframes related to races, drivers, constructors, qualifications, circuits, lap times, pit stops, and championships.
      Merge these dataframes into a single comprehensive dataset for analysis.
      Address missing values strategically:
      Fill numerical columns (e.g., fastest Lap) with the mean value.
      Fill categorical columns (e.g., rank) with 0.
      Filter out rows with extreme outliers in speed or time (potentially indicating data errors).
Data Exploration:
      Analyze the distribution of numerical features like driver age, race lap times, and car speeds using kernel density plots.
      Identify relationships between variables (e.g., driver age vs. race wins) using appropriate visualizations.
      Explore categorical features like driver nationality and constructor dominance over time.
      Investigate race outcomes (finished, retired, disqualified) and their impact on performance metrics.
Data Filtering and Preparation:
      Focus on data relevant to finished races, potentially excluding incomplete data for a more accurate analysis.
      Remove redundant or unnecessary columns to optimize the dataset for further exploration or modeling.
      Prepare the cleaned and enriched data for further analysis tasks.
Expected Outcome:
      This EDA project aims to provide a foundational understanding of the Formula 1 data. By uncovering hidden patterns and trends, 
      the analysis can lead to valuable insights for:
          Race Fans: Explore statistics on their favorite drivers, constructors, or historical races.
          F1 Analysts: Identify factors influencing driver performance, team strategies, and race outcomes.
          Data Scientists: Prepare the data for predictive modeling (e.g., predicting race winners, fastest laps) or building interactive dashboards.
          The project establishes a clean and informative dataset ready for further investigation, ultimately contributing to a deeper understanding of 
          the dynamic world of Formula 1 racing.
