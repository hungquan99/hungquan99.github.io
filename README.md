
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CER₃</title>
    <link rel="icon" href="https://cer3.lol/logo.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Sora:wght@100..800&family=Source+Code+Pro:ital,wght@0,300;1,300&display=swap" rel="stylesheet">
          <title>cer3.lol</title>
          <meta property="og:title" content="cer3.lol">
          <meta name="description" content="Enhance your fisching 
experience with CER3t">
          <meta property="og:description" content="Enhance your fisching 
experience with CER3">
          <meta name="theme-color" content="#b7cfff">
          <meta property="og:image" content="https://cer3.lol/logo.png">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Sora', sans-serif;
            color: #FFFFFF;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
            background: #05071a;
            overflow-y: scroll;
        }

        nav {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            background-color: rgba(18, 18, 18, 0);
            backdrop-filter: blur(10px);
        }

        .logo {
            height: 50px;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            text-decoration: none;
            color: #FFFFFF;
            font-weight: 500;
            opacity: 0.8;
            transition: opacity 0.3s;
        }

        .nav-links a:hover {
            opacity: 1;
        }

        /* Header Section */
        header {
            text-align: center;
            max-width: 700px;
            margin-top: 300px;;
        }

        h1 {
            font-size: 65px;
            font-weight: 700;
            color: #FFFFFF;
            letter-spacing: 2px;
            line-height: 1;
            max-width: 1000px;
            margin: 0;
        }

        .highlight {
            color: #b7cfff;
            font-weight: 800;
            text-shadow: 0 0 10px #b7cfff;
        }

        p {
            font-size: 1.1rem;
            color: #AAAAAA;
            margin-top: 20px;
            line-height: 1.5;
        }

        .cta-button {
            margin-top: 20px;
            background-color: #b7cfff;
            color: #FFFFFF;
            padding: 12px 24px;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.3s ease, border 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 0 10px #b7cfff;
        }

        .cta-button:hover {
            background-color: #b7cfff;
            box-shadow: 0 0 15px #b7cfff;
            transform: scale(1.08);
        }

        .compatibility {
            font-size: 0.9rem;
            color: #888888;
            margin-top: 10px;
            font-family: 'Source Code Pro', monospace;
        }

        html, body {
            height: 100%;
        }

        .features {
            padding: 60px 20px;
            text-align: center;
            background-color: #05071a;
            margin-top: 250px;
            width: 100%;
        }

        .features-intro h2 {
            font-size: 2.5em;
            margin-bottom: 10px;
            color: #FFFFFF;
        }

        .features-intro p {
            color: #AAAAAA;
            font-size: 1.1em;
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.5;
        }

        .feature-cards {
            display: flex;
            gap: 20px;
            justify-content: center;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .feature-card {
            background-color: #13162B;
            padding: 20px;
            border-radius: 15px;
            width: 250px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            border: 1px solid #b7cfff;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, border 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 0 15px rgba(183, 207, 255, 0.6); 
        }

        .feature-card:hover {
            transform: scale(1.08);
            border: 1px solid #b7cfff;
            box-shadow: 0 0 15px rgba(183, 207, 255, 0.8);
        }

        .feature-icon {
            width: 50px;
            height: 50px;
            background-color: #1f2238;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 15px;
            font-size: 1.5em;
            color: #b7cfff;
        }

        .feature-card h3 {
            font-size: 1.2em;
            color: #FFFFFF;
            margin: 10px 0;
        }

        .feature-card p {
            font-size: 0.9em;
            color: #AAAAAA;
            line-height: 1.5;
        }

        .features-video {
            flex: 1;
            max-width: 50%;
            margin-right: 20px;
            position: relative;
            display: block;
        }

        .features-video iframe {
            width: 100%;
            height: 100%;
            border: none;
        }

        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
        }


        .stunning-features {
            text-align: center;
            margin-top: 60px;
        }

        .stunning-features h2 {
            font-size: 2.5em;
            margin-bottom: 10px;
            color: #FFFFFF;
        }

        .stunning-features p {
            color: #AAAAAA;
            font-size: 1.2em;
            max-width: 700px;
            margin: 0 auto;
        }

        .prices-intro {
            font-size: 2.5em;
            margin-bottom: 10px;
            color: #FFFFFF;
            margin-top: 250px;
            text-align: center;
        }

        .price-cards {
            display: flex;
            gap: 20px;
            justify-content: center;
            margin-top: 30px;
            flex-wrap: wrap;
            margin-bottom: 50px;
        }


        .monthly {
            background-color: #13162B;
            padding: 20px;
            border-radius: 15px;
            width: 250px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            border: 1px solid #b7cfff;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, border 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 0 15px rgba(183, 207, 255, 0.6);
        }

        .monthly:hover {
            transform: scale(1.04);
            border: 1px solid #b7cfff;
            box-shadow: 0 0 15px rgba(183, 207, 255, 0.8);
        }

        .new-text {
            display: inline-block;
            padding: 5px 10px;
            background-color: #fa3333;
            color: white;
            font-size: 14px;
            border-radius: 12px;
            font-family: Arial, sans-serif;
        }
        .discount {
            display: inline-block;
            padding: 5px 10px;
            background-color: #339afa;
            color: white;
            font-size: 14px;
            border-radius: 12px;
            font-family: Arial, sans-serif;
        }
        
        .lifetime {
            background-color: #13162B;
            padding: 20px;
            border-radius: 15px;
            width: 250px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            border: 1px solid #b7cfff;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, border 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 0 15px rgba(183, 207, 255, 0.6);
        }

        .lifetime:hover {
            transform: scale(1.04);
            border: 1px solid #b7cfff;
            box-shadow: 0 0 15px rgba(183, 207, 255, 0.8);
        }
        .price-container {
    margin-top: 10px;
    display: flex;
    align-items: center;
}

.old-price {
    text-decoration: line-through;
    color: grey;
    font-size: 23px;
    margin-right: 10px;
}

.new-price {
    color: white;
    padding: 5px 10px;
    font-size: 25px;
    font-weight: bold;
}
.divider {
    margin-top: 10px;
    margin-bottom: 10px;
    border: none;
    border-top: 2px solid #ddddddc2;
    width: 100%;
}

.exclusive {
    display: inline-block;
            padding: 5px 10px;
            background-color: #6915f1; 
            color: white; 
            font-size: 14px; 
            border-radius: 12px; 
            font-family: Arial, sans-serif;
}
.features-list {
    list-style-type: none;
    padding-left: 0;
    margin-top: 10px;
}

.features-list li {
    display: flex;
    align-items: center; 
    margin-bottom: 8px;
    font-size: 14px;
    color: #c2c2c2;
}

.features-list .yes {
    background-image: url('check.svg'); 
    background-repeat: no-repeat;
    background-position: left center;
    padding-left: 30px; 
    margin-left: 10px; 
}

.features-list .no {
    background-image: url('no.webp'); 
    background-repeat: no-repeat;
    background-position: left center;
    padding-left: 30px;
    margin-left: 10px; 
}

.btn {
            margin-top: 20px;
            background-color: #b7cfff;
            color: #FFFFFF;
            padding: 12px 24px;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.3s ease, border 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 0 10px #b7cfff;
            align-items: center;
        }

        .btn:hover {
            background-color: #b7cfff;
            box-shadow: 0 0 15px #b7cfff;
            transform: scale(1.08);
        }


        .com {
            margin-top: 270px;
            text-align: center;
        }
        .com p{
            text-align: center;
        }

        .reviews {
            text-align: center;
        }
        .reviews p{
            text-align: center;
        }
        .review-cards {
            display: flex;
            gap: 20px;
            justify-content: center;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .review-card {
            background-color: #13162B;
            padding: 20px;
            border-radius: 15px;
            width: 250px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            border: 1px solid #b7cfff; 
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2); 
            transition: transform 0.3s ease, border 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 0 15px rgba(183, 207, 255, 0.6); 
        }

        .review-card:hover {
            transform: scale(1.08); 
            border: 1px solid #b7cfff; 
            box-shadow: 0 0 15px rgba(183, 207, 255, 0.8); 
        }

        .review-icon {
            width: 50px;
            height: 50px;
            background-color: #1f2238;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 15px;
            font-size: 1.5em;
            color: #b7cfff;
        }

        .review-card h3 {
            font-size: 1.2em;
            color: #FFFFFF;
            margin: 10px 0;
        }

        .review-card p {
            font-size: 0.9em;
            color: #AAAAAA;
            line-height: 1.5;
        }

        .reviews1{
            margin-top: 150px;
        }

        .dsc {
            margin-top: 20px;
            background-color: #b7cfff;
            color: #FFFFFF;
            padding: 24px 48px;
            border: none;
            border-radius: 8px;
            font-size: 26px;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.3s ease, border 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 0 10px #b7cfff;
            align-items: center;
        }

        .dsc:hover {
            background-color: #b7cfff;
            box-shadow: 0 0 15px #b7cfff;
            transform: scale(1.08);
        }
