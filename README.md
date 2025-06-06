# Ex.06 Book Front Cover Page Design
# Date:28-04-2025
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
    <title>Book Cover</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600&family=Cormorant+Garamond:ital,wght@1,400;1,600&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Cormorant Garamond', serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #fdfdfd; /* Soft off-white background */
        }
        .book-cover {
            width: 500px;
            height: 700px;
            background: url('650fac21471462a1831d08d641e679a1.jpg') center/cover no-repeat;
            border: 10px solid #c7a585;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.35);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            text-align: center;
            padding: 40px 20px;
            position: relative;
            backdrop-filter: brightness(0.9);
        }
        .title {
            font-family: 'Cinzel', serif;
            font-size: 3rem;
            font-weight: 600;
            color: #fff;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin: 20px 0;
            text-shadow: 3px 3px 8px rgba(0, 0, 0, 0.7);
        }
        .subtitle {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.4rem;
            color: #f2f2f2;
            font-style: italic;
            margin: 10px 0 20px 0;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.6);
        }
        .quote {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.1rem;
            color: #f0f0f0;
            margin: 20px 10px;
            font-style: italic;
            line-height: 1.6;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.7);
        }
        .author {
            font-family: 'Cinzel', serif;
            font-size: 1.6rem;
            font-weight: bold;
            color: #fff;
            margin-top: 30px;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.7);
        }
        .decorative-line {
            height: 3px;
            width: 80%;
            margin: 20px auto;
            background: linear-gradient(90deg, rgba(187, 154, 121, 0.9), #ffffff, rgba(187, 154, 121, 0.9));
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="title">The Architecture of Silence</div>
        <div class="decorative-line"></div>
        <div class="subtitle">Chilling, elegant, and deeply psychological.</div>
        <div class="quote">"He built not with brick or stone, but with the spaces between — the hollow pauses where words might have been."</div>
        <div class="author">By- Vatsan.g</div>
    </div>
</body>
</html>



```



# OUTPUT:

![alt text](<Screenshot 2025-04-28 214705.png>)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
