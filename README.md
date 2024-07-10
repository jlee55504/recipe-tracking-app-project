Completed Chegg Skill's "_Recipe-tracking app project_" "_Qualified_" assessment.

App.js
The "App" 'function/component' holds the "recipes" 'variable' and "setRecipes" 
'function' which holds and 'updates' the 'data' from the "RecipeData" 'variable' 
and the "getRecipes" 'function'. The "deleteRecipe" 'function' uses the 'filter' 
'method' 'updates' the "recipes" 'variable/array'. A 'div' JSX 'element' returned 
with an 'h1' JSX 'element', a 'header' JSX 'element' and the "RecipeCreate" 
'component'.

RecipeCreate.js
The "RecipeCreate" 'function/component' takes three 'parameters', "getRecipes" 
(a 'function'), "deleteRecipe" (a 'function') and "recipes" (a 'variable/array'), 
and returns a 'form JSX element' with 'input fields (all 'required')' to create a 
new recipe while 'clearing' the 'input elements'. 

RecipeData.js
The "RecipeData" 'component' contains an 'array' named "RecipeData" which holds all 
the 'recipes data'.

RecipeList.js
The "RecipeList" 'function/component' takes two 'parameters'; "recipes" (a 
'variable/array' from './App.js') and the "deleteRecipe" (a 'function' from 
'./App.js'). It displays the list of 'recipes' using a 'table JSX element'. 
Each 'recipe' has a "Delete" 'button JSX element' allowing the 'recipe' to be 
deleted and updated immediately. 