.footer {
    color: #ccc;
    padding: 20px;
    text-align: center;
    font-family: Arial, sans-serif;
    margin-top: 250px;
}

.footer-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 20px;
}

.brand {
    display: flex;
    align-items: center;
    gap: 8px;
}

.logo {
    width: 24px;
    height: 24px;
}

.brand-name {
    font-size: 1.2em;
    color: #ccccff;
    font-weight: bold;
}

.tagline {
    margin-top: 8px;
    font-size: 0.9em;
    max-width: 600px;
    line-height: 1.5;
    color: #888;
}

.nav-links {
    display: flex;
    gap: 20px;
    margin-top: 10px;
}

.link {
    color: #888;
    text-decoration: none;
    font-size: 0.9em;
}

.link:hover {
    color: #ccccff;
}

.footer-bottom {
    border-top: 1px solid #333;
    padding-top: 15px;
    font-size: 12px;
    color: #666;
}

    </style>
</head>
<body>
    <nav>
        <img src="logo.png" class="logo" width="100px" alt="Logo">
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#prices">Pricing</a></li>
            <li><a href="#com">Community</a></li>
            <li><a href="#reviews">Reviews</a></li>
        </ul>
    </nav>

    <header> 
        <h1>The most <span class="highlight">powerful</span> script for Fisch.</h1>
        <p>Experience a new level of gameplay, completely undetectable ghost features, and stunning UI design.</p>
        <button class="cta-button" onclick="scrollToFeatures()">Get Started now</button>

        <div class="compatibility">Works on all executors</div>
    </header>

    <section class="features" id="features">
        <div class="features-intro">
            <h2>The features you'll love.</h2>
            <p>These are some of our best features. We make sure our client is the smoothest, fastest and safest.</p>
        </div>
        <div class="feature-cards">
            <div class="feature-card">
                <div class="feature-icon">⚙️</div>
                <h3>Good Team</h3>
                <hr class="divider">
                <p>Our dedicated team ensures fast updates and top-tier support. We are always here to help you whenever you need it.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🌟</div>
                <h3>Exclusive Features</h3>
                <hr class="divider">
                <p>Our exclusive features are unmatched. From advanced customizations to premium tools, you'll get a unique experience.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">👻</div>
                <h3>Ghost Cheat</h3>
                <hr class="divider">
                <p>With our ghostly undetectable features, you can enjoy the ultimate gameplay without ever being detected.</p>
            </div>
        </div>


        <div class="stunning-features">
            <h2>Our stunning features.</h2>
            <p>We offer cutting-edge technology that ensures top-notch performance and security, with new features released regularly.</p>
        </div>


        <iframe width="560" height="315" src="https://www.youtube.com/embed/YQQTMUcv6O0?si=dkS-7GYxgMjnrQjt&autoplay=1&controls=0&mute=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; margin-top=10px; muted; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

        
    </section>


    <section class="prices" id="prices">
        <div class="prices-intro">
            <h2>Prices. </h2>
            <p>Designed to Simplify Your Experience and Maximize the Benefits of CER3's Innovative Features.</p>
        </div>
        <div class="price-cards">
        <div class="monthly">
            <h3>Free <span class="exclusive">★ Exclusive</span> </h3> 
            <p>Finish key steps to get a free 12h key.</p>
            <hr class="divider">
            <div class="price-container">
                <span class="new-price">Free</span>
                <span class="old-price">2.5€</span>
            </div>
            <ul class="features-list">
                <li class="yes">All the features</li>
                <li class="yes">24/7 support</li>
                <li class="yes">Fast updates</li>
                <li class="no">Lifetime</li>
            </ul>
            <button class="btn" onclick=" window.open('https://cer3.lol/keysystem','_blank')"> Get started</button>
        </button>
        </div>
        <div class="lifetime">
            <h3>Lifetime <span class="new-text">New</span> <span class="discount">-80%</span> </h3> 
            <p>Get full access forever to the best fisch script.</p>
            <hr class="divider">
            <div class="price-container">
                <span class="new-price">4.99€</span>
                <span class="old-price">15.99€</span>
            </div>
            <ul class="features-list">
                <li class="yes">All the features</li>
                <li class="yes">24/7 support</li>
                <li class="yes">Fast updates</li>
                <li class="yes">Lifetime</li>
            </ul>
            <button class="btn" onclick=" window.open('https://cer3.sellsn.io/product/4aed4322-2d97-4c86-919b-2f313e02ed6d','_blank')"> Get started</button>
              </button>
        </div>
    </div>
    </section>
    <section class="com" id="com">
        <h1>Community.</h1>
        <p>Join the best fisching community</p>
        <button class="dsc" onclick=" window.open('https://discord.gg/cer3','_blank')">Join Discord</button>
    </button>
    </section>
    <section class="reviews">
    <h1 class="reviews1" id="reviews">Reviews.</h1>
    <p>Here is some reviews (100% real)</p>
    <div class="review-cards">
        <div class="review-card">
            <div class="review-icon">👤</div>
            <h3>Discord User</h3>
            <hr class="divider">
            <p>Really good script i leik</p>
        </div>
        <div class="review-card">
            <div class="review-icon">👤</div>
            <h3>Fisch Owner</h3>
            <hr class="divider">
            <p>CER3 best fisch script i recommend it</p>
        </div>
        <div class="review-card">
            <div class="review-icon">👤</div>
            <h3>oto</h3>
            <hr class="divider">
            <p>Use CER3 its the best fisch free script</p>
        </div>
    </div>
    </section>


    <section class="credit">
        <footer class="footer">
            <div class="footer-content">
                <div class="brand">
                    <img src="logo.png" alt="Logo" class="logo">
                    <span class="brand-name">cer3</span>
                </div>
                <p class="tagline">
                    Experience a new level of gameplay, completely undetectable ghost features, and stunning UI design.
                </p>
                <div class="nav-links">
                    <a href="https://discord.gg/cer3" class="link">Discord Server</a>
                    <a href="#prices" class="link">Pricing</a>
                    <a href="#reviews" class="link">Reviews</a>
                </div>
            </div>
            <div class="footer-bottom">
                <p>Copyright © 2024 CER3<br>All Rights Reserved</p>
            </div>
        </footer>


    </section>
    <script>
        function scrollToFeatures() {
            document.getElementById("features").scrollIntoView({
                behavior: "smooth"
            });
        }
    </script>
</body>
</html>
