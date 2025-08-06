<!DOCTYPE html><html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nasi Uduk 46 - Ala Alifia & Amel</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fffaf0;
            color: #333;
        }
        header {
            background-color: #d2691e;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #f4a460;
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background-image: url('https://example.com/nasi-uduk.jpg'); /* ganti dengan gambar asli */
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 2em;
            font-weight: bold;
            text-shadow: 2px 2px 4px #000;
        }
        .content {
            padding: 20px;
        }
        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .menu-item {
            background-color: #fff8dc;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #d2691e;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Nasi Uduk 46</h1>
        <p>Ala Alifia & Amel</p>
    </header>
    <nav>
        <a href="#menu">Menu</a>
        <a href="#tentang">Tentang</a>
        <a href="#kontak">Kontak</a>
    </nav>
    <section class="hero">
        "Makan nasi uduk biar hidup ga uduk-uduk"
    </section>
    <section class="content" id="menu">
        <h2>Menu Andalan</h2>
        <div class="menu">
            <div class="menu-item">
                <h3>Nasi Uduk Komplit</h3>
                <p>Paha ayam, tempe, telur dadar, sambal, timun & selada</p>
            </div>
            <div class="menu-item">
                <h3>Nasi Uduk Ayam</h3>
                <p>Nasi uduk dengan ayam goreng renyah</p>
            </div>
            <div class="menu-item">
                <h3>Nasi Uduk Tempe</h3>
                <p>Simple & nikmat dengan tempe goreng</p>
            </div>
        </div>
    </section>
    <section class="content" id="tentang">
        <h2>Tentang Kami</h2>
        <p>Nasi Uduk 46 adalah warung makan yang menyajikan nasi uduk khas dengan rasa autentik dan harga terjangkau. Dikelola oleh Alifia dan Amel, kami hadir untuk menemani hari-harimu agar tak lagi uduk-uduk!</p>
    </section>
    <section class="content" id="kontak">
        <h2>Kontak</h2>
        <p>📍 Jalan Kenangan No. 46, Bantul, Yogyakarta</p>
        <p>📞 0812-3456-7890</p>
        <p>📧 nasuduk46@warungmail.com</p>
    </section>
    <footer>
        &copy; 2025 Nasi Uduk 46. Dibuat dengan cinta oleh Alifia & Amel.
    </footer>
</body>
</html>
