# Healthy-Recipes-Project

## Description
This project involves styling a recipe website using CSS selectors. The focus is on a specific recipe titled "Kale Caesar Quinoa Salad with Roasted Chicken." The website includes details such as the recipe name, image, description, cook time, ingredients, preparation steps, and a citation linking to the source.

## Code
## HTML (index.html)
```html
Copy code
<!DOCTYPE html>
<html>

<head>
  <title>Quinoa and Kale Salad Recipe</title>
  <link href="style.css" type="text/css" rel="stylesheet">
</head>

<body>

  <img src="https://content.codecademy.com/courses/freelance-1/unit-2/salad.jpg" alt="Kale Caeasar Salad"/>
  <h1>Kale Caesar Quinoa Salad with Roasted Chicken</h1>
  <p class="description">Kale and quinoa provide a healthy base for roasted chicken topped with a light Caesar sauce.</p>

  <p id="cook-time">Total time: 45 minutes</p>

  <h2>Ingredients</h2>
  <ul class="ingredients">
    <li>1/4 cup kale</li>
    <li>1 cup Quinoa</li>
    <li>2 tbsp Olive Oil</li>
    <li>1 chicken breast</li>
    <li>Caesar Dressing</li>
  </ul>

  <h2>Preparation</h2>
  <ol>
    <li>
      <p>Prepare quinoa and roast chicken until golden brown and 165 in middle.</p>
      <p class="time">Time: 40 minutes</p>
    </li>
    <li>
      <p>Toss quinoa, chicken, kale, and Caesar dressing until coated.</p>
      <p class="time">Time: 4 minutes</p>
    </li>
    <li>
      <p>Add walnuts and olive oil as garnish.</p>
      <p class="time">Time: 1 minute</p>
    </li>
  </ol>

  <p class="citation">Find this recipe and more <a href="http://www.myrecipes.com/recipe/kale-caesar-salad-chicken" target="_blank" class="external-link">here</a>.</p>

</body>

</html>
```
## CSS (style.css)
```css
Copy code
img {
  height: 200px;
}

.description {
  font-size: 20px;
}

#cook-time {
  font-weight: bold;
}

.ingredients li {
  list-style: square;
}

p.time {
  color: gray;
}

.external-link {
  color: SeaGreen;
}

h1, h2, p, li {
  font-family: Helvetica;
}
```
## Instructions
1. Ensure the HTML and CSS files are in the same directory.
2. Open the '**index.html**' file in a web browser to view the styled recipe website.

Feel free to modify the CSS styles to suit your preferences or the overall theme of your website.