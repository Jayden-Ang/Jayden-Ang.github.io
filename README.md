<<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jayden's Soy Milk Stand</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        header {
            background-color: #ffcc66;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            width: 100%;
        }
        .hero {
            background-image: url('images/soy_milk_banner_16_9.jpg'); /* Ensure image is in /images/ */
            background-size: cover;
            background-position: center;
            color: white;
            width: 100%;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 32px;
            font-weight: bold;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            width: 90%;
            max-width: 1200px;
        }
        .section {
            flex: 1;
            padding: 40px;
            background-color: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            min-width: 300px;
        }
        footer {
            background-color: #ffcc66;
            padding: 10px;
            margin-top: 20px;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>Jayden's Soy Milk Stand</header>
    <div class="hero">Delicious, Fresh, and Nutritious Soy Milk!</div>
    <div class="container">
        <div class="section">
            <h2>About Us</h2>
            <p>We provide freshly made soy milk with natural ingredients, ensuring a healthy and tasty experience.</p>
        </div>
        <div class="section">
            <h2>Our Products</h2>
            <p>Original, Vanilla, Chocolate, and more!</p>
        </div>
        <div class="section">
            <h2>Customer Testimonials</h2>
            <p>"Best soy milk in town! So fresh and tasty!" - A Happy Customer</p>
        </div>
    </div>
    <footer>Contact us at: jayden@soymilk.com</footer>
</body>
</html>

