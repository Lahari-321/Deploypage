<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #4CAF50;
            color: white;
            border-radius: 8px 8px 0 0;
        }

        header img {
            width: 100%;
            height: auto;
            border-radius: 8px 8px 0 0;
        }

        h1 {
            margin: 10px 0 0;
        }

        h2 {
            margin-top: 20px;
            color: #333;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            padding: 10px 0;
            border-bottom: 1px solid #ddd;
        }

        .cta-button {
            display: inline-block;
            margin: 20px 0;
            padding: 10px 20px;
            background: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .cta-button:hover {
            background: #45a049;
        }

        footer {
            text-align: center;
            margin-top: 30px;
        }

        form {
            margin-top: 10px;
        }

        input[type="email"] {
            padding: 10px;
            width: 70%;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        button {
            padding: 10px 15px;
            background: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background: #45a049;
        }

        .features {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }

        .feature {
            text-align: center;
            flex: 1;
            padding: 10px;
            margin: 0 10px;
        }

        .feature img {
            max-width: 80%;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img src="https://source.unsplash.com/1600x400/?business" alt="Business Image">
            <h1>Welcome to Our Service</h1>
            <p>Your one-stop solution for all your needs.</p>
        </header>
        <main>
            <h2>Why Choose Us?</h2>
            <div class="features">
                <div class="feature">
                    <img src="https://source.unsplash.com/300x200/?quality" alt="Quality">
                    <h3>High Quality</h3>
                    <p>We deliver high-quality services that meet your needs.</p>
                </div>
                <div class="feature">
                    <img src="https://source.unsplash.com/300x200/?affordable" alt="Affordable Prices">
                    <h3>Affordable Prices</h3>
                    <p>Get the best value for your money with our services.</p>
                </div>
                <div class="feature">
                    <img src="https://source.unsplash.com/300x200/?support" alt="Customer Support">
                    <h3>24/7 Customer Support</h3>
                    <p>Our support team is here to help you anytime.</p>
                </div>
            </div>
            <a href="#signup" class="cta-button">Get Started Now</a>
        </main>
        <footer>
            <h3>Sign Up for Updates</h3>
            <form id="signup" action="#" method="post">
                <input type="email" placeholder="Enter your email" required>
                <button type="submit">Subscribe</button>
            </form>
        </footer>
    </div>
</body>
</html>

            
