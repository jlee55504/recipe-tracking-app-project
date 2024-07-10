Completed Chegg Skill's "_Recipe-tracking app project_" "_Qualified_" assessment.

![Alt text](https://github.com/jlee55504/recipe-tracking-app-project/blob/main/img/recipe-tracking-app-project%20image.png?raw=true "recipe tracking app project screenshot")

Built with:
  * React.js
  * HTML5
  * CSS3
  * Testing done with Jest

Overview:
The project displays food recipes which includes the name of the dish, its type of cuisine, a URL link to a photo of the food, the ingredients used to make the meal, preparation instructions, and a "Delete" 'button' which will delete the selected recipe. Users are allowed to create their own dishes and add them to the app with the "Create" 'button'.

App.js
The "App" 'function/component' holds the "recipes" 'variable' and "setRecipes" 
'function' which holds and 'updates' the 'data' from the "RecipeData" 'variable' 
and the "getRecipes" 'function'. The "areThereOddNumberRecipes" 'variable' holds a 'boolean value' depending on if they're an odd amount of 'items' in the "recipes" 'array'.The "checkIfRecipesAreOdd" 'function' checks if the "recipes" 'variable/array's' 'length' (the total number of items in the "recipes" 'variable/array') is odd or even and 'sets' the 'value' for the "areThereOddNumberRecipes" 'variable'. The "getRecipes" 'function' takes a "newRecipe" 'parameter' (an 'object' from "RecipeCreate.js") and calls the "setRecipes" 'function' to add new 'recipes' ('objects') to the 'recipes' 'variable/array' ('updates' the "recipes" 'variable'). The "deleteRecipe" 'function' uses the 'filter' 'method' which 'updates' the "recipes" 'variable/array'. A 'div' JSX 'element' returned with an 'h1' JSX 'element', a 'header' JSX 'element' and the "RecipeList" and "RecipeCreate" 'components'.

RecipeCreate.js
The "RecipeCreate" 'function/component' takes two 'parameters'; "getRecipes" 
(a 'function') and "areThereOddNumberRecipes" (a 'variable' containing a 'boolean'
'value') and returns a 'form JSX element' with 'input fields (all 'required')' to create a new recipe while 'clearing' the 'input elements' upon the user submitting the new 'recipe'. The "areThereOddNumberRecipes" 'variable/component' determines the background color of each 'tr JSX element'. The "initialFormState" 'object' holds all the names of the inputted data from the displayed 'form' JSX element's' 'fields' as 'keys' with empty 'strings' as 'values'. The "formData" 'variable' and the "setFormData" 'function' the 'useState' 'method' with the "initialFormState" passed as an 'argument' using the 'spread operator'. The "handleChange" 'function' handles all the 'data' inputted by users via the "setFormData" 'function'. The "handleSubmit" 'function' 'calls' the "getRecipes" 'function/component' with the "formData" 'variable' as its argument. The "styling" 'variable' holds the 'tr' JSX 'elements'' 'backgroundColor'. The "styleBackground" 'function' takes the "areThereOddNumberRecipes" 'parameter/variable' and sets the "styling" 'variable's' 'value' depending on the "areThereOddNumberRecipes" 'parameter/variable' 'value'. It's then 'called' with the "areThereOddNumberRecipes" 'parameter/variable' as an 'argument'.

RecipeData.js
The "RecipeData" 'component' contains an 'array' named "RecipeData" which holds all the 'recipes data'.

RecipeList.js
The "RecipeList" 'function/component' takes two 'parameters'; "recipes" (a 
'variable/array' from './App.js') and the "deleteRecipe" (a 'function' from 
'./App.js'). It displays the 'list/array' of 'recipes' using a 'table JSX element'. Each 'recipe' has a "Delete" 'button JSX element' allowing the 'recipe' to be deleted and updated immediately. The "getIndexToDelete" 'function' takes the 'index' of the 'recipe' to be deleted as a 'parameter' which is used as an argument with the "deleteRecipe" 'function'.  The "createRecipeTableData" 'variable' uses the '.map' 'method' on the "recipes" 'parameter' ('array') to create a 'tr' JSX 'element' containing six 'td' JSX 'elements' with the 'data' from the "recipes" 'array' and a 'button JSX element' allowing each recipe to be deleted (the "deleteRecipe" 'function'). 