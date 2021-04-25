---
layout: post
title: "Actors in Numbers : a Data Analysis of the Egyptian Cinema"
category: Data Analysis
---

> *Disclaimer: All data used in this article has been scraped from [elCinema](https://elcinema.com). Due to the high probability of the website missing some information, it might be wise to take the shown statistics with a grain of salt. The scrapper and all generated data files can be found on my [GitHub](https://github.com/nyuriumuri/Actors_in_Numbers_data)*  

In this article, we will be using data from [elCinema](https://elcinema.com) to try and identify some of the most prominent actors of the Egyptian cinema. Due to the lack of reliable ratings and sales figures on movies earlier than 2010, the criterion used here will just be the number of movies an actor participated in (as an actor). The first section will cover the 5 actors with the largest total number of works, and will include some analysis on their activities and movies. In the second section, the most common genres and the actors who contributed the most in them will similarly be identified.

A *TL;DR* is available at the end.


# The Actors with the Largest Number of Works



&nbsp;  
## Mahmoud El Meleigy: 375 Movies


![Meleigy]({{site.baseurl}}/assets/images/EgyptianMovies/meligy.jpg)



 El Meleigy was born in 1910 in the village of Meleig. He is considered one of the most popular and well respected actors of the 20th century, as he earned numerous rewards for his work both in Egypt and outside. El Meleigy was well known for his villainous roles, earning him titles such as "Shereer al Shasha" (Villain of the Screen) and "Anthony Quinnn al Sharq" (Anthony Quinn of the East). El Meleigy died in 1983.

&nbsp;  

## Motawea Oweis: 373 Movies

![Oweis]({{site.baseurl}}/assets/images/EgyptianMovies/oweis.jpg)

Oweis was born in 1929 and died in 2015. Oweis was popular for his secondary roles, such as those of the fruit merchat, the doorman, the ruffian, and the informant.

&nbsp;

## Abdelghani El Nagdi: 359 Movies

![Nagdi]({{site.baseurl}}/assets/images/EgyptianMovies/nagdi.jpg)

El Nagdi was born in 1915 and died in 1980. Similar to Oweis, El Nagdi most often took up the secondary roles of servants, doormen, and policemen. In addition to his acting career, El Nagdi was a screenwriter who authored screenplays for many movies. When he wasn't acting or writing screenplays, El Nagdi used to make up and sell jokes to some of the most prominent comedians of the time.

&nbsp;

## Farid Shawqy: 332 Movies
![Shawqy]({{site.baseurl}}/assets/images/EgyptianMovies/Farid_Shawqi.jpg)

Farid Shawqy was a very well known Egyptain actor, screenwriter, and producer born in 1920. Whether it be by acting, writing, or producing, Shawqy's contributed to over 400 works. Throughout his 50 year career, Shawqy earned numerous rewards for his contributions to the industry and acting performances. Shawqy died in the summer of 1998.

&nbsp;

## Hussain Ismael: 306 Movies
![Hussain]({{site.baseurl}}/assets/images/EgyptianMovies/Ismael.jpg)

Hussain Ismael was an actor born in 1922. Like Abdelghani El Nagdi and Motawea Oweis, Ismael was well known for his secondary roles. Although his characters were usually minor ones, Ismael often succeeded at creating a brilliant little touch of humor that made him memorable in the eyes of his audience.

&nbsp;

Now that we have introduced our actors individually, we can start digging deeper and compare their works.

&nbsp;

## Genres


![Genres Heatmap]({{site.baseurl}}/assets/images/EgyptianMovies/Top_5_Genres.png)

Here we first see a little observation that will repeat throughout this article: drama is a *very* common genre. So common, it almost left the remainder of heatmap very dark and purple-like. However, since we will come back to this little discussion later in the article, let us ignore it for now.

Interestingly enough, even though El Meleigy has the largest *total* number of works, his record breaks once we look at the genres individually.

For the rest of our actors, we can see some interesting specialties! By decently large margins, El Nagdi favored comedies, Oweis dramas, and Ismael romances. Whether their records will hold outside this group or not is a question we will come back to later on.

&nbsp;
## Activity

When were our actors at the peak of their activity? From the earlier mini biographies, we know they all lived during the mid-to-late 20th century. Let us explore this further.

![Top 5 Activity]({{site.baseurl}}/assets/images/EgyptianMovies/Top_5.png)

All of the actors seem to have begun their careers some time between 1930 and 1950. With the exception of Ismael, all of them actors had long careers, with Shawqy and Oweis produced works up until the early 2000's.




  Hussain Ismael's graph, in particular, stands out the most. Although his career was relatively short, he showed an astounding consistency in contributing to a very large number of movies every year. One possible explanation is Ismael being known for participating in nameless secondary roles. Since such roles are less demanding of an actor's time, it could have been that he was available for more roles than his contemporaries.  This might also explain El Meleigy and  Shawqy's smaller peaks, as they are the only actors in the group who are known for actively playing lead roles.


&nbsp;
> Despite being contemporaries, all 5 were present together in only one movie: Fatwat Al-Huseeinya  (1954)

&nbsp;

Is it purely coincidental, though, that all of our actors came from the same time period? Most likely not.

One possible theory could be that there were more movies being produced in the 20th century, and less actors to play roles in them. To investigate this further, let us ask two questions:
1. Were there more movies being produced in the 1950-80's than in recent years?
2. Were there less actors in the 1950-80's than there are now?

&nbsp;

To answer the first question, let us look at the number of movies produced over the years

![Movies Released Per Year]({{site.baseurl}}/assets/images/EgyptianMovies/Movies_Per_Year.png)



Although there were large drops of production in the early 1980's and early 2000's, overall the number of movies released each year in the period between 1950 and 1980 is more or less very similar to the average of the past 15 years.  It seems, then, that the answer to our first question is "No"; there are about as many movies being released now as there were back then.

Next, let us observe the number of actors working in the field each year.



![Active Actors Per Year]({{site.baseurl}}/assets/images/EgyptianMovies/Actors_Per_Year.png)

Ah! It appears we have guessed correctly. There are indeed far more actors today than 60 years ago! Since we just earlier concluded that there is no overall increase in the number of movies being produced, we have good reason to believe that actors in the past were on a much lower supply for an equal demand. If we were to crudely model this factor of supply and demand as a ratio between the number of actors and the number of movies, we will observe the following:

![Actors to Movies]({{site.baseurl}}/assets/images/EgyptianMovies/Actors_to_Movies.png)



As we can see, the ratio of actors to movies nearly doubled in the past 50 years.

&nbsp;

## Movie Lengths

Did any of the actors have a larger presence in shorter (< 40 minutes) or longer (> 120 minutes) movies? Here we'll take a look at each of the actors' shortest longest, and average movie lengths.

| Actor               | Shortest Movie    |         | Longest Movie     |          | Average Duration |
| ------------------- | ----------------- | ------- | ----------------- | -------- | ---------------- |
| Mahmoud El Meleigy  | على أد لحافك      | 72 mins | الناصر صلاح الدين | 180 mins | 105 mins         |
| Motawea Oweis       | الذئب             | 70 mins | المطب             | 180 mins | 107 mins         |
| Abdelghani El Nagdi | رجل وحصان         | 35 mins | الرجل الثاني      | 170 mins | 104 mins         |
| Farid Shawqy        | رجل لا يعرف الخوف | 69 mins | أمير الانتقام     | 165 mins | 105 mins         |
| Hussain Ismail      | رجل وحصان         | 35 mins | الرجل الثاني      | 170 mins | 105 mins         |


Funnily enough, both El Nagdi and Ismail shared their longest and shortest works. As for the rest, none of them seemed to have participated in any movie that was less than an hour long. On average though, it doesn't appear that any of the actors was more likely to appear in movies that were notably short or long.

&nbsp;

# The Actors with the Largest Number of Works by Genre

&nbsp;

Which actors contributed the most to the popular genres? Let us start by figuring out which genres are actually the most popular.

![Movies per Genre]({{site.baseurl}}/assets/images/EgyptianMovies/Movie_Per_Genre.png)

Similar to what we have observed earlier, there are *lots* of dramas. So there is a good chance it's just a catch-all genre. Tailing right behind dramas are comedies, thrillers, and romances, with comedies being the most popular of the lot. Comedies being popular will probably come off as unsurprising to most. As a child, at least, I remember comedies being a common topic of conversation.

Now that we have identified the most popular genres, let us discuss the actors with the largest number of works in each:

&nbsp;

## Drama: Motawea Oweis | 214 Movies
&nbsp;
## Thriller: Farid Shawqy, Motawea Oweis | 43 Movies Each
&nbsp;
## Romance: Hussain Ismael | 57 Movies

&nbsp;

Three familiar faces appear once again! As it indeed turns out, Oweis, Shawqy, and Hussain Ismail's records in most of their genres hold across all Egyptian actors, and not just within the top 5 group.

As for the actor with the largest number of works in Comedy:

&nbsp;

## Comedy: Ismail Yasin | 103 Movies

![Ismail Yassin]({{site.baseurl}}/assets/images/EgyptianMovies/Ismail_Yasin.jpg)

Ismail Yasin was one of the most, if not the most, popular Egyptian actor of comedies of the last century. His works are often still takled about to this day. In addition to his career in the cinema, Ismail Yassin had his own theatrical troupe that produced over 50 works. At the height of his career, Ismail Yasin's movies often contained his name. Ismail Yassin was born in 1912 and died in 1972 at the age of 59.

&nbsp;
# TL;DR
&nbsp;
* Mahmoud El Meligy, Motawea Oweis, Abdelghani El Nagid, Farid Shawqy, and Hussain Ismael were the five actors with largest total number of movies.

* All top five actors were from the same time period (1950-1980). A further investigation revealed that the ratio of active Egyptain actors to movies being released was at its lowest at the time.

* Dramas and Comedies are the most common genres.

* Motawea Oweis and Ismail Yasin had the largest number of roles in dramas and comedies, respectively.

&nbsp;
&nbsp;


*WIP: Same analysis, but only on movies released the past two decades.*


*WIP: Same analysis, but on TV series.*
