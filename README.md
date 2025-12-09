<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mazayin Restaurant - Authentic Moroccan Cuisine</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar" id="navbar">
        <div class="container">
            <div class="nav-wrapper">
                <div class="logo">
                    <h1>MAZAYIN</h1>
                    <span class="tagline">Restaurant</span>
                </div>
                <div class="hamburger" id="hamburger">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <ul class="nav-menu" id="navMenu">
                    <li><a href="#home" class="nav-link">Home</a></li>
                    <li><a href="#about" class="nav-link">About</a></li>
                    <li><a href="#menu" class="nav-link">Menu</a></li>
                    <li><a href="#gallery" class="nav-link">Gallery</a></li>
                    <li><a href="#contact" class="nav-link">Contact</a></li>
                    <li><a href="#reservation" class="btn-reserve">Reserve Table</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section class="hero" id="home">
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <div class="hero-text">
                <span class="subtitle">Welcome to Mazayin</span>
                <h1 class="hero-title">Experience the Magic of Moroccan Cuisine</h1>
                <p class="hero-description">Indulge in authentic flavors and traditional recipes passed down through generations</p>
                <div class="hero-buttons">
                    <a href="#menu" class="btn btn-primary">Explore Menu</a>
                    <a href="#reservation" class="btn btn-secondary">Book a Table</a>
                </div>
            </div>
        </div>
        <div class="scroll-indicator">
            <span>Scroll</span>
            <div class="scroll-line"></div>
        </div>
    </section>

    <section class="about" id="about">
        <div class="container">
            <div class="about-content">
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1552566626-52f8b828add9?w=800&h=1000&fit=crop" alt="Mazayin Restaurant Interior">
                    <div class="about-badge">
                        <span class="badge-years">25+</span>
                        <span class="badge-text">Years of Excellence</span>
                    </div>
                </div>
                <div class="about-text">
                    <span class="section-subtitle">Our Story</span>
                    <h2 class="section-title">Where Tradition Meets Elegance</h2>
                    <p>For over two decades, Mazayin has been the heart of authentic Moroccan dining, bringing the rich flavors and warm hospitality of Morocco to your table. Our journey began with a simple vision: to share the culinary treasures of our homeland with food lovers around the world.</p>
                    <p>Every dish tells a story, crafted with passion using traditional recipes and the finest ingredients. From our signature tagines to our delicate pastries, we honor the culinary heritage that has been passed down through generations of Moroccan families.</p>
                    <div class="about-features">
                        <div class="feature-item">
                            <div class="feature-icon">🌟</div>
                            <h3>Premium Quality</h3>
                            <p>Only the finest ingredients</p>
                        </div>
                        <div class="feature-item">
                            <div class="feature-icon">👨‍🍳</div>
                            <h3>Master Chefs</h3>
                            <p>Trained in traditional methods</p>
                        </div>
                        <div class="feature-item">
                            <div class="feature-icon">❤️</div>
                            <h3>Made with Love</h3>
                            <p>Every dish crafted with care</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="menu" id="menu">
        <div class="container">
            <div class="section-header">
                <span class="section-subtitle">Our Specialties</span>
                <h2 class="section-title">Discover Our Menu</h2>
                <p class="section-description">A culinary journey through the flavors of Morocco</p>
            </div>

            <div class="menu-tabs">
                <button class="tab-btn active" data-tab="appetizers">Appetizers</button>
                <button class="tab-btn" data-tab="mains">Main Courses</button>
                <button class="tab-btn" data-tab="desserts">Desserts</button>
                <button class="tab-btn" data-tab="drinks">Beverages</button>
            </div>

            <div class="menu-content">
                <div class="tab-content active" id="appetizers">
                    <div class="menu-grid">
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1599487488170-d11ec9c172f0?w=600&h=400&fit=crop" alt="Moroccan Mezze">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Moroccan Mezze Platter</h3>
                                    <span class="price">$18</span>
                                </div>
                                <p>Assorted traditional dips including hummus, zaalouk, and taktouka served with warm bread</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1534080564583-6be75777b70a?w=600&h=400&fit=crop" alt="Briouats">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Chicken Briouats</h3>
                                    <span class="price">$14</span>
                                </div>
                                <p>Crispy phyllo pastries filled with spiced chicken, almonds, and fresh herbs</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1544025162-d76694265947?w=600&h=400&fit=crop" alt="Harira Soup">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Harira Soup</h3>
                                    <span class="price">$12</span>
                                </div>
                                <p>Traditional Moroccan soup with tomatoes, lentils, chickpeas, and aromatic spices</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1601050690597-df0568f70950?w=600&h=400&fit=crop" alt="Zaalouk">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Zaalouk Dip</h3>
                                    <span class="price">$10</span>
                                </div>
                                <p>Roasted eggplant and tomato salad with garlic, cumin, and olive oil</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-content" id="mains">
                    <div class="menu-grid">
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1588137378633-dea1336ce1e2?w=600&h=400&fit=crop" alt="Lamb Tagine">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Lamb Tagine with Prunes</h3>
                                    <span class="price">$32</span>
                                </div>
                                <p>Slow-cooked tender lamb with sweet prunes, almonds, and aromatic spices</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1603360946369-dc9bb6258143?w=600&h=400&fit=crop" alt="Chicken Bastilla">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Chicken Bastilla</h3>
                                    <span class="price">$28</span>
                                </div>
                                <p>Traditional pie with spiced chicken, eggs, and almonds in crispy phyllo pastry</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1551183053-bf91a1d81141?w=600&h=400&fit=crop" alt="Couscous Royale">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Couscous Royale</h3>
                                    <span class="price">$34</span>
                                </div>
                                <p>Steamed couscous with seven vegetables and your choice of lamb, chicken, or merguez</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1598103442097-8b74394b95c6?w=600&h=400&fit=crop" alt="Fish Chermoula">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Grilled Fish Chermoula</h3>
                                    <span class="price">$30</span>
                                </div>
                                <p>Fresh sea bass marinated in chermoula sauce with herbs and spices</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-content" id="desserts">
                    <div class="menu-grid">
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1571115177098-24ec42ed204d?w=600&h=400&fit=crop" alt="Baklava">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Honey Baklava</h3>
                                    <span class="price">$12</span>
                                </div>
                                <p>Layers of phyllo pastry filled with nuts and sweetened with honey syrup</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1563805042-7684c019e1cb?w=600&h=400&fit=crop" alt="Chebakia">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Chebakia</h3>
                                    <span class="price">$10</span>
                                </div>
                                <p>Sesame cookies fried and coated in honey, sprinkled with sesame seeds</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?w=600&h=400&fit=crop" alt="Orange Salad">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Moroccan Orange Salad</h3>
                                    <span class="price">$8</span>
                                </div>
                                <p>Fresh oranges with cinnamon, orange blossom water, and toasted almonds</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1567327418247-7e0a7a28e1ed?w=600&h=400&fit=crop" alt="Mint Tea Cake">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Mint Tea Cake</h3>
                                    <span class="price">$11</span>
                                </div>
                                <p>Moist almond cake infused with fresh mint and served with whipped cream</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-content" id="drinks">
                    <div class="menu-grid">
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1556679343-c7306c1976bc?w=600&h=400&fit=crop" alt="Mint Tea">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Traditional Mint Tea</h3>
                                    <span class="price">$6</span>
                                </div>
                                <p>Freshly brewed green tea with fresh mint leaves and a touch of sugar</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1577968897966-3d77d07e3304?w=600&h=400&fit=crop" alt="Avocado Smoothie">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Avocado Smoothie</h3>
                                    <span class="price">$8</span>
                                </div>
                                <p>Creamy avocado blended with milk, dates, and a hint of orange blossom</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1570831739435-6601aa3fa4fb?w=600&h=400&fit=crop" alt="Fresh Juice">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Fresh Orange Juice</h3>
                                    <span class="price">$7</span>
                                </div>
                                <p>Freshly squeezed juice from premium Moroccan oranges</p>
                            </div>
                        </div>
                        <div class="menu-item">
                            <div class="menu-item-image">
                                <img src="https://images.unsplash.com/photo-1517487881594-2787fef5ebf7?w=600&h=400&fit=crop" alt="Spiced Coffee">
                            </div>
                            <div class="menu-item-info">
                                <div class="menu-item-header">
                                    <h3>Spiced Coffee</h3>
                                    <span class="price">$5</span>
                                </div>
                                <p>Rich Arabic coffee infused with cardamom and a hint of cinnamon</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="gallery" id="gallery">
        <div class="container">
            <div class="section-header">
                <span class="section-subtitle">Visual Journey</span>
                <h2 class="section-title">Gallery</h2>
                <p class="section-description">Experience the ambiance and beauty of Mazayin</p>
            </div>

            <div class="gallery-grid">
                <div class="gallery-item tall">
                    <img src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?w=800&h=1000&fit=crop" alt="Restaurant Interior">
                    <div class="gallery-overlay">
                        <span>Elegant Dining</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1590846406792-0adc7f938f1d?w=600&h=400&fit=crop" alt="Moroccan Tagine">
                    <div class="gallery-overlay">
                        <span>Traditional Tagines</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?w=600&h=400&fit=crop" alt="Restaurant Ambiance">
                    <div class="gallery-overlay">
                        <span>Warm Atmosphere</span>
                    </div>
                </div>
                <div class="gallery-item wide">
                    <img src="https://images.unsplash.com/photo-1559339352-11d035aa65de?w=1200&h=600&fit=crop" alt="Moroccan Spices">
                    <div class="gallery-overlay">
                        <span>Authentic Spices</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1578474846511-04ba529f0b88?w=600&h=400&fit=crop" alt="Fine Dining">
                    <div class="gallery-overlay">
                        <span>Premium Service</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1533777324565-a040eb52facd?w=600&h=400&fit=crop" alt="Couscous Dish">
                    <div class="gallery-overlay">
                        <span>Signature Dishes</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="reservation" id="reservation">
        <div class="container">
            <div class="reservation-content">
                <div class="reservation-info">
                    <span class="section-subtitle">Reserve Your Table</span>
                    <h2 class="section-title">Book Your Experience</h2>
                    <p>Join us for an unforgettable dining experience. Our team is ready to welcome you with traditional Moroccan hospitality.</p>
                    <div class="info-items">
                        <div class="info-item">
                            <div class="info-icon">📞</div>
                            <div>
                                <h4>Call Us</h4>
                                <p>+212 522 123 456</p>
                            </div>
                        </div>
                        <div class="info-item">
                            <div class="info-icon">⏰</div>
                            <div>
                                <h4>Opening Hours</h4>
                                <p>Daily: 12:00 PM - 11:00 PM</p>
                            </div>
                        </div>
                        <div class="info-item">
                            <div class="info-icon">📍</div>
                            <div>
                                <h4>Location</h4>
                                <p>Boulevard Anfa, Casablanca</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="reservation-form">
                    <form id="bookingForm">
                        <div class="form-row">
                            <div class="form-group">
                                <input type="text" id="name" required>
                                <label for="name">Full Name</label>
                            </div>
                            <div class="form-group">
                                <input type="email" id="email" required>
                                <label for="email">Email Address</label>
                            </div>
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <input type="tel" id="phone" required>
                                <label for="phone">Phone Number</label>
                            </div>
                            <div class="form-group">
                                <input type="number" id="guests" min="1" max="20" required>
                                <label for="guests">Number of Guests</label>
                            </div>
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <input type="date" id="date" required>
                                <label for="date">Date</label>
                            </div>
                            <div class="form-group">
                                <input type="time" id="time" required>
                                <label for="time">Time</label>
                            </div>
                        </div>
                        <div class="form-group">
                            <textarea id="message" rows="3"></textarea>
                            <label for="message">Special Requests (Optional)</label>
                        </div>
                        <button type="submit" class="btn btn-primary btn-full">Complete Reservation</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <div class="container">
            <div class="contact-content">
                <div class="contact-map">
                    <img src="https://images.unsplash.com/photo-1569336415962-a4bd9f69cd83?w=1200&h=600&fit=crop" alt="Casablanca Location Map">
                    <div class="map-marker">
                        <span>📍</span>
                    </div>
                </div>
                <div class="contact-details">
                    <h2>Visit Us</h2>
                    <div class="contact-item">
                        <h3>Address</h3>
                        <p>123 Boulevard Anfa<br>Casablanca, Morocco 20250</p>
                    </div>
                    <div class="contact-item">
                        <h3>Contact</h3>
                        <p>Phone: +212 522 123 456<br>Email: info@mazayin.ma</p>
                    </div>
                    <div class="contact-item">
                        <h3>Hours</h3>
                        <p>Monday - Sunday<br>12:00 PM - 11:00 PM</p>
                    </div>
                    <div class="social-links">
                        <a href="#" class="social-link">Facebook</a>
                        <a href="#" class="social-link">Instagram</a>
                        <a href="#" class="social-link">Twitter</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-col">
                    <div class="footer-logo">
                        <h3>MAZAYIN</h3>
                        <span>Restaurant</span>
                    </div>
                    <p>Bringing authentic Moroccan flavors and hospitality to your table since 1999.</p>
                </div>
                <div class="footer-col">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#menu">Our Menu</a></li>
                        <li><a href="#gallery">Gallery</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Services</h4>
                    <ul>
                        <li><a href="#reservation">Reservations</a></li>
                        <li><a href="#contact">Private Events</a></li>
                        <li><a href="#contact">Catering</a></li>
                        <li><a href="#contact">Gift Cards</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Newsletter</h4>
                    <p>Subscribe to receive updates and special offers</p>
                    <form class="newsletter-form">
                        <input type="email" placeholder="Your email">
                        <button type="submit">Subscribe</button>
                    </form>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2024 Mazayin Restaurant. All rights reserved.</p>
                <div class="footer-links">
                    <a href="#">Privacy Policy</a>
                    <a href="#">Terms of Service</a>
                </div>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
css* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-gold: #D4AF37;
    --dark-gold: #B8941F;
    --deep-brown: #2C1810;
    --warm-brown: #4A3428;
    --cream: #FFF8E7;
    --light-cream: #FFFBF0;
    --text-dark: #1A1A1A;
    --text-light: #666666;
    --white: #FFFFFF;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Poppins', sans-serif;
    color: var(--text-dark);
    line-height: 1.6;
    overflow-x: hidden;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.navbar {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
    background: rgba(44, 24, 16, 0.95);
    backdrop-filter: blur(10px);
    transition: all 0.3s ease;
    box-shadow: 0 2px 20px rgba(0, 0, 0, 0.1);
}

.navbar.scrolled {
    background: rgba(44, 24, 16, 1);
    box-shadow: 0 2px 30px rgba(0, 0, 0, 0.3);
}

.nav-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.2rem 0;
}

.logo h1 {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    font-weight: 700;
    color: var(--primary-gold);
    letter-spacing: 3px;
}

.logo .tagline {
    display: block;
    font-size: 0.75rem;
    color: var(--cream);
    letter-spacing: 2px;
    text-align: center;
    margin-top: -5px;
}

.nav-menu {
    display: flex;
    list-style: none;
    align-items: center;
    gap: 2rem;
}

.nav-link {
    color: var(--cream);
    text-decoration: none;
    font-size: 0.95rem;
    font-weight: 400;
    position: relative;
    transition: color 0.3s ease;
}

.nav-link::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 0;
    height: 2px;
    background: var(--primary-gold);
    transition: width 0.3s ease;
}

.nav-link:hover {
    color: var(--primary-gold);
}

.nav-link:hover::after {
    width: 100%;
}

.btn-reserve {
    padding: 0.7rem 1.5rem;
    background: var(--primary-gold);
    color: var(--deep-brown);
    text-decoration: none;
    border-radius: 30px;
    font-weight: 500;
    transition: all 0.3s ease;
}

.btn-reserve:hover {
    background: var(--dark-gold);
    transform: translateY(-2px);
    box-shadow: 0 5px 15px rgba(212, 175, 55, 0.3);
}

.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
    gap: 5px;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background: var(--cream);
    transition: all 0.3s ease;
    border-radius: 3px;
}

.hero {
    height: 100vh;
    background: linear-gradient(rgba(44, 24, 16,
