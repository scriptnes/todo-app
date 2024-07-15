# Cooking Demo ToDo App

This repository contains a demo preset for a cooking ToDo app. The preset includes three recipes: Spaghetti Carbonara, Chicken Curry, and Chocolate Chip Cookies. Each recipe is broken down into tasks for buying ingredients and step-by-step instructions for preparing the dish.

## JSON Structure

The JSON structure follows a specific format to ensure compatibility with the ToDo app. Each recipe is a ToDo item with tasks split into shorter strings to fit within the app's width constraints.

## Demo Preset

Here is the demo preset in JSON format:

Usage
To use this preset, simply copy the JSON structure and import it into your ToDo app. The tasks are designed to be concise and split into shorter strings to ensure they fit within the app's width constraints.

License
This project is licensed under the MIT License - see the LICENSE file for details.

```json
{
  "id": "demo-cooking-preset",
  "tourName": "Cooking Demo",
  "tourNumber": "101",
  "tourModel": "Cook-Demo",
  "totalTodos": 3,
  "totalTasks": 0,
  "totalCompletedTasks": 0,
  "createdAt": "2024-07-15T12:00:00.000Z",
  "updatedAt": "2024-07-15T12:00:00.000Z",
  "todos": [
    {
      "name": "Spaghetti Carbonara",
      "startDate": "2024-07-15T12:00:00.000Z",
      "tasks": [
        "Buy Ingredients: Spaghetti, Eggs, Pancetta,",
        "Parmesan cheese, Garlic, Salt, Pepper",
        "Cook spaghetti according to package instructions.",
        "In a separate pan, cook pancetta until crispy.",
        "Beat eggs and mix with grated Parmesan cheese.",
        "Combine cooked spaghetti with pancetta and garlic.",
        "Remove from heat and quickly mix in egg and cheese mixture.",
        "Season with salt and pepper to taste.",
        "Serve immediately."
      ],
      "completedTasks": [],
      "editableTask": null,
      "taskEdits": "",
      "taskMenuVisible": null
    },
    {
      "name": "Chicken Curry",
      "startDate": "2024-07-15T12:00:00.000Z",
      "tasks": [
        "Buy Ingredients: Chicken breast, Onions, Garlic, Ginger,",
        "Tomato paste, Coconut milk, Curry powder,",
        "Salt, Pepper, Olive oil, Rice",
        "Heat olive oil in a pot and sauté onions, garlic, and ginger.",
        "Add chicken breast pieces and cook until browned.",
        "Stir in tomato paste and curry powder.",
        "Pour in coconut milk and bring to a simmer.",
        "Cook until chicken is fully cooked and sauce has thickened.",
        "Season with salt and pepper to taste.",
        "Serve with cooked rice."
      ],
      "completedTasks": [],
      "editableTask": null,
      "taskEdits": "",
      "taskMenuVisible": null
    },
    {
      "name": "Chocolate Chip Cookies",
      "startDate": "2024-07-15T12:00:00.000Z",
      "tasks": [
        "Buy Ingredients: All-purpose flour, Baking soda, Salt,",
        "Butter, Sugar, Brown sugar, Vanilla extract,",
        "Eggs, Chocolate chips",
        "Preheat oven to 350°F (175°C).",
        "In a bowl, mix flour, baking soda, and salt.",
        "In a separate bowl, cream together butter, sugar, and brown sugar.",
        "Beat in vanilla extract and eggs.",
        "Gradually add dry ingredients to wet ingredients.",
        "Stir in chocolate chips.",
        "Drop dough onto baking sheet and bake for 10-12 minutes.",
        "Let cool on a wire rack before serving."
      ],
      "completedTasks": [],
      "editableTask": null,
      "taskEdits": "",
      "taskMenuVisible": null
    }
  ]
}

