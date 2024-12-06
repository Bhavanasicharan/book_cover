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
'''
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: rgb(229, 14, 14);
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Times New Roman', Times, serif;
            background-image: linear-gradient(rgb(0, 255, 229), rgb(255, 192, 247)), url('../images/back.png');
            background-size: cover;
        }

        .insight{
            color: rgba(10, 1, 18, 0.29);

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: rgb(37, 4, 51);
            display: inline;
            position: relative;
            color: rgb(0, 17, 255);
            top: 190px;

            font-family: Georgia, 'Comic Sans MS', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id{
            width: 400px;
            position: relative;
            top: 180px;

        }

        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }
        .ed{
            color: rgb(182, 61, 13);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 85px;

        }
        .subtile{
            font-family: Tahoma;
            font-size: large;
            text-align: center;  
            position: relative;
            top: 40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHTS
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(0, 255, 166);">
            </div>
            <div class="booktitle">
                <h1>CSS and HTML</h1>
            </div>
            <div class="subtitle">
            and <br> javascript demystified
            </div>
            <div class="mypic">
                <img src="swan.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(0, 17, 255);">
            </div>
            <div class="author">
                <p><b> B.Charan reddy</b></p>
            </div>
            <div class="pub">
                Saveetha<br> Engineering<br> College 
            </div>
            <div class="ed">
                <b>Extended Edition</b><br>
            </div>
        </div>
    </body>
</html>
'''
# OUTPUT:

![Screenshot 2024-12-06 233533](https://github.com/user-attachments/assets/48ecb2ae-5788-475e-bf8f-979d01ceca30)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
