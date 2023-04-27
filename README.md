# Exploratory analysis on Chocolate Flavors 

I was able to carry out analysis and visualization of Chocolate Flavors dataset using Microsoft Excel after being a part of a WhatsApp group created by data enthusiasts with the objective of performing data analysis for portfolio creation and overall growth and improvement. 

# About Dataset
The dataset was dowloaded from https://www.kaggle.com/
Chocolate is one of the most popular candies in the world. Each year, residents of the United States collectively eat more than 2.8 billions pounds. However, not all chocolate bars are created equal! This dataset contains expert ratings of over 1,700 individual chocolate bars, along with information on their regional origin, percentage of cocoa, the variety of chocolate bean used and where the beans were grown.
Flavors of Cacao Rating System:
5= Elite (Transcending beyond the ordinary limits)
4= Premium (Superior flavor development, character and style)
3= Satisfactory(3.0) to praiseworthy(3.75) (well made with special qualities)
2= Disappointing (Passable but contains at least one significant flaw)
1= Unpleasant (mostly unpalatable)

Each chocolate is evaluated from a combination of both objective qualities and subjective interpretation. A rating here only represents an experience with one bar from one batch. Batch numbers, vintages and review dates are included in the database when known.
The database is narrowly focused on plain dark chocolate with an aim of appreciating the flavors of the cacao when made into chocolate. The ratings do not reflect health benefits, social missions, or organic status.
Flavor is the most important component of the Flavors of Cacao ratings. Diversity, balance, intensity and purity of flavors are all considered. It is possible for a straight forward single note chocolate to rate as high as a complex flavor profile that changes throughout. Genetics, terroir, post harvest techniques, processing and storage can all be discussed when considering the flavor component.
Texture has a great impact on the overall experience and it is also possible for texture related issues to impact flavor. It is a good way to evaluate the makers vision, attention to detail and level of proficiency.
Aftermelt is the experience after the chocolate has melted. Higher quality chocolate will linger and be long lasting and enjoyable. Since the aftermelt is the last impression you get from the chocolate, it receives equal importance in the overall rating.
Overall Opinion is really where the ratings reflect a subjective opinion. Ideally it is my evaluation of whether or not the components above worked together and an opinion on the flavor development, character and style. It is also here where each chocolate can usually be summarized by the most prominent impressions that you would remember about each chocolate.

Acknowledgements
These ratings were compiled by Brady Brelinski, Founding Member of the Manhattan Chocolate Society. For up-to-date information, as well as additional content (including interviews with craft chocolate makers), please see his website:  http://flavorsofcacao.com/index.html

License: https://creativecommons.org/publicdomain/zero/1.0/


# Data cleaning
✓Re-aligned the headers
✓Checked for and removed duplicates
✓Applied filter and checked for misspellings on all columns and removed blanks under ‘broad bean origin’ column.
✓Dropped about 4 columns because they were not important for the analysis


# Objectives
Below are the business questions to be answered from analysis;
1. Where are the best cocoa beans grown?
2. Which countries produce the highest-rated bars?
3. What’s the relationship between cocoa solids percentage and rating?

# Analysis & Insights

![Cocoa Dashboard](https://user-images.githubusercontent.com/116006674/226657654-4c9f88c0-dd01-4bae-ba2b-4ea005f03a15.png)

My findings after analysis showed that VENEZUELA had the highest rated chocolate and it is where the best cocoa bean is grown. I compared the broad regions against the rating column on a pivot table. I limited the countries that produce the highest rated bars to 5.

The higher cocoa % had the lowest ratings. I believe ratings were determined also considering the broad bean origin of the cocoa bean considering the fact that venezuela did not produce the cocoa bean with the highest cocoa % but still had the highest rating.

# Conclusion
Varying factors, asides cocoa % such as bean type and country of origin, determine the rating of a cocoa bean.
