# Ex.06 Book Front Cover Page Design
## Date:15.12.2023

## AIM:
To design a book front cover page using HTML and CSS.

## ALGORITHM


1.Create a Django Admin project.


2.Create an app in the Django interface.


3.Create a folder named 'static' in the app folder.


4.Create a new HTML file in the static folder. 
5.Write the HTML code with relevant CSS properties.


6.Choose the appropriate style and color scheme.


7.Insert the images in their appropriate places.


8.Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
<title>
Front cover page
</title>
<style>
.bookpage{
height:720px;
width:500px;
margin-left:35%;
background-image: url(img1.jpg);
padding:10px;
background-size: cover;
}
.hr1{
width:200px
}
.booktitle{
margin-top: 30px;
color:rgb(255, 0, 0);
padding:5px;
font-size: xx-large;
}
.subtitle{
color:rgb(0, 255, 225);
font-size: large;
}
.mypic{
position: relative;
top:90px;
left:390px;
height: 80px;
width: 90px;
}
.hr2{
padding-top: 130px;
}
*{
color: rgb(200, 0, 255);
}
.ed{
position:relative;
top: 110px;
}
.author{
font-family: 'Trebuchet MS';
font-size: large;
}
.pb{
position: relative;
left:420px;
top:-40px;
font-size: x-large;
}
</style>
<body>
<div class="bookpage">
<div style="color:rgb(0, 255, 64)">INSIGHT </div>
<div class="hr1"><hr ></div>
<div class="booktitle"><h1>Python Programming for Beginners</h1></div>
<div class="subtitle">Beginner-friendly guide to learning Python programming, covering everything from basic syntax to advanced topics with practical exercises and projects.</div>
<div class="mypic"><img src="mypic.jpg" height="130px" ></div>
<div class="ed">SPECIAL EDITION</div>
<div class="hr2"><hr ></div>
<div class="author"> HEMANTH A</div>
<div class="pb"> <h2>SEC</h2></div>
</div>
</body>
</head>
</html>


```

## OUTPUT:
![Alt text](<Screenshot (25).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
