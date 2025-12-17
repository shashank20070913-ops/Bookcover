# Ex.06 Book Front Cover Page Design
## Date:17/12/2025

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
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #ffffff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgb(243, 135, 11);
      border: 2px solid #101b0c;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(237, 10, 10, 0.2);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: #ffffff;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
      color: bisque;
    }

     .image {
      flex: 1;
      margin: 30px 0;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    
    .image img {
      max-width: 75%;
      height: auto;
      object-fit: contain;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #0ad598;
      margin-top: 20px;
    }

    .quote{
      text-align: center;
      font-size: 18px;
      margin-top: 20px;
      color: aquamarine;
    }

    .line {
      height: 2px;
      background: #fdfcfc;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">The Great Gatsby</div>
      <div class="line"></div>
      <div class="subtitle">F. Scott Fitzgerald's 1925 masterpiece does not have an official subtitle. However, the novel is famous for the many alternative titles Fitzgerald considered and the self-composed epigraph that often appears on its title page. 
      </div>
    </div>
    <div class="image">
        <img src="download.jpeg" length="20%" width="75%">
    </div>
    <div class="quote">
      An Amazing book to get strong in your fundamentals
    </div>
    <div class="author">F. Scott Fitzgerald</div>
  </div>
</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot 2025-12-17 110530.png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
