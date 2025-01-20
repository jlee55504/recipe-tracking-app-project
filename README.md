# Recipe-Tracking App Project

An application that lists information for food recipes with the ability to add new recipes or delete recipes.

## Features

  - **Food Recipe Management:** Adds, lists, and deletes food recipe information.
  - **User-friendly Interface:** Simple structured layout for easy navigation.

## Technologies Used

  * **React.js:** Core programming language (React 18.2.0)
  * **HTML:** Visually displays the content of the application
  * **CSS:** Provides visual styling for the application
  * **Jest:** Unit testing framework

## Screenshot

![Alt text](https://github.com/jlee55504/recipe-tracking-app-project/blob/main/img/recipe-tracking-app-project%20image.png?raw=true "recipe tracking app project screenshot")

## Getting Started

### Prerequisites

  - Node Package Manager (NPM)

### Installation:

  1. Clone the repository:
     ```
     git clone https://github.com/jlee55504/recipe-tracking-app-project.git
     ```
  2. Navigate to the project directory:
     ```
     cd recipe-tracking-app-project
     ```
  3. Build the project:
     ```
     npm install
     ```
  4. Run the application:
     ```
     npm start
     ```

## Usage

Upon running the application, you'll be presented with the options to:

  1. Delete an existing food recipe
  2. Create a new food recipe

To create a new food recipe, enter the recipe information and click "Create". 
To delete a recipe, click "Delete". 

## Code Structure

  - ``index.html:`` Main application entry point
  - ``src/App.js:`` Contains the main structure of the application, updates changes made to the application, deletes selected recipes, and determines the background color to be used for food recipes
  - ``src/RecipeCreate.js:`` Handles creating new food recipes
  - ``src/RecipeData.js:`` Holds all the food recipe data
  - ``src/RecipeList.js:`` Lists all the food recipes
  - ``src/App.css:`` Handles the visual styling for the application
  - ``src/RecipeCreate.css:`` Handles the input size styling for new food recipes

## Acknowledgments

  - This project was built for the Chegg Skill's software engineering program
  - This was my first project using React.js and was extremely helpful learning the power and ease of using React  

