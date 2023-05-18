# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a new Django project and app.

### Step 2:
Create a static file directory and mention the changes in settings.

### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

### Step 4:
Write down the code for book cover using HTML and CSS.

### Step 5:
Add images and other contents using CSS record a screenshot of it.
## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 650px;
            color:rgb(0, 221, 255);
            margin-left: auto;
            margin-right: auto;
            padding: 25px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/pxfuel.jpg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(0, 221, 255);

        }

        
        .hrstyle{
            width:230px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(0, 255, 26);
            top:300px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(8, 0, 255);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 0px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:300px;
            
        }
        .pub{
            color:rgb(255, 0, 0);
            font-size: medium;
            position: relative;
            top:270px;
            left:330px;
        }
        .ed{
            color:rgb(255, 0, 212);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:200px;

        }
        .subtitle{
            color:rgb(0, 213, 255);
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:200px;
        }
        .mypic{
            position: relative;
            top: 240px;
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
                Glory to the future of "RACISTS"
            </div>
            <div class="hrstyle">
                <hr style="color: greenyellow;">
            </div>
            <div class="booktitle">
                <h1>WANT TO BECOME A CYBERPUNK?</h1></div>
            <div class="subtitle">
                The future is there..
                Looking back at us..
                Trying to make the sense of fiction we have become.
            </div>
            <div class="mypic">
                <img src="/static/images/thookdurai.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(255, 0, 0);">
            </div>
            <div class="author">
               <p><b>Ashwin</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Best edition</b>
            </div>
        </div>
    </body>
</html>
```
## Output:
![output](./output.png)
![output](./prgm.png)
## Result:
The program for designingbook cover page using HTML and CSS is executed successfully