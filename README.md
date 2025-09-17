<!DOCTYPE html>
<html lang="zh-HK">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cool Vape Shop</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <!-- 年齡驗證彈窗 -->
    <div id="age-verification" class="modal">
        <div class="modal-content">
            <h2>年齡驗證</h2>
            <p>本網站只限18歲以上人士。請輸入出生年份：</p>
            <input type="number" id="birth-year" placeholder="例如 1990">
            <button onclick="verifyAge()">確認</button>
            <p>警告：本產品含尼古丁，只限成人使用。</p>
        </div>
    </div>

    <!-- 網站內容 -->
    <header>
        <h1>Cool Vape Shop</h1>
        <p>最新電子煙、煙油同配件，立即聯絡我哋！</p>
    </header>

    <section class="products">
        <h2>熱賣產品</h2>
        <div class="product">
            <img src="images/vape1.jpg" alt="VapeX Pro">
            <h3>VapeX Pro</h3>
            <p>5000mAh電池，7款潮流顏色，輕巧設計。</p>
            <a href="https://wa.me/+85212345678?text=我想查詢VapeX%20Pro" class="cta-button">WhatsApp下單</a>
        </div>
        <div class="product">
            <img src="images/juice1.jpg" alt="Cool Mint 煙油">
            <h3>Cool Mint 煙油</h3>
            <p>清涼薄荷，50ml，3mg尼古丁，適合新手。</p>
            <a href="https://wa.me/+85212345678?text=我想查詢Cool%20Mint%20煙油" class="cta-button">WhatsApp下單</a>
        </div>
        <div class="product">
            <img src="images/coil1.jpg" alt="專用霧化器">
            <h3>專用霧化器</h3>
            <p>耐用陶瓷芯，兼容多款主機，提升煙霧量。</p>
            <a href="https://wa.me/+85212345678?text=我想查詢霧化器" class="cta-button">WhatsApp下單</a>
        </div>
    </section>

    <section class="contact">
        <h2>聯絡我哋</h2>
        <p>WhatsApp: <a href="https://wa.me/+85212345678">+852 1234 5678</a></p>
        <p>Email: <a href="mailto:info@coolvapeshop.com">info@coolvapeshop.com</a></p>
        <form action="https://formspree.io/f/你的ID" method="POST">
            <input type="text" name="name" placeholder="你嘅姓名" required>
