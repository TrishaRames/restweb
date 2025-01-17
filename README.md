# Ex.07 Restaurant Website
## Date:12-12-24

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

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSP RESTAURANT</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            background: url('back ground.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #36032b;
        }

        header {
            background-color: rgba(180, 145, 172, 0.8); 
            color: rgb(208, 120, 120);
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 20px;
        }

        header nav ul li a {
            color: rgb(65, 6, 6);
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: #16a085;
            font-weight: bold;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            text-align: center;
            background-color: rgba(255, 255, 255, 0.8); 
            padding: 20px;
            border-radius: 15px;
        }

        h2 {
            color: #2980b9;
        }

        footer {
            background-color: rgba(173, 131, 170, 0.9); 
            color: rgb(80, 10, 10);
            text-align: center;
            padding: 15px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
        }

        ::-webkit-scrollbar {
            width: 5px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #16a085;
            border-radius: 10px;
        }
    </style>
</head>

<body>
    <header>
        <h1>MSP RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="food.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="container">
        <h2>Welcome to Our Restaurant</h2>
        <p>Experience the finest dining with us. Enjoy our delicious menu, excellent service, and a cozy atmosphere.</p>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 MSP RESTAURANT | Designed by TRISHA </p>
        </div>
    </footer>
</body>

</html>

