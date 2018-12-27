# AtheleteProfile
Bit Bucket Athelete Profile

Overview:
In this project I am creating and deploying a simple, full-stack, single-page application in Node and Angular 1.
This is a single-page application and there is no page reloads between screens.

Project Description:
The project is a multi-step or multi-screen athlete profile form that gathers standard demographic, sports and event data. Attributes used for list of data points and sports used are given below:
Data Points
Name
Date of Birth
Nationality
Location
Association (e.g. NBA, NFL)
Team (e.g. New York Giants)
Gender
Sports (Can Multiple)
About
Interests
Charities
Social Media Handles (Facebook, Twitter, Instagram, Youtube, Twitch, Snapchat)
Pets
Drinks Alcohol
Married
Profile Image (If you have time - S3 storage)
Sports
Golf
Tennis
Cricket
Basketball
Baseball
American Football
Aquatics
Archery
Automobile Racing
Badminton
Beach Volleyball
Bobsleigh
Body Building
Boxing
Cross Country Running
Cross Country Skiing
Curling
Cycling
Darts
Decathlon
Down Hill Skiing
Equestrianism
eSports
Fencing
Field Hockey
Figure Skating
Gymnastics
Ice Hockey
Martial Arts
Mixed Martial Arts
Modern Pentathlon
Motorcycle Racing
Netball
Polo
Racquetball
Rowing
Rugby
Sailing
Softball
Shooting
Skateboarding
Skeet Shooting
Skeleton
Snow Boarding
Soccer (Football)
Squash
Surfing
Swimming
Track and Field

The input form has been organized and created as given below:
Basic Info: name, sport, nationality, gender, date of birth
About: description, location, team etc
Social Media: handles
Summary: show the athlete a wrap-up screen with the info they added, and give them a way to go back and edit if there are any mistake
Submit: On submit, the payload should be sent to a simple end point which persists the profile. This should be saved to a simple free MongoDB instance, such as mLab.
List: After submission one should see a list of all profiles I have created

Technologies Used:
Node/Express
Mongoose ORM (MongoDB)
3 End Points - POST, GET, PUT
Request Param Validation - express-validator (Bonus Feature)

