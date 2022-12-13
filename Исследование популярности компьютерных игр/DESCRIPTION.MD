## Project. Research of gaming platforms
### Description of the project
The Strimchik online store sells computer games all over the world. Historical game sales data, user and expert ratings, genres and platforms (such as Xbox or PlayStation) are available from public sources. It is necessary to identify patterns that determine the success of the game. This will allow you to bid on a potentially popular product and plan advertising campaigns.

Here is the data up to 2016. Let's say it's December 2016 and you're planning a campaign for 2017. It is necessary to work out the principle of working with data. It doesn't matter if you're forecasting 2017 sales based on 2016 data or 2027 sales based on 2026 data.

The abbreviation ESRB (Entertainment Software Rating Board) comes across in the data set - this is an association that determines the age rating of computer games. The ESRB evaluates game content and assigns it to an appropriate age rating, such as Mature, Toddler, or Teen.

### Content of the project
1. Exploring general information about the data

2. Data preparation
     - Replace column names (bring to lower case)
     - Convert data to desired types
     - Handle gaps if necessary
     - Calculate the total sales in all regions
    
3. Data analysis and answering questions
     - How many games were produced in different years. Select platforms with the highest total sales and plot the distribution by year.
     - What is the characteristic period for new platforms to appear and old ones to disappear?
     - Which platforms are leading in sales, growing or falling?
     - Plot a box-and-mustache plot of each game's global sales and breakdown by platform. Is there a big difference in sales? What about average sales across platforms?
     - How do user reviews and critics influence sales within one popular platform?
     - What can you say about the most profitable genres? Do genres with high and low sales stand out?
    
4. Drawing up a portrait of the user of each region and answering questions
     - What are the most popular platforms (top 5)?
     - What are the most popular genres (top 5)?
     - Does the age rating affect sales in a particular region?

5. Hypothesis testing
     - Hypothesis 1 - The average user ratings of the Xbox One and PC platforms are the same;
     - Hypothesis 2 - The average user ratings of the Action and Sports genres are different.
    
### Libraries used in the project:
- pandas
- Numpy
-Scipy
-Math
- matplotlib
- Seaborn
