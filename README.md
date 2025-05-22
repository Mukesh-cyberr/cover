# Ex.06 Book Front Cover Page Design
## Date:22/05/2025

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

      <html>
<head>
    <meta name="viewport" content="width=device=width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    .bookpage {
        width: 400px;
        height: 600px;
        color: rgb(0, 0, 0);
        margin: auto;
        padding: 20px;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        background-image: url("C:\\Users\\mukes\\OneDrive\\Desktop\\54587.jpg"); 
        background-size: cover;
        background-repeat: no-repeat;
    }

    .insight {
        color: rgb(255, 166, 0);
    }

    .hrstyle {
        width: 100px;
    }

    .author {
        color: rgb(20, 20, 19);
        font-size: small;
        text-align: center;
        margin-top: 150px;
    }

    .booktitle {
        font-size: larger;
        text-align: center;
        margin-top: 30px;
    }

    .id {
        width: 100%;
        margin-top: 80px;
    }

    .pub {
        font-size: medium;
        text-align: right;
        margin-top: 30px;
    }

    .ed {
        color: rgb(17, 21, 13);
        font-size: medium;
        text-align: center;
        margin-top: 50px;
    }

    .subtitle {
        font-size: large;
        text-align: center;
        margin-top: 10px;
    }

    .mypic {
        position: absolute;
        bottom: 20px;
        right: 20px;
        width: 100px;
        height: 100px;
        background-image: url('author.jpg'); /* Update with your image */
        background-size: cover;
        border-radius: 50%;
    }
</style>

    <title>BOOK COVER</title>
</head>
<body>
    <div class="bookpage">
        <div class="insight"> INSIGHT</div>
        <div class="hrstyle">
            <hr style="color: rgb(18, 17, 17)">
        </div>
        <div class="booktitle">
         <h1>"The Grace of Waiting"
                </h1>
        </div>
        <div class="subtitle">
            <center>
                Moments That Shape the Soul
            </center>
        </div>
       
        <div class="id">
            <hr style="color: rgb(154, 114, 40)">
        </div>
        <div class="author">
            <p><b> MUKESH RAJ D (212224100038)</b></p>
        </div>
        <div class="pub">
            
        </div>
        <div class="ed">
            <b>LIMITED EDITION</b>
        </div>
    </div>
</body>

</html>
       

```

## OUTPUT:
![alt text](<maha/Screenshot 2025-05-22 084022.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
