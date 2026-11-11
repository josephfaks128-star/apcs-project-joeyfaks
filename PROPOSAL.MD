# Coffee Recipe App — Project Proposal

## 1. Problem

Many people enjoy making coffee at home but have difficulty finding recipes, keeping track of ingredients, and figuring out the correct measurements. My program will organize coffee recipes in one place and help users make different drinks without guessing ingredient amounts.

## 2. Target User

The target users are people who enjoy drinking coffee and want to make different coffee drinks at home. This includes beginners who need simple instructions as well as people who already make coffee and want to organize their favorite recipes.

## 3. What the Program Does

The Coffee Recipe App allows users to browse, search, save, and create coffee recipes. Users can view the ingredients and instructions for each drink. They can also change the serving size, and the program will automatically calculate the new ingredient amounts.

## 4. Features

### Must-Have Features
1. **Browse Recipes:** Users can view a collection of coffee recipes, such as iced lattes, cappuccinos, americanos, and cold brew.
2. **Add Recipes:** Users can create and save their own coffee recipes with ingredients and instructions.
3. **Search Recipes:** Users can search for drinks by name or coffee type.
4. **Serving Size Calculator:** Users can change the number of servings, and the program will automatically adjust the ingredient measurements.

### Nice-to-Have Features
1. **Favorites:** Users can save their favorite coffee recipes for easy access.
2. **Ingredient Checker:** Users can select the ingredients they have available, and the program will tell them which recipes they can make.

## 5. Data Model

The program will store information about each coffee recipe.

| Data | Type | Example |
|---|---|---|
| Recipe Name | String | Iced Latte |
| Coffee Type | String | Espresso |
| Milk Amount | Double | 200 mL |
| Coffee Amount | Double | 60 mL |
| Sugar Amount | Double | 10 g |
| Servings | Integer | 1 |
| Prep Time | Integer | 5 minutes |
| Instructions | String | Mix espresso with milk and ice |

Each recipe will be stored as an object. The program will maintain a collection of recipe objects so users can add, view, search, and update recipes.

## 6. Decision and Calculation

**Decision:**

The program will check whether the user has all the ingredients needed for a selected recipe. If the user has everything, the program will tell them they can make the drink. Otherwise, it will display the missing ingredients.

**Calculation:**

The program will calculate ingredient amounts based on the number of servings.

For example, if one iced latte requires 200 mL of milk and the user wants to make three servings:

200 × 3 = 600 mL of milk.

The program will perform this calculation for every ingredient in the recipe.

## 7. Mockup

The application will have a simple layout with a title, search bar, recipe list, and buttons.

```text
================================
        COFFEE RECIPE APP
================================

Search for a coffee: [________]

        AVAILABLE RECIPES

1. Iced Latte
2. Cappuccino
3. Americano
4. Cold Brew
5. Mocha

--------------------------------
       SELECTED RECIPE
--------------------------------

Recipe: Iced Latte

Coffee: 60 mL
Milk: 200 mL
Sugar: 10 g

Servings: [ 1 ]  [+]  [-]

[ View Instructions ]
[ Add to Favorites ]
[ Check Ingredients ]

================================
```

## 8. Why I Chose This Project

I chose this project because coffee is something many people enjoy, and I thought it would be interesting to create an application that makes preparing different drinks easier. I also like that the project can start with basic recipe storage and calculations and eventually grow to include more advanced features. It will allow me to practice important Java programming skills such as objects, arrays or ArrayLists, methods, searching, and calculations.
