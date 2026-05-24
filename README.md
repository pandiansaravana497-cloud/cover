# Ex.05 Book Front Cover Page Design
## Date:

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

### book.html
~~~
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="book">

    <div class="circle circle1"></div>
    <div class="circle circle2"></div>
    <div class="circle circle3"></div>
    <div class="circle circle4"></div>

    <div class="content">

        <h1>
            THE PATH <br>
            TO <br>
            WISDOM
        </h1>

        <p class="subtitle">
            "Navigating Life's Challenges with Insight and Clarity"
        </p>

    </div>

    <div class="photo">
        <img src="image.png" alt="Author">
    </div>

    <div class="footer">

        <div class="name">
            PON SARAVANA PANDIAN B
        </div>

        <div class="year">
            2025 - SEC
        </div>

    </div>

</div>

</body>
</html>
~~~
### style.css
~~~
body{
    margin:0;
    padding:0;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    background:#dbefff;
    font-family:Georgia, serif;
}

.book{
    width:540px;
    height:770px;
    background:linear-gradient(to bottom,#9fc4df,#c8dcec);
    border-radius:18px;
    overflow:hidden;
    position:relative;
    box-shadow:0 8px 20px rgba(0,0,0,0.3);
}


.circle{
    position:absolute;
    background:rgba(255,255,255,0.2);
    border-radius:50%;
}

.circle1{
    width:220px;
    height:140px;
    top:30px;
    right:-10px;
}

.circle2{
    width:170px;
    height:110px;
    top:125px;
    right:-20px;
}

.circle3{
    width:280px;
    height:150px;
    top:325px;
    left:100px;
}

.circle4{
    width:230px;
    height:120px;
    bottom:125px;
    right:0;
}



.content{
    padding:40px;
    position:relative;
    z-index:2;
}

h1{
    font-size:60px;
    line-height:1.05;
    margin:0;
    color:black;
    font-weight:bold;
}

.subtitle{
    margin-top:25px;
    font-size:18px;
    font-style:italic;
    line-height:1.6;
    color:#222;
}
.photo{
    position:absolute;
    right:35px;
    bottom:110px;
    z-index:2;
}

.photo img{
    width:135px;
    height:165px;
    object-fit:cover;
    border:4px solid white;
    box-shadow:0 5px 15px rgba(0,0,0,0.3);
}

.footer{
    position:absolute;
    bottom:0;
    width:100%;
    background:#173f88;
    color:white;
    display:flex;
    justify-content:space-between;
    padding:18px 30px;
    box-sizing:border-box;
    font-size:20px;
    font-weight:bold;
}
~~~

## OUTPUT:

<img width="544" height="778" alt="Screenshot 2026-05-24 153134" src="https://github.com/user-attachments/assets/6f50b118-f911-4a3b-9a0c-7b64ef922293" />

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
