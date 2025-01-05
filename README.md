<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RF Calculators</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: #333;
            background-color: #f4f6f8;
            line-height: 1.6;
        }

        header {
            background-color: #003366;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
            font-weight: 300;
        }

        nav {
            background-color: #00509e;
            display: flex;
            justify-content: center;
            padding: 0.5rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1rem;
            font-weight: bold;
            text-transform: uppercase;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
        }

        .calculator-section {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            justify-content: center;
        }

        .card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
            padding: 1rem;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .card h3 {
            font-size: 1.5rem;
            color: #00509e;
            margin-bottom: 1rem;
        }

        .card button {
            background-color: #003366;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            font-size: 1rem;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.2s ease;
        }

        .card button:hover {
            background-color: #00509e;
        }

        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        footer p {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>RF Calculators</h1>
        <p>Your one-stop solution for RF design calculations and resources</p>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Calculators</a>
        <a href="#">Resources</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
    <div class="container">
        <section class="calculator-section">
            <div class="card">
                <h3>Impedance Calculator</h3>
                <p>Calculate RF impedance with ease.</p>
                <button onclick="alert('Impedance Calculator Coming Soon!')">Try Now</button>
            </div>
            <div class="card">
                <h3>Power Conversion</h3>
                <p>Convert dBm to Watts and more.</p>
                <button onclick="alert('Power Conversion Tool Coming Soon!')">Try Now</button>
            </div>
            <div class="card">
                <h3>VSWR Calculator</h3>
                <p>Determine Voltage Standing Wave Ratio.</p>
                <button onclick="alert('VSWR Calculator Coming Soon!')">Try Now</button>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 RF Calculators. All rights reserved. | Designed for RF enthusiasts</p>
    </footer>
</body>
</html>

