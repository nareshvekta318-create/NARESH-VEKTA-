<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NARESH VEKTA | No.1 Global Digital Store</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --nv-gold: #FFD700;
            --nv-dark: #000000;
            --nv-card: #1C1C1E;
            --nv-success: #34C759;
        }
        
        body { font-family: 'Inter', -apple-system, sans-serif; background: var(--nv-dark); color: white; margin: 0; padding-bottom: 120px; }

        /* Premium Glass Header */
        header {
            background: rgba(0,0,0,0.85); backdrop-filter: blur(20px);
            padding: 20px; position: sticky; top: 0; z-index: 5000;
            border-bottom: 1px solid rgba(255,215,0,0.2);
            display: flex; justify-content: space-between; align-items: center;
        }
        .logo { font-size: 24px; font-weight: 900; color: var(--nv-gold); letter-spacing: 2px; text-transform: uppercase; }

        /* Smart Search with Voice Interaction */
        .search-prime {
            margin: 15px; background: #2C2C2E; border-radius: 18px;
            display: flex; align-items: center; padding: 5px 15px; border: 1px solid #3A3A3C;
        }
        .search-prime input { background: transparent; border: none; color: white; padding: 12px; width: 100%; outline: none; font-size: 16px; }
        .voice-pulse { color: var(--nv-gold); font-size: 20px; cursor: pointer; animation: breathe 2.5s infinite; }

        @keyframes breathe { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.5; transform: scale(1.15); } }

        /* Delivery Tracker Card */
        .live-tracker {
            background: linear-gradient(135deg, #1c1c1e 0%, #000 100%);
            margin: 15px; padding: 20px; border-radius: 25px; border: 1px solid var(--nv-gold);
        }
        .track-header { display: flex; justify-content: space-between; font-size: 12px; color: var(--nv-gold); font-weight: bold; margin-bottom: 15px; }
        .progress-container { display: flex; align-items: center; gap: 5px; }
        .bar { flex: 1; height: 4px; background: #333; border-radius: 2px; position: relative; overflow: hidden; }
        .bar-fill { position: absolute; left: 0; top: 0; height: 100%; width: 75%; background: var(--nv-gold); box-shadow: 0 0 10px var(--nv-gold); }

        /* Elite Product Grid */
        .grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px; padding: 15px; }
        .elite-card {
            background: var(--nv-card); border-radius: 25px; padding: 15px;
            border: 1px solid rgba(255,255,255,0.05); transition: 0.4s;
        }
        .elite-card:hover { border-color: var(--nv-gold); transform: translateY(-5px); }
        .elite-card img { width: 100%; height: 140px; object-fit: contain; filter: drop-shadow(0 10px 10px rgba(0,0,0,0.3)); }
        .price { font-size: 20px; font-weight: 800; color: var(--nv-gold); margin-top: 10px; }
        .meta { font-size: 10px; color: #888; margin-top: 5px; text-transform: uppercase; letter-spacing: 0.5px; }

        /* Unified Payment Center */
        .pay-center { background: white; color: black; margin: 20px; border-radius: 30px; padding: 25px; }
        .pay-method {
            display: flex; align-items: center; gap: 15px; padding: 15px; border: 1px solid #eee;
            border-radius: 15px; margin-bottom: 10px; font-weight: 700; cursor: pointer;
        }
        .pay-method.active { background: #fffbeb; border-color: var(--nv-gold); }
        .pay-method i { font-size: 22px; width: 30px; text-align: center; }

        /* Floating Nav Bar */
        .nav-float {
            position: fixed; bottom: 25px; left: 50%; transform: translateX(-50%);
            width: 85%; background: rgba(255,255,255,0.1); backdrop-filter: blur(25px);
            border-radius: 35px; display: flex; justify-content: space-around; padding: 15px;
            border: 1px solid rgba(255,255,255,0.15); z-index: 6000;
        }
        .nav-float a { color: #aaa; font-size: 22px; transition: 0.3s; }
        .nav-float a.active { color: var(--nv-gold); transform: scale(1.2); text-shadow: 0 0 15px var(--nv-gold); }
    </style>
</head>
<body>

    <header>
        <div class="logo">NV EMPIRE</div>
        <div style="font-size: 12px; font-weight: 800;"><i class="fas fa-certificate" style="color:var(--nv-gold);"></i> No.1 BRAND</div>
    </header>

    <div class="search-prime">
        <input type="text" placeholder="सर्च करें 'दूध, पनीर, दाल'...">
        <i class="fas fa-microphone voice-pulse"></i>
    </div>

    <div class="live-tracker">
        <div class="track-header">
            <span>ORDER: #NV2026</span>
            <span>स्थिति: रास्ते में है</span>
        </div>
        <div class="progress-container">
            <div class="bar"><div class="bar-fill"></div></div>
            <i class="fas fa-motorcycle" style="color: var(--nv-gold);"></i>
        </div>
        <p style="font-size: 11px; margin-top: 10px; opacity: 0.8;">सामान ठियोग बाजार से निकल चुका है।</p>
    </div>

    <div class="grid">
        <div class="elite-card">
            <img src="https://via.placeholder.com/150" alt="Product">
            <div style="font-weight: 700; margin-top: 10px;">Aashirvaad Atta (5kg)</div>
            <div class="price">₹285</div>
            <div class="meta">Batch: NV-99 | Exp: 2028</div>
        </div>
        <div class="elite-card">
            <img src="https://via.placeholder.com/150" alt="Product">
            <div style="font-weight: 700; margin-top: 10px;">Fortune Oil (1L)</div>
            <div class="price">₹175</div>
            <div class="meta">Batch: NV-45 | Fresh Stock</div>
        </div>
    </div>

    <div class="pay-center">
        <h3 style="margin-top:0;">भुगतान का विकल्प</h3>
        <div class="pay-method"><i class="fas fa-hand-holding-usd" style="color:#28a745;"></i> Cash on Delivery</div>
        <div class="pay-method active"><i class="fas fa-credit-card" style="color:#007bff;"></i> Card / Debit Card</div>
        <div class="pay-method"><i class="fas fa-bolt" style="color:#673ab7;"></i> UPI (PhonePe / G-Pay)</div>
        <div class="pay-method"><i class="fas fa-book" style="color:#e67e22;"></i> खाता बुक (Credit)</div>
        
        <button style="width:100%; background:black; color:var(--nv-gold); border:none; padding:18px; border-radius:15px; font-weight:900; font-size:18px; margin-top:10px; cursor:pointer;">BOOK NOW</button>
    </div>

    <div class="nav-float">
        <a href="#" class="active"><i class="fas fa-home"></i></a>
        <a href="#"><i class="fas fa-boxes-stacked"></i></a>
        <a href="#"><i class="fas fa-map-location-dot"></i></a>
        <a href="#"><i class="fas fa-user-circle"></i></a>
    </div>

</body>
</html>
