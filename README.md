# Netflix-Login
Creating a netflix login page using HTML and CSS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #111;
            color: white;
        }

        header {
            padding: 20px;
            background-color: #111;
            text-align: center;
        }

        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .movie {
            width: 200px;
            margin: 10px;
        }

        .movie img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #111;
        }
    </style>
</head>

<body>

    <header>
        <h1>Netflix Clone</h1>
    </header>

    <section>
        <div class="movie">
            <img src="movie1.jpg" alt="Movie 1">
            <h3>Movie Title 1</h3>
        </div>

        <div class="movie">
            <img src="movie2.jpg" alt="Movie 2">
            <h3>Movie Title 2</h3>
        </div>

        <div class="movie">
            <img src="movie3.jpg" alt="Movie 3">
            <h3>Movie Title 3</h3>
        </div>

        <!-- Add more movies as needed -->

    </section>

    <footer>
        <p>&copy; 2024 Netflix Clone</p>
    </footer>

</body>

</html>
