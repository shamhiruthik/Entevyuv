## Comment2Likes: Estimating Video Likesusing Comment Data - `completed`
### Author - Sham Hiruthik

## Problem Statement:

The objective of the "Comment2Likes: Estimating Video Likes using Comment Data" project is
to develop a predictive model that can estimate the number of likes a video will receive based
on the information extracted from its comments. By leveraging the valuable insights present in
user comments, this project aims to provide content creators, marketers, and platform
administrators with a tool to gauge the potential popularity of their videos and optimize their
content strategies accordingly.

## About Data:

This dataset contains two files for analyzing the relationship between the popularity of a certain
video, the most relevant/liked comments of said video and like counts
## File Descriptions
`videos-stats.csv:`This file contains some basic information about each video, such as the title, likes, views,
keyword, and comment count.
`comments.csv:` For each video in videos-stats.csv, comments.csv contains the top ten most relevant
comments as well as said comments' sentiments and likes.

## Column Descriptions
### videos-stats.csv:

● Title: Video Title.
● Video ID: The Video Identifier.
● Published At: The date the video was published in YYYY-MM-DD.
● Keyword: The keyword associated with the video.

● Likes: The number of likes the video received. If this value is -1, the likes are not
publicly visible.
● Comments: The number of comments the video has. If this value is -1, the video creator
has disabled comments.
● Views: The number of views the video got.

### comments.csv:

● Video ID: The Video Identifier.
● Comment: The comment text.
● Likes: The number of likes the comment received.
● Sentiment: The sentiment of the comment. A value of 0 represents a negative
sentiment, while values of 1 or 2 represent neutral and positive sentiments respectively.

