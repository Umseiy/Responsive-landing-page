<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SmartProduct Landing Page</title>
    <style>
        /* Reset and General Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        a {
            text-decoration: none;
            color: inherit;
        }

        /* Hero Section */
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }
        header h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        header p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        .cta-button {
            background-color: white;
            color: #4CAF50;
            padding: 12px 25px;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
            display: inline-block;
        }
        .cta-button:hover {
            background-color: #45a049;
            color: white;
        }

        /* Features Section */
        section.features-section {
            padding: 60px 20px;
            background-color: white;
        }
        .features-section h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        .features-section p.section-description {
            text-align: center;
            margin-bottom: 40px;
            font-size: 1.1rem;
        }
        .features-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .feature {
            flex: 1 1 300px;
            background-color: #e0f7e0;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
        .feature img {
            width: 80px;
            margin-bottom: 15px;
            animation: bounce 2s infinite;
        }
        .feature h3 {
            margin-bottom: 10px;
            font-size: 1.5rem;
        }
        .feature p {
            font-size: 1rem;
        }

        /* Animation */
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

        /* Footer Section */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 30px 15px;
        }
        footer p, footer a {
            margin: 5px 0;
            color: #4CAF50;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            .features-container {
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
        <p>SmartProduct simplifies your life with innovative and user-friendly solutions.</p>
        <a href="#" class="cta-button">Sign Up Now</a>
    </header>

    <!-- Features Section -->
    <section class="features-section">
        <h2>Our Features</h2>
        <p class="section-description">Explore the key features that make SmartProduct the best choice for you.</p>

        <div class="features-container">
            <div class="feature">
                <img src="https://cdn-icons-png.flaticon.com/512/847/847969.png" alt="Easy to Use Icon">
                <h3>Easy to Use</h3>
                <p>Our product is designed to be simple, intuitive, and user-friendly for everyone.</p>
            </div>

            <div class="feature">
                <img src="https://cdn-icons-png.flaticon.com/512/3064/3064197.png" alt="Highly Secure Icon">
                <h3>Highly Secure</h3>
                <p>We ensure your privacy and security with top-notch, advanced protection measures.</p>
            </div>

            <div class="feature">
                <img src="https://cdn-icons-png.flaticon.com/512/483/483947.png" alt="24/7 Support Icon">
                <h3>24/7 Support</h3>
                <p>Our dedicated support team is always available to assist you, day or night.</p>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>Contact: 08169483837</p>
        <p>Address: Gaida Ring-Road</p>
        <p>Copywriter: Hauwa Salihu Ahmad</p>
        <p>Email: <a href="mailto:email@smartproduct@yahoo.com">email@smartproduct@yahoo.com</a></p>
        <p>&copy; 2025 SmartProduct. All rights reserved.</p>
    </footer>

</body>
</html
