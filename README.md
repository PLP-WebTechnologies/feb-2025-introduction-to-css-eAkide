# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking the external CSS file -->
</head>
<body>

    <header>
        <h1 class="title">Welcome to My Styled Page</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <h2 class="subtitle">About Us</h2>
        <p id="intro">This is an example of how to apply CSS styling to an HTML page.</p>

        <img src="https://www.pexels.com/photo/nature-123.jpg" alt="Nature Image" class="styled-image">
    </main>

    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>

</body>
</html>


body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}
#intro {
    font-size: 18px;
    color: #333;
    padding: 10px;
    border-left: 4px solid #007bff;
}
title {
    color: #007bff;
    text-align: center;
    font-size: 28px;
}
.subtitle {
    color: #ff6600;
    font-weight: bold;
}
.styled-image {
    width: 300px;
    border-radius: 10px;
    margin: 20px auto;
    display: block;
}
nav ul {
    list-style-type: none;
    padding: 0;
    background-color: #007bff;
    overflow: hidden;
    text-align: center;
}
nav ul li {
    display: inline;
    margin: 0 10px;
}
nav ul li a {
    color: white;
    text-decoration: none;
    padding: 10px 15px;
}
footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: white;
    margin-top: 20px;
}
