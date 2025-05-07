# Ex.07 Restaurant Website
## Date:07-05-2025

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
res.html
<!DOCTYPE html>
<html lang="en"?>
    <head>
        <title>THE GRILL</title>
        <link rel="icon" href="logo.png">
    </head>
    <style>
        body{
            background-image: url("temp.png");
            background-size: cover;
            background-position: center;
        }
        .nav-list{
            position: absolute;
            top: 30px;
            left: 80%;
            transform:  translatex(10%);
        }
        .nav-list a{
            display: inline blocks;
            margin: 0 10px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: rgb(229, 50, 214);
        }
        .nav-list a:hover{
            color: rgb(235, 9, 149);
        }
    </style>
        <div class="nav-list">
        
        <a href="res.html">Home</a>
        <a href="menu.html">menu</a>
        <a href="contact.html">contact</a>
        <a href="administration.html">Administration</a>

        </div>
    <body style="color: rgb(239, 236, 239);">
        <center>
        <img src="logo.png" style="height: 150px;">
        </center>
        <center>
            <h1 style="color:rgb(249, 245, 249); font-size: 50px;">THE GRILL</h1>
    <table> 
        <center>
        <tr>
            <td><img src="biriyani.png"" style="width: 300px; height: 250px;"></td>
            <td><img src="tikka.png" style="width:300px; height: 250px;"></td>
            <td><img src="lolli.png" style="width:300px; height: 250px;"></td>
            <td><img src="noodles.png" style="width:300px; height: 250px;"></td>
            <td><img src="parotta.png" style="width:300px; height: 250px;"></td>
        </tr>
        </center>
        <tr>
            <td><h3 style="color:white;"><center>BIRIYANI</center></h3></td>
            <td><h3 style="color:white;"><center>CHICKEN TIKKA</center></h3></td>
            <td><h3 style="color:azure;"><center>CHICKEN LOLLIPOP</center></h3></td>
            <td><h3 style="color:azure;"><center>NOODLES</center></h3></td>
            <td><h3 style="color:azure;"><center>BUN PAROTTA</center></h3></td>
        </tr>
    </table>
    <h2>OUR specialities:
        <h2><center>ARE:</center></h2>
    </h2>
        <p style="font-family: 'Times New Roman',Times, serif";><center>Welcome to our grill restaurant, where every meal is a celebration of fresh, high-quality ingredients and expertly grilled flavors. From sizzling steaks and juicy burgers to flavorful vegetarian dishes, our menu offers something for everyone. We take pride in providing a customizable dining experience, allowing you to create your perfect meal. Whether you're enjoying a casual lunch, a family gathering, or a special celebration, our cozy and inviting atmosphere makes every occasion memorable. With weekly specials, friendly service, and a commitment to quality, we promise an unforgettable dining experience. Come visit us and taste the difference today!

        </p> 
        <hr>
        <tr>
            <td><h4 style="font-size: larger;"><center>THE BEST PLACE TO EXPERIENCE THE REAL TASTE!</center></h4></td>
        </tr>
        <footer align="center" id="copywrite">
            Designed and developed by Madhupriya R &copy 2025
        </footer>
    </body>        