menu.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MENU - MSP RESTAURANT</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #f0e5d8, #d9c9b5);
            color: #333;
        }

        header {
            background-color: #340202;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-weight: 700;
            letter-spacing: 2px;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        header nav ul li a:hover {
            background-color: #360311;
            color: #f7f1e3;
        }

        .menu-container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto 100px auto;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .menu-item {
            width: 28%;
            background: rgba(255, 255, 255, 0.8);
            padding: 15px;
            border-radius: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .menu-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        .menu-item h3 {
            margin: 10px 0;
            font-size: 1.2em;
            color: #8e44ad;
        }

        .menu-item p {
            text-align: center;
            font-size: 0.9em;
            color: #555;
        }

        footer {
            background-color: #350304;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.2);
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #8e44ad;
            border-radius: 10px;
        }
    </style>
</head>

<body>
    <header>
        <h1>OUR MENU</h1>
        <nav>
            <ul>
                <li><a href="food.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div class="menu-container">
        <div class="menu-item">
            <img src="biryani.jpg" alt="biryani">
            <h3>BIRYANI</h3>
            <p>A vibrant rice dish with mixed vegetables, chicken or mutton, and an egg.</p>
        </div>
        <div class="menu-item">
            <img src="non veg meal.jpg" alt="NON VEG MEALS">
            <h3>NON VEG MEALS</h3>
            <p>Rice with chicken, mutton, fish gravy with rotti and chicken starters.</p>
        </div>
        <div class="menu-item">
            <img src="burger.jpg" alt="Naan">
            <h3>BURGER</h3>
            <p>Soft and fluffy buns stuffed with chicken and cheese.</p>
        </div>
        <div class="menu-item">
            <img src="chicken 65.jpg" alt="chicken65">
            <h3>CHICKEN 65</h3>
            <p>Fresh chicken fried with Indian spices for a crispy delight.</p>
        </div>
        <div class="menu-item">
            <img src="butter chicken.jpg" alt="butterchicken">
            <h3>BUTTER CHICKEN</h3>
            <p>Rich, creamy, and flavorful chicken curry in buttery sauce.</p>
        </div>
        <div class="menu-item">
            <img src="mutton gravy.jpg" alt="mutton">
            <h3>MUTTON GRAVY</h3>
            <p>Mouth-watering mutton curry with aromatic Indian spices.</p>
        </div>
        <div class="menu-item">
            <img src="prawnthokku.jpg" alt="prawnthokku">
            <h3>PRAWNTHOKKU</h3>
            <p>Succulent prawns cooked in a tangy, spicy Indian sauce.</p>
        </div>
        <div class="menu-item">
            <img src="crabsoup.jpg" alt="crabsoup">
            <h3>SOFT DRINK</h3>
            <p>A refreshing and tasty soft drinks for digestion.</p>
        </div>
        <div class="menu-item">
            <img src="attukal soup.jpg" alt="attukalsoup">
            <h3>ATTUKAL SOUP</h3>
            <p>A hearty and flavorful bone soup for a warm beginning.</p>
        </div>
        <div class="menu-item">
            <img src="ice cream.jpg" alt="elaneerpayasam">
            <h3>ICECREAM</h3>
            <p>A cold dessert for fulfilling your delicious meal.</p>
        </div>
        <div class="menu-item">
            <img src="jigrathanda.jpg" alt="jigarthanda">
            <h3>JIGRATHANDA</h3>
            <p>Cool drink after meals.</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Designed by TRISHA </p>
    </footer>
</body>

</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADMINISTRATION - MSP RESTAURANT</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #7c9dcf;
            color: #333;
        }

        header {
            background-color: #38040e;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 500;
            margin: 0;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        header nav ul li {
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        header nav ul li a:hover {
            color: #ffab40;
        }

        .admin-container {
            width: 90%;
            margin: 20px auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .admin-card {
            width: 240px;
            padding: 20px;
            background-color: #ffffff;
            border: 1px solid #e0e0e0;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .admin-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .admin-card img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 15px;
        }

        .admin-card h3 {
            margin: 10px 0 5px;
            font-size: 1.2em;
            color: #283593;
        }

        .admin-card p {
            font-size: 0.9em;
            color: #555;
        }

        footer {
            background-color: #2d0202;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        ::-webkit-scrollbar {
            width: 10px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #3f51b5;
            border-radius: 10px;
        }
    </style>
</head>
<body>
<header>
    <h1>ADMINISTRATION TEAM</h1>
    <nav>
        <ul>
            <li><a href="food.html">HOME</a></li>
            <li><a href="menu.html">MENU</a></li>
            <li><a href="administration.html">ADMINISTRATION</a></li>
            <li><a href="contact.html">CONTACT US</a></li>
        </ul>
    </nav>
</header>

<div class="admin-container">
    <div class="admin-card">
        <img src="Chandra babu.jpg" alt="Owner">
        <h3>CHANDRA BABU</h3>
        <p>Owner</p>
        <p>Visionary leader ensuring the success of MSP Restaurant.</p>
    </div>
    <div class="admin-card">
        <img src="Vijay.jpg" alt="Executive Chef">
        <h3>JOSEPH VIJAY</h3>
        <p>Executive Chef</p>
        <p>Mastermind behind our exquisite menu and culinary excellence.</p>
    </div>
    <div class="admin-card">
        <img src="allu arjun.jpg" alt="Operations Manager">
        <h3>ALLU ARJUN</h3>
        <p>Operations Manager</p>
        <p>Ensures smooth day-to-day operations and exceptional service.</p>
    </div>
    <div class="admin-card">
        <img src="brahmani.jpg" alt="Customer Experience Manager">
        <h3>BRAHMANI</h3>
        <p>Customer Experience Manager</p>
        <p>Focuses on guest satisfaction and memorable dining experiences.</p>
    </div>
    <div class="admin-card">
        <img src="Balakrishna.jpg" alt="Beverage Specialist">
        <h3>BALAKRISHNA</h3>
        <p>Beverage Specialist</p>
        <p>Crafts refreshing and unique drinks to complement every meal.</p>
    </div>
    <div class="admin-card">
        <img src="keerthy suresh.jpg" alt="Front Desk Manager">
        <h3>KEERTHY SURESH</h3>
        <p>Front Desk Manager</p>
        <p>Welcomes guests and manages reservations with a smile.</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Designed by TRISHA</p>
</footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTACT US - MSP RESTAURANT</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #d5f3fe, #ffffff);
            color: #333;
        }

        header {
            background-color: #34020c;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-weight: 700;
            letter-spacing: 2px;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: rgb(172, 210, 116);
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        header nav ul li a:hover {
            background-color: #8151b7;
            color: #f7f1e3;
        }

        .contact-container {
            width: 70%;
            margin: 50px auto;
            padding: 30px;
            background: rgba(132, 107, 107, 0.9);
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
        }

        .contact-container h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #6b3fa0;
            font-size: 1.8em;
        }

        .contact-item {
            margin-bottom: 20px;
            text-align: center;
        }

        .contact-item label {
            font-weight: bold;
            font-size: 1.2em;
        }

        .contact-item p {
            margin: 5px 0;
            font-size: 1.1em;
            color: #555;
        }

        .contact-item a {
            color: #6b3fa0;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        .contact-item a:hover {
            color: #a569bd;
        }

        footer {
            background-color: #3c030c;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.2);
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #6b3fa0;
            border-radius: 10px;
        }
    </style>
</head>
<body>
<header>
    <h1>CONTACT US</h1>
    <nav>
        <ul>
            <li><a href="food.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
</header>

<div class="contact-container">
    <h2>We Would Love to Hear from You</h2>
    <div class="contact-item">
        <label>Email:</label>
        <p><a href="mailto:info@msprestaurant.com">info@msprestaurant.com</a></p>
    </div>
    <div class="contact-item">
        <label>Phone:</label>
        <p><a href="tel:+919676563660">9676563660</a></p>
    </div>
    <div class="contact-item">
        <label>Address:</label>
        <p>kuppam,chittoor,andhra pradesh-517425</p>
    </div>
    <div class="contact-item">
        <label>Operating Hours:</label>
        <p>Monday - Sunday: 10:00 AM - 11:00 PM</p>
    </div>
    <div class="contact-item">
        <label>Follow Us:</label>
        <p>
            <a href="#" target="_blank">Facebook</a> | 
            <a href="#" target="_blank">Instagram</a> | 
            <a href="#" target="_blank">Twitter</a>
        </p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Designed by TRISHA | All rights reserved</p>
</footer>
</body>
</html>
```

## OUTPUT:
![Screenshot (49)](https://github.com/user-attachments/assets/c44cd286-fcc0-4b68-aad0-9aa4eb9b8770)
![Screenshot (50)](https://github.com/user-attachments/assets/a3552e1b-ddde-46aa-bcaa-a93f70b12803)
![Screenshot (51)](https://github.com/user-attachments/assets/a0daeeb6-2698-48fe-828e-b4b565fac474)
![Screenshot (52)](https://github.com/user-attachments/assets/0443aec8-6f8a-40bc-994c-8c0ac33411a3)
![Screenshot (53)](https://github.com/user-attachments/assets/1943e440-9bc7-43f6-8a1c-50ae8956363f)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
