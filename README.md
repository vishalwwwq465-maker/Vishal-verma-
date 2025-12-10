<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DUSIAN Education</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }

        /* Navbar */
        nav {
            background: #1a1a1a;
            color: white;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
        }

        .nav-links a {
            margin-left: 20px;
            text-decoration: none;
            color: white;
            font-size: 16px;
        }

        .nav-links a:hover {
            color: #ffcc00;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(to right, #2c3e50, #4ca1af);
            color: white;
            padding: 80px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 45px;
        }

        .hero p {
            font-size: 18px;
            margin-top: 10px;
        }

        /* Features section */
        .features {
            padding: 40px 20px;
            text-align: center;
        }

        .card {
            background: white;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            display: inline-block;
            width: 270px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

    </style>
</head>

<body>

    <!-- Navbar -->
    <nav>
        <div class="logo">📘 DUSIAN</div>
        <div class="nav-links">
            <a href="#">Home</a>
            <a href="#">Courses</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero">
        <h1>Welcome to DUSIAN Education</h1>
        <p>Modern learning platform for students</p>
    </div>

    <!-- Features -->
    <div class="features">
        <div class="card">
            <h3>📚 Online Courses</h3>
            <p>Best educational courses for every student.</p>
        </div>

        <div class="card">
            <h3>🎯 Target Learning</h3>
            <p>Focus on real knowledge and skills.</p>
        </div>

        <div class="card">
            <h3>💡 Smart Study</h3>
            <p>Learn with modern digital tools.</p>
        </div>
    </div>

</body>
</html>