</html>
menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - THE GRILL</title>
  <style>
    body { font-family: Arial, sans-serif; background: #fdf5e6; margin: 0; color: #333; }
    .header, .footer { background: #6ecf86; color: #fff; text-align: center; padding: 1rem; }
    .header nav ul { list-style: none; display: flex; justify-content: center; padding: 0; }
    .header nav ul li { margin: 0 1rem; }
    .header nav ul li a { color: #ecdee7; text-decoration: none; font-size: 1.1rem; }
    .menu { padding: 2rem; text-align: center; }
    .menu ul { list-style: none; padding: 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; }
    .menu ul li { background: #d1c2c2; border: 1px solid #f7e8e8; padding: 1rem; border-radius: 5px; }
    .menu ul li:hover { transform: scale(1.05); transition: transform 0.3s; }
  </style>
</head>
<body>
  <header class="header">
    <h1>Tasty Bites</h1>
    <nav>
      <ul>
        <li><a href="res.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Our Menu</h2>
    <ul>
        <li>
            <img src="biriyani.png" alt="Biriyani" width="90" height="90">
            Biriyani - $52
        </li>
        <li>
            <img src="burger.png" alt="KING SIZE BURGER" width="90" height="90">
            Burger - $25
        </li>
        <li>
            <img src="choco.png" alt="choco" width="90" height="90">
            Choco lava cake - $30
        </li>
        <li>
            <img src="pizza.png" alt="pizza" width="90" height="90">
           Family Pizza - $73
        </li>
        <li>
            <img src="salad.png" alt="Caesar Salad" width="90" height="90">
            Caesar Salad - $8
        </li>
        <li>
            <img src="mutton.png" alt="Mutton Gravy" width="90" height="90">
            Mutton Gravy - $10
        </li>
        <li>
            <img src="noodles.png" alt="Noodles" width="90" height="90">
            
            Raman Noodles- $7
        </li>
        <li>
            <img src="french.png" alt="French Fries" width="90" height="90">
            French Fries - $4
        </li>
        <li>
            <img src="salmon.png" alt="salmon" width="90" height="90">
            Salmon Fish - $9
        </li>
        <li>
            <img src="tikka.png" alt="tikka" width="90" height="90">
            Chicken Tikka - $15
        </li>
        <li>
            <img src="parotta.png" alt="parotta" width="90" height="90">
            Bun Parotta - $8
        </li>
        <li>
            <img src="lolli.png" alt="loli" width="90" height="90">
            Chicken Lillipop - $20
        </li>
        
    </ul>
</section>
     
      </body>
      </html>
administration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE GRIILL - Administration</title>

    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #070c31;
            background-color: #232121;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #000b0a;
            color: rgb(47, 79, 88);
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(64, 59, 94, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: rgb(131, 71, 118);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #48a7de;
        }

        .admin-container {
            padding: 40px 20px;
            background: #48797a;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2.5rem;
            color: #14b7b9;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .admin-item {
            background: rgb(224, 225, 220);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(88, 80, 70, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        footer {
            background: #978b5a;
            color: rgb(200, 27, 206);
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #dba419;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #3e96ac;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>    

<header>
        <h1>THE GRILL</h1>
        <nav>
            <a href="res.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="administration.html">Administration</a>
        </nav>
    </header>

    <div class="admin-container">
        <h1>OUR BACKBONES</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="Dhruv.png" alt="CEO">
                <div class="admin-details">
                    <h3>Dhruv vikram</h3>
                    <p>CEO of THE GRILL</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="atharva.png" alt="Manager">
                <div class="admin-details">
                    <h3>Atharva</h3>
                    <p>Manager of THE GRILL</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="samantha.png" alt="Master Chef">
                <div class="admin-details">
                    <h3>Samantha</h3>
                    <p>Master Chef of THE GRILL</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="kashmira.png" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>kashmira</h3>
                    <p>Assistant Managing Director of THE GRILL</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 THE GRILL. All rights reserved. | <a href="res.html">Back to Home</a></p>
    </footer>

</body>
</html>
contact.html
<html>
    <head>
        <title> CONTACT </title>
    </head>
    <style>
        
        body{
        
            background-image: url("back.png");
            background-size: cover;
            background-position: center;
        }
        body{
            display: inline blocks;
            margin:0 600px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 23px;
            font-weight: bolder;
            color: rgb(8, 7, 8);
            position:absolute;
            top: 200px;
        }
    </style>
    <div class="nav-list">
        
        <a href="res.html">Home</a>
        <a href="menu.html">menu</a>
        <a href="contact.html">contact</a>
        <a href="administration.html">Administration</a>

        </div>
    <center>
        <section id="contact">  
            <h1 style="color:rgb(24, 22, 24)">contact<h1>
            <h4  style="color:rgb(26, 19, 24)">+91 9080702009 <br> |The Grill restuarent@gmail.com</h4>
            <P  style="color:rgb(12, 11, 12)">Address: no.39 Near SEC ,Thandalam,Kanchipuram <br>
                <br> contact us to place the order<br>
            <hr> THE PLACE WHERE YOU FIND THE REAL TASTE
            </P>
            <footer align="center" id="copywrite">
                Designed and developed by Madhupriya R &copy 2025
            </footer>
         </section> 
    </center>
    </body>
</html> 

```


## OUTPUT:
<img width="960" alt="2025-05-07" src="https://github.com/user-attachments/assets/e6e91114-e056-4900-af67-c6537cb398a6" />
<img width="960" alt="2025-05-07 (1)" src="https://github.com/user-attachments/assets/8caa7a63-eea0-4e4f-83e1-0b7527054519" />
<img width="960" alt="2025-05-07 (2)" src="https://github.com/user-attachments/assets/d498fe5a-e289-4322-917e-331c3285f220" />
<img width="960" alt="2025-05-07 (3)" src="https://github.com/user-attachments/assets/331d4f35-9eab-4d08-b280-1c33c2956386" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
