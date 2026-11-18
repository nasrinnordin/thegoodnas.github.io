<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nasrin Nordin | @thegoodnas</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #e74c3c;
            --bg-color: #f8f9fa;
            --card-bg: #ffffff;
            --text-main: #333333;
            --text-muted: #666666;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .profile-header {
            text-align: center;
            background: var(--card-bg);
            padding: 40px 20px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }

        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid var(--card-bg);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-bottom: 20px;
            /* Gantikan pautan di bawah dengan gambar profil awak */
            background-image: url('https://placehold.co/150x150/e74c3c/white?text=NN');
            background-size: cover;
        }

        h1 {
            color: var(--primary);
            font-size: 2.2rem;
            margin-bottom: 5px;
        }

        .username {
            color: var(--secondary);
            font-weight: 600;
            font-size: 1.1rem;
            margin-bottom: 15px;
        }

        .bio {
            color: var(--text-muted);
            max-width: 600px;
            margin: 0 auto 25px auto;
            font-size: 1.05rem;
        }

        .location {
            font-size: 0.9rem;
            color: #95a5a6;
            margin-bottom: 20px;
        }

        .location i {
            margin-right: 5px;
        }

        .section-title {
            color: var(--primary);
            font-size: 1.5rem;
            margin-bottom: 20px;
            border-left: 4px solid var(--secondary);
            padding-left: 10px;
        }

        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .card {
            background: var(--card-bg);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card-icon {
            font-size: 2rem;
            color: var(--secondary);
            margin-bottom: 15px;
        }

        .card h3 {
            color: var(--primary);
            margin-bottom: 10px;
        }

        .card p {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 30px;
        }

        .social-btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 45px;
            height: 45px;
            background: var(--card-bg);
            color: var(--primary);
            border-radius: 50%;
            text-decoration: none;
            font-size: 1.2rem;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
        }

        .social-btn:hover {
            background: var(--secondary);
            color: white;
            transform: translateY(-3px);
        }

        .btn-primary {
            display: inline-block;
            padding: 12px 30px;
            background: #ee4d2d; /* Shopee Orange */
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-weight: 600;
            transition: background 0.3s ease;
        }

        .btn-primary:hover {
            background: #d73a1e;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            color: #95a5a6;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header Section -->
        <div class="profile-header">
            <div class="avatar"></div>
            <h1>Nasrin Nordin</h1>
            <div class="username">@thegoodnas</div>
            <div class="location"><i class="fas fa-map-marker-alt"></i> Johor Bahru, Johor</div>
            
            <p class="bio">
                Pengasas Runchick Farm dan peniaga e-dagang. Meminati teknologi, automasi pengurusan, 
                serta penggemar seni pengarkiban media digital dan kopi Americano.
            </p>
            
            <a href="https://shopee.com.my/nasrinnordinofficialstore" target="_blank" class="btn-primary">
                <i class="fas fa-shopping-bag"></i> Nasrin Nordin Official Store
            </a>

            <div class="social-links">
                <a href="https://github.com/nasrinnordin" class="social-btn" title="GitHub"><i class="fab fa-github"></i></a>
                <!-- Boleh tambah pautan WhatsApp atau media sosial lain di sini -->
                <a href="#" class="social-btn" title="Email"><i class="fas fa-envelope"></i></a>
            </div>
        </div>

        <!-- Projects / Portfolio Section -->
        <h2 class="section-title">Projek & Kepakaran</h2>
        <div class="cards-grid">
            
            <div class="card">
                <i class="fas fa-kiwi-bird card-icon"></i>
                <h3>Runchick Farm</h3>
                <p>Menguruskan penternakan baka ayam terpilih seperti Barred Plymouth Rock, Australorp, dan Bresse. Turut membangunkan sistem pengurusan digital menggunakan Firebase untuk pemantauan ternakan, rekod mesin inkubator, dan inventori ladang.</p>
            </div>

            <div class="card">
                <i class="fas fa-store card-icon"></i>
                <h3>E-Dagang & Perniagaan</h3>
                <p>Menguruskan Nasrin Nordin Official Store di Shopee. Berpengalaman dalam jualan atas talian, perkhidmatan pelanggan, dan pengurusan inventori digital.</p>
            </div>

            <div class="card">
                <i class="fas fa-server card-icon"></i>
                <h3>Pengarkiban Media</h3>
                <p>Menguruskan arkib media dan pelayan filem peribadi menggunakan yt-dlp, FFmpeg, dan Tailscale untuk mampatan video resolusi tinggi berformat x264/x265.</p>
            </div>

        </div>

        <footer>
            <p>&copy; 2026 Nasrin Nordin (@thegoodnas). Dibina dengan GitHub Pages.</p>
        </footer>
    </div>

</body>
</html>
