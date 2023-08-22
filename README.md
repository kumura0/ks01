<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>ks-903 web camera</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>KS-903 web camera</h1>
        <nav>
            <ul>
                <li><a href="#home">ホーム</a></li>
                <li><a href="#services">サービス</a></li>
                 <li><a href="#portfolio">ポートフォリオ</a></li>
                 <li><a href="#contact">お問い合わせ</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section>
            <h2>ウェルカムメッセージ</h2>
            <p>ウェブサイトへようこそ。カメラコンテンツを提供しています。</p>
            <video id="camera" width="300" height="200"></video>
            <canvas id="picture" width="300" height="200"></canvas>
<form>
  <button type="button" id="shutter">シャッター</button>
</form>

        </section>
        
        <section>
            <div id="home" class="section">
                <h1>ホーム</h1>
                <p>ホームページのコンテンツがここに入ります。</p>
                <a href="#contact">お問い合わせ</a>
            </div>
            <div id="portfolio" class="section">
                <img src="nikoniko.jpg" alt="プロジェクト1">
                <h3>上にカメラがあります</h3>
                <p>カメラマーク。これは写真の例です</p>
            </div>
            <div id="services" class="section">
                <img src="download.jpg" alt="プロジェクト2">
                <h3>好きなだけ撮影できます</h3>
                <p>ここはカメラ撮影用のウェブサイトです</p>
                
            </div>
            <div id="contact" class="section">
                <h1>お問い合わせ</h1>
                <p>お問い合わせ先: <a href="mailto:tsst0925@gmail.com">tsst0925@gmail.com</a></p>
                <p>お問い合わせフォームや連絡先情報がここに入ります。</p>
            </div>
        </section>
    </main>
    <script src="script.js"></script>
    <script src="camera.js"></script>
    
    <footer>
        <p>&copy; 2023 ウェブサイトの著作権</p>
    </footer>
</body>
</html>
