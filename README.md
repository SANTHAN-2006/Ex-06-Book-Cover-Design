# Ex-06-Book-Cover-Design

# AIM : 
To Design a Book cover page using HTML and CSS.

# Requirements :
Code editors like visual studio code or notepad to run the html and css code.

# Step 1:
## Create a New HTML File:

Open your favorite text editor or an integrated development environment (IDE).

Create a new file and save it with a .html extension, for example, index.html.
# Step 2:
## HTML Structure:
Set up the basic HTML structure.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Web Development Technologies</title>
    <link rel="stylesheet" href="path/to/your/css/file.css">
</head>
<body>
    <!-- Content goes here -->
</body>
</html>

```
# Step 3:
## Add CSS Styling:

Create a new CSS file, for example, styles.css.
Link the CSS file to your HTML.
# Step 4:
## CSS Styling:

Copy and paste the CSS styles you've provided into your styles.css file.
Adjust styles as needed.
# Code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
        <style>
            body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    margin:auto;
    position: relative;
    background-image: url(https://static.vecteezy.com/system/resources/previews/001/962/594/large_2x/abstract-wave-element-for-design-stylized-line-art-background-free-vector.jpg);
    background-repeat: no-repeat;
    background-size:cover;
    background-position: bottom 0px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: xx-large;
    font-weight:10px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    color:#f47027

}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 10px;
    border-top:2px solid #f47027;
    padding-top:0px;
    width:726px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.photo{
            position: relative;
            top: 170px;
            left: 550px;
            width: 120px;
            height: 120px;
            background-size: cover;
        }
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
        </style>
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition</h3>  
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>Santhan Kumar</span>
                    <span id="end"><u>Packt></u></span>
                </div>
            </footer>
            <div class="photo">
                <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\43A115CBD6F4788924537365BE3D6012\WhatsApp Image 2023-12-15 at 10.06.36_9be43d67.jpg" width="150" height="170"alt="">
            </div>  
    </section>
    </body>
</html>
```
# Step 5:
Run the html and css code in any code editor.
# Output:
![image](https://github.com/SANTHAN-2006/Ex-06-Book-Cover-Design/assets/80164014/f99664fb-ab38-4e58-be5a-d2f880304473)
# Result :
Therefore, successfully created a Book Cover Page Design using HTML and CSS.
## Developed By : K. Santhan Kumar
## Register Number : 212223240065
