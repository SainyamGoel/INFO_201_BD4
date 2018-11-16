# INFO_201_BD4
Project Proposal Repo

Jared Lai
Addie Fair
Mohneel Parakh
Sainyam Goel 

Project Proposal 

Project Description 
For our final project, we will be analyzing gender trends across Twitter users. The dataset is provided by the Data For Everyone Library on Crowdflower (now known as Figure Eight) and was used to train an algorithm to predict if a specific Twitter account belonged to a man or a woman. Ten-thousand random tweets with the word “the” in them and another ten-thousand tweets with the word “and” in them were pulled, along with the user info for each account that tweeted it. This dataset contains various information about the twenty-thousand Twitter users, such as their Twitter handle, name, profile picture, gender, time when the account was created, number of tweets, number of retweets, and number of tweets the user has favorited. Our goal for the project is to allow our audience to see which gender trends to perform a particular activity more than the other. For example, you could see if males or females tend to favorite tweets more, or which gender has a higher average of tweets. Other questions you could ask are what is the most popular time to tweet for a specific gender, what kind of tweets get retweeted the most, or even what percentage of a specific gender have profile pictures. This audience could be anybody who wants to analyze Twitter user trends, but will most likely be targeted more towards people who are looking to use Twitter for marketing or advertisement purposes, so they can get a better idea of who their target audience should be.

Technical Description
The goal is to make an HTML page that will be displaying the trends of words and profile characteristics that are strongly associated with gender. The data we will be working with is in .csv format. There are four columns for “gender” which are male, female, brands/companies, and unknown. We would perform queries to filter out the male and female data and use libraries that have already been taught in class to work with the data. Additionally, rpart and mice may be used for machine learning to predict whether or not a user is male or female
