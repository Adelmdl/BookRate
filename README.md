<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BookRate</title>

  <style>

    /* ============================================
       GENERAL RESET & BODY
       ============================================ */

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #222222;
    }


    /* ============================================
       HEADER
       ============================================ */

    header {
      background-color: #ffffff;
      border-bottom: 2px solid #eeeeee;
      padding: 20px 40px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #222222;
    }

    nav {
      display: flex;
      gap: 30px;
    }

    nav a {
      text-decoration: none;
      color: #444444;
      font-size: 16px;
    }

    nav a:hover {
      color: #000000;
    }


    /* ============================================
       HERO SECTION
       ============================================ */

    .hero {
      background-color: #f5f5f5;
      text-align: center;
      padding: 80px 40px;
    }

    .hero h1 {
      font-size: 42px;
      color: #111111;
      margin-bottom: 16px;
    }

    .hero p {
      font-size: 18px;
      color: #555555;
      margin-bottom: 32px;
    }

    .hero-button {
      background-color: #222222;
      color: #ffffff;
      padding: 14px 32px;
      font-size: 16px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
    }

    .hero-button:hover {
      background-color: #000000;
    }


    /* ============================================
       BOOKS SECTION
       ============================================ */

    .books-section {
      background-color: #ffffff;
      padding: 60px 40px;
    }

    .books-section h2 {
      text-align: center;
      font-size: 28px;
      color: #111111;
      margin-bottom: 8px;
    }

    .books-section .subtitle {
      text-align: center;
      color: #777777;
      font-size: 16px;
      margin-bottom: 40px;
    }

    /* Grid layout: 3 cards per row */
    .books-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 24px;
      max-width: 1000px;
      margin: 0 auto;
    }

    /* Single book card */
    .book-card {
      background-color: #f9f9f9;
      border: 1px solid #e0e0e0;
      border-radius: 10px;
      overflow: hidden;
    }

    .book-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      display: block;
    }

    .book-info {
      padding: 16px;
    }

    .book-title {
      font-size: 16px;
      font-weight: bold;
      color: #111111;
      margin-bottom: 6px;
    }

    .book-author {
      font-size: 14px;
      color: #666666;
      margin-bottom: 10px;
    }

    .book-rating {
      font-size: 14px;
      color: #f59e0b;
    }


    /* ============================================
       FOOTER
       ============================================ */

    footer {
      background-color: #f5f5f5;
      border-top: 2px solid #eeeeee;
      text-align: center;
      padding: 30px 40px;
    }

    .footer-logo {
      font-size: 18px;
      font-weight: bold;
      color: #222222;
      margin-bottom: 8px;
    }

    .footer-copy {
      font-size: 14px;
      color: #888888;
    }

  </style>
</head>

<body>


  <!-- ============================================
       HEADER
       ============================================ -->

  <header>

    <div class="logo">📚 BookRate</div>

    <nav>
      <a href="#">Home</a>
      <a href="#books">Books</a>
      <a href="#">Contact</a>
    </nav>

  </header>


  <!-- ============================================
       HERO SECTION
       ============================================ -->

  <section class="hero">

    <h1>Top Rated Books</h1>

    <p>Discover the best books chosen by thousands of readers around the world.</p>

    <a href="#books" class="hero-button">View Books</a>

  </section>


  <!-- ============================================
       BOOKS SECTION
       ============================================ -->

  <section class="books-section" id="books">

    <h2>Book Ranking</h2>
    <p class="subtitle">Our top picks based on reader reviews and ratings</p>

    <div class="books-grid">

      <!-- Book Card 1 -->
      <div class="book-card">
        <img
          src="https://images.unsplash.com/photo-1555252586-d77e8c828e41?w=400&q=80"
          alt="Your Heart is the Sea"
        />
        <div class="book-info">
          <p class="book-title">Your Heart is the Sea</p>
          <p class="book-author">Thought Catalog</p>
          <p class="book-rating">★★★★★ 4.8</p>
        </div>
      </div>

      <!-- Book Card 2 -->
      <div class="book-card">
        <img
          src="https://images.unsplash.com/photo-1529521818954-c76995518833?w=400&q=80"
          alt="The First New Universe"
        />
        <div class="book-info">
          <p class="book-title">The First New Universe</p>
          <p class="book-author">Elena Marsh</p>
          <p class="book-rating">★★★★☆ 4.7</p>
        </div>
      </div>

      <!-- Book Card 3 -->
      <div class="book-card">
        <img
          src="https://images.unsplash.com/photo-1760696473709-a7da66ee87a6?w=400&q=80"
          alt="Tell Me Your Dreams"
        />
        <div class="book-info">
          <p class="book-title">Tell Me Your Dreams</p>
          <p class="book-author">Godwin Leones</p>
          <p class="book-rating">★★★★☆ 4.6</p>
        </div>
      </div>

      <!-- Book Card 4 -->
      <div class="book-card">
        <img
          src="https://images.unsplash.com/photo-1752243751485-28462bdee57a?w=400&q=80"
          alt="Crime and Punishment"
        />
        <div class="book-info">
          <p class="book-title">Crime and Punishment</p>
          <p class="book-author">Fyodor Dostoevsky</p>
          <p class="book-rating">★★★★★ 4.9</p>
        </div>
      </div>

      <!-- Book Card 5 -->
      <div class="book-card">
        <img
          src="https://images.unsplash.com/photo-1771712745074-80faaadc030e?w=400&q=80"
          alt="Harry Potter and the Order"
        />
        <div class="book-info">
          <p class="book-title">Harry Potter & The Order</p>
          <p class="book-author">J.K. Rowling</p>
          <p class="book-rating">★★★★★ 4.8</p>
        </div>
      </div>

      <!-- Book Card 6 -->
      <div class="book-card">
        <img
          src="https://images.unsplash.com/photo-1752243713887-cb4a37a0a3d7?w=400&q=80"
          alt="The Stranger"
        />
        <div class="book-info">
          <p class="book-title">The Stranger</p>
          <p class="book-author">Albert Camus</p>
          <p class="book-rating">★★★★☆ 4.5</p>
        </div>
      </div>

    </div>

  </section>


  <!-- ============================================
       FOOTER
       ============================================ -->

  <footer>
    <p class="footer-logo">📚 BookRate</p>
    <p class="footer-copy">© 2026 BookRate. All rights reserved.</p>
  </footer>


</body>
</html>
