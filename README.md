<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>AutoCare - Service & Sales</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        header {
            background: #111;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background: #e60000;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70') no-repeat center/cover;
            color: white;
            padding: 100px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 48px;
        }

        .container {
            padding: 30px;
            max-width: 1000px;
            margin: auto;
        }

        .section {
            margin-bottom: 40px;
        }

        .cards {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        .card {
            background: white;
            padding: 20px;
            flex: 1 1 250px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 15px;
        }

        button {
            background: #e60000;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 4px;
        }

        button:hover {
            background: #cc0000;
        }
    </style>
</head>
<body>

<header>
    <h1>AutoCare</h1>
    <p>Your Trusted Automobile Service & Sales Center</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#sales">Vehicle Sales</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
    <h1>Quality Cars & Reliable Service</h1>
    <p>Sales | Repairs | Maintenance</p>
    <button>Book a Service</button>
</section>

<div class="container">

    <section class="section" id="services">
        <h2>Our Services</h2>
        <div class="cards">
            <div class="card">
                <h3>Oil Change</h3>
                <p>Quick and affordable engine oil replacement.</p>
            </div>
            <div class="card">
                <h3>Brake Service</h3>
                <p>Complete brake inspection and repair.</p>
            </div>
            <div class="card">
                <h3>Engine Repair</h3>
                <p>Professional engine diagnostics and repair.</p>
            </div>
        </div>
    </section>

    <section class="section" id="sales">
        <h2>Vehicles for Sale</h2>
        <div class="cards">
            <div class="card">
                <h3>Sedan 2022</h3>
                <p>Comfortable family car with great mileage.</p>
                <button>View Details</button>
            </div>
            <div class="card">
                <h3>SUV 2023</h3>
                <p>Spacious SUV perfect for long trips.</p>
                <button>View Details</button>
            </div>
            <div class="card">
                <h3>Sports Car</h3>
                <p>High performance with stylish design.</p>
                <button>View Details</button>
            </div>
        </div>
    </section>

    <section class="section" id="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> Main Road, Your City</p>
        <p><strong>Phone:</strong> +91 98765 43210</p>
        <p><strong>Email:</strong> info@autocare.com</p>
    </section>

</div>

<footer>
    <p>© 2026 AutoCare. All Rights Reserved.</p>
</footer>

</body>
</html>
