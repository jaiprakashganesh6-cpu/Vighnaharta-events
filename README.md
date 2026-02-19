# Vighnaharta-event
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vighnaharta Events | Devotional Event Management</title>
    <style>
        /* --- CSS STYLES --- */
        :root {
            --primary-color: #FF9933; /* Saffron */
            --secondary-color: #800000; /* Deep Maroon/Red */
            --accent-color: #FFD700; /* Gold */
            --text-light: #FFF5E1; /* Cream */
            --text-dark: #333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #FFFAF0; /* Floral White */
            color: var(--text-dark);
            line-height: 1.6;
        }

        /* Header */
        header {
            background-color: var(--secondary-color);
            color: var(--text-light);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--accent-color);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            padding: 0;
        }

        nav a {
            color: var(--text-light);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--accent-color);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(128, 0, 0, 0.7), rgba(128, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1605218457293-84b2e8477610?q=80&w=1920&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            color: var(--accent-color);
        }

        .hero-content p {
            font-size: 1.5rem;
            margin-bottom: 2rem;
            font-style: italic;
        }

        .btn {
            background-color: var(--primary-color);
            color: white;
            padding: 12px 30px;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            text-decoration: none;
            transition: background 0.3s;
            font-weight: bold;
        }

        .btn:hover {
            background-color: #e68a00;
        }

        /* Services Section */
        .section {
            padding: 4rem 0;
        }

        .section-title {
            text-align: center;
            color: var(--secondary-color);
            font-size: 2.5rem;
            margin-bottom: 3rem;
            position: relative;
        }
        
        .section-title::after {
            content: '🕉'; /* Om Symbol */
            display: block;
            font-size: 1.5rem;
            margin-top: 10px;
            color: var(--primary-color);
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            border-top: 4px solid var(--primary-color);
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-icon {
            font-size: 3rem;
            color: var(--secondary-color);
            margin-bottom: 1rem;
        }

        /* About Section */
        .about {
            background-color: #FFF5E1; /* Light Cream */
        }

        /* Contact Section */
        .contact-bar {
            background-color: var(--secondary-color);
            color: white;
            padding: 3rem 0;
            text-align: center;
        }

        .contact-numbers {
            font-size: 1.5rem;
            font-weight: bold;
            margin: 1.5rem 0;
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
        }

        .phone-link {
            color: var(--accent-color);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: #ccc;
            text-align: center;
            padding: 1rem 0;
            font-size: 0.9rem;
        }

        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            .hero-content h1 { font-size: 2.5rem; }
            .container { flex-direction: column; gap: 15px; }
            .contact-numbers { flex-direction: column; gap: 10px; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <div class="logo">🕉 Vighnaharta Events</div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Devotion in Every Detail</h1>
            <p>"We undertake orders for all occasions"</p>
            <a href="#contact" class="btn">Book Now</a>
        </div>
    </section>

    <section id="services" class="section container">
        <h2 class="section-title">Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <div class="service-icon">🕯️</div>
                <h3>Jagrata & Chowki</h3>
                <p>Complete devotional setups including singers, orchestra, and sound systems for a divine experience.</p>
            </div>
            <div class="service-card">
                <div class="service-icon">🌺</div>
                <h3>Floral Decoration</h3>
                <p>Beautiful fresh flower decorations for Mandaps, stages, and home entrances.</p>
            </div>
            <div class="service-card">
                <div class="service-icon">🐘</div>
                <h3>Ganesh Utsav</h3>
                <p>Grand Pandal management, idol decoration, and procession planning.</p>
            </div>
            <div class="service-card">
                <div class="service-icon">🔥</div>
                <h3>Pooja & Havan</h3>
                <p>Arrangement of all Samagri and experienced Pandits for home rituals.</p>
            </div>
        </div>
    </section>

    <section class="section about">
        <div class="container" style="text-align: center; max-width: 800px;">
            <h2 class="section-title">About Us</h2>
            <p style="font-size: 1.1rem;">
                At <strong>Vighnaharta Events</strong>, we believe that every religious occasion is a blessing. 
                Based in Anekal, Karnataka, we specialize in organizing traditional Hindu events with purity and perfection.
                From small home ceremonies to large community gatherings, we handle everything so you can focus on your prayers.
            </p>
        </div>
    </section>

    <section id="contact" class="contact-bar">
        <div class="container">
            <h2 style="margin:0; color:white;">Plan Your Event With Us</h2>
            <p>Call us today for bookings and inquiries</p>
            
            <div class="contact-numbers">
                <a href="tel:8073366743" class="phone-link">📞 80733 66743</a>
                <a href="tel:9886193882" class="phone-link">📞 98861 93882</a>
            </div>

            <a href="https://wa.me/918073366743" class="btn" style="background-color: #25D366;">Chat on WhatsApp</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Vighnaharta Events. All rights reserved.</p>
    </footer>

</body>
</html>
