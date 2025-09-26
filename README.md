    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
            text-align: center;
            color: #333;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            color: #4CAF50;
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        p {
            color: #555;
            font-size: 1.2em;
            line-height: 1.6;
            margin-bottom: 30px;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 30px;
        }

        a {
            color: #2196F3;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
            padding: 10px 20px;
            border: 2px solid #2196F3;
            border-radius: 5px;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        a:hover {
            background-color: #2196F3;
            color: #fff;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to My Page!</h1>
        <p>
            Hello! I enjoy spending my free time reading fantasy novels and exploring new places. There's nothing quite like getting lost in a good story or discovering a hidden gem in my own city. It's a great way to relax and recharge.
        </p>
        <img src="https://placehold.co/800x400/B2DFDB/000000?text=My%20Favorite%20Hobby" alt="A placeholder image representing my hobby">
        <br>
        <a href="https://www.google.com" target="_blank">Visit a Great Website</a>
    </div>
</body>
</html>
git init
git add .
git commit -m "My first website"
git branch -M main
git remote add origin https://github.com/<your-username>/my-first-website.git
git push -u origin main
