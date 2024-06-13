<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bella Hernandez - Vegan Recipes</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            background-color: #e8f5e9;
            color: #2e7d32;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #66bb6a;
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #388e3c;
            padding: 1rem 0;
        }
        nav a {
            color: white;
            margin: 0 1.5rem;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem;
        }
        section {
            margin-bottom: 2rem;
            padding: 1.5rem;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        h2 {
            color: #388e3c;
            border-bottom: 2px solid #66bb6a;
            padding-bottom: 0.5rem;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        footer {
            background-color: #66bb6a;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Fork and Wander</h1>
    <p>Unveiling the Delicious: A Vegan Foodie's Imperfect Journey</p>
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#recipes">Recipes</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="about">
        <h2>About Me</h2>
        <p>Hey everyone!   I'm Bella, just a regular ol' culinarian (or "foodie" if you prefer) on a mission to shatter vegan stereotypes. Let's face it, sometimes vegan options get a bad rap: bland, boring, and let's not forget – expensive! But trust me, it doesn't have to be that way.

I believe vegan food can be an explosion of flavor, fresh, budget-friendly, and anything but boring.  In fact, I'm obsessed with unlocking the potential of everyday ingredients to create mouthwatering, plant-based dishes inspired by global cuisines.

Come along with me on this delicious adventure!  I'll be sharing recipes, tips, and maybe even some imperfect moments along the way (because hey, nobody's perfect!).  Get ready to explore the incredibly diverse and satisfying world of vegan food, one flavorful bite at a time!</p>
    </section>

    <section id="recipes">
        <h2>Recipes</h2>
        <p>Explore my collection of 100 recipes per vegetable from around the world. Let's start with some amazing eggplant recipes:</p>
        <ul>
            <li>Grilled Eggplant with Garlic Sauce</li>
            <li>Eggplant Parmesan</li>
            <li>Baba Ganoush</li>
            <li>Szechuan Spicy Eggplant</li>
            <li>Stuffed Eggplant</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me at:</p>
        <p>Email: <a href="mailto:bellaph.hernandez@gmail.com">bellaph.hernandez@gmail.com</a></p>
    </section>
</div>

<footer>
    <p>&copy; 2024 Bella Hernandez. All rights reserved.</p>
</footer>

<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bella Hernandez - Vegan Recipes</title>
<style>
    body {
        font-family: 'Helvetica Neue', Arial, sans-serif;
        background-color: #e8f5e9;
        color: #2e7d32;
        margin: 0;
        padding: 0;
    }
    header {
        background-color: #66bb6a;
        color: white;
        padding: 2rem 0;
        text-align: center;
    }
    nav {
        display: flex;
        justify-content: center;
        background-color: #388e3c;
        padding: 1rem 0;
    }
    nav a {
        color: white;
        margin: 0 1.5rem;
        text-decoration: none;
        font-weight: bold;
    }
    nav a:hover {
        text-decoration: underline;
    }
    .container {
        max-width: 1000px;
        margin: 0 auto;
        padding: 2rem;
    }
    section {
        margin-bottom: 2rem;
        padding: 1.5rem;
        background-color: #ffffff;
        border-radius: 8px;
        box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    h2 {
        color: #388e3c;
        border-bottom: 2px solid #66bb6a;
        padding-bottom: 0.5rem;
    }
    .recipe {
        cursor: pointer;
        margin-bottom: 1rem;
    }
    .recipe h3 {
        margin-bottom: 0.5rem;
    }
    .recipe-content {
        display: none;
        padding: 1rem;
        border-top: 1px solid #ddd;
    }
    footer {
        background-color: #66bb6a;
        color: white;
        text-align: center;
        padding: 1rem 0;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
</style>
</head>
<body>
**Recipes**
<section>
  <h2>Explore My Vegan Delights</h2>
  <div class="recipe">
    <h3>Grilled Eggplant with Garlic Sauce</h3>
    <div class="recipe-content">
      **Ingredients:**
      <ul>
        <li>1 large eggplant, sliced</li>
        <li>2 tablespoons olive oil</li>
        <li>1/2 teaspoon salt</li>
        <li>1/4 teaspoon black pepper</li>
        <li>3 cloves garlic, minced</li>
        <li>1/4 cup chopped fresh parsley</li>
        <li>1/4 cup lemon juice</li>
      </ul>
      **Instructions:**
      <p> (detailed recipe instructions here) </p>
    </div>
  </div>
  </section>

<script>
const recipeTitles = document.querySelectorAll('.recipe');

recipeTitles.forEach(recipe => {
  recipe.addEventListener('click', function() {
    const content = this.nextElementSibling; // Target the next sibling element (recipe-content)
    content.style.display = content.style.display === 'none' ? 'block' : 'none';
  });
});
</script>

<footer>
  © 2024 Bella Hernandez. All rights reserved.
  </footer>
</body>
</html>

</body>
</html>


