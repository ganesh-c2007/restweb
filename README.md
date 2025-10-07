# Ex.07 Restaurant Website
## Date:07.10.2025

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
MAIN.HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Koko Restaurant | Home</title>
  <link rel="stylesheet" href="main.css">
</head>
<body>
  <header>
    <h1>KOKO RESTARUNT</h1>
    <img src="download (7).jpg" class="bagbag">
    <nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Admin</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="home">
    
    <h2></color>Welcome to Koko restarunt</h2>
    <p> </p>
    <img src="photo-1517248135467-4c7edcad34c4.jpg">
  </section>

  <footer>
    <p>© koko restaurant | Designed by <strong>Ganesh.c(25017481)</strong></p>
  </footer>
</body>
</html>





MAIN.CSS

body {
  background-image: url('photo-1517248135467-4c7edcad34c4.jpg');
  background-repeat:no-repeat;
  object-fit:cover;
  font-family: Arial, sans-serif;
  background-color: white;
  color: white;
  margin: 0;
  text-align: center;
}
.bagbag{
    background-repeat:no-repeat;
    object-fit: cover;
    width:1500px;
    text-align: center;
    height:520px;
    z-index:-1;
    position:absolute;
    top:170px;
    right:0px;
}

header {
  background-color: black;
  padding: 20px;
  border-bottom: 3px solid red;
}

h1 {
    position:relative;
  color: red;
  right:30%;
  top:20%;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  position: relative;
  left:30%;
  
}

nav a.active,
nav a:hover {
  color: red;
  position: relative;
  left:30%;
}


.home {
  padding: 40px;
}

.home img {
  width: 500px;
  border-radius: 10px;
  margin-top: 20px;
  border: 3px solid red;
}

footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid red;
}


MENU.HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu | Ten Taste</title>
  <link rel="stylesheet" href="menu.css">
</head>
<body>
  <header>
    <h1>OUR SPECIAL MENU</h1>
    <nav>
      <ul>
        <li><a href="main.html">Home</a></li>
        <li><a href="menu.html" class="active">Menu</a></li>
        <li><a href="admin.html">Admin</a></li>
        <li><a href="contact.html">Contact us</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Food Items</h2>
    <div class="menu-items">
      <div class="item"><img src="images.jpg"><p>Idly - Rs.30</p></div>
      <div class="item"><img src="download (3).jpg"><p>Dosa - Rs.80</p></div>
      <div class="item"><img src="Mexican-Restaurant-Menu-Ideas-Tacos-Burritos-Rice-Beans-and-Aguas-Frescas.jpg"><p>Tacos Burritos - Rs.1170</p></div>
      <div class="item"><img src="download (2).jpg"><p>Poori - Rs.50</p></div>
      <div class="item"><img src="5dd8d8db50b5430482e4da8722c10aea.jpg"><p>Half pork - Rs.1160</p></div>
      <div class="item"><img src="download.jpg"><p>Parotta - Rs.40</p></div>
      <div class="item"><img src="images (1).jpg"><p>French Fries - Rs.40</p></div>
      <div class="item"><img src="download (5).jpg"><p>Curve bread (5) - Rs.500</p></div>
      <div class="item"><img src="download (6).jpg"><p>Beef Soup- Rs.100</p></div>
      <div class="item"><img src="download (1).jpg"><p>Samosa(5) - Rs.260</p></div>
    </div>
  </section>

  <footer>
    <p>© 2025 Koko Restaurant | Designed by <strong>Ganesh.c(25017481)</strong></p>
  </footer>
</body>
</html>



MENU.CSS

body {
  font-family: Arial, sans-serif;
  background-color: #151414;
  color: rgb(20, 20, 20);
  margin: 0;
  text-align: center;
}

header {
  background-color: rgb(207, 198, 198);
  padding: 20px;
  border-bottom: 3px solid red;
}

h1 {
  color: red;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: rgb(22, 22, 22);
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color: red;
}

.menu {
  padding: 40px;
}

