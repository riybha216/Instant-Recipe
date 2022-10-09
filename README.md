# instant-recipe

InstantRecipe is a Reddit bot that sends queries to Reddit's r/recipes page to find custom-curated recipes for users. The goal of this bot is to reduce manual searching and reading through long-winded articles when users are looking for recipes. By simply inputting the general category and/or ingredients of the dish that users want to create, the bot will output the ingredients needed, recipe, link to the post, and save the image of finished recipe to the user's local computer.

The bot ensures that all recipes outputted includes the ingredients mentioned. If it cannot find such a recipe, it will output the recipe with the largest number of ingredients mentioned. In turn, the bot also subtly encourages people to reduce food waste, and thus, their carbon footprint, by using ingredients they already have.

This project uses PRAW (Python Reddit API Wrapper) to recieve recipes from Reddit -- see the documentation here: https://praw.readthedocs.io/en/stable/.

# What I Learned:
* Good API documentation (and, good documentation for any project!) is important. Thorough documentation can allow understanding the project's code to be easier, and can allow others to understand the code as well. Specifically, Reddit's API was thoroughly documented and clearly listed the various features of a post that could be processed.
* Readable code with comments is important. This code was written around 3 months ago, and I was able to understand why I added certain features by reading the comments and descriptive variable names.

# To-dos:
* Instead of using the command line, implement a web application that allows users to input their ingredients in a more interactive method.
* Take dietary needs (allergies, etc) into account when providing recipe outputs.
* If users don't have essential ingredients that recipes ask for, direct them to grocery stores/farmer markers near them (using Google Maps API?). 

