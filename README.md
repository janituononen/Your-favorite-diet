# Your favorite diet


## Summary

Your favorite diet program helps people to eat their favorite foods every day while staying fit.



## Background

Have you ever tried any particular diet? Do you feel like you are eating unilaterally? Would you like to feel eating something new and healthy every day and at the same time get the feeling of eating your favorite foods? I have noticed in everyday life, that I have been eating the same foods all the time. Breakfast and dinner are the same every day, and for lunch and dinner the same recipes run from time to time. Why not have a program built with artificial intelligence that could tell you what you like to eat and the program would tell you healthy options from which to choose the foods you like.



## How is it used?

Users are all those who want a change in their eating habits. People who want to eat healthy and varied. Those who don’t want to pay for the services of a nutritionist or can’t afford to spend their time searching for recipes themselves.

Program operation:
- User enters age, height and weight.
- User tells how many pounds he wants to lose weight or gain weight or wants to stay the same weight.
- Program calculates database based on BMI and target kilocalories.
- User tells how many times a day he eats, including snacks.
- Program prints a list of foods. The user tells the program the foods they like. The user tells you which foods you are allergic to and whether you are vegan, for example.
- Program searches the recipes entered in the database for ready-made recipe options for the given number of dishes and snacks based on the ideal nutritional values. The      program notifies you of every meal and snack: calories, prot, carbs, fats and micronutrients (vitamins etc ..).
- User can choose which recipes he wants to use and can still edit the recipes as he wants.
- Program creates a ready-made shopping cart for the store (eg in Finland we have Foodie (S Group) and K-Ruoka (Kesko) so that the user can compare where to buy the necessary raw materials at the cheapest price.
- User can then add the desired products to the shopping cart.
- Order shopping cart can be picked in store or delivered at home.



## Data sources and AI methods

Initially, a sufficient number of recipes is needed for the program database, which could be obtained, for example, from sites that offer recipes. A sufficient number of test users is then required. The program could take advantage of the KNN algorithm, giving similar users similar recommendations. The program would be constantly evolving as the number of users increased.



## Challenges

The program gives its recommendations only to the individual. The program does not work if the recipes are meant to make food for people living in the same household who have completely different diets or preferences for different foods or different calorie or nutrient needs.



## What next?

The values of blood tests could be entered into the program, in which case the program modifies the proposed recipes so that, for example, if the user's vitamin-d level is low, it will suggest recipes with raw materials that are rich in vitamin-d. The program could add a like button to the tried and tested recipes, so that the liked recipes would remain in memory and the program could suggest them again from time to time. Other programs could be integrated into the program, such as Oura(ring) and if the program noticed the user had slept worse recently than before, the program would recommend, for example, drinking chamomile tea in the evenings.



## Acknowledgments

- [Helsingin yliopisto & Reaktor courses "Elements of AI" and "Building AI"](https://www.elementsofai.com/)
- [Foodie application](https://play.google.com/store/apps/details?id=fi.foodie.Foodie&hl=fi&gl=US)
