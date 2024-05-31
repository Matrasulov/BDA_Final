# Big Data Analysis
## FInal project presentation on Netflix data set
Link for datasets analysed [Origin of the data](https://www.kaggle.com/datasets/arnavsmayan/netflix-userbase-dataset)
     And [Secondary dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

> [!NOTE]
> The project includes presentation slides, a detailed report, code implementation


## Code implementation:  
[BDA_SurveyAnalysis.ipynb](https://github.com/Matrasulov/BDA_Final/blob/main/BDA_SurveyAnalysis.ipynb)

I made a dataset by inputting the survey results using one of the Language Models like OpenAI's **ChatGPT**. **But**, it didn't produce the full dataset, so I manually entered the survey answers of the last 10 participants.

**Python libraries used in code implementation**:
To analyze the selection method using Python and plot a graph, you can use libraries like Pandas for data manipulation and Matplotlib or Seaborn for plotting.
```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

### Dataset
Let's take a look at the **data** variable and its structure
The **data** variable is a list of dictionaries where each dictionary represents an individual's survey response. Each dictionary contains key-value pairs for various attributes related to the participant's movie-watching habits'
```
data = [
    {'Name': 'Remy', 'Gender': 'Male', 'Frequency': 'Every day or two days', 'Time_of_Day': 'Evening',
     'Movies_per_Week': 4, 'Preference': 'With wife',
     'Genres': 'Action, Comedy, Drama, Horror, Science Fiction, Romance, Documentary, Other',
     'Favorite_Movies': 'The Shawshank Redemption', 'Selection_Method': 'Watchlist',
     'Favorite_Actors': 'Robin Williams, Morgan Freeman', 'Importance_of_New_Releases': 'Very important',
     'Rewatch_Frequency': 'Often', 'Participation_in_Discussions': 'Yes', 'Device': 'TV app',
     'Satisfaction': 'Somewhat dissatisfied', 'Recommendation_Likelihood': 'Likely'}
.
.
.
]
```
Here are the details of each attribute in each dictionary:

**Name:** The respondent's name
**Gender:** The respondent's gender
**Frequency:** How often the respondent watches a movie
**Time_of_Day:** The preferred time of the day for watching a movie
**Movies_per_Week:** The number of movies watched per week
**Preference:** The respondent's preference for watching movies(e.g alone, with family etc.)






