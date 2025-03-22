<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile-Friendly Webpage</title>
    <style>
        /* Basic styles for mobile-first design */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Header styles */
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }

        /* Navigation bar styles */
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-align: center;
            text-decoration: none;
            display: block;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        /* Main content styles */
        .content {
            padding: 20px;
        }

        h1 {
            text-align: center;
            color: #333;
        }

        .content p {
            font-size: 16px;
            color: #555;
        }

        /* Responsive styles for larger screens */
        @media (min-width: 600px) {
            nav {
                justify-content: space-around;
            }

            .content {
                padding: 40px;
            }

            h1 {
                font-size: 2em;
            }

            .content p {
                font-size: 18px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Mobile Page</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="content">
        <h1>About Us</h1>
        <p>
            This is a simple mobile-friendly webpage. It adjusts to fit different screen sizes, 
            so it works well on both mobile devices and larger screens.
        </p>
    </div>

</body>
</html>
