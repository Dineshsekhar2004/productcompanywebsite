# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content">
        <h1 id="home-h" >THINK DIFFERENT.</h1>
        <p id="home-p">Everything is designed. Few things are designed well. And those are designed by us.</p>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by DINESH.
      </div>
    </div>
  </body>
</html>


### Home Page:

![output]
![Screenshot (36)](https://user-images.githubusercontent.com/119405916/215347339-0484cf06-f843-49c8-9e84-2b3726f4cf20.png)



## Result

Thus a website is designed for the software product company and the HTML,CSS code are validated.
