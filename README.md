# Ex.07 Restaurant Website
## Date:26.12.2025

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
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ABC Software Solutions</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>ABC Software Solutions</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="product.html">Products</a>
    <a href="softwares.html">Softwares</a>
    <a href="people.html">Team</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section class="hero">
  <img src="softwares.png" alt="Software solutions banner">
  <h2>Reliable software for your business</h2>
  <p>We build scalable applications, automation tools and cloud solutions.</p>
</section>

<footer>
  <p>&copy; 2025 ABC Software Solutions</p>
</footer>
</body>
</html>

product.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Products - ABC Software</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>Our Products</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="product.html">Products</a>
    <a href="softwares.html">Softwares</a>
    <a href="people.html">Team</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section>
  <h2>Featured Products</h2>
  <ul>
    <li><strong>ABC ERP</strong> – Enterprise resource planning for midsize companies.</li>
    <li><strong>ABC CRM</strong> – Customer relationship management web app.</li>
    <li><strong>ABC Desk</strong> – Helpdesk and ticket management system.</li>
  </ul>
</section>

<footer>
  <p>&copy; 2025 ABC Software Solutions</p>
</footer>
</body>
</html>


style.css

/* Common layout for whole site */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f3f3f3;
}

header {
  background: #1e88e5;
  color: #fff;
  padding: 15px 20px;
}

header h1 {
  margin: 0;
}

/* Top navigation */
nav a {
  color: #fff;
  margin-right: 15px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

/* Sections and tables */
section {
  padding: 20px;
  background: #fff;
  margin: 15px;
}

table {
  width: 100%;
  border-collapse: collapse;
}

th, td {
  border: 1px solid #ccc;
  padding: 8px;
  text-align: left;
}

/* Banner on home page */
.hero {
  text-align: center;
}

.hero img {
  max-width: 100%;
  height: 200px;
  object-fit: cover;
}

/* Buttons */
button {
  margin-top: 12px;
  padding: 8px;
  background: #1e88e5;
  border: none;
  color: #fff;
  cursor: pointer;
}

button:hover {
  background: #1565c0;
}

/* Footer */
footer {
  text-align: center;
  padding: 10px;
  background: #eee;
}


contact.css

/* Extra styles only for contact.html */

.contact {
  max-width: 500px;
  margin: 0 auto;
}

.contact form {
  display: flex;
  flex-direction: column;
}

.contact label {
  margin-top: 10px;
}

.contact input,
.contact textarea {
  padding: 6px;
  margin-top: 4px;
  border: 1px solid #ccc;
  border-radius: 3px;
}


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - ABC Software</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="contact.css">
</head>
<body>

<header>
  <h1>ABC Software Solutions</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="product.html">Products</a>
    <a href="softwares.html">Softwares</a>
    <a href="people.html">Team</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section class="contact">
  <h2>Contact Us</h2>

  <form>
    <label for="name">Name:</label>
    <input id="name" type="text" name="name" required>

    <label for="email">Email:</label>
    <input id="email" type="email" name="email" required>

    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" required></textarea>

    <button type="submit">Submit</button>
  </form>

  <h3>Office Address</h3>
  <p>
    ABC Software Solutions<br>
    Chennai, India<br>
    Email: info@abcsoft.com<br>
    Phone: +91-90000 00000
  </p>
</section>

<footer>
  <p>&copy; 2025 ABC Software Solutions</p>
</footer>

</body>
</html>


people.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Our Team - ABC Software</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="people.css">
</head>
<body>

<header>
  <h1>ABC Software Solutions</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="product.html">Products</a>
    <a href="softwares.html">Softwares</a>
    <a href="people.html">Team</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section class="team">
  <div class="member">
    <img src="person1.jpg" alt="CEO">
    <h3>Arjun Kumar</h3>
    <p>Chief Executive Officer</p>
  </div>

  <div class="member">
    <img src="person2.jpg" alt="CTO">
    <h3>Neha Sharma</h3>
    <p>Chief Technology Officer</p>
  </div>

  <div class="member">
    <img src="person3.jpg" alt="Lead Developer">
    <h3>Ravi Singh</h3>
    <p>Lead Developer</p>
  </div>

  <div class="member">
    <img src="person4.jpg" alt="UI/UX Designer">
    <h3>Priya Patel</h3>
    <p>UI/UX Designer</p>
  </div>

  <div class="member">
    <img src="person5.jpg" alt="QA Engineer">
    <h3>Karan Mehta</h3>
    <p>QA Engineer</p>
  </div>

  <div class="member">
    <img src="person6.jpg" alt="Support Engineer">
    <h3>Simran Kaur</h3>
    <p>Support Engineer</p>
  </div>
</section>

<footer>
  <p>&copy; 2025 ABC Software Solutions</p>
</footer>

</body>
</html>


people.css

/* Extra styles only for people.html */

.team {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.member {
  width: 150px;
  text-align: center;
}

.member img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
}


software.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Softwares & Services</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>Softwares & Services</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="product.html">Products</a>
    <a href="softwares.html">Softwares</a>
    <a href="people.html">Team</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section>
  <table>
    <tr>
      <th>Name</th>
      <th>Type</th>
      <th>Description</th>
    </tr>
    <tr>
      <td>ABC ERP</td>
      <td>Desktop / Web</td>
      <td>Manages inventory, finance and HR.</td>
    </tr>
    <tr>
      <td>ABC CRM</td>
      <td>Web</td>
      <td>Tracks leads and customer interactions.</td>
    </tr>
    <tr>
      <td>ABC Desk</td>
      <td>Web</td>
      <td>Tickets, SLA and support analytics.</td>
    </tr>
  </table>
</section>

<footer>
  <p>&copy; 2025 ABC Software Solutions</p>
</footer>
</body>
</html>


```

## OUTPUT:

![alt text](<Screenshot 2025-12-27 133519.png>)
![alt text](<Screenshot 2025-12-27 133528.png>)
![alt text](<Screenshot 2025-12-27 133549.png>)
![alt text](<Screenshot 2025-12-27 133558.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
