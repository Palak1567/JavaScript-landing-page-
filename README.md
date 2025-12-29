<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Palak Thakur Landing Page</title>
<style>
* { margin:0; padding:0; box-sizing:border-box; }
body { font-family: Arial, sans-serif; line-height:1.6; background:#f0f2f5; color:#333; }

/* Navbar */
nav { background:#4CAF50; color:white; padding:15px 20px; display:flex; justify-content:space-between; align-items:center; }
nav h1 { font-size:24px; }
nav ul { list-style:none; display:flex; }
nav ul li { margin-left:20px; }
nav ul li a { color:white; text-decoration:none; font-weight:bold; transition:0.3s; }
nav ul li a:hover { color:#ddd; }

/* Hero */
.hero { background:#4CAF50; height:60vh; display:flex; justify-content:center; align-items:center; text-align:center; color:white; padding:0 20px; }
.hero h2 { font-size:36px; margin-bottom:15px; }
.hero p { font-size:18px; margin-bottom:20px; }
.hero button { padding:12px 25px; font-size:16px; border:none; border-radius:5px; background:#ff5722; color:white; cursor:pointer; transition:0.3s; }
.hero button:hover { background:#e64a19; }

/* Features */
.features { display:flex; justify-content:space-around; flex-wrap:wrap; padding:50px 20px; background:#fff; }
.feature { background:white; border-radius:10px; padding:20px; margin:10px; width:250px; box-shadow:0 4px 10px rgba(0,0,0,0.2); text-align:center; transition:0.3s; }
.feature:hover { transform:translateY(-5px); box-shadow:0 6px 12px rgba(0,0,0,0.3); }
.feature h3 { margin-bottom:15px; color:#4CAF50; }
.feature p { color:#555; }

/* Footer */
footer { text-align:center; padding:20px; background:#333; color:white; }

@media(max-width:768px){
    .features { flex-direction:column; align-items:center; }
}
</style>
</head>
<body>

<!-- Navbar -->
<nav>
    <h1>Palak Thakur</h1>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- Hero Section -->
<section class="hero" id="home">
    <div>
        <h2>Welcome to My Landing Page</h2>
        <p>Hello! I'm <strong>Palak Thakur</strong> — a passionate learner and web enthusiast.</p>
        <button>Get Started</button>
    </div>
</section>

<!-- Features Section -->
<section class="features" id="features">
    <div class="feature">
        <h3>Responsive Design</h3>
        <p>Looks great on any device, mobile, tablet, or desktop.</p>
    </div>
    <div class="feature">
        <h3>Easy to Use</h3>
        <p>Simple structure makes it easy to customize and deploy.</p>
    </div>
    <div class="feature">
        <h3>Modern Design</h3>
        <p>Clean and professional design that impresses visitors.</p>
    </div>
</section>

<!-- Footer -->
<footer id="contact">
    &copy; 2025 Palak Thakur. All rights reserved.
</footer>

</body>
</html>