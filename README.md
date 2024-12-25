# Ex.06 Book Front Cover Page Design
# Date:05-10-2024
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
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compataible"content="IE=edge">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <link rel="stylesheet"href="style.css">
        <title>book cover</title>
    </head>
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <style>
        .image-container {
          position: relative;
          text-align: center;
        }
        .image-container img {
          width: 650px;
          height: 700px;
        }
        .inner-image img{
          width: 200px;
          height: 200px;
        }
        .inner-image{
          position: absolute;
          bottom: 35px;
          left: 235px;
          width: 50px;
          height: auto;
          border-radius: 50%;
        }
        .centered-text {
          position: absolute;
          top:10%;
          left: 50%;
          transform: translate(-50%, -50%);
          color:wheat;
          font-size: 24px;
          font-weight: bold;
        }
        .centered-text2{
            position: absolute;
            top:20%;
            left:30%;
            transform:translate(-50,-50) ;
            color:black;
            font-size: 24px ;
            font-weight: bold;
        }
        .centered-text3{
            position: absolute;
            TOP:33%;
            left:35%;
            transform:translate(-50,-50) ;
            color:honeydew;
            font: size 24px; 
            font-weight: bold;
        }
        .centered-text4{
            position: absolute;
            TOP:39%;
            left:38%;
            transform:translate(-50,-50) ;
            color:honeydew;
            font: size 24px; 
            font-weight: bold;
        }
        .centered-text5{
          position: absolute;
            TOP:90%;
            left:35%;
            transform:translate(-50,-50) ;
            color:honeydew;
            font: size 24px; 
            font-weight: bold;
        }
        .centered-text6{
            position: absolute;
            TOP: 47%;
            left:30%;
            transform:translate(-50,-50) ;
            color:rgb(80, 215, 27);
            font: size 24px; 
            font-weight: bold;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }
        .centered-text7{
            position: absolute;
            TOP: 51%;
            left:35%;
            transform:translate(-50,-50) ;
            color:rgb(80, 215, 27);
            font: size 20px; 
            font-weight: bold;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }
        .spaced-text{
          letter-spacing: 20px;
        }
      </style>
    </head>
    <body>
        <div class="image-container">
          <img src="save.jpg" alt="Image">
          <div class="centered-text"><h1>GREEN WONDER'S<hr></h1></div><br>
        
          <div class="centered-text2"><h3><b>"To plant a garden is<br> to believe in tomorrow"</b></h3></div>
          
          <div class="centered-text3"><h2>"Save a tree, it will<br><br></h2></div>
          <div class="centered-text4"><blockquote><h2>save you in return"</h2></blockquote></div>
          <div class="centered-text6"><h2>“We must protect and preserve our </h2></div>
          <div class="centered-text7"><blockquote><h2>natural resources for future generations.”</h2></blockquote></div>

          <div class="inner-image">
            <img src="swamy.jpg" alt="Inner Image" class="inner-image">
          </div>
          <div class="centered-text5"><p class="spaced-text" style="font-size: larger;">M.S. SWAMINATHAN</p></div>

        </div> 
          </body>
    </html>
    
</html>
```
# OUTPUT:
![alt text](<Screenshot (15).png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
