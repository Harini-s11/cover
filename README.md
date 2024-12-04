# Ex.06 Book Front Cover Page Design
## Date:04.12.2024

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
book.html
<html>
    <head>
        <style>
            .bookcover{
                width:400px;
                height:600px;
                margin-left:auto;
                margin-right:auto;
                font-family:Georgia, 'Times New Roman', Times, serif;
                padding:20px;
                background-image:url(bookcover.jpeg);
                background-size:cover;
                color:cornsilk;

            }
            .insight{
                color:rgb(182, 252, 251);
    

            }
            .hrstyle{
                width:10px;
                

            }
            .author{
                display:inline;
                position:relative;
                color:rgb(197, 254, 253);
                font-family:Georgia, 'Times New Roman', Times, serif;
                font-size:medium;
                top:360px;


            }
            .booktitle{
                position:relative;
                text-align:center;
                font-family:Georgia, 'Times New Roman', Times, serif;
                font-size:larger;
                top:30px;
                color:azure;

            }
            .edition{
                font-family:Georgia, 'Times New Roman', Times, serif;
                font-size:medium;
                color:rgb(182, 250, 242);
                position:relative;
                top:200px;
                border-width:10px;
                border-color:white;
            }
            .about{
                position:relative;
                text-align:center;
                font-size:large;
                font-family:Georgia, 'Times New Roman', Times, serif;
                top:40px;
                
            }
            .authorpic{
                position:absolute;
                top:450px;
                right:600px;
                width:100px;
                height:100px;
                background:cover;

            }
            .pub{
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                font-size:medium;
                text-align:right;
                position: absolute;
                top: 590px;
                color:white;
                left: 830px;
            }
        </style>
    </head>
    <title>MY BOOK</title>
    <body>
        <div class="bookcover">
            <div class="insight">EXPERT INSIGHT
                
            </div>
            <div class="hrstyle">
                <hr style ="color:rgb(250, 254, 253 )";>
            </div>
            <div class="booktitle">
                <h1><b>OPEN YOUR MIND WITH WEB</b></h1>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             
            </div>
            <div class="authorpic">
                <img src="mypic.jpg" width="130" height="145" alt="">
            </div>
            <div class="author">
                <p><b>HARINI S</b></p>
            </div>
            <div class="pub">
                <p><b>SEC Publication</b></p>
            </div>
            <div class="edition">
                <b>Fourth edition</b>
            </div>
        </div>
    </body>
</html>
```


## OUTPUT:


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
