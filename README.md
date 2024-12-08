# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```html
{% load static %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Science Book Cover</title>
    <style>
        body {
            text-align: center;
            background-color: #e0f7fa;
            font-family: Arial, sans-serif;
        }
        .cover {
            position: relative;
            display: inline-block;
            width: 450px;
            margin: 50px;
            background-color: aliceblue;
        }
        .cover img {
            width: 100%;
        }
        h1, h2 {
            position: absolute;
            top: 20px; 
            left: 50%;
            transform: translateX(-50%);
            color: #0f0e0e;
            margin: 0;
        }
        h1 {
            top: 10px; 
            font-size: 0.5em;
        }
        h2 {
            top: 80px;
            font-size: 1.5em;
        }
    </style>
</head>
<body>

<div class="cover">
    <img src="{% static 'myapp/boo.png' %}" alt="Book Cover">
</div>

</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-08 182316](https://github.com/user-attachments/assets/b98f49ac-2109-4724-ba46-71189e00145a)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
