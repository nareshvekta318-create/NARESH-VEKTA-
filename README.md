# Here's a simple, responsive HTML homepage for Naresh Vekta General Store. Copy-paste this code into a file named index.html and open it in any browser.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Naresh Vekta General Store - Theog</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: Arial, sans-serif; line-height: 1.6; color: #333; }
        .header { background: #4CAF50; color: white; text-align: center; padding: 2rem; }
        .container { max-width: 1200px; margin: 0 auto; padding: 2rem; }
        .hero { text-align: center; padding: 3rem 1rem; background: #f4f4f4; }
        .info-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin: 2rem 0; }
        .contact { background: #e7f3ff; padding: 2rem; border-radius: 8px; }
        .map { height: 300px; background: #ddd; border-radius: 8px; margin-top: 1rem; display: flex; align-items: center; justify-content: center; color: #666; }
        footer { background: #333; color: white; text-align: center; padding: 1rem; }
        @media (max-width: 768px) { .info-grid { grid-template-columns: 1fr; } }
    </style>
</head>
<body>
    <header class="header">
        <h1>🛒 Naresh Vekta General Store</h1>
        <p>Your Trusted Local Store for Daily Essentials</p>
    </header>

    <div class="container">
        <section class="hero">
            <h2>Welcome to Naresh Vekta General Store</h2>
            <p>Proprietor: Sohan Lal Vekta<br>
            Serving Theog community with groceries, household items & more since years.</p>
        </section>

        <div class="info-grid">
            <div>
                <h3>📍 Address</h3>
                <p>Munda Niwas Hatti<br>
                Near Jawahar Navodaya Vidyalaya<br>
                Theog NH-22, Theog<br>
                Himachal Pradesh 171209</p>
            </div>

            <div class="contact">
                <h3>📞 Contact Us</h3>
                <p><strong>Phone:</strong> +91-XXXXXXXXXX (Add your number)<br>
                <strong>WhatsApp:</strong> +91-XXXXXXXXXX<br>
                <strong>Email:</strong> nareshvekta.store@gmail.com</p>
                <p><strong>Hours:</strong><br>Mon-Sat: 8 AM - 9 PM<br>Sunday: 9 AM - 7 PM</p>
            </div>
        </div>

        <div id="map" class="map">📍 Google Maps Embed Placeholder<br>Add your location: https://maps.google.com/maps?q=Theog+NH-22,+Himachal+Pradesh</div>
    </div>

    <footer>
        <p>&copy; 2026 Naresh Vekta General Store. Serving Theog with pride. | Local Delivery Available</p>
    </footer>
</body>
</html>Quick CustomizationReplace XXXXXXXXXX with your actual phone/WhatsApp number. For the map, get your exact Google Maps embed code (free) by searching your address on maps.google.com and clicking "Share > Embed a map." Paste the iframe code inside <div id="map" class="map"> replacing the placeholder. Upload to free hosting like GitHub Pages or Netlify for a live site (yourstore.netlify.app). Fully mobile-responsive and SEO-ready for "general store Theog."
