# Fridge Smart - DeltaHacks IX Submission

<img src="/src/images/home.png" width="800"> 

## Inspiration
Ever feel the guilt of throwing out your leftover food? Ever find food in the back of your fridge that you totally forgot about since you didn’t know how to cook it? As students learning to cook for ourselves for the first time, many face the problem of food waste. Whether it's from food being left unused due to not knowing how to include it in a dish, or from leftovers never being finished, food waste has been a recurring problem in Canada. In fact, 2.3 million tonnes of avoidable household food waste is produced in Canada every year.

## What it does
FridgeSmart is a web application which acts as a recipe-making AI. The user takes a picture of their open fridge and uploads it to the website. The machine learning AI then automatically detects what items are in the fridge and outputs them onto an ingredient list. Using this data, another AI produces all possible recipes that can be made with the ingredients. It orders the recipes by whichever ones the user has the most ingredients for. If there are some missing, it'll output them as well so that the user knows exactly what they need to buy and what they don't need to. This helps prevent food waste.

<img src="/src/images/presentation_1.png" width="500"> <img src="/src/images/presentation_2.png" width="500"> 

## How we built it
Users upload their images onto a React web app. The image gets processed through our custom YOLO v8 model hosted on Roboflow. After getting a list of ingredients detected, we use the Spoonacular API to find recipes and update the React state.

### Challenges we ran into
- Steep learning curve as we were all new to Javascript and jumped straight to using React and JSX 
- APIs did not provide a lot of data and sometimes gave inaccurate readings

### Accomplishments that we're proud of
- Incorporated machine learning for the first time for some of us! 
- The fridge animation!
- Website is visually appealing!

### What we learned
- We learned about frontend frameworks!
- We learned how to integrate APIs!

## What's next for FridgeSmart
We hope to add an option to manually add ingredients which didn't make it into the picture the user took. We may want to organize the recipes by type of cuisine and recommend the user dishes based on their past cooking selections. We could also consider providing environmentally friendly composting options. Also healthy recipe highlights!

__Built With:__
- Javascript
- React

More information provided on our [DevPost](https://devpost.com/software/fridgesmart).
Our presentation slides can be found [here](https://docs.google.com/presentation/d/10Ds7oKdDYMz2oKDj0MpJ8OjkEwE8MajuWW2J3WLEeVo/edit?usp=sharing).

*Background Art Creds to ArseniXC.*
