# pattathu-vinayagar
transport service
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pattathu Vinayagar Lorry Booking</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Rubik', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f3f4f6;
      color: #333;
    }
    .main-container {
      background: linear-gradient(to right, #e67e22, #f39c12);
      color: white;
      text-align: center;
      padding: 60px 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
    }
    .main-container h1 {
      font-size: 3rem;
      margin-bottom: 15px;
    }
    .main-container p {
      font-size: 1.25rem;
      font-weight: 500;
    }
    nav {
      background-color: #2d3436;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 20px;
    }
    nav a {
      color: #fff;
      margin: 10px 25px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #f39c12;
    }
    .section-block {
      max-width: 1100px;
      margin: 0 auto;
      padding: 60px 20px;
    }
    .section-block h2 {
      font-size: 2.2rem;
      color: #e67e22;
      margin-bottom: 20px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .gallery img {
      width: 240px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    form {
      background-color: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
    }
    form input, form textarea {
      width: 100%;
      padding: 14px;
      margin-bottom: 15px;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    form button {
      background: #e67e22;
      color: white;
      font-size: 1rem;
      padding: 12px 20px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    form button:hover {
      background: #d35400;
    }
    footer {
      background-color: #2d3436;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <div class="main-container">
    <h1>Pattathu Vinayagar Lorry Booking</h1>
    <p>Your Load, Our Responsibility — Safe & Reliable Transport Services</p>
  </div>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#booking">Booking</a>
    <a href="#gallery">Gallery</a>
    <a href="#reviews">Reviews</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="section-block">
    <h2>Welcome</h2>
    <p>We specialize in lorry transport services from Madurai and surrounding regions. We handle your cargo with care, picking it up from your location and delivering it safely to the destination. Whether you're moving construction materials, furniture, goods for your business, or personal items, we make sure everything reaches the right place on time. We take pride in our punctuality, transparency, and commitment to safety.</p>
  </section>

  <section id="about" class="section-block">
    <h2>About Us</h2>
    <p>Pattathu Vinayagar is a growing logistics partner rooted in Madurai, Tamil Nadu. We began our journey with a single lorry and a vision to deliver reliable transportation to every business and individual who needs it. Today, we operate across southern Tamil Nadu and are proud to have earned a reputation for consistency, affordability, and professionalism. Our team of drivers and support staff ensures that every load is treated with utmost care and delivered as promised.</p>
  </section>

  <section id="services" class="section-block">
    <h2>Our Services</h2>
    <p>We offer tailored lorry services for businesses, individuals, and industries. Whether it’s a single trip or regular transportation needs, we have a plan for you. Our services include:</p>
    <ul>
      <li>Point-to-point delivery in Madurai, Trichy, and nearby towns</li>
      <li>Timely pickup and drop with real-time driver updates</li>
      <li>Experienced and trained drivers</li>
      <li>Affordable pricing without hidden charges</li>
    </ul>
  </section>

  <section id="booking" class="section-block">
    <h2>Lorry Booking</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="text" placeholder="Pickup Location" required />
      <input type="text" placeholder="Drop Location" required />
      <input type="tel" placeholder="Phone Number" required />
      <textarea placeholder="Load Description" rows="4"></textarea>
      <button type="submit">Book My Lorry</button>
    </form>
    <p style="margin-top:20px; font-size: 1.1rem;">Need urgent help? Call us directly at <strong>9361125023</strong> anytime — we are available 24/7!</p>
  </section>

  <section id="gallery" class="section-block">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="/mnt/data/download.jfif" alt="Lorry 1" />
      <img src="/mnt/data/download (1).jfif" alt="Lorry 2" />
      <img src="/mnt/data/images.jfif" alt="Lorry 3" />
      <img src="/mnt/data/images (1).jfif" alt="Lorry 4" />
      <img src="/mnt/data/images (2).jfif" alt="Lorry 5" />
      <img src="/mnt/data/download (2).jfif" alt="Lorry 6" />
    </div>
  </section>

  <section id="reviews" class="section-block">
    <h2>Customer Reviews</h2>
    <p>4.3 / 5 ⭐ — Our clients appreciate our timeliness, professional drivers, and transparent communication. Here are a few of their words:</p>
    <blockquote>"Reliable service! My cargo was delivered exactly on time, and the booking was super easy." – Muthukumar, Madurai</blockquote>
    <blockquote>"Professional drivers, clean lorries, and fair rates. Highly recommended!" – Saranya, Trichy</blockquote>
  </section>

  <section id="contact" class="section-block">
    <h2>Contact Us</h2>
    <p><strong>Phone/WhatsApp:</strong> <a href="tel:9361125023">9361125023</a></p>
    <p><strong>Email:</strong> <a href="mailto:bkeerthikkumar19219762@gmail.com">bkeerthikkumar19219762@gmail.com</a></p>
    <p><strong>Available:</strong> 24/7 Transport Support</p>
    <p><strong>Address:</strong> Madurai – Serving all nearby towns including Tiruchirappalli, Dindigul, Sivaganga, and beyond.</p>
  </section>

  <footer>
    <p>&copy; 2025 Pattathu Vinayagar Lorry Booking. Built with pride in Madurai.</p>
  </footer>
</body>
</html>
