# Fridge Smart

<img src="/src/images/home.png" width="800"> 
## What it does
FridgeSmart is a web application which acts as a recipe-making AI. The user takes a picture of their open fridge and uploads it to the website. The machine learning AI then automatically detects what items are in the fridge and outputs them onto an ingredient list. Using this data, another AI produces all possible recipes that can be made with the ingredients. It orders the recipes by whichever ones the user has the most ingredients for. If there are some missing, it'll output them as well so that the user knows exactly what they need to buy and what they don't need to. This helps prevent food waste.

## How to use our webapp!
Upload an image of your open fridge! 📥
Click get recipes by hovering over the fridge! 🍽
Scroll down and enjoy your recipes! 🥳

<img src="/src/images/presentation_1.png" width="500"> <img src="/src/images/presentation_2.png" width="500"> 

## How we built it
Users upload their images onto a React web app. The image gets processed through our custom YOLO v8 model hosted on Roboflow. After getting a list of ingredients detected, we use the Spoonacular API to find recipes and update the React state.

__Built With:__
- Javascript
- React
