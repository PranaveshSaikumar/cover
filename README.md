# Ex.06 Book Front Cover Page Design
## Date:
8-05-24
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
html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cover</title>
  <link rel="stylesheet" href="coverpage.css">
</head>
<body>
   <div class="bookbox">
     <div id="div1">
      <span>Author of the #1 Worldwide Bestseller</span> <br> <br>
      <span>The Monk Who Sold His Ferrari</span>
     </div>
     <div id="circle">
      20 <br> MILLION <br> BOOKS SOLD <br> WORLDWIDE <br> --
     </div>
      <h1>R O B I N  <br>S H A R M A</h1>
      <h2>WHO WILL  CRY <br> WHEN  YOU  DIE?</h2>
     <div id="div2">
      <span class="span3">
          Life Lessons From The Monk <br> Who Sold His Ferrari
      </span>
     </div>
    </div>  
</body>
</html>
```
CSS
```
body{
    background-color: black;
}
.bookbox{
    width: 600px;
    height: 800px;
    background-color: rgba(0,185,242,255);
    margin: auto;
    position: relative;
    background-image: url(coverpic.png);
    background-repeat: no-repeat;
    background-size: 350px;
    background-position: bottom center;
}
#div1{
  text-align: center;
  padding-top: 50px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: 15px;
}
h1{
    color: white;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 75px;
    font-weight: bold;
    text-align: center;
    margin: 10px;
}
h2{
    color: black;
    font-weight: lighter;
    font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    text-align: center;
    font-size: 60px;
    margin: 10px;
}
.span3{
    color: grey;
    font-size: 20px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-style: italic;
    text-align: center;
}
#div2{
    text-align: center;
    margin: 10px;
}
#circle{
    width: 110px;
    height: 110px;
    border-radius: 50%;
    color: white;
    background-color: black;
    text-align: center;
    margin-left: 480px;
}
```

## OUTPUT:

![image](https://github.com/PranaveshSaikumar/cover/assets/151001393/7487b721-2753-40c5-a60d-5721f02c8bbe)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
