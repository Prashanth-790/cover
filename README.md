# Ex.06 Book Front Cover Page Design
## Date: 15/5/2025

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
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Web Design Book Cover</title>
    <style>
        *{
            font-size: 15px;
        }
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color:rgb(196, 33, 33);
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }

      .cover {
        width: 29vw;
        height: 79vh;
        background-color: #232323;
        border: white;
        padding: 20px;
        box-sizing: border-box;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
      }

      .cover .header {
        font-size: 14px;
        color: orange;
        font-weight: bold;
        z-index: 1;
        margin-bottom: 5px;
      }

      .cover .title {
        /* font-size: 28px; */
        margin-top: 10px;
        font-weight: bold;
        line-height: 1.2;
        z-index: 1;
      }

      .master {
        display: flex;
        flex-wrap: wrap;
        flex: content;
      }

      .cover .subtitle {
        font-size: 12px;
        margin-top: 15px;
        line-height: 1.5;
        z-index: 1;
        margin-bottom: 30px;
      }

      .about {
        background-color: #232323;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 5px;
      }

      .wave {
        height: 100px;
        scale: 80%;
        background: linear-gradient(45deg, transparent 50%, #c0c0c0 50%),linear-gradient(135deg, transparent 50%, #ffffff 50%);
        background-size: 100px 90px;
        transform: rotate(-45deg);
        opacity: 0.5;
        z-index: 0;
        margin-top: 13%;
        margin-bottom: 14%;

      }

      .bottom-section {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: auto;
        margin-bottom: -5px;
      }

      .cover .edition {
        color: orange;
        font-weight: bold;
        /* font-size: 18px; */
      }

      .cover .author {
        font-size: 12px;
        font-weight: bold;
      }

      .cover .publisher {
        font-style: italic;
        font-size: 14px;
        color: white;
        font-weight: bold;
      }

      .author-photo {
        width: 33px;
        height: 33px;
        border-radius: 50%;
        background: orange url("./Abishek\ Image\ in\ GR.png") top/cover
          no-repeat;
        margin-left: auto;
        margin-bottom: 11px;
        margin-top: -10px;
      }

      .ruler {
        background-color: orange;
        height: 1px;
        width: 59%;
        margin-left: -20px;
      }

      .rulerL {
        background-color: orange;
        height: 1px;
        width: 29vw;
        margin-left: -20px;
        margin-right: 0px;
      }
    </style>
  </head>

  <body>
    <div class="cover">
      <div class="header">EXPERT INSIGHT</div>
      <div class="ruler"></div>
      <div class="title">Responsive Web Design with <br />HTML5 and CSS</div>
      <div class="subtitle">
        Develop future-proof responsive websites<br />
        using the latest HTML5 and CSS techniques
      </div>
      <div class="wave"></div>
      <div class="bottom-section">
        <div class="edition">Fourth Edition</div>
        <br />
      </div>
      <div class="rulerL"></div>
      <div class="about">
        <div class="author">LAKSHMEN PRASHANTH </div>
        <div class="publisher">Science Saru</div>
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
