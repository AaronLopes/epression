# Epression

#Inspiration
We knew how big of a problem depression is and the complications it could cause so we set out to find a way that would let parents and loved ones of a depressed individual know that their loved one is depressed. That is when we came across the idea that to be able to detect depression, we could look at a sentiment analysis of a user’s social media page to see how trends of emotion were seeming to go.

#What it does
Epression is able to use natural language processing technology and machine learning algorithms of integrated apis to extract semantic meta-data from content in order to obtain the necessary components from pages to have Alchemy’s sentiment analyzer give us the analytics for social media pages being examined. From there, we are able to determine whether or not the sentiment in a particular user’s social media page is uncommonly negative and if so, state that the account holder of the social media page should go to a physician to properly diagnose them and complete the necessary steps to get them help. A graph is also displayed, which portrays the change of sentiment in the social media page over time.

#How we built it
We integrated a variety of features in Alchemy’s API into our project. We built the application using Ionic and AngularJS, which allowed us to test and deploy on iOS, web, and Android. We made our app take in social media page typed in by the user and then use ajax calls to obtain the necessary text from the social media page which was then analyzed by Alchemy’s API and outputted a sentiment analysis of the text in a JSON file. We then parsed through the JSON file and got the necessary sentiment values we needed in order to classify the social media page. If the sentiment values were uncommonly negative then our app would display a message stating that the account holder of the social media page should visit a physician to see if they have depression as the sentiment analysis of their posts shows that they might.

#Challenges we ran into
Incorporating Alchemy’s API was challenging as sending it the necessary info obtained from ajax calls was difficult as we had to experiment with passing different types of data without being able to manually parse through it to get the desired format. This caused us to have to use a variety of API calls before finally finding the right one. Also, using ionic caused us to run into some challenges as its format was not one that we were used to so it took some time to familiarize ourselves with it.

#Accomplishments that we're proud of
Building it. This was not an easy project to build as we had to use many tools that we had not used before and experiment with them. Incorporating APIs while using angular js and ionic and parsing through JSON files was a complicated task as we were not used to the format of the calls.

#What we learned
We learned a lot about working s a team throughout this hackathon as we were together for such a long period of time and had to regroup every few hours to make sure each one of us was on task and on pace to complete their part.

#What's next for Epression
Expanding Epression to more than just a few media sites is the goal. In addition, incorporating sources for those depressed to get help on our app is another feature we would like to add.

.tech domain www.epression.tech
