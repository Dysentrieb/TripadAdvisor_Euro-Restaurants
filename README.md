# TripadAdvisor_Euro-Restaurants
Data Analytics on Tripadvisor European Cities dataset. This project is associated to the Udacity Project "Write A Data Science Blog Post". It uses the "TripAdvisor Restaurants Info for 31 Euro-Cities"-dataset, which can be downloaded at: https://www.kaggle.com/damienbeneschi/krakow-ta-restaurans-data-raw

Motivation:

I was in south-western Poland recently and while searching for a good place to eat on Google Maps I noticed, that there were a lot of restaurants that had really good ratings and reviews in the 4+ region, in cities as well as at the countryside. This made me thinking, because in my hometown Munich there is also many great places, but also a lot that are in not-so-good-region around 3 stars. In general, ratings seemed to be better there compared to what I know. So I thought, maybe people just rate more mildly there. Trying the local food, I noticed the great service, taste and the relatively low pricetag. Subjectively the quality and price-performance ratio seemed better than that of bavarian restaurants. But what does data science say? Are there differences in average ratings and number of ratings between regions? To answer this question, I used the TripAdvisor Restaurants Info for 31 Euro-Cities from Kaggle. This dataset contains the TripAdvisor reviews and ratings for 111927 restaurants in 31 European cities.
Specifically, the this project asks and answers the following 3 Research Questions (RQ):
RQ1: Are there differences in average ratings and number of ratings between cities?
RQ2: Are there more vegetarian-friendly cities and if so, are they locally concentrated?
RQ3: Is local cuisine rated better than foreign cusine and if so, is there a difference between cities?

Tools and libraries used:

- Jupyter Notebooks
- Python 3
- Pandas
- Numpy

Files:

- 20190909_TA_Restaurants_V1.html: Jupyter Notebook as html, can be read with a regular browser.
- 20190909_TA_Restaurants_V1.ipynb Original Jupyter Notebook file, needs Jupyter Notebooks installed: https://jupyter.org

Results short Version:

RQ1: There are differences in average ratings and number of ratings.
RQ2: There are certain cities, that are a lot more veggy-friendly than other ones. Local patterns are not spotted.
RQ3: In general there are no significant differences in ratings for local cusine restaurant. Yet for certain cities it is true, with differences of more than 0.2.

Results long Version:
RQ1: As it can clearly be seen, there is a difference in average ratings by citiy. The highest average rating is 4.232 for the city of Rome and 3.797 for the city of Madrid. An interesting follow-up question would be, wether the general quality of restaurants is better in Rome or if reviewers give better ratings in Rome compared to Madrid. Another more vague explaination would be that Tripadvisor is more often used by Tourists than locals, and that tourists rate Italian food better, as they are better used to it since it is better known in the world compared to spanish food.
Also with the number of ratings it can be noted, that there definitely is a a difference in number of ratings. The highest average number of ratings with 293.896 is (again) seen in the city of Rome, while Hamburg with 45.942 has the lowest average number of ratings, which makes up of a difference of close to 248 in average ratings - that means rome has 6 times the average number of ratings as Hamburg, which can't be explained by the difference in inhabitants, which is 2.872.800 for Rome (Wikipedia) and 1.841.179 for Hamburg (Wikipedia). Other explainations would be that certain regions are more rating-friendly, prefer Tripadvisor or other tools such as Google Maps or that the probably higher number of tourists in Rome uses Tripadvisor more often.
RQ2: It seems that there are also great differences in average number of restaurants with vegetarian/vegan option available: Edinburgh has the highest number of restaurants that offer veg, with 56.9%, Lyon on the other hand with 12,9% is a lot less veg-friendly. A clear local pattern can not be distinguished.
RQ3: Although there is a difference with local restaurants being rated better than restaurants not serving local food (aggregated difference is 0.026 / total difference is 0.0155), it is quite small and not neccessarily statistically significant in general. Yet it is interesting to notive, that for some cities the hypothesis is true. Especially Copenhagen, Edicnburgh, Helsinki, Ljubliana and Lyana show more significant differences with local restaurants being favored and cities like Barcelona, Berlin, Bratislava, Brussels and Prahgue, where local restaurants are rated less good, in the case of Bratislava the difference is greater than 0.2.
So, again, this can have multiple reasons. It is possible that people who use Tripadvisor, which are often tourists, prefer certain cousines that they are familiar to. Also it is possible, that certain local cuisines are "easier" for the non local. Other reasons are thinkable.
