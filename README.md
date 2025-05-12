# Ex.07 Restaurant Website
## Date:12/05/2025

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
**HTML**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Restaurant Food Menu</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <header>
        <h1>Hotel Restaurant</h1>
        <h2>Food Menu</h2>
    </header>
    <main>
        <section class="menu-category">
            <h3>Starters</h3>
            <div class="menu-item">
                <h4>Bruschetta</h4>
                <p class="description">Grilled bread with tomatoes, garlic, and basil.</p>
                <p class="price">$8.99</p>
                <img src="C:\Users\admin\Desktop\web\WhatsApp Image 2025-05-12 at 18.00.07_7dbc552c.jpg" alt="right">
            </div>

        <section class="menu-category">
            <h3>Main Courses</h3>
            <div class="menu-item">
                <h4>Grilled Salmon</h4>
                <p class="description">Fresh salmon fillet grilled to perfection.</p>
                <p class="price">$18.99</p>
                <img src="C:\Users\admin\Desktop\web\WhatsApp Image 2025-05-12 at 18.00.08_a49cc8a3.jpg" height="180px" width="200px">
            </div>
            <div class="menu-item">
                <h4>Beef Steak</h4>
                <p class="description">Juicy rib-eye steak served with mashed potatoes and vegetables.</p>
                <p class="price">$22.99</p>
                <img src="C:\Users\admin\Desktop\web\WhatsApp Image 2025-05-12 at 18.00.07_cae7cad0.jpg" >
            </div>
        </section>

        <section class="menu-category">
            <h3>Desserts</h3>
            <div class="menu-item">
                <h4>Chocolate Cake</h4>
                <p class="description">Rich and moist chocolate cake with a layer of creamy frosting.</p>
                <p class="price">$6.99</p>
                <img src="C:\Users\admin\Desktop\web\WhatsApp Image 2025-05-12 at 18.00.07_f6ba7399.jpg" height="160px" width="200px" >
            </div>
            <div class="menu-item">
                <h4>Tiramisu</h4>
                <p class="description">Classic Italian dessert made with coffee-soaked ladyfingers and mascarpone cream.</p>
                <p class="price">$7.99</p>
                <img src="C:\Users\admin\Desktop\web\WhatsApp Image 2025-05-12 at 18.00.07_bc6af115.jpg" >

            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Hotel Restaurant. All rights reserved.</p>
    </footer>
</body>
</html>

```
**CSS**
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: Arial, sans-serif;
    background-image: url(img1.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    color: #333;
}

header {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 20px 0;
}

header h1 {
    font-size: 3em;
    margin-bottom: 10px;
}

header h2 {
    font-size: 1.5em;
}

main {
    padding: 20px;
}

.menu-category {
    margin-bottom: 30px;
}

.menu-category h3 {
    font-size: 2em;
    text-align: center;
    margin-bottom: 15px;
    color: #ffffff;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.menu-item {
    background-color: white;
    margin: 10px 0;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.menu-item h4 {
    font-size: 1.5em;
    margin-bottom: 10px;

}

.menu-item .description {
    font-size: 1em;
    margin-bottom: 10px;
}

.menu-item .price {
    font-size: 1.2em;
    font-weight: bold;
    color: #f75c03;
}

footer {
    text-align: center;
    padding: 10px 0;
    background-color: #333;
    color: white;
    margin-top: 30px;
}

```

## OUTPUT:
![alt text](image.png)
![alt text](image-1.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
