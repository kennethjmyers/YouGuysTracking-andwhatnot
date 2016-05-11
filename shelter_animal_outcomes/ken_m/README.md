# Shelter Animal Outcomes

This is the work of [Ken Myers](https://github.com/kennmyers) for the shelter animal outcomes challenge on Kaggle. With this I peaked at 32nd/436 on the leaderboards (May 6, 2016).

I started in shelter_animals-v1 using only the features given to us and modeling with RFC. By v6 I had done feature extraction on those variables to get more than 50 features and broke the top 10% with XGBoost.

Note that this exploits the data leak in the time data. Time data isn't actually helpful for an animal shelter and it shouldn't be used, but because this is sandbox challenge and the rules aren't enforced, everyone is exploiting the data leak.
