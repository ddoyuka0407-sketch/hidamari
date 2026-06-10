# hidamari
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>洋食レストラン Soleil</title>

<style>
    body {
        margin: 0;
        font-family: "Yu Gothic", sans-serif;
        color: #333;
        line-height: 1.6;
    }

    nav {
        background: #8B4513;
        color: white;
        padding: 15px 30px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    nav h1 {
        margin: 0;
    }

    nav ul {
        list-style: none;
        display: flex;
        gap: 20px;
        margin: 0;
        padding: 0;
    }

    nav a {
        color: white;
        text-decoration: none;
    }

    .hero {
        background:
            linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
            url("https://images.unsplash.com/photo-1552566626-52f8b828add9?w=1600")
            center/cover;
        color: white;
        text-align: center;
        padding: 140px 20px;
    }

    .hero h2 {
        font-size: 3rem;
        margin-bottom: 10px;
    }

    section {
        max-width: 1000px;
        margin: auto;
        padding: 60px 20px;
    }

    h3 {
        text-align: center;
        color: #8B4513;
    }

    .menu {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
        gap: 20px;
    }

    .card {
        border: 1px solid #ddd;
        border-radius: 10px;
        overflow: hidden;
    }

    .card img {
        width: 100%;
        height: 200px;
        object-fit: cover;
    }

    .card-content {
        padding: 20px;
    }

    .info {
        background: #f8f8f8;
        border-radius: 10px;
        padding: 30px;
    }

    footer {
        background: #333;
        color: white;
        text-align: center;
        padding: 20px;
    }
</style>
</head>

<body>

<nav>
    <h1>Soleil</h1>

    <ul>
        <li><a href="#about">こだわり</a></li>
        <li><a href="#menu">メニュー</a></li>
        <li><a href="#access">アクセス</a></li>
    </ul>
</nav>

<section class="hero">
    <h2>心温まる、昔ながらの洋食を。</h2>
    <p>家族みんなが笑顔になる、手作りの味。</p>
</section>

<section id="about">
    <h3>当店のこだわり</h3>

    <p>
        デミグラスソースは毎日じっくり仕込み、
        厳選した食材を使用しています。
        懐かしさの中に新しさを感じる洋食をお楽しみください。
    </p>
</section>

<section id="menu">
    <h3>人気メニュー</h3>

    <div class="menu">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1517244683847-7456b63c5969?w=600">
            <div class="card-content">
                <h4>ふわとろオムライス</h4>
                <p>自家製デミグラスソースが人気。</p>
                <strong>1,200円</strong>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1544025162-d76694265947?w=600">
            <div class="card-content">
                <h4>特製ハンバーグステーキ</h4>
                <p>肉汁あふれる看板メニュー。</p>
                <strong>1,450円</strong>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1600891964092-4316c288032e?w=600">
            <div class="card-content">
                <h4>ビーフシチュー</h4>
                <p>じっくり煮込んだ贅沢な味わい。</p>
                <strong>1,800円</strong>
            </div>
        </div>

    </div>
</section>

<section id="access">
    <h3>店舗情報</h3>

    <div class="info">
        <p><strong>営業時間：</strong>11:00～15:00 / 17:00～22:00</p>
        <p><strong>定休日：</strong>毎週火曜日</p>
        <p><strong>住所：</strong>神奈川県○○市○○1-2-3</p>
        <p><strong>TEL：</strong>045-123-4567</p>
    </div>
</section>

<footer>
    <p>© 2026 洋食レストラン Soleil</p>
</footer>

</body>
</html>