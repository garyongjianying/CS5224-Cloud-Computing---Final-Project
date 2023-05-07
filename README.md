# CS5224-Cloud-Computing---Final-Project
CS5224 Cloud Computing Final Project - PlayPal implementation on AWS

PlayPal is a cloud-based web application targeting sports enthusiasts serving as a one-stop
site to host, find and join leisure sports activities. Users can create events for others to join,
or participate in existing events created by other users. The service recommends users a
list of upcoming activities hosted by other users based on their preferences and interests.


Data Source:
https://data.gov.sg for sports-related data and SportSG Sport Facilities and SportsFields@SG

Utilized the following:
AWS Lambda - perform role of recommender for logged in users (using cosine similarity for recommending users that are nearby and have similar sports interests)
MongoDB Atlas
AWS S3 for object storag
AWS EC2 instances for hosting
AWS Simple Email Services - to notify users via email for user registration and verify account details
