<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Langkah Delivery - Full Energy</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --main-gradient: linear-gradient(180deg, #ff8c00 0%, #ffc107 100%);
            --glass-white: rgba(255, 255, 255, 0.9);
            --text-dark: #332200;
        }

        body { 
            font-family: 'Inter', sans-serif; 
            margin: 0; padding: 0; 
            background: var(--main-gradient);
            background-attachment: fixed;
            color: var(--text-dark);
            min-height: 100vh;
        }

        header {
            padding: 25px 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .logo-container {
            background: white;
            padding: 12px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .logo-img {
            max-height: 80px;
            width: auto;
            object-fit: contain;
        }

        .hero {
            text-align: center;
            padding: 10px 20px 30px;
        }
        .hero h1 { margin: 0; font-size: 1.5rem; font-weight: 800; color: white; text-shadow: 0 2px 4px rgba(0,0,0,0.2); }
        .hero p { color: rgba(255,255,255,0.9); font-size: 0.95rem; margin-top: 5px; font-weight: 600; margin-bottom: 0; }

        .category-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            padding: 0 20px 20px;
            max-width: 500px;
            margin: auto;
        }

        .cat-link { text-decoration: none; color: inherit; }

        .cat-item {
            background: var(--glass-white);
            backdrop-filter: blur(10px);
            padding: 25px 15px;
            border-radius: 28px;
            text-align: center;
            transition: all 0.3s ease;
            box-shadow: 0 8px 32px rgba(0,0,0,0.1);
            border: 1px solid rgba(255, 255, 255, 0.3);
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .icon-box {
            width: 65px;
            height: 65px;
            background: var(--main-gradient);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 32px;
            margin-bottom: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            color: white;
        }

        .cat-item:active {
            transform: translateY(5px);
            background: white;
        }

        .cat-item span {
            font-weight: 800;
            font-size: 14px;
            color: #d35400;
            letter-spacing: 0.5px;
        }

        .cat-desc {
            font-size: 11px;
            color: #666;
            margin-top: 5px;
            font-weight: 600;
        }

        /* Seksi Kontak Admin */
        .contact-admin {
            max-width: 500px;
            margin: 20px auto;
            padding: 0 20px;
        }

        .admin-card {
            background: #332200; /* Warna gelap agar kontras dengan background kuning */
            color: white;
            border-radius: 20px;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            text-decoration: none;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
            transition: 0.3s;
        }

        .admin-card:active { transform: scale(0.97); }

        .admin-info { display: flex; align-items: center; gap: 12px; }
        .admin-text h3 { margin: 0; font-size: 0.9rem; font-weight: 800; }
        .admin-text p { margin: 0; font-size: 0.75rem; opacity: 0.8; }
        
        .wa-icon-small { font-size: 24px; }

        footer {
            text-align: center;
            padding: 30px 20px;
            color: white;
            font-size: 0.8rem;
            font-weight: 700;
            text-shadow: 0 1px 2px rgba(0,0,0,0.1);
            line-height: 1.5;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <img src="logo.png" alt="Logo Langkah Delivery" class="logo-img">
        </div>
    </header>

    <div class="hero">
        <h1>LANGKAH DELIVERY</h1>
        <p>Cepat • Aman • Terpercaya</p>
        <p>Pesan sekarang, Kami yang antar!</p>
    </div>

    <div class="category-grid">
        <a href="https://wa.me/6282310850001?text=Halo%20Langkah%20Delivery,%20mau%20order%20Layanan%20FOOD" class="cat-link">
            <div class="cat-item">
                <div class="icon-box">🍱</div>
                <span>FOOD</span>
                <span class="cat-desc">Pesan Makanan</span>
            </div>
        </a>

        <a href="https://wa.me/6282310850001?text=Halo%20Langkah%20Delivery,%20mau%20order%20Layanan%20PAKET" class="cat-link">
            <div class="cat-item">
                <div class="icon-box">📦</div>
                <span>PAKET</span>
                <span class="cat-desc">Kirim Barang</span>
            </div>
        </a>

        <a href="https://wa.me/6282310850001?text=Halo%20Langkah%20Delivery,%20mau%20order%20Layanan%20MART" class="cat-link">
            <div class="cat-item">
                <div class="icon-box">🛒</div>
                <span>MART</span>
                <span class="cat-desc">Titip Belanja</span>
            </div>
        </a>

        <a href="https://wa.me/6282310850001?text=Halo%20Langkah%20Delivery,%20mau%20order%20Layanan%20KURIR" class="cat-link">
            <div class="cat-item">
                <div class="icon-box">🛵</div>
                <span>KURIR</span>
                <span class="cat-desc">Antar Jemput</span>
            </div>
        </a>
    </div>

    <div class="contact-admin">
        <a href="https://wa.me/6282310850001?text=Halo%20Admin,%20saya%20ingin%20bertanya%20tentang%20Langkah%20Delivery" class="admin-card">
            <div class="admin-info">
                <div class="wa-icon-small">💬</div>
                <div class="admin-text">
                    <h3>Hubungi Admin</h3>
                    <p>Tanya-tanya atau bantuan lainnya</p>
                </div>
            </div>
            <span>➔</span>
        </a>
    </div>

    <footer>
        &mdash; LANGKAH DELIVERY 2025 &mdash;
    </footer>

</body>
</html>
