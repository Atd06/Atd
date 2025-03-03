# Atd 
<!-- resources/views/index.blade.php -->
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Turizmarket.com</title>
    <link rel="stylesheet" href="{{ asset('css/styles.css') }}">
    <script defer src="{{ asset('js/scripts.js') }}"></script>
</head>
<body>
    <header>
        <div class="logo">
            <img src="{{ asset('images/logo.png') }}" alt="Turizmarket Logo">
        </div>
        <h1>TURİZMARKET.COM</h1>
        <nav>
            <ul>
                <li><a href="{{ url('/') }}">Ana Sayfa</a></li>
                <li><a href="{{ url('/turizm') }}">Turizm</a></li>
                <li><a href="{{ url('/lojistik') }}">Lojistik</a></li>
                <li><a href="{{ url('/otomotiv') }}">Otomotiv</a></li>
                <li><a href="{{ url('/tamircim') }}">Tamircim</a></li>
                <li><a href="{{ url('/admin') }}">Admin Paneli</a></li>
                <li><a href="{{ url('/iletisim') }}">İletişim</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h2>Uygun, Hızlı ve Güvenli Alışveriş</h2>
            <p>Turizm, lojistik ve otomotiv sektöründe en iyi fırsatları keşfedin.</p>
            <a href="{{ url('/urunler') }}" class="btn">Ürünleri Keşfet</a>
        </section>
        <section class="featured-products">
            <h2>Öne Çıkan Ürünler</h2>
            <div id="products">
                <!-- JavaScript ile dinamik olarak ürünler eklenecek -->
            </div>
        </section>
        <section class="sponsors">
            <h2>Sponsorlar</h2>
            <div class="sponsor-logos">
                <img src="{{ asset('images/sponsor1.png') }}" alt="Sponsor 1">
                <img src="{{ asset('images/sponsor2.png') }}" alt="Sponsor 2">
                <img src="{{ asset('images/sponsor3.png') }}" alt="Sponsor 3">
            </div>
        </section>
        <section class="tamircim">
            <h2>Tamircim</h2>
            <p>Usta problemini çözüyoruz! En iyi tamircileri bul.</p>
            <a href="{{ url('/tamircim') }}" class="btn">Detaylı Bilgi</a>
        </section>
    </main>
    <footer>
        <div class="footer-links">
            <a href="{{ url('/hakkimizda') }}">Hakkımızda</a>
            <a href="{{ url('/gizlilik') }}">Gizlilik Politikası</a>
            <a href="{{ url('/kullanim') }}">Kullanım Koşulları</a>
        </div>
        <p>&copy; 2025 Turizmarket.com</p>
        <a href="whatsapp://send?phone=05050102861" class="btn">WhatsApp ile İletişim</a>
    </footer>
</body>
</html>
