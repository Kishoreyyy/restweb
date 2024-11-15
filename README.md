## Ex.06 RESTURANT PROJECT
## Date: 10/11/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Delicious Bites</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="hero">
    <div class="hero-content">
      <h1>Delicious Bites</h1>
      <p>Your Favorite Spot for Tasty Meals</p>
      <a href="#menu" class="btn">Explore Menu</a>
    </div>
  </header>

  <nav class="navbar">
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#menu">Menu</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>
      Welcome to Delicious Bites, where we serve the freshest and most delightful dishes.
      Our chefs use high-quality ingredients to create meals that will tantalize your taste buds.
    </p>
  </section>

  <section id="menu" class="menu">
    <h2>Our Menu</h2>
    <div class="menu-items">
      <div class="menu-item">
        <h3>Grilled Chicken</h3>
        <p>Succulent chicken grilled to perfection. $12</p>
      </div>
      <div class="menu-item">
        <h3>Vegetarian Pasta</h3>
        <p>Fresh veggies with our homemade sauce. $10</p>
      </div>
      <div class="menu-item">
        <h3>Classic Burger</h3>
        <p>Juicy beef patty with all the toppings. $8</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Address: 123 Flavor Street, Food City</p>
    <p>Email: contact@deliciousbites.com</p>
    <p>Phone: +123 456 7890</p>
  </section>

  <footer>
    <p>&copy; 2024 Delicious Bites. All Rights Reserved.</p>
  </footer>
</body>
</html>

```
## styles.css
```
/* General Styles */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
  }
  
  a {
    text-decoration: none;
    color: inherit;
  }
  
  /* Header Section */
  .hero {
    background: url('https://source.unsplash.com/1600x900/?food') no-repeat center center/cover;
    color: white;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  
  .hero-content {
    background-color: rgba(0, 0, 0, 0.5);
    padding: 20px;
    border-radius: 10px;
  }
  
  .hero h1 {
    font-size: 3rem;
    margin-bottom: 10px;
  }
  
  .hero p {
    font-size: 1.5rem;
  }
  
  .btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background: #ff6347;
    color: white;
    border-radius: 5px;
    transition: 0.3s;
  }
  
  .btn:hover {
    background: #d9534f;
  }
  
  /* Navbar */
  .navbar {
    background: #333;
    color: white;
    padding: 10px;
    position: sticky;
    top: 0;
    z-index: 1000;
  }
  
  .navbar ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 0;
    padding: 0;
  }
  
  .navbar ul li {
    margin: 0 15px;
  }
  
  .navbar ul li a {
    color: white;
    font-size: 1rem;
    text-transform: uppercase;
  }
  
  /* About Section */
  .about, .menu, .contact {
    padding: 50px 20px;
    text-align: center;
  }
  
  .about h2, .menu h2, .contact h2 {
    font-size: 2rem;
    margin-bottom: 20px;
  }
  
  /* Menu Section */
  .menu-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }
  
  .menu-item {
    background: #f4f4f4;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    width: 250px;
    text-align: left;
  }
  
  /* Contact Section */
  .contact p {
    margin: 10px 0;
  }
  
  /* Footer */
  footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
  }
  
```


## OUTPUT:
![alt text](<Screenshot 2024-11-16 005708.png>)

![alt text](<Screenshot 2024-11-16 005842.png>)

![alt text](<Screenshot 2024-11-16 005941.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
