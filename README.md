# Ex.07 Restaurant Website
# Date:13.12.2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
## home.html
```
<html>
<head>
  <title>HUSSAIN SITE</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 10px 0;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 20px;
    }

    nav .container {
      display: flex;
      align-items: center;
    }

    nav img {
      margin-right: 10px;
    }

    nav h1 {
      margin: 0;
    }

    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      font-size: 100%;
    }

    nav ul li {
      display: inline;
    }

    nav ul li a {
      text-decoration: none;
      color: #fff;
      margin: 0 15px;
    }

    nav ul li a:hover {
      color: #ffd700; 
    }

    section {
      padding: 50px;
    }
    .home{
        padding-left: 1100px;
        margin-bottom: 150px;
        padding-top: 40px;
        font-size: 200%;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 8px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

  </style>
</head>
    <body bgcolor="red" background="har bg2.jpg" style="background-size: cover" >
    <header>
        <nav>
          <div class="container">
            <img src="logo.png" height="50px" width="80px">
            <h1>HUSSAIN SITE</h1>
          </div>
          <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="member.html">Members</a></li>
            <li><a href="sales.html">Contact Us</a></li>
          </ul>
        </nav>
      </header>

  <div class="home">
    <h1   style="color: rgb(255, 255, 255);"><br>ULTIMATE PROTECTION FOR <br> YOUR FAMILY'S DIGITAL WORLD</h1>
    <p  style="color: rgb(255, 253, 253);"><br><b>Shop, Bank, Browse, Play,and Connect the web securely with the <br>award-winning best antivirus software trusted by millions of users. <br>Cloud-light, easy to install, and effortless to use, Quick Heal antivirus <br>for PC, Laptop, Mac, and Windows offers better performance, ultimate <br>threat protection, and a secure experience you can trust and rely on.</b></p>
  </div>

  <footer>
    <p>&copy; 2024- HUSSAIN SITE. All rights reserved.</p>
  </footer>

</body>
</html>
```
## member.html
```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Members</title>
    <style>
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
          color: white;
        }
    
        header {
          background-color: #333;
          color: #fff;
          padding: 10px 0;
        }
    
        nav {
          display: flex;
          justify-content: space-between;
          align-items: center;
          padding: 0 20px;
        }
    
        nav .container {
          display: flex;
          align-items: center;
        }
    
        nav img {
          margin-right: 10px;
        }
    
        nav h1 {
          margin: 0;
        }
    
        nav ul {
          list-style-type: none;
          margin: 0;
          padding: 0;
        }
    
        nav ul li {
          display: inline;
        }
    
        nav ul li a {
          text-decoration: none;
          color: #fff;
          margin: 0 15px;
        }
    
        nav ul li a:hover {
          color: #ffd700; 
        }
    
        section {
          padding: 10px;
          text-align: center;
        }
    
        footer {
          background-color: #333;
          color: #fff;
          text-align: center;
          padding: 20px 0;
          position: fixed;
          bottom: 0;
          width: 100%;
        }
        .container1 {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .member {
      text-align: center;
      margin-bottom: 50px;
      flex-basis: calc(25% - 20px); 
      border: 3px solid white; 
      padding: 20px;
      box-sizing: border-box;
    }

    .member img {
      max-width: 100%;
      height: 250px;
      width: 200px; 
      margin-bottom: 20px;
    }

    .member-name {
      font-weight: bold;
      font-size: 18px;
    }

    .member-designation {
      font-size: 16px;
      margin-top: 10px;
    }
    .team{
        padding-left: 20px;
    }
    
      </style>
</head>
<body bgcolor="red" background="har bg3.jpg" style="background-size: cover;">
    <header>
        <nav>
          <div class="container">
            <img src="logo.png" height="50px" width="80px">
            <h1>HUSSAIN SITE</h1>
          </div>
          <ul>
            <li><a href="soft.html">Home</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="member.html">Team</a></li>
            <li><a href="sales.html">Contact Us</a></li>
          </ul>
        </nav>
      </header>
    
      <div class="team">
        <h1> Our Team</h1 >
            <p>Team member profiles</p>
      </div>
        
      

      <div class="container1">
        <div class="member">
          <img src="har mem1.jpg">
          <div class="member-info">
            <div class="member-name">Dhoni</div>
            <div class="member-designation">CEO</div>
          </div>
        </div>
    
        <div class="member">
          <img src="har mem2.jpg">
          <div class="member-info">
            <div class="member-name">Virat</div>
            <div class="member-designation">CO-FOUNDER</div>
          </div>
        </div>
    
        <div class="member">
          <img src="har mem3.jpg" >
          <div class="member-info">
            <div class="member-name">Jadeja</div>
            <div class="member-designation">DIRECTOR</div>
          </div>
        </div>
    
        <div class="member">
          <img src="har mem4.jpg">
          <div class="member-info">
            <div class="member-name">Sachin</div>
            <div class="member-designation">HR </div>
          </div>
        </div>
      </div>

      <footer>
        <p>&copy; 2024 HUSSAIN SITE. All rights reserved.</p>
      </footer>
</body>
</html>
```
## product.html
```
<html>
<head>
    <title>Products</title>
    <style>
        
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
          color: white;
        }
    
        header {
          background-color: #333;
          color: #fff;
          padding: 10px 0;
        }
    
        nav {
          display: flex;
          justify-content: space-between;
          align-items: center;
          padding: 0 20px;
        }
    
        nav .container {
          display: flex;
          align-items: center;
        }
    
        nav img {
          margin-right: 10px;
        }
    
        nav h1 {
          margin: 0;
        }
    
        nav ul {
          list-style-type: none;
          margin: 0;
          padding: 0;
        }
    
        nav ul li {
          display: inline;
        }
    
        nav ul li a {
          text-decoration: none;
          color: #fff;
          margin: 0 15px;
        }
    
        nav ul li a:hover {
          color: #ffd700; 
        }
    
        section {
          padding: 50px;
        }
    
        footer {
          background-color: #333;
          color: #fff;
          text-align: center;
          padding: 20px 0;
          position: fixed;
          bottom: 0;
          width: 100%;
        }
        .container1 {
      max-width: 1200px;
      margin: 0 auto;
      padding: 18px;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .product {
      text-align: center;
      margin-bottom: 50px;
      flex-basis: calc(25% - 20px); 
      border: 5px solid #ccc; 
      padding: 20px;
      box-sizing: border-box;
    }

    .product img {
      max-width: 100%;
      height: 200px; 
      width: 200px; 
      object-fit: cover; 
      margin-bottom: 10px;
    }

    .product-info {
      margin-top: 20px;
    }

    .product-name {
      font-weight: bold;
      font-size: 18px;
    }

    .product-description {
      font-size: 16px;
      margin-top: 10px;
    }

    .product-price {
      font-size: 16px;
      margin-top: 10px;
      color: rgb(208, 255, 0); 
    }
    .buy {
      background-color: #007bff;
      color: #fff;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
      </style>
</head>
<body bgcolor="red" background="har bg2.jpg" style="background-size: cover;"> 
    <header>
        <nav>
          <div class="container">
            <img src="logo.png" height="50px" width="80px">
            <h1>HUSSAIN SITE</h1>
          </div>
          <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="member.html">Members</a></li>
            <li><a href="sales.html">Contact Us</a></li>
          </ul>
        </nav>
      </header>
      <h1 align="center">Products</h1>
      <div class="container1">
        <div class="product">
          <img src="har book1.jpg" alt="Product 1">
          <div class="product-info">
            <div class="product-name">Quick Heal Total Security</div>
            <div class="product-description">Keep your online identity private wherever you go on the internet with our robust features for all devices.  <b>1 User, 1 Year</b></div>
            <div class="product-price">Rs.500</div>
            <button class="buy">Buy Now</button>

          </div>
        </div>
        <div class="product">
          <img src="har book2.jpg" alt="Product 2">
          <div class="product-info">
            <div class="product-name">Quick Heal Internet Security</div>
            <div class="product-description">Secure your Wi-Fi and PC from threats when you browse, bank, chat, and email. <b>1 User, 1 Year</b></div>
            <div class="product-price">Rs.900</div>
            <button class="buy">Buy Now</button>

          </div>
        </div>
    
        <div class="product">
          <img src="har book3.jpg" alt="Product 3">
          <div class="product-info">
            <div class="product-name">Quick Heal AntiVirus Pro</div>
            <div class="product-description">Cloud-Based Al-Powered predictive malware hunting technology for protection against advanced cyberthreats and Anti-Ransomware <b>1 User, 1 Year</b></div>
            <div class="product-price">Rs.1500</div>
            <button class="buy">Buy Now</button>

          </div>
        </div>
    
        <div class="product">
          <img src="har book4.jpg" alt="Product 4">
          <div class="product-info">
            <div class="product-name">Quick Heal Total Security Multi- Device</div>
            <div class="product-description">Secure your Windows, Mac or Android device with a single Product Key! <b>3 User, 1 Year</b></div>
            <div class="product-price">Rs.3000</div>
            <button class="buy">Buy Now</button>

          </div>
        </div>
      </div>

      <footer>
        <p>&copy; 2024 HUSSAIN SITE. All rights reserved.</p>
      </footer>
</body>
</html>

```
## sales.html
```
<html>
<head>
    <title>Contact</title>
    <style>
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
        }
    
        header {
          background-color: #333;
          color: #fff;
          padding: 10px 0;
        }
    
        nav {
          display: flex;
          justify-content: space-between;
          align-items: center;
          padding: 0 20px;
        }
    
        nav .container {
          display: flex;
          align-items: center;
        }
    
        nav img {
          margin-right: 10px;
        }
    
        nav h1 {
          margin: 0;
        }
    
        nav ul {
          list-style-type: none;
          margin: 0;
          padding: 0;
        }
    
        nav ul li {
          display: inline;
        }
    
        nav ul li a {
          text-decoration: none;
          color: #fff;
          margin: 0 15px;
        }
    
        nav ul li a:hover {
          color: #ffd700; 
        }
    
        section {
          padding: 50px;
        }
    
        footer {
          background-color: #333;
          color: #fff;
          text-align: center;
          padding: 20px 0;
          position: fixed;
          bottom: 0;
          width: 100%;
        }
    
    

.contact-box {
  max-width: 500px;
  margin: 50px auto;
  margin-top: 120px;
  padding: 30px;
  border: 4px solid black;
  border-radius: 10px;
  text-align: center;
  color: #ccc;
}

.contact-info {
  margin-bottom: 20px;
}

.contact-info p {
  margin: 5px 0;
}

.subscribe-form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.subscribe-form h3 {
  margin-bottom: 10px;
  color: #333;
}

.subscribe-form input[type="email"] {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 5px;
  border: 2px solid #ccc;
}

.subscribe-form button {
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

</style>

</head>
<body bgcolor="red" background="har bg3.jpg" style="background-size: cover;">

    <header>
        <nav>
          <div class="container">
            <img src="logo.png" height="50px" width="80px">
            <h1>HUSSAIN SITE</h1>
          </div>
          <ul>
            <li><a href="home.html">Home</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="member.html">Members</a></li>
            <li><a href="sales.html">Contact Us</a></li>
          </ul>
        </nav>
      </header>

      <div class="contact-box">
        <h2>Contact Us</h2>
        <p>If you have any questions or concerns, feel free to contact us.</p>
        <div class="contact-info">
          <p>Email: <a href="mailto:rpsecurities@example.com">rpsecurities@example.com</a></p>
          <p>Toll Free : 1800 121 7377</p>
        </div>
        <form class="subscribe-form">
          <h3>Subscribe to Our Newsletter</h3>
          <input type="email" name="email" placeholder="Enter your email address">
          <button type="submit">Subscribe</button>
        </form>
    </div>

      <footer>
        <p>&copy; 2024 HUSSAIN SITE. All rights reserved.</p>
      </footer>
</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-12 234205](https://github.com/user-attachments/assets/98a5904c-d6ca-4634-b5ea-f8ceb299dcf6)
![Screenshot 2024-12-12 235006](https://github.com/user-attachments/assets/9a8243fb-8c62-4f8a-8be4-045ed289f48f)
![Screenshot 2024-12-12 235603](https://github.com/user-attachments/assets/fd6a013c-eb5c-4f6f-9a2f-4d87f2664ab3)
![Screenshot 2024-12-13 000111](https://github.com/user-attachments/assets/cbf09510-2cd2-4def-b2e2-6592015c1a34)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
