# Ex.06 Book Front Cover Page Design
# Date:22/11/2024
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
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: rgba(0, 38, 255, 0.845);
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: linear-gradient(rgba(191, 0, 255, 0.756), rgb(255, 235, 192)), url('../images/back.png');
            background-size: cover;
        }

        .insight{
            color: rgb(122, 80, 122);

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: rgb(255, 255, 255);
            display: inline;
            position: relative;
            color: rgb(0, 0, 0);
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
            color: rgb(0, 217, 255);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 85px;

        }
        .subtile{
            font-family: Tahoma;
            font-size: large;
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
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:red;">
            </div>
            <div class="booktitle">
                <h1>INNER ENGINEERING</h1>
            </div>
            <div class="subtitle">
                Finding the source of your happiness
            </div>
            <div class="mypic">
                <img src="C:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-12-05 205159.png" width="150" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(0, 17, 255);">
            </div>
            <div class="author">
                <p><b>Bhavanasi Charan reddy</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>
    </body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-13 231245](https://github.com/user-attachments/assets/40244c5d-51ed-48f6-805e-aebbc68adc37)

NAME : BHAVANASI CHARAN REDDY

REGISTER NUMBER : 24009453

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
