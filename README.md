<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Notes Arena - Organized Productivity</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;700&display=swap" rel="stylesheet">
</head>
<body>
    <main class="container">
        <h2 class="welcome-text">Welcome to <span class="dash"></span></h2>
        <h1 class="brand-name">Notes Arena</h1>
        <p class="tagline">
"Discover a curated collection of organized notes to enhance your learning. Access expertly crafted content for maximum clarity and efficiency. Revolutionize the way you study."</p>
        <a href="#" class="explore-btn" role="button">Continue to Explore........</a>
    </main>
</body>

<style>

/* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

/* Default background for desktop */
body {
    background: url('desktop-background.png') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Layout: Center-left for desktop, Center for mobile */
.container {
    max-width: 500px;
    padding: 40px;
    color: #222;
}

/* Desktop: Position at center-left */
@media (min-width: 769px) {
    .container {
        text-align: left;
        position: absolute;
        left: 15%;
        top: 50%;
        transform: translateY(-50%);
    }
}

/* Mobile: Align center */
@media (max-width: 768px) {
    body {
        background: url('mobile-background.png') no-repeat center center/cover;
    }
    .container {
        text-align: center;
        margin: auto;
    }
}

/* Tablet: Align center */
@media (min-width: 768px) and (max-width: 1024px) {
    body {
        background: url('tablet-background.png') no-repeat center center/cover;
    }

    .container {
        text-align: center;
        position: relative;
        left: 0;
        top: 50%;
        transform: translateY(-50%);
    }

    .welcome-text {
        font-size: 20px;
    }

    .brand-name {
        font-size: 42px;
    }

    .tagline {
        font-size: 14px;
    }

    .explore-btn {
        font-size: 17px;
        padding: 11px 22px;
    }
}

/* Welcome text */
.welcome-text {
    font-size: 22px;
    font-weight: 300;
    color: #666;
    text-transform: uppercase;
    letter-spacing: 1px;
    display: flex;
    align-items: center;
    gap: 10px;
}

/* Dash appears after "Welcome to" */
.dash {
    display: inline-block;
    width: 60px;
    height: 2px;
    background: #666;
}

/* Title */
.brand-name {
    font-size: 48px;
    font-weight: 700;
    margin-top: 5px;
}

/* Paragraph */
.tagline {
    margin-top: 10px;
    font-size: 14px; /* Reduced size */
    color: #444;
}

/* Button */
.explore-btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 24px;
    font-size: 18px;
    background-color: #4CAF50;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s ease, color 0.3s ease;
}

.explore-btn:hover {
    background-color: white;
    color: #4CAF50;
    border: 2px solid #4CAF50;
}

/* Responsive adjustments */
@media (max-width: 768px) {
    .welcome-text {
        font-size: 18px;
    }

    .brand-name {
        font-size: 36px;
    }

    .tagline {
        font-size: 14px; /* Smaller text for tagline */
    }

    .explore-btn {
        font-size: 16px;
        padding: 10px 20px;
    }
}

 </style>   
</html>

