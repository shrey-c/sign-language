# Submission for UBC LHD Build Day

## The Problem
In the USA, there are 250 000 to 500 000 individuals who know ASL. Out of the total population, that is .2%. Most of these individuals are deaf or hard of hearing, and in order to interact with the world, must rely on observing mouth patterns, which can be difficult due to each individuals unique speech pattern. Furthermore, the rest of the population never realizes that ASL is a learnable and simple language, so it is rarely used except for those close to the hard of hearing. 

## Our Solution 
Our solution is a web app that quickly translates either speech or text to ASL. Users can either type or speak directly to the web app, and in return, are given a translation of their speech in ASL. For common phrases, it returns a picture describing the motion, while other words are directly translated using the ASL alphabet. A Google Cloud Speech-to-Text API that utilizes neural networks is able to translate speech with astounding accuracy. The app is easy to use, and more efficient than searching up commands. This creates a pathway for those hard of hearing and those who have never been introduced to ASL.

## How we built it 
We used the Flask framework to build a simple back end. Our front-end is coded in CSS and HTML. We also hooked up a Google Cloud Speech to Text API.

## Challenges we ran into
The biggest we faced was creating the front end. Both members of the team have never used CSS or HTML, so we were unsure of how components worked together. This lead to a lot of guessing and checking. Eventually, we got a better handle on the language. Another difficulty was linking common ASL phrases into our web app. 

## Accomplishments we are proud of
We are proud of how our front end turned out, this being the first time we have ever coded in CSS and HTML. Overall, we are proud of being able to create a web app to combat a real life issue. 

## What we learned
We learned how to send input from the user, to the back end and back to the front end as well as how to communicate with an API. Additionally, we also learned how to design a minimalistic, but functional front end. 

## Here is an example!

![An example of our project](/static/Example.png)