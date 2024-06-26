# Ex.06 Book Front Cover Page Design
## Date: 27/04/2024

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
book.html
<!DOCTYPE html>
<html>

<head>
  <title>Book Cover</title>
  <style>
    body 
    {
      margin: 0;
      padding: 0;
      background-color:rgb(241, 235, 243);
    }


    .book-cover 
    {
      width: 500px;
      height: 700px;
      background-color:rgb(0, 0, 0);
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      margin: 50px auto;
      position: relative;
    }

    
    .book-cover .insight
    {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 50px;
      font-weight: bold;
      color: rgb(255, 255, 255);
    }



    .book-cover .line1
    {
      position: absolute;
      top: 40px;
      left: 10px;
      width: 80px;
    }



    .book-cover .title1 
    {
      position: absolute;
      top: 80px;
      left: 20px;
      font-size: 35px;
      font-weight: bold;
      color:  rgb(202, 224, 247);
    }

    

    .book-cover .subtitle2
    {
      position: absolute;
      top: 500px;
      left: 20px;
      font-size: 17px;
      font-weight: bold;
      color: rgb(232, 171, 227);
    }



    .book-cover .subtitle3
    {
      position: absolute;
      top: 530px;
      left: 20px;
      font-size: 29px;
      font-weight: bold;
      color: rgb(138, 251, 251);
    }



    .book-cover .line2
    {
      position: absolute;
      top: 480px;
      left: 20px;
      width: 160px;
    }



    .book-cover .line3
    {
      position: absolute;
      bottom:38px;
      left: 20px;
      width: 115px;
    }



    .book-cover .college 
    {
      position: absolute;
      bottom: 20px;
      left: 20px;
      font-family: 'Verdana';
      font-size: 20px;
      color: rgb(115, 181, 251);
    }



    .book-cover .ed
    {
      position: absolute;
      bottom: 50px;
      left: 18px;
      font-family: 'Verdana';
      font-size: 25px;
      color: rgb(255, 179, 206);
    }

 
    .book-cover .end 
    {
      position: absolute;
      bottom: 15px;
      right: 50px;
      font-family: 'Verdana';
      font-size: 18px;
      color: rgb(120, 241, 156);
    }



    .book-cover .mypic
    {
      position: relative;
      top:520px;
      left: 370px;
      width : 8px;
      height: 8px;
      background-size:fit;
    }


    .book-cover .image 
    {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top:  0;
      left: 10;
    }
  

  </style>

</head>

<body>
    
    <div class="book-cover">
      <img src="web img.jpg" alt="Book Cover" class="image">
      <div class="insight">PIXELS TO PAGES</div>
      <div class="title1">CREATIVE GUIDE TO WEB DESIGN</div>
      <div class="subtitle3">Learn Fundamentals of web design with HTML.</div>
      <div class="line3"><hr style="width:400%;text-align:left;margin-left:0"></div>
      <div class="mypic"><img src= "passport.jpg"width="120" height="120" ></div>
      <div class="ed"><b>Extended Edition</b></div>
      <div class="end">SEC</div>
      <div class="college">Sabeeha Shaik</div>
    </div>

  </body>

</html>
```




## OUTPUT:


![alt text](<Screenshot 2024-04-28 124838.png>)







## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
