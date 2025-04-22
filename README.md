# Ex.06 Book Front Cover Page Design
# Date: 22-4-2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>BOOK COVER PAGE</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f9f9f9;
            font-family: 'Didot', 'Baskerville', 'Georgia', 'Palatino', serif;
        }

        .book-cover {
            background: url('bookcover.jpg') no-repeat center / cover;
            height: 600px;
            width: 400px;
            color: white;
            box-shadow: 0 0 30px rgba(0, 0, 0, 0.5);
            padding: 30px 20px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            text-align: center;
        }

        .book-title h2 {
            font-size: 1.1rem;
            margin-bottom: 5px;
            font-style: italic;
            letter-spacing: 1px;
        }

        .book-tagline {
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .book-tagline h1 {
            font-size: 2.2rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin: 5px 0;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.4);
        }

        .bottom-text {
            font-size: 1.05rem;
            margin-bottom: 15px;
            font-style: italic;
            color: #f5f5f5;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.6);
        }

        .book-author {
            display: flex;
            flex-direction: column;
            align-items: flex-end;
            text-align: right;
        }

        .book-author img {
            border-radius: 20%;
            margin-bottom: 8px;
            border: 1.5px solid white;
        }

        .book-author h2 {
            font-weight: normal;
            font-style:Bold;
            font-size: 1rem;
            letter-spacing: 1px;
        }

        hr {
            border: none;
            height: 1px;
            background-color: #ffffff;
            margin: 10px auto;
            width: 80%;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="book-title">
            <hr>
            <h2>The International Best Seller</h2>
            <hr>
        </div>

        <div class="book-tagline">
            <h1><i>The</i></h1>
            <h1><i>Psychology</i></h1>
            <h1><i>of</i></h1>
            <h1><i>Money</i></h1>
        </div>

        <div class="bottom-text">
            Timeless Lessons on Wealth, Greed, and Happiness
        </div>

        <div class="book-author">
            <h2>JEEVIKA R </h2>
        </div>
    </div>
</body>
</html>
```

# OUTPUT:

![image](https://github.com/user-attachments/assets/f325f0ec-d116-480a-bd04-30ab4f90f2c3)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
