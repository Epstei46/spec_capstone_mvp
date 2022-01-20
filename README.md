MVP for my Specialization (Data Solutions) Capstone Project in the Bright Paths Program

### Challenge
Which game genres were the most popular on each system? By number of games and by sales. Focus on Xbox One, PS4, Wii. Maybe PC, Xbox 360, PS3 as well.

### Purpose
If some genres were more popular on a particular system, or if a system had the most games of that genre, would make more sense for **developers** to focus development/testing on that system and maybe even consider exclusivity deals.
    And if **consumers** have a preference for a particular genre, would make more sense for them to get that system & upgrade that system first.

### Tech Stack
    - numpy (needed for Pandas)
    - pandas (for interacting with the dataset, data cleaning/wrangling)
    - matplotlib (visualization of data with bar charts)

### Data Sources
    <https://data.world/sumitrock/video-games-sales> .csv file. Sources VGChartz for all the data, which they obtained/verified by using "a number of proprietrary [sic] and ever-developing methods".

### Acceptance criteria
    - As a user, I should be able to see which system had the largest number of games per genre.
    - As a user, I should be able to see which system had the highest sales per genre.

<br><br><br>

If I have extra time:
1. Was there a significant difference in number of units sold per system globally (or per region)? If yes, possible implications?
    Which system had the largest number of exclusives? For each genre? Of exclusive games, which system had the most out of the top 20 exclusives? Possibly limit dataset to top 100-500 games when looking at exclusives.
    If there is enough data for comparison, can look at critic/user scores for games on both systems.
2. For **developers** considering exclusivity deals, could be interesting to compare best performing exclusive games to best performing non-exclusives.
    User scores would be an additional useful metric for success of the games. Can compare all games or each genre, if a particular system more often had better scores/reviews.
3. Additional bar charts.
    For bar charts showing sales or number of games, per genre per system, can I change a portion of the bar to represent exclusives? Different color for that portion?
4. <https://www.vgchartz.com/analysis/platform_totals/> Total sales for each system/platform. If there is a difference between different regions, worth mentioning and looking into how that affects the data.
    <https://www.kaggle.com/tyedwardse/metacritic-game-scores> sourced metacritic. If I want to fill in data gaps for critic/user scores and/or update with more current data.\
5. Acceptance Criteria:
    - As a user, I should be able to see which system had the highest sales per region or globally.
    - As a user, I should be able to see which system had the largest number of exclusives.
    - As a user, I should be able to see which system had the largest number of popular exclusives.
    - As a user, I should be able to see if one system more often had better reviews than the other system(s), overall or per genre.
