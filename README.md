<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GlowFit - Smart Fitness Band</title>
    <style>
        /* Reset default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            padding: 20px 0;
        }

        header {
            background-color: #222;
            color: #fff;
            padding: 20px 0;
        }

        header .logo {
            font-size: 24px;
            font-weight: bold;
            text-align: center;
        }

        nav {
            display: flex;
            gap: 20px;
            justify-content: center;
            margin-top: 10px;
            flex-wrap: wrap;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:focus, nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: linear-gradient(to right, #00c6ff, #0072ff);
            color: #fff;
            padding: 80px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
        }

        .btn {
            background-color: #fff;
            color: #0072ff;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
            display: inline-block;
        }

        .btn:hover, .btn:focus {
            background-color: #f1f1f1;
        }

        .features {
            background-color: #fff;
            padding: 60px 20px;
            text-align: center;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .feature-card {
            background-color: #f0f0f0;
            padding: 20px;
            border-radius: 10px;
        }

        .pricing {
            background-color: #e0f7fa;
            padding: 60px 20px;
            text-align: center;
        }

        .price-card {
            background-color: #fff;
            display: inline-block;
            padding: 30px;
            border-radius: 10px;
        }

        footer {
            background-color: #222;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 28px;
            }

            nav {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>

    <header role="banner">
        <div class="container">
            <h1 class="logo">GlowFit</h1>
            <nav aria-label="Main Navigation">
                <a href="#">Home</a>
                <a href="#features">Features</a>
                <a href="#pricing">Pricing</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero" aria-label="Product Introduction">
            <div class="container">
                <h1>Track Your Fitness. Transform Your Life.</h1>
                <p>The smart band that keeps you motivated and on track.</p>
                <a href="#pricing" class="btn" role="button">Get Started</a>
            </div>
        </section>

        <section id="features" class="features" aria-label="Product Features">
            <div class="container">
                <h2>Features</h2>
                <div class="feature-grid">
                    <div class="feature-card">
                        <h3>Heart Rate Monitor</h3>
                        <p>Track your heart rate in real-time for optimal workouts.</p>
                    </div>
                    <div class="feature-card">
                        <h3>Sleep Tracking</h3>
                        <p>Monitor your sleep patterns and improve your rest.</p>
                    </div>
                    <div class="feature-card">
                        <h3>Water Resistant</h3>
                        <p>Wear it anywhere – rain, swim, or sweat!</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="pricing" class="pricing" aria-label="Product Pricing">
            <div class="container">
                <h2>Pricing</h2>
                <div class="price-card">
                    <h3>Only $49.99</h3>
                    <p>Includes all features, free shipping, and a 1-year warranty.</p>
                    <a href="#contact" class="btn" role="button">Order Now</a>
                </div>
            </div>
        </section>
    </main>

    <footer id="contact" role="contentinfo">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: <a href="mailto:support@glowfit.com" style="color: #fff;">support@glowfit.com</a></p>
            <p>Phone: <a href="tel:+1234567890" style="color: #fff;">+123-456-7890</a></p>
            <p>&copy; 2025 GlowFit. All rights reserved.</p>
        </div>
    </footer>

</body>
</html
