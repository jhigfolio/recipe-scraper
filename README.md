# Recipe Scraper
A simple scraper to get around the fluff stuff (and ads!) in the the standard blog recipes you find on the web today. Gets the ingredients and directions. That's it.
## How To Use:
1. Make sure you have NodeJS installed on your machine.
2. Clone this repo to a directory of your choice. 
3. Run ```npm install``` while in the same directory of this repo to install dependencies. 
4. Then run ```node findRecipe.js``` to run scraper. 
5. Follow the prompts to search for and save recipes. 

## Example Usage:

After running this command in your terminal:
<img src="./images/find_recipe.png"
     alt="find recipe" 
     width= "35%" />

It will ask you what you want to make. We'll say tacos (cause tacos are awesome). The recipe scraper will search google's top results for taco recipes and try to extract just the instructions and ingredients. While it does that it will display the urls it is currently searching, like this: 
<img src="./images/recipe_search.png"
     alt="search for recipe" />

After it is done searching, it will display the first recipe it found.
<img src="./images/recipe_display.png"
     alt="display recipe" />

From here, there are a few things you can. Your options are displayed below the recipe. 
<img src="./images/recipe_options.png"
     alt="display recipe"
     width= "50%" />

You can view another recipe it found if you would like.

Or you can save the recipe to a .txt file by hitting highlighting convert recipe to txt file and hitting enter.
<img src="./images/save_recipe.png"
     alt="display recipe" />

Finally, You can search for another recipe. Hope you enjoy!

## License: 
[MIT](https://choosealicense.com/licenses/mit/)
