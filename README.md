# spec_capstone_mvp
MVP for my Specialization (Data Solutions) Capstone Project in the Bright Paths Program

1 - State the challenge (A specific question or set of questions to answer or a theory to test using data analysis)
    Which game genres were the most popular on each system? By number of games and by sales. Focus on Xbox One, PS4, Wii, PC.
2 - What does this application address (A purpose behind the question - what does this solve?)
    If some genres were more popular on a particular system, or if a system had the most games of that genre, would make more sense for **developers** to focus development/testing on that system and maybe even consider exclusivity deals. And if **consumers** have a preference for a particular genre, would make more sense for them to get that system.
3 - Tech stack (all modules) with a description of use
    numpy (needed for Pandas), pandas (for interacting with the dataset, data cleaning/wrangling), matplotlib (visualization of data with bar charts)
4 - Data Sources
    You Eat too Much API
5 - Acceptance criteria
    - As a user I should be able to evaluate BMI progress visually…

If I have extra time:
1 - Which system had the largest number of exclusives? For each genre? Of exclusive games, which system had the most out of the top 20 exclusives?
    If there is enough data for comparison, can look at critic/user scores for games on both systems.
2 - For **developers** considering exclusivity deals, could be interesting to compare best performing exclusive games to best performing non-exclusives.
    User scores would be an additional useful metric for success of the games. Can compare all games or each genre, if a particular system more often had better scores/reviews.
3 - Additional bar charts?
4 - 
5 - 



A specific question or set of questions to answer or a theory to test using data analysis:
    Which games and game genres were the most popular on each system?
    Can test this by looking at totals overall or by year, number of games developed and total sales.
    Could also be interesting to look at the top 100-250 selling games, how many of them were exclusives.

A purpose behind the question - why does this matter:
    If particular genres are more popular on the Xbox than PlayStation or Wii, then it may be more worthwhile
    for developers making a game of that genre to consider an exclusivity deal. And for consumers, if their
    favorite genre has more games on one system, then that should be their primary system they upgrade first. 

Choose at least 2 data sources - can be static datasets, live data, APIs, or other:
NOTE -- Pretty sure all below data sets source vgcharts AND metacritic.
    3 Data Tables: Xbox One Sales, PS4 Sales, All Sales 1980-2016 for past systems.
    <https://www.kaggle.com/sidtwr/videogames-sales-dataset>
    Full data set, needs some data cleaning   <https://data.world/sumitrock/video-games-sales>
    Reduced data set, top 2k global sales <https://data.world/bramwax/video-games-sales/>

Propose 2-3 visual elements you will include in your analysis (charts, visualizations, etc.):
    Bar charts for each genre, y-axis total sales & x-axis system
    Bar charts for each genre, y-axis number of games & x-axis system
        If I can make a portion of the bar a different color for exclusives, very nice.
