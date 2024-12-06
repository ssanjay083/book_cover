# Ex.06 Book Front Cover Page Design
# Date:15.10.2024
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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Design</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #ececec;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .book-cover {
            width: 350px;
            height: 550px;
            background: linear-gradient(to bottom, #0d1b2a, #1a5276, #333333);

            color: white;
            padding: 20px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
            border-radius: 12px;
            position: relative;
        }

        .header {
            text-align: left;
        }

        .tagline {
            color: #00ff99;
            font-size: 12px;
            margin-bottom: 10px;
            text-transform: uppercase;
            font-weight: bold;
            letter-spacing: 1px;
        }

        h1 {
            font-size: 26px;
            margin: 0;
            line-height: 1.3;
            font-weight: bold;
        }

        .subtitle {
            font-size: 14px;
            color: #b0e8ff;
            margin-top: 10px;
        }

        .iot-image {
            height: 180px;
            background: url('iot pic.png') no-repeat center center;
            background-size: cover;
            border-radius: 8px;
            margin: 20px 0;
        }

        .footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .edition {
            color: #00ff99;
            font-size: 14px;
            font-weight: bold;
        }

        .author-info {
            text-align: right;
        }

        .author-name {
            font-size: 14px;
        }

        .publisher {
            font-size: 16px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="header">
            <p class="tagline">FUTURE INNOVATION</p>
            <h1>The Art of IoT<br>Designing Intelligent Systems</h1>
            <p class="subtitle">A comprehensive guide to creating smart, connected devices for a better future</p>
        </div>
        <div class="iot-image"></div>
        <div class="footer">
            <p class="edition">First Edition</p>
            <div class="author-info">
                <p class="author-name">AMY PAUL</p>
                <p class="publisher">TechPress</p>
            </div>
        </div>
    </div>
</body>
</html>

```
# OUTPUT:
![Screenshot 2024-12-07 004537](https://github.com/user-attachments/assets/c432a277-e9cc-4d10-8571-bdbde6b7da7c)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
