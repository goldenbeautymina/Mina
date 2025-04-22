<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>我的個人網頁</title>
  <style>
    body {
      font-family: "Helvetica Neue", sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #004466;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      background-color: #e0e0e0;
      padding: 1rem 0;
    }
    nav a {
      text-decoration: none;
      color: #004466;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .photo-gallery img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      margin-bottom: 1rem;
    }
    footer {
      background-color: #004466;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>歡迎來到我的個人網頁</h1>
    <p>一個展現作品與想法的平台</p>
  </header>

  <nav>
    <a href="#about">自我介紹</a>
    <a href="#portfolio">作品展示</a>
    <a href="#resume">履歷下載</a>
    <a href="#blog">部落格文章</a>
    <a href="#gallery">照片牆</a>
    <a href="#contact">聯絡方式</a>
  </nav>

  <section id="about">
    <h2>自我介紹</h2>
    <p>您好，我是一位熱愛創作與分享的工作者，擅長以簡約風格呈現內容，專注於設計、寫作與數位技術的結合。</p>
  </section>

  <section id="portfolio">
    <h2>作品展示</h2>
    <ul>
      <li>作品一：設計案例 A</li>
      <li>作品二：攝影專案 B</li>
      <li>作品三：網頁開發 C</li>
    </ul>
  </section>

  <section id="resume">
    <h2>履歷下載</h2>
    <p><a href="resume.pdf" download>點我下載 PDF 履歷</a></p>
  </section>

  <section id="blog">
    <h2>部落格文章</h2>
    <ul>
      <li><a href="#">如何建立個人品牌網站</a></li>
      <li><a href="#">我最喜歡的設計靈感來源</a></li>
      <li><a href="#">數位工具提升創作效率的方法</a></li>
    </ul>
  </section>

  <section id="gallery">
    <h2>照片牆</h2>
    <div class="photo-gallery">
      <img src="https://github.com/goldenbeautymina/Mina/blob/main/photo3.jpg" alt="作品照片1">
      <img src="images/photo2.jpg" alt="作品照片2">
      <img src="images/photo3.jpg" alt="作品照片3">
    </div>
  </section>

  <section id="contact">
    <h2>聯絡方式</h2>
    <p>Email：youremail@example.com</p>
    <p>社群連結：
      <a href="https://www.linkedin.com">LinkedIn</a> ｜ 
      <a href="https://www.instagram.com">Instagram</a> ｜ 
      <a href="https://www.github.com">GitHub</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 您的大名 | 保留所有權利</p>
  </footer>
</body>
</html>
