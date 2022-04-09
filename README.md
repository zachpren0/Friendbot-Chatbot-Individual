# 310IndividualProject
Modified Team 48 project for Cosc 310 at UBC okanagan. 
Apis incorporated:
Twitter
Yahoo Finance 
Twitter: 
Twitter api was incorporated via setting up a twitter developer account which gives access to twitter site for the purposes of this project. Account gives keys that the bot can use to scrape the queried data. 
Twitter4j is an open source API that is for Java that i incorporated into my project that allows for the querying of Twitter data in a Java environment download is from https://twitter4j.org/en/index.html
With the twitter4j jar file downloaded and my keys from the developer account, developed with a method that queries the latest tweet from a user. The method was then called in the EventListener class whenever a user mentioned twitter
An @ sign is required in front of the twitter username so the bot knows what to query for.

<img width="535" alt="Screen Shot 2022-04-09 at 12 15 29 PM" src="https://user-images.githubusercontent.com/77454945/162593148-0ec16eb5-1500-4134-b3b9-c87b87e0e303.png">



Yahoo Finance:
Yahoo finance api just required the download of a jar file and incorporation into the eclipse project https://github.com/sstrickx/yahoofinance-api
Developed a method that takes the ticker symbol of the requested stock and uses yahoo finance to query the real time price, incorporated in the EventListener class when a user mentions stock
Requires the $ symbol before the ticker symbol so bot knows what to query.

<img width="535" alt="Screen Shot 2022-04-09 at 12 15 37 PM" src="https://user-images.githubusercontent.com/77454945/162593152-78069b88-2584-49dc-a39f-f404cafb23bb.png">

