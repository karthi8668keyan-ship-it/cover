# Ex.05 Book Front Cover Page Design
## Date:

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
  <meta charset="UTF-8">
  <title>Book Cover - Karthikeyan A</title>

  <style>

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      min-height: 100vh;
      background-color: #1a1a2e;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: Georgia, serif;
    }

    .book {
      width: 320px;
      border-radius: 6px;
      overflow: hidden;
      box-shadow: 8px 12px 40px rgba(0, 0, 0, 0.6);
    }

    .top-section {
      background-color: #2D1B69;
      padding: 50px 36px 44px;
      text-align: center;
    }

    .deco-line {
      width: 40px;
      height: 2px;
      background-color: #F6C90E;
      margin: 0 auto 20px;
    }

    .deco-line-bottom {
      width: 40px;
      height: 2px;
      background-color: #F6C90E;
      margin: 20px auto 0;
    }

    .book-title {
      font-size: 50px;
      font-weight: 900;
      color: #F6C90E;
      line-height: 1.05;
      letter-spacing: 3px;
    }

    .middle-band {
      background-color: #F6C90E;
      padding: 10px 36px;
      text-align: center;
    }

    .tagline {
      font-size: 10px;
      font-weight: 800;
      letter-spacing: 5px;
      color: #2D1B69;
    }

    .bottom-section {
      background-color: #0F0F23;
      padding: 32px 36px 40px;
      text-align: center;
    }

    .divider {
      width: 50px;
      height: 1px;
      background-color: #F6C90E;
      margin: 0 auto 22px;
      opacity: 0.6;
    }

    .quote {
      font-size: 14.5px;
      font-style: italic;
      color: #c9b99a;
      line-height: 1.8;
      margin-bottom: 28px;
    }

    .author-name {
      font-size: 16px;
      font-weight: 800;
      color: #F6C90E;
      letter-spacing: 2px;
      margin-bottom: 8px;
    }

    .small-divider {
      width: 30px;
      height: 1px;
      background-color: #F6C90E;
      margin: 10px auto;
      opacity: 0.4;
    }

    .publisher {
      font-size: 9.5px;
      letter-spacing: 4px;
      color: #5a5a7a;
      font-weight: 600;
    }

  </style>
</head>
<body>

  <div class="book">
    <div class="top-section">
      <div class="deco-line"></div>
      <h1 class="book-title">GOLDEN<br>SPARKS</h1>
      <div class="deco-line-bottom"></div>
    </div>

    <div class="middle-band">
      <p class="tagline">INSPIRE &nbsp;✦&nbsp; CREATE &nbsp;✦&nbsp; CONQUER</p>
    </div>

    <div class="bottom-section">
      <div class="divider"></div>

      <p class="quote">
        "Those who dare to dream<br>
        beyond the ordinary<br>
        shall light the world ablaze"
      </p>

      <p class="author-name">KARTHIKEYAN A</p>
      <div class="small-divider"></div>
      <p class="publisher">AURORA PRESS</p>
    </div>

  </div>

</body>
</html>
```
## OUTPUT:

![alt text](image.png)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully..