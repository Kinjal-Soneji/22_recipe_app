# Recipe App

A modern web application for browsing and managing recipes with a clean, responsive interface. The app fetches recipe data from the DummyJSON API and displays it in an attractive card layout with detailed view functionality.

## Features

- Display recipes in a responsive grid layout
- Show detailed recipe information including:
  - Recipe name
  - Cuisine type
  - Ingredients list
  - Meal type
  - Rating
  - Recipe image
- Loading animation while fetching data
- Smooth scrolling to recipe details
- Ability to add new ingredients to existing recipes
- Responsive design that works across different screen sizes

## Technologies Used

- HTML5
- CSS3 (with Grid and Flexbox)
- Vanilla JavaScript
- Fetch API for data retrieval
- DummyJSON API for recipe data

## Project Structure

```
recipe-app/
├── index.html
├── style.css
└── main.js
```

## Setup and Installation

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Navigate to the project directory:
```bash
cd recipe-app
```

3. Open `index.html` in your preferred web browser

Note: You'll need an active internet connection to fetch recipe data from the DummyJSON API.

## Usage

- The main page displays a grid of recipe cards
- Each recipe card shows:
  - Recipe image
  - Recipe name
  - Cuisine type
  - List of ingredients
  - Meal type
  - Rating
- Click the "Recipe Details" button to view more information about a specific recipe
- Use the add ingredients form to append new ingredients to existing recipes

## CSS Features

- CSS Grid for responsive layout
- Custom loader animation
- Gradient backgrounds for recipe cards
- Smooth transitions and animations
- Mobile-responsive design

## JavaScript Functionality

- Asynchronous data fetching
- Dynamic DOM manipulation
- Event handling for user interactions
- Smooth scrolling implementation
- Loading state management

## API Integration

The app uses the DummyJSON API with the following endpoints:
- GET `https://dummyjson.com/recipes` - Fetch all recipes
- GET `https://dummyjson.com/recipes/{id}` - Fetch specific recipe details

## Future Enhancements

- Add search functionality
- Implement filtering by cuisine type and meal type
- Add recipe creation capability
- Implement user authentication
- Add favorite recipes feature
- Add recipe sharing functionality
