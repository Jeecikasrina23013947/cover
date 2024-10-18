# Ex.06 Book Front Cover Page Design
## Date:18.10.2024

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
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 450px;
            height: 800px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(background.jpeg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(240, 233, 233);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:red;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: -12px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:purple;
            font-size: small;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 140px;
            left: 260px;
            width: 80px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                18th Edition
            </div>
            <div class="hrstyle">
                <hr style="color: yellow;">
            </div>
            <div class="booktitle">
                <h1> Convergence: Exploring the Synergy of Artificial Intelligence and Web Technologies</h1></div>
            <div class="subtitle">
                "Convergence" is about the fusion of AI and web tech, changing digital experiences with personalized content and smart search engines.
            </div>
            <div class="mypic">
                <img src="meee.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Ranjani A</b></p>
            </div>
            <div class="pub">
               AI-DS
                <br>Student at SEC
            </div>
            <div class="ed">
                <br>
                    Published by
                </br>
                
            </div>
        </div>
    </body>
</html>
```


## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