.menu-items {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.item {
  background-color: rgb(241, 234, 234);
  border: 2px solid red;
  border-radius: 10px;
  padding: 10px;
  width: 200px;
}

.item img {
  width: 100%;
  border-radius: 8px;
}

footer {
  background-color: #111;
  color: #e3e0e0;
  padding: 15px;
  border-top: 2px solid red;
}

CONTACT.HTML


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | Koko Restaurant</title>
  <link rel="stylesheet" href="contact.css">
</head>
<body>
  <header>
    <h1>CONTACT US</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Admin</a></li>
        <li><a href="contact.html" class="active">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="contact">
    <h2>Contact Us</h2>
    <p>📍 23,Near PHENIOX Mall,Chennai</p>
    <p>📞 09635489372</p>
    <p>✉ superducks@gmail.com</p>
  </section>

  <footer>
    <p>© Koko Restaurant | Designed by <strong>Ganesh.c(25017481)</strong></p>
  </footer>
</body>
</html>


CONTACT.CSS


body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #dc3b3b;
}

/* Header */
header {
    background-color: #FFD500;
    color: red;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: black;
    font-weight: 600;
}

nav ul li a.active {
    text-decoration: underline;
}

/* Main Section */
main {
    text-align: center;
    padding: 40px 20px;
}

main h2 {
    color: #222;
    font-size: 1.8em;
    margin-bottom: 40px;
}

/* Team Cards */
.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.member {
    background-color: #111;
    color: white;
    border-radius: 12px;
    width: 150px;
    padding: 20px;
    transition: transform 0.3s;
}

.member:hover {
    transform: translateY(-8px);
}

.member img {
    width: 80%;
    height: 230px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid orange;
}

.member h3 {
    margin-top: 15px;
    color: #fff;
    font-size: 1.2em;
}

.member p {
    color: #FFD500;
    font-weight: 500;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 10px;
    font-size: 0.9em;
}

ADMIN.HTML


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <header>
        <h1>Admin Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html" class="active">Admin</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Meet Our Team</h2>

        <div class="team">
            <div class="member">
                <img src="licensed-image.webp"alt="">
                <h3></h3>
                <p>CEO</p>
            </div>

            <div class="member">
                <img src="Chris-Hemsworth-.webp" alt="">
                <h3></h3>
                <p>Marketing Manager</p>
            </div>

            <div class="member">
                <img src= "tom1.jpg"alt="">
                <h3></h3>
                <p>Operations Manager</p>
            </div>

            <div class="member">
                <img src="Hr photo.webp" alt="">
                <h3></h3>
                <p>HR Manager</p>
            </div>

            <div class="member">
                <img src= "captain.jpg"alt="">
                <h3></h3>
                <p>Executive Chef</p>
            </div>

            <div class="member">
                <img src="ana de.jpg" alt="">
                <h3></h3>
                <p>Customer Service Manager</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© Koko Restaurant| Designed by <strong>Ganesh.c(25017481)</strong></p>
    </footer>
</body>
</html>

ADMIN.CSS



body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #dc3b3b;
}

/* Header */
header {
    background-color: #FFD500;
    color: red;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: black;
    font-weight: 600;
}

nav ul li a.active {
    text-decoration: underline;
}

/* Main Section */
main {
    text-align: center;
    padding: 40px 20px;
}

main h2 {
    color: #222;
    font-size: 1.8em;
    margin-bottom: 40px;
}

/* Team Cards */
.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.member {
    background-color: #111;
    color: white;
    border-radius: 12px;
    width: 150px;
    padding: 20px;
    transition: transform 0.3s;
}

.member:hover {
    transform: translateY(-8px);
}

.member img {
    width: 80%;
    height: 230px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid orange;
}

.member h3 {
    margin-top: 15px;
    color: #fff;
    font-size: 1.2em;
}

.member p {
    color: #FFD500;
    font-weight: 500;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 10px;
    font-size: 0.9em;
}

```














## OUTPUT:

![alt text](<restar/Screenshot (40).png>)

![alt text](<restar/Screenshot (41).png>)

![alt text](<restar/Screenshot (42).png>)

![alt text](<restar/Screenshot (43).png>)

![alt text](<restar/Screenshot (44).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
