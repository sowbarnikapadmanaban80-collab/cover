# Ex.05 Book Cover Page Design
## Date:14/12/25

## AIM:
To design a book back cover page using HTML and CSS.

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
<html>
    <head>
        <title>book cover</title>
        <link href="coverapp.css" rel="stylesheet">
    </head>
    <body>
        <div class="container">
            <h1>About This Book</h1>
            <hr style="width: 100%;">
    <p>This book <span class="highlight">"COMPUTER FUNDAMENTALS"</span> are the basic concepts of using and understanding digital devices, covering how a computer takes input, processes it, and provides output. This includes an understanding of hardware (physical parts like the CPU and keyboard), software (instructions and programs), storage, and fundamental skills like navigation, file management, and basic troubleshooting. A core function is processing data into meaningful information using input, processing, and output operations, often referred to as the IPO model.
     </p>
    <div class="quote">
        “the computers are like old Testament gods;lots of rules and no mercy."
    </div>

    <div class="author">
        <img src="img.jpg" class="img">
        <div>
            <h3>SOWBARNIKA.M.P</h3>
            <p> Sowbarnika M P is a prominent young writer recognized for her thoughtful expression, academic discipline, and passion for knowledge and creative writing.           </p>
        </div>
    </div>

    <div class="footer">
        <span>SEC Publishers<br>Printed in India</span>
        <span class="price">Price: ₹600</span>
    </div>
</div>
</body>

</html>

.container
{
    margin: 0;
    background :url(bg.png.png) no-repeat center/contain;
    background-size: 800px 700px;
    padding: 100px;
    width: 470px;
    margin: 35 auto;
    padding: 25;
    border-radius: 5px;
}

h1 {
    color: #006611;
}

hr {
    border: none;
    height: 3px;
    background: #003366;
}

p {
    line-height: 1.5
    font-size: 18px;
}

.highlight {
    background: rgb(255, 187, 0);
    font-weight: bold;
}

.quote {
    background: #e6f4ff;
    border-left: 6px solid #2b6cb0;
    padding: 15px;
    margin: 20px 0;
    font-style: italic;
}

.author {
    display: flex;
    gap: 15px;
    background: #ffffff;
    padding: 15px;
    border-radius: 8px;
}

.author img {
    width: 140px;
    height: 130px;
    border-radius: 3px;
    object-fit: cover;
}

.author h3 {
    margin: 0;
    color: #003366;
}

.footer {
    margin-top: 40px;
    background: #660058;
    color: rgb(255, 255, 255);
    padding: 15px;
    display: flex;
    justify-content: space-between;
    border-radius: 7px;
    font-size:17px;
}

.price {
    font-weight: bold;
}


```

## OUTPUT:

![alt text](<Screenshot 2025-12-14 221229.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
