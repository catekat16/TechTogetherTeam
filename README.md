# Sincerely, Your Penpal
Pen pal matching & communication app (we will be matching users to their pen pal based on the interests they indicated, and use ML to determine the personality of the user based on their Twitter tweets). Once matched, pen pals have the ability to create customized letters and upload videos to send each other (with a delay in time, as based on their real-life locations)

## Inspiration
Covid has changed the way how people interact with each other. In the middle of the pandemic, with no chance of attending events physically and meeting people with similar interests and ways of self-care, we thought it would be great to re-introduce the concept of letter-writing for meeting new people

## What it does
With a machine Learning model using a Kaggle dataset to predict the personality type of a person. Data is taken from the past 50 posts of the users twitter account to get an accurate idea of the personality type. Additionally, people enter their interests (finance/economics/UI design/ programming/software development, etc) and ways of self-care (art therapy, mindfulness, yoga, running, gymming, eating healthy, etc). Based on these three parameters, we find your perfect match.

## How we built it
* The Machine learning model was built using the scikit learn library available in python. The model was then stored using joblib. Data was collected from a user through a website whose backend was supported in flask. 
* Figma was used to sketch the look and feel of the website. Posthaste, work was started on the front-end web development in HTML, CSS, JS.
* Flask is used in the backend to deploy the machine learning model on the website and collect data from the user.

## Challenges we ran into
* Ppeople located in different timezones, scheduling meets and passing on work took good documentation
* Getting accuracy in the Machine Learning model was difficult, since it used unclean textual data and required data processing
* Attempts was made to use the Figma for HTML plugin - but that gave very bad results. So the website was coded from scratch.

## Accomplishments that we're proud of


## What we learned




## What's next for Sincerely, Your Penpal
* Improving the accuracy of the model

