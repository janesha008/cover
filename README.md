# Ex.06 Book Front Cover Page Design
## Date: 05.10.2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
bookcover.html

<html>
    <head>
        <title>Book Cover</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="background">
            <div class="inner">
                <div class="title">
                    <p>SEC Insights</p>
                    <hr>
                    <br><br>
                    <h1 align="center">WEBPAGE OR WEBAPP AND SERVER INTERACTIONS</h1>
                    <br>
                    <p class="sub">Client-server model, HTTP request-response cycle, APIs, and rendering content.</p><br>
                    <p>2025 Best-Seller</p>
                </div>
                <div class="footer">
                    <div class="edition-section">
                        <h3 class="edition">SPECIAL EDITION</h3>
                        <img src="photo.png" class="image" alt="Author Photo">
                    </div>
                    <hr class="line">
                    <div class="footer-text">
                        <p class="left-text">Janesha S</p>
                        <p class="right-text">SEC</p>
                    </div>
                </div>
            </div>
        </div>
    </body>
</html>

style.css

body{
    display: flex;
    justify-content: center;
    color:white
}
.background{
    width: 450px;
    height: 650px;
    margin-top: 30px;
    background-image: url("back.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    position: relative;
    padding: 10px;
}
.inner{
    width:440px;
    height: 640px;
    border: 4px solid rgb(218, 178, 254)
}
.title{
    margin: 5px
}
.sub{
    font-size: large;
}
.footer {
    margin: 5px;
    position: absolute;
    bottom: 20px;
    left: 20px;
    right: 20px;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
}

.edition-section {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
}

.image {
    width: 100px;
    height: auto;
}

.footer-text {
    display: flex;
    justify-content: space-between;
    font-weight: bold;
    font-size: 14px;
}

.left-text {
    text-align: left;
    font-size: large;
}

.right-text {
    text-align: right;
    font-size: large;
}
.line{
    width: 400px;
}
```
## OUTPUT:
![alt text](<Screenshot (78).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
