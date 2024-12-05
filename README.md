# Ex.07 Restaurant Website
## Date:

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

```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Family Diner</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <div class="banner-content">
            <h1>Welcome to Our Restaurant</h1>
            <p>We serve the finest dishes made with fresh ingredients. Come visit us!</p>
        </div>
    </section>

    <footer>
        <p>Designed by [keerthika]</p>
    </footer>
</body>
</html>
 
 menu.html

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - The Family Diner</title>
    <link rel="stylesheet" href="styless.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Our Menu</h1>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="M1.jpg" alt="Pizza Margherita">
                <h2>Pizza Margherita</h2>
                <p>A classic pizza with fresh mozzarella, tomato sauce, and basil.</p>
                <p class="price">rs.400</p>
            </div>
            <div class="menu-item">
            <img src="M2.jpg" alt="Pasta Alfredo">
                <h2>Pasta Alfredo</h2>
                <p>Creamy Alfredo sauce with fettuccine pasta.</p>
                <p class="price">rs.200</p>
            </div>
            <div class="menu-item">
                <img src="M3.jpg" alt="Cheeseburger">
                <h2>Cheeseburger</h2>
                <p>A juicy beef patty with cheddar cheese, lettuce, and tomato.</p>
                <p class="price">rs.232</p>
            </div>
            <div class="menu-item">
                <img src="M4.jpg" alt="Caesar Salad">
                <h2>Caesar Salad</h2>
                <p>Crisp romaine lettuce with Caesar dressing, croutons, and parmesan.</p>
                <p class="price">rs.350</p>
            </div>
            <div class="menu-item">
                <img src="M5.jpg" alt="Spaghetti Bolognese">
                <h2>Spaghetti Bolognese</h2>
                <p>Spaghetti pasta topped with rich, flavorful meat sauce.</p>
                <p class="price">rs.555</p>
            </div>
            <div class="menu-item">
                <img src="M6.jpg" alt="Grilled Steak">
                <h2>Grilled Steak</h2>
                <p>Juicy grilled steak served with mashed potatoes and veggies.</p>
                <p class="price">rs.499</p>
            </div>
        <div class="menu-item">
            <img src="M7.jpg" alt="Double burger">
            <h2>Double burger</h2>
            <p>Full pound of meat stacked on a toastesd bun.</p>
            <p class="price">rs.222</p>
        </div>
        <div class="menu-item">
            <img src="M8.jpg" alt="Chicken sandwich">
            <h2>Chicken sandwich</h2>
            <p>Grilled or fried</p>
            <p class="price">rs.90</p>
        </div>
        <div class="menu-item">
            <img src="M9.webp" alt="BBQ">
            <h2>BBQ</h2>
            <p>Smokin' Barrel BBQ,BBQ Haven,Grill & Smoke,Flame & Ash BBQ</p>
            <p class="price">rs.750</p>
        </div>
        <div class="menu-item">
            <img src="M10.jpg" alt="BBQ pulled pork">
            <h2>BBQ pulled pork</h2>
            <p>Somked brisket served on toasted bun with onions and pickles</p>
            <p class="price">rs.444</p>
        </div>
        <div class="menu-item">
            <img src="M11.jpg" alt="Biryani">
            <h2>Biryani</h2>
            <p>chicken biryani with egg ,chicken lollypop dry</p>
            <p class="price">rs.350</p>
        </div>
        <div class="menu-item">
            <img src="M12.jpg" alt="Parotta">
            <h2>Parotta</h2>
            <p>Flaky & Hot Parottas,Golden Parotta,Parotta & Curries</p>
            <p class="price">rs.70</p>
        </div>





    </section>

    <footer>
        <p>Designed by [keerthika]</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - The Family Diner</title>
    <link rel="stylesheet" href="sty.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h1>Meet Our Team</h1>
        <div class="team-grid">
            <div class="team-member">
                <img src="chef.2.jpg" alt="Admin 1">
                <h2>sandhy</h2>
                <p>General Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.4.jpg" alt="Admin 2">
                <h2>hema</h2>
                <p>Head Chef</p>
            </div>
            <div class="team-member">
                <img src="chef.3.jpg" alt="Admin 3">
                <h2>sai</h2>
                <p>Operations Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.5.png" alt="Admin 4">
                <h2>hari</h2>
                <p>Marketing Manager</p>
            </div>
            <div class="team-member">
                <img src="type-of-chef.1.jpg" alt="Admin 5">
                <h2>bharath</h2>
                <p>HR Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.6.avif" alt="Admin 6">
                <h2>somesh</h2>
                <p>Head Waiter</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Designed by [keerthika]</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - The Family Diner</title>
    <link rel="stylesheet" href="st.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Address: 123 Restaurant St., City, Country</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@restaurant.com</p>
    </section>

    <footer>
        <p>Designed by [keerthika]</p>
    </footer>
</body>
</html>

css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

section {
    padding: 20px;
    margin: 20px;
}

section h1 {
    font-size: 2em;
    color: #333;
}

section .menu ul {
    list-style-type: none;
}

section .menu li {
    margin: 15px 0;
}

section .team-member {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

section .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Administration Section */
.administration {
    padding: 40px;
    text-align: center;
    background-color: #fff;
}

.administration h1 {
    font-size: 2.5em;
    margin-bottom: 40px;
    color: #333;
}

/* Grid Layout for Team Members */
.team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 30px;
    justify-items: center;
    padding: 20px;
}

/* Individual Team Member Card */
.team-member {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    width: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.team-member:hover {
    transform: scale(1.05); /* Slight zoom effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Team Member Image Styling */
.team-member img {
    width: 100%;
    height: 200px; /* Fixed height for uniformity */
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}

/* Team Member Name */
.team-member h2 {
    font-size: 1.5em;
    margin: 10px 0;
    color: #333;
}

/* Team Member Designation */
.team-member p {
    font-size: 1em;
    color: #777;
    margin-top: 5px;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Banner section with background image */
.banner {
    background-image: url('BG\ .1.avif'); /* Change this to the path of your image */
    background-size: cover;
    background-position: center;
    height: 400px; /* Adjust the height of the banner */
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    position: relative;
}

.banner-content {
    z-index: 1; /* Makes sure the text is above the background */
}

.banner h1 {
    font-size: 3em;
    margin: 0;
}

.banner p {
    font-size: 1.2em;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

/* Other sections styling */
section {
    padding: 20px;
    margin: 20px;
}

section h1 {
    font-size: 2em;
    color: #333;
}

section .menu ul {
    list-style-type: none;
}

section .menu li {
    margin: 15px 0;
}

section .team-member {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

section .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Menu Section */
.menu {
    padding: 20px;
    text-align: center;
}

.menu h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

/* Grid Layout for Menu Items */
.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 20px;
    justify-items: center;
    padding: 20px;
}

/* Individual Menu Item Styles */
.menu-item {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    width: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-item:hover {
    transform: scale(1.05); /* Slight zoom effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Menu Item Image */
.menu-item img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

/* Menu Item Name */
.menu-item h2 {
    font-size: 1.5em;
    margin: 15px 0;
    color: #333;
}

/* Menu Item Description */
.menu-item p {
    color: #777;
    font-size: 1em;
    margin-bottom: 10px;
}

/* Price Styling */
.menu-item .price {
    font-size: 1.2em;
    font-weight: bold;
    color: #e60000;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}



```

## OUTPUT:

![alt text](<Screenshot 2024-12-05 203741.png>)
![alt text](<Screenshot 2024-12-05 203652.png>)
![alt text](<Screenshot 2024-12-05 203703.png>)
![alt text](<Screenshot 2024-12-05 203711.png>)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
