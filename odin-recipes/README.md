# Odin Recipes Project Guide

## Iteration 1: Initial Structure

- Inside the `odin-recipes` directory, create an `index.html` file.
- Add the usual HTML boilerplate to it.
- Inside the `<body>`, add a heading:

```html
<h1>Odin Recipes</h1>
```

---

## Iteration 2: Recipe Page

- Create a new folder inside `odin-recipes` called `recipes`.
- Inside the `recipes/` folder, create a new HTML file (e.g., `lasagna.html`).
- Add full HTML boilerplate to that new recipe file.
- Add an `<h1>` with the name of the recipe.

```html
<h1>Lasagna</h1>
```

- In `index.html`, add a link to your recipe page under the `<h1>`:

```html
<a href="recipes/lasagna.html">Lasagna</a>
```

- In your recipe page (`lasagna.html`), add a link back to the homepage for easier navigation:

```html
<a href="../index.html">Home</a>
```

---

## Iteration 3: Recipe Page Content

Each recipe page should include the following content:

1. A **free image** of the finished dish directly below the `<h1>` heading.
2. A heading titled “**Description**” followed by a paragraph or two describing the recipe.
3. A heading titled “**Ingredients**” followed by an unordered list (`<ul>`) of ingredients.
4. A heading titled “**Steps**” followed by an ordered list (`<ol>`) of steps to make the dish.

---

## Iteration 4: Add More Recipes

- Create two more recipes using the same structure as the first one.
- Add links to the new recipes in `index.html`.
- Use an unordered list to organize all the recipe links nicely:

```html
<ul>
  <li><a href="recipes/lasagna.html">Lasagna</a></li>
  <li><a href="recipes/pizza.html">Pizza</a></li>
  <li><a href="recipes/tacos.html">Tacos</a></li>
</ul>
```

Don’t worry about making the links look fancy yet. Focus on making it **functional and organized**.
