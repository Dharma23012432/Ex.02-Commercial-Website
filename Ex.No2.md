# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Simple Commercial Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }
    header {
      background: #333;
      color: #fff;
      padding: 15px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #444;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
    }
    .hero {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
      padding: 50px 20px;
      background: #e0f7fa;
    }
    .features, .products, .contact {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      padding: 20px;
      background: white;
      margin: 10px;
      border-radius: 10px;
    }
    .feature, .product {
      background: #f0f0f0;
      padding: 15px;
      margin: 10px;
      border-radius: 8px;
      text-align: center;
      flex: 1 1 200px;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
    button {
      background: #00796b;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Store</h1>
    <p>Quality Products at Great Prices</p>
  </header>

  <nav>
    <a href="#features">Features</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Welcome to Our Store</h2>
    <p>Find the best products designed to make your life easier.</p>
    <button>Shop Now</button>
  </section>

  <section id="features" class="features">
    <div class="feature">
      <h3>Fast Delivery</h3>
      <p>Get your orders quickly and on time.</p>
    </div>
    <div class="feature">
      <h3>Quality Products</h3>
      <p>We offer only the best and most reliable products.</p>
    </div>
    <div class="feature">
      <h3>Support</h3>
      <p>24/7 customer support for your convenience.</p>
    </div>
  </section>

  <section id="products" class="products">
    <div class="product">
      <h3>Product 1</h3>
      <p>100</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <h3>Product 2</h3>
      <p>150</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <h3>Product 3</h3>
      <p>200</p>
      <button>Add to Cart</button>
    </div>
  </section>

  <section id="contact" class="contact">
    <div>
      <h3>Contact Us</h3>
      <p>Email: dlingam@gmail.com</p>
      <p>Phone: +91 7598769579</p>
    </div>
  </section>

  <footer>
    <p>© 2025 My Store. All rights reserved.</p>
  </footer>
</body>
</html>

```

## OUTPUT
<img width="1902" height="967" alt="image" src="https://github.com/user-attachments/assets/93a6d4fc-1eca-43a1-8d8d-ca1c3b2703f6" />
<img width="1902" height="965" alt="image" src="https://github.com/user-attachments/assets/9c27b6ca-3e2d-4c25-9cec-4b71b6336e16" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
