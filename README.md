<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SmartProduct Landing Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        header a {
            background-color: white;
            color: #4CAF50;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        header a:hover {
            background-color: #45a049;
            color: white;
        }
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 40px 20px;
            background-color: white;
        }
        .feature {
            flex: 1 1 300px;
            margin: 20px;
            padding: 20px;
            background-color: #e0f7e0;
            border-radius: 10px;
            text-align: center;
        }
        .feature img {
            width: 80px;
            margin-bottom: 15px;
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-20px);
            }
            60% {
                transform: translateY(-10px);
            }
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 10px;
            margin-top: 30px;
        }
        footer a {
            color: #4CAF50;
            margin: 0 10px;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            .features {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <header>
        <h1>Welcome to SmartProduct</h1>
        <p>Discover the best solutions to improve your life. Smart, efficient, and tailored just for you.</p>
        <a href="#">Sign Up Now</a>
    </header>

    <!-- Features Section -->
    <section class="features">
        <div class="feature">
            <img src="https://cdn-icons-png.flaticon.com/512/847/847969.png" alt="Easy to Use">
            <h3>Easy to Use</h3>
            <p>Our product is designed to be user-friendly and intuitive for everyone.</p>
        </div>
        <div class="feature">
            <img src="https://cdn-icons-png.flaticon.com/512/3064/3064197.png" alt="Highly Secure">
            <h3>Highly Secure</h3>
            <p>We prioritize your privacy and security with top-notch protection.</p>
        </div>
        <div class="feature">
            <img src="https://cdn-icons-png.flaticon.com/512/483/483947.png" alt="24/7 Support">
            <h3>24/7 Support</h3>
            <p>Our dedicated team is always available to assist you anytime, anywhere.</p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>Contact us: <a href="mailto:email@smartproduct@yahoo.com">email@smartproduct@yahoo.com</a></p>
        <p>
            <a href="#">Facebook</a> | 
            <a href="#">Twitter</a> | 
            <a href="#">Instagram</a>
        </p>
        <p>&copy; 2025 SmartProduct. All rights reserved.</p>
    </footer>

</body>
</html>
