# Project-1-final
## How has the trending algorithm changed on YouTube between September 2020 and September 2022

## Slideshow:
https://docs.google.com/presentation/d/1WBams7DWl59welUQEDxKdqxwjmmjvi_o/edit?usp=sharing&ouid=109145600298487603219&rtpof=true&sd=true

## Technologies used:
* Python
* Pandas
* Matplotlib

## Files in the Folder
* "creating datasets" - creating datasets by year and cleaning data
* "merge data" - mergeing datasets
* "youtube data" - analsysi of datasets

## Introduction 
According to YouTube, trending helps viewers to see "what's happening on YouTube and in the world." Another purpose of the trending tab is to "surface videos and shorts that a wide range of viewers would find interesting. Trending is not personalised and is the same for all viewers in the same country. The list is updated every 15 minutes.
* According to YouTube, Trending aims to surface videos that:
* Are appealing to a wide range of viewers
* Are not misleading, clickbait or sensational
* Capture the breadth of what's happening on YouTube and in the world
* Showcase a diversity of creators
* Ideally, are surprising or novel

Trending considers many signals, including (but not limited to):
* View count
* How quickly the video is generating views (i.e. “temperature”)
* Where views are coming from, including outside of YouTube
* The age of the video
* How the video performs compared to other recent uploads from the same channel

All these factors mean that "the video with the highest view count on a given day may not be #1 on Trending, and videos with more views may be shown below videos with fewer views."

Since 2016 YouTube has been focused on brand safety which has affected the trending algorithm whereas the homepage is more affected by personalization and but so do factors such as 
* click-through rate
* average view duration
* average percentage viewed
* likes
* dislikes
* viewer surveys. 

For this project, I have chosen to analyse the YouTube videos that were ranked as trending in the months of September 2020 and September 2022 in the UK to compare the difference in trending factors between the two years.

Factors like this are important for creators to know so that they can adapt their content to the changing algorithms. Especially as YouTube does not allow them to know the full picture of the algorithms and it is down to the creator to figure them out

## Questions

* How have the views, likes and comments changed between September 2020 and September 2022 for trending videos?
* What are the different variations in video titles of trending videos?
* What are the differences in channels with the most trending videos between September 2020 and September 2022?
* Is there a difference in publishing day of trending videos between September 2020 and September 2022?


## Data Clenaing
The data used found here: https://www.kaggle.com/datasets/datasnaek/youtube-new?select=GBvideos.csv
The dataset includes months of data on daily trending YouTube videos with up to 200 listed trending videos per day. Data inlcudes tredning date, title, channel, views, likes and comnments.

I chose to use the GB dataset as well as comparing two of the months from the data set - Septemeber 2020 and September 2022. Three datasets were created one of each month and one combined. The dataset was cleaned by deleting duplicates so that the videos were only shown on the first day that they were trnding.

## Views, Likes and Comments
Compared to 2020, in 2022 videos were more likely to have a higher view count.
This could imply that either the trending algorithm relies more on videos that have higher views, more people are viewing the trending tab or more people are watching YouTube in general .

![image](https://user-images.githubusercontent.com/86980650/203623677-b5413349-c8f3-4144-9a1a-ede7cc54cb50.png)
![image](https://user-images.githubusercontent.com/86980650/203623691-4fe5dbb1-f624-41d0-8e33-7ba5da58e045.png)
![image](https://user-images.githubusercontent.com/86980650/203623718-981d4a7f-aa2a-4ca3-aed3-d6e0f10a5ed6.png)

Unlike views, the number have likes on trending videos in 2022 is similar to that in 2022
This implies that the number of likes on a YouTube video has not changed importance in the trending algorithm since 2020.

![image](https://user-images.githubusercontent.com/86980650/203624208-65fddaff-7fde-4f84-b439-39e298ddc1ff.png)
![image](https://user-images.githubusercontent.com/86980650/203624222-12d759c8-c215-4e6a-8f81-ebd70016fd67.png)
![image](https://user-images.githubusercontent.com/86980650/203624234-8003c324-31e4-4b85-8fc8-ccd935a2e2e7.png)

* Overall, 73% of videos had over 4000 comments
* In 2020 70% of videos had over 4000 comments
* In 2022 76% of videos had over 4000 comments
* This indicates that comments may be more important to the trending algorithm in 2022 than in 2020 or that videos that encourage users to engage further with their content are pushed 

How have the views, likes and comments changed between September 2020 and September 2022 for trending videos?
* Overall, video views on trending videos have increased and so have comments but likes have stayed at a similar rate.
* This implies that views and comments have gone up in importance in relation to the algorithm whereas likes have stayed the same.

## Title Variations









