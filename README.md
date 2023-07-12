# StudentMentalHealth

## DataCollection
* DataCollection.ipynb: Code for gathering reddit submission for uAlberta subreddit from January 1, 2019 to June 30, 2022 using Pushshift.

* RedditPosts.csv: Reddit submissions (reddit dataset)

## DataPreprocessing
* DataPreprocessing.ipynb: Code for preprocessing the reddit dataset.

* PreprocessedPosts.json: Preprocessed reddit data.

## TopicModeling
* LDA.ipynb: Code of the LDA model trained for topic modeling on the reddit dataset.

* coherence1.png: Coherence for varying number of topics extracted using topic modeling (LDA model) from the reddit dataset.

* Model: Files for trained LDA model with 11 number of topics.

* TopicDistribution.ipynb: Code for extracting topic distribution percentage for each post in the reddit dataset.

* TopicDistribution: json and csv files with topic distribution for each post in the reddit dataset.

* MentalHealth80.csv / MentalHealth80.json: Dataset of all the posts in the reddit dataset with topic distribution for mental health topic higher than 80%.



## MentalHealthData
* MentalHealthData.ipynb: Code of creating a dataset of posts relating to mental health of students and extracting comment ids for these posts.

* MentalHealthData.json: Dataset of posts relating to mental health extracted using combining the posts that made the 80% threshold of mental health topic from topic modeling and the posts that explicitly contained the words from mental health lexicon in them. (mental health dataset)

* Comments.csv: Dataset of comment ids for the posts in mental health dataset.

## Analysis
* Analysis.ipynb: Code of the analysis performed on the various snippets of the mental health dataset.

* fig1.png: Distribution of mental health posts in uAlberta subreddit from January 1, 2019 to June 30, 2022.

* fig2.png: Distribution of posts in uAlberta subreddit from January 1, 2019 to June 30, 2022.

* fig3.png: Number of posts made at an X time of the day.

* fig4.png: Number of posts made on the X day of the week.

* fig5.png: Number of posts made at an X time of the day on the Y day of the week.

* coherence2.png: Coherence for varying number of topics extracted using topic modeling (LDA model) from the mental health dataset.

* MentalHealthTopics.json: Top 15 terms for 5 number of topics from mental health dataset with relevancy metric set to 0.1.

* CSMentalHealth.json: Dataset of all the posts from mental health dataset relating to computing science.

* MentalHealthResources.json: Dataset of all the posts from mental health dataset directly speaking about mental health resources available for students at the UofA with sentiment analysis performed.
