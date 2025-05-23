# Ex.06 Book Front Cover Page Design
## Date:10/04/2025

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
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover with Text on Image</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background-color: #f5f5f5;
    }

    .book-cover {
      position: relative;
      width: 300px;
      height: 450px;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
    }

    .book-cover img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .text-overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      text-align: center;
      font-family: 'Arial', sans-serif;
      text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.8);
    }

    .text-overlay .title {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .text-overlay .subtitle {
      font-size: 18px;
      margin-bottom: 20px;
    }

    .text-overlay .author {
      font-size: 16px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <img src="C:\Users\admin\cover\vijay\bookapp\static\images (1).jpeg" alt="Book Cover">
        <div class="text-overlay"><hr>
      <div class="title" style="color: rgb(255, 255, 255);">THE DAWN OF HOPE</div>
      <div class="subtitle" style="color:rgb(0, 0, 0)"> A Tale Of The Boy</div>
      <div class="author" style="color:rgb(255, 252, 252)">By Zack Snyder</div><hr>
    </div>
  </div>
</body>
</html>

```

## OUTPUT:
![Alt text](<Screenshot (56).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
