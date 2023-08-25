# Anime-Recommender

This was a simple project where I used transformers in order to predict ratings of anime based off a users top 5 anime. 

# Architecture 

The transformer was fed the metadata of the top 2000 anime (# episodes, MAL rating, genre, etc) and over 60k instances of MAL user top 5 anime data. With this, the transformer was able to make connections between metadata and users top choices. Such that it could recognize any patterns that would emerge. 

# Results
Here is an example result. It would output the names of the top 25 anime that were rated the highest for the user. 
![image](https://github.com/durzal1/Anime-Recommender-/assets/67489054/44598d3e-caad-417a-b540-43276305f4d2)

# Patterns
I tested this out on 8 different top 5 lists and i noticed the transformer favored those anime that had a higher MAL rating since it was on more user top 5 lists. Thus, there were be certain anime in all lists no matter what they fed in such as Gintama and Your Name. 

Overall, it was able to create a list that was semi-accurate. 
