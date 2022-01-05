# Forecasting-Using-R
**Project Goal:**
Nate Silver looked at 22 comparable films to produce an estimate of how much “The Interview” might have made in theaters had it been released under normal circumstances. 

**His Criteria:** 
Action/Comedies 
Rated R
Released in 2000 or later by a “mini-major” American Studio

**His Model:** 
Nate used a linear regression against the comparable films worldwide box office grosses, production budgets and Rotten Tomatoes ratings to attempt to predict The Interview’s worldwide box office sales. Nate calculated that a 1 percent gain in Rotten Tomatoes ratings is associated with a roughly $2 million increase in international box office gross. And every additional $1 million in production budget translates to about $2 million more at the box office.

**His Conclusion:** Roughly $100 million in box office sales
![image](https://user-images.githubusercontent.com/24640491/148225621-c6bbb3ad-7559-43be-8676-acd7ff327f7d.png)

Like Nate Silver, we used a subset of movie data to create our own set of comparable movies to model ‘The Interview’ against. 
**Our Criteria:** 
Action/Comedies 
Rated R
Made in the USA
Budget Range: $20M - $80M
Released in 2000 or later

![image](https://user-images.githubusercontent.com/24640491/148225689-ee8c12ce-8efe-42c4-93f5-1aca5f933893.png)

We created a duplicate model similar to Nates using our data set. The only difference being we used IMDB ratings instead of Rotten Tomatoes ratings. We then created our own predictive model using our own datapoints and ran an accuracy test to determine the strength of the model.  
![image](https://user-images.githubusercontent.com/24640491/148225714-967f2a8e-6f72-42be-95c6-89fe960920f6.png)

Taking it a step further, we used a more selective group of movies to test our model. ‘Neighbors’, ‘Horrible Bosses’, ‘This is the End’, and ‘Bad Moms’ are all films with a lot of unmeasurable similarities to ‘The Interview’
![image](https://user-images.githubusercontent.com/24640491/148225751-6dd93742-a36b-48be-a1a5-23c3f0fdbf38.png)
![image](https://user-images.githubusercontent.com/24640491/148225774-3de39835-bf7f-4e55-8d81-57a0b08d79a5.png)
