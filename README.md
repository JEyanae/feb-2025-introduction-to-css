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

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joseph Eyanae Longoli</title>
    <!-- Linking external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="main-header">
        <h1>Welcome to the world of software development</h1>
    </header>

    <section id="about">
        <p></p>
    </section>

    <img src="https://www.bdtask.com/blog/software-development-life-cycle?utm_source=chatgpt.com" alt="Software development image" class="profile-img">

    <footer>
        <p class="Joseph Eyanae">Copyright.</p>
    </footer>
</body>
</html>

styel.css

/* ID selector */
#about {
    background-color: #f0f8ff;
    padding: 15px;
    border: 2px solid #3498db;
    margin: 20px 0;
    font-family: 'Verdana', sans-serif;
}

/* Class selector */
.main-header {
    background-color: #3498db;
    color: white;
    text-align: center;
    padding: 20px;
    border-radius: 8px;
}

/* Element selector */
p {
    color: #333;
    line-height: 1.6;
    font-size: 16px;
    margin: 10px 20px;
}

/* Image styling */
.profile-img {
    display: block;
    margin: 20px auto;
    border: 4px solid #2ecc71;
    padding: 5px;
    border-radius: 10px;
    width: 150px;
}

/* Another class selector */
.footer-text {
    text-align: center;
    color: gray;
    font-style: italic;
}

