# Final-Project: MLB Betting Analysis

For our final project we wanted to build an algorithm that was able to read the differences in betting lines from the time they open to the time the close. We wanted to find out if a big change in the lines could be directly connected to a winning bet. Usually a big change in the betting lines means that most of the public money is on that team and so Vegas is accounting for that. 

We then asked ourselves could we find data for these changes and build an algorithm that could analyze those changes and predict the winning team based off those changes. Also can we make money? 

# The Process 

We started by finding large data sets of previous MLB games that held the information on who played, won, and what the betting lines opened and closed at. We found a dataset that contained all of the information we needed for every game of the 2021 MLB season. Cleaning the data was very important to make sure we got it in the right format for our model.

Next was building the model using linear regression with bthe cleaned data. We read in the data and very quickly got things into an array. We then used the array to predict wins from a 10%, 15%, 20%, and 25% difference in betting odds. By getting the win percentage from our model for each of those difference percentages we determined that a 20% difference at a win percentage of 54 gave us the best value.

# Winning 

With that 20% diff in mind it was time to apply it to the modern day games. We took that difference and started to apply it to real games through the week of 7/30 to 08/06. After using this model and applying it to real games from the week we ended up using it on 28 games and we went 18 - 10 which is great news. A 64% win total is a a great winning margin especially when it comes to Vgeas. If we also bet $100 on everygame we would be making a $187 profit which is a plus as well. We also compared our picks to the expert picks on CBSsports.com and they went 13-15.

# Conclusion 

The conlusion is that there is a direct corelation between the public bets and wins when the lines move as much as they do. Our model proves that when Vegas moves their line by 20% or more it usually means a win. 

