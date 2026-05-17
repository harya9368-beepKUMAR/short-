[deepseek_html_20260517_b83c9d.html](https://github.com/user-attachments/files/27870885/deepseek_html_20260517_b83c9d.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes, viewport-fit=cover">
  <title>Prem | Lifestyle • Fashion • Motivation • Finance</title>
  <!-- Font Awesome 6 for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <!-- Google Fonts: modern & clean -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,500;14..32,600;14..32,700&family=Montserrat:wght@500;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: #f9fafb;
      color: #1f2937;
      line-height: 1.5;
      scroll-behavior: smooth;
    }

    .container {
      max-width: 1280px;
      margin: 0 auto;
      padding: 0 24px;
    }

    /* header / hero */
    .hero {
      background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
      color: white;
      padding: 32px 0 48px;
      border-radius: 0 0 40px 40px;
      box-shadow: 0 20px 35px rgba(0,0,0,0.1);
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      margin-bottom: 40px;
    }

    .logo {
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 2rem;
      letter-spacing: -0.5px;
      background: linear-gradient(to right, #fbbf24, #f59e0b);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .nav-links {
      display: flex;
      gap: 28px;
      align-items: center;
      flex-wrap: wrap;
    }

    .nav-links a {
      color: #e2e8f0;
      text-decoration: none;
      font-weight: 500;
      font-size: 1rem;
      transition: 0.2s;
      display: flex;
      align-items: center;
      gap: 6px;
    }

    .nav-links a:hover {
      color: #fbbf24;
    }

    .social-top i {
      font-size: 1.2rem;
      margin-left: 12px;
      color: #cbd5e1;
      transition: 0.2s;
    }
    .social-top i:hover {
      color: #fbbf24;
      transform: scale(1.1);
    }

    .hero-content {
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 32px;
    }

    .hero-text {
      flex: 1 1 400px;
    }

    .hero-text h1 {
      font-size: 3.2rem;
      font-weight: 700;
      font-family: 'Montserrat', sans-serif;
      line-height: 1.2;
      margin-bottom: 16px;
    }
    .hero-text .highlight {
      color: #fbbf24;
    }

    .hero-text p {
      font-size: 1.2rem;
      color: #cbd5e1;
      max-width: 500px;
      margin-bottom: 28px;
    }

    .cta-buttons {
      display: flex;
      gap: 16px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 12px 28px;
      border-radius: 40px;
      font-weight: 600;
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      transition: all 0.25s;
      font-size: 1rem;
      border: none;
      cursor: pointer;
    }

    .btn-primary {
      background: #fbbf24;
      color: #0f172a;
      box-shadow: 0 8px 18px rgba(251, 191, 36, 0.35);
    }
    .btn-primary:hover {
      background: #f59e0b;
      transform: translateY(-2px);
    }

    .btn-outline {
      border: 2px solid #fbbf24;
      color: #fbbf24;
      background: transparent;
    }
    .btn-outline:hover {
      background: rgba(251, 191, 36, 0.1);
    }

    .hero-image {
      flex: 1 1 300px;
      text-align: center;
    }
    .hero-image img {
      max-width: 100%;
      height: auto;
      border-radius: 32px;
      box-shadow: 0 25px 40px rgba(0,0,0,0.4);
      border: 3px solid rgba(251, 191, 36, 0.3);
      background: #334155;
    }

    /* category pills */
    .section-title {
      font-size: 2rem;
      font-weight: 700;
      font-family: 'Montserrat', sans-serif;
      margin: 48px 0 24px;
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .section-title i {
      color: #f59e0b;
    }

    .category-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
      margin-bottom: 32px;
    }
    .category-pill {
      background: white;
      padding: 10px 24px;
      border-radius: 40px;
      font-weight: 600;
      color: #1e293b;
      box-shadow: 0 4px 12px rgba(0,0,0,0.03);
      display: flex;
      align-items: center;
      gap: 8px;
      transition: 0.2s;
      border: 1px solid #f1f5f9;
    }
    .category-pill i {
      color: #f59e0b;
    }
    .category-pill:hover {
      background: #fef3c7;
      border-color: #fbbf24;
    }

    /* cards grid */
    .cards-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 24px;
      margin: 24px 0 48px;
    }

    .card {
      background: white;
      border-radius: 28px;
      padding: 24px;
      box-shadow: 0 12px 28px rgba(0,0,0,0.04);
      transition: 0.25s ease;
      border: 1px solid #f1f5f9;
      display: flex;
      flex-direction: column;
    }
    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 24px 40px rgba(0,0,0,0.08);
    }
    .card-icon {
      font-size: 2.4rem;
      color: #f59e0b;
      margin-bottom: 16px;
    }
    .card h3 {
      font-size: 1.4rem;
      font-weight: 700;
      margin-bottom: 10px;
    }
    .card p {
      color: #4b5563;
      margin-bottom: 18px;
      flex: 1;
    }
    .tag {
      background: #fef3c7;
      color: #92400e;
      padding: 4px 14px;
      border-radius: 20px;
      font-size: 0.8rem;
      font-weight: 600;
      display: inline-block;
      align-self: flex-start;
    }

    .finance-highlight {
      background: linear-gradient(120deg, #fef9c3, #fde68a);
      border-left: 5px solid #f59e0b;
    }

    /* video/preview placeholder */
    .video-placeholder {
      background: #1e293b;
      border-radius: 24px;
      padding: 24px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 16px;
      margin: 32px 0;
      flex-wrap: wrap;
    }
    .play-btn {
      background: #fbbf24;
      color: #0f172a;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.8rem;
    }

    footer {
      background: #0f172a;
      color: #cbd5e1;
      padding: 40px 0 24px;
      margin-top: 48px;
      border-radius: 40px 40px 0 0;
    }
    .footer-content {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 32px;
    }
    .footer-links a {
      color: #94a3b8;
      text-decoration: none;
      margin-right: 20px;
    }
    .footer-links a:hover {
      color: #fbbf24;
    }

    @media (max-width: 700px) {
      .hero-text h1 {
        font-size: 2.4rem;
      }
      nav {
        flex-direction: column;
        align-items: flex-start;
        gap: 16px;
      }
    }
  </style>
</head>
<body>
  <div class="hero">
    <div class="container">
      <nav>
        <div class="logo">PREM.</div>
        <div class="nav-links">
          <a href="#daily"><i class="fas fa-calendar-day"></i> Daily Life</a>
          <a href="#fashion"><i class="fas fa-tshirt"></i> Fashion</a>
          <a href="#motivation"><i class="fas fa-fire"></i> Motivation</a>
          <a href="#finance"><i class="fas fa-chart-line"></i> Finance</a>
          <div class="social-top">
            <i class="fab fa-instagram"></i>
            <i class="fab fa-youtube"></i>
            <i class="fab fa-tiktok"></i>
          </div>
        </div>
      </nav>

      <div class="hero-content">
        <div class="hero-text">
          <h1>Prem <span class="highlight">Inspires</span> Your Everyday</h1>
          <p>Daily vlogs • Style tips • Wealth mindset • Real motivation. Join the journey to elevate your life.</p>
          <div class="cta-buttons">
            <a href="#" class="btn btn-primary"><i class="fab fa-youtube"></i> Watch Daily</a>
            <a href="#" class="btn btn-outline"><i class="fas fa-star"></i> Join Community</a>
          </div>
        </div>
        <div class="hero-image">
          <!-- Prem's representative image (modern influencer style) -->
          <img src="https://placehold.co/400x400/1e293b/fbbf24?text=PREM•OFFICIAL&font=montserrat" alt="Prem influencer style" style="width:100%; max-width:360px;">
        </div>
      </div>
    </div>
  </div>

  <main class="container">
    <!-- Categories quick view -->
    <div class="category-grid">
      <span class="category-pill"><i class="fas fa-mug-hot"></i> Morning Routine</span>
      <span class="category-pill"><i class="fas fa-tshirt"></i> OOTD</span>
      <span class="category-pill"><i class="fas fa-dumbbell"></i> Fitness</span>
      <span class="category-pill"><i class="fas fa-brain"></i> Mindset</span>
      <span class="category-pill"><i class="fas fa-coins"></i> Investing</span>
      <span class="category-pill"><i class="fas fa-camera"></i> Behind the scenes</span>
    </div>

    <!-- Daily Life Section -->
    <section id="daily">
      <h2 class="section-title"><i class="fas fa-sun"></i> Daily Life with Prem</h2>
      <div class="cards-grid">
        <div class="card">
          <div class="card-icon"><i class="fas fa-cloud-sun"></i></div>
          <h3>Morning Vlog</h3>
          <p>Starting the day at 5:30 AM with gratitude, green tea & planning. Real routine, no filters.</p>
          <span class="tag">#PremDaily</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-utensils"></i></div>
          <h3>What I Eat</h3>
          <p>High-protein vegetarian meals & hydration tips. Fueling the body for a productive day.</p>
          <span class="tag">#FuelWithPrem</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-city"></i></div>
          <h3>City Explorations</h3>
          <p>Exploring hidden cafes & street style. Bringing you along for everyday adventures.</p>
          <span class="tag">#PremExplores</span>
        </div>
      </div>
      <div class="video-placeholder">
        <div class="play-btn"><i class="fas fa-play"></i></div>
        <div><strong>Latest Daily Vlog:</strong> "A Real Day in My Life – Balance & Hustle" <br><small style="color:#fbbf24;">Click to watch on YouTube</small></div>
      </div>
    </section>

    <!-- Fashion Section -->
    <section id="fashion">
      <h2 class="section-title"><i class="fas fa-tshirt"></i> Fashion & Style</h2>
      <div class="cards-grid">
        <div class="card">
          <div class="card-icon"><i class="fas fa-gem"></i></div>
          <h3>Streetwear Lookbook</h3>
          <p>Affordable street style, layering hacks & seasonal essentials. Look sharp without breaking the bank.</p>
          <span class="tag">#PremStyle</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-glasses"></i></div>
          <h3>Accessories Game</h3>
          <p>Watches, sunglasses & minimal jewelry that elevate any outfit. Curated picks.</p>
          <span class="tag">#AccessoryGuide</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-shoe-prints"></i></div>
          <h3>Sneaker Collection</h3>
          <p>Latest sneaker reviews, cleaning tips & how to style iconic pairs.</p>
          <span class="tag">#SneakerPrem</span>
        </div>
      </div>
    </section>

    <!-- Motivation Section -->
    <section id="motivation">
      <h2 class="section-title"><i class="fas fa-fire"></i> Motivation & Mindset</h2>
      <div class="cards-grid">
        <div class="card">
          <div class="card-icon"><i class="fas fa-bullseye"></i></div>
          <h3>Monday Reset</h3>
          <p>Weekly intentions, goal setting & overcoming procrastination. Your push to start strong.</p>
          <span class="tag">#PremMotivation</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-book-open"></i></div>
          <h3>Book Lessons</h3>
          <p>Summaries from atomic habits to deep work. Practical wisdom in 60 seconds.</p>
          <span class="tag">#PremReads</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-comments"></i></div>
          <h3>Real Talk</h3>
          <p>Overcoming failure, self-doubt & building confidence. Unfiltered conversations.</p>
          <span class="tag">#RealWithPrem</span>
        </div>
      </div>
    </section>

    <!-- Finance Section (special highlight) -->
    <section id="finance">
      <h2 class="section-title"><i class="fas fa-chart-pie"></i> Finance & Wealth</h2>
      <div class="cards-grid">
        <div class="card finance-highlight">
          <div class="card-icon"><i class="fas fa-piggy-bank"></i></div>
          <h3>Budgeting 101</h3>
          <p>How I manage money with 50/30/20 rule. Track expenses & save for freedom.</p>
          <span class="tag">#PremFinance</span>
        </div>
        <div class="card finance-highlight">
          <div class="card-icon"><i class="fas fa-chart-line"></i></div>
          <h3>Investing Basics</h3>
          <p>Index funds, SIPs & starting with small amounts. Wealth building for beginners.</p>
          <span class="tag">#InvestWithPrem</span>
        </div>
        <div class="card finance-highlight">
          <div class="card-icon"><i class="fas fa-credit-card"></i></div>
          <h3>Side Hustles</h3>
          <p>Content creator income streams, freelancing & monetizing passion. Real numbers.</p>
          <span class="tag">#PremHustle</span>
        </div>
      </div>
      <div style="background: #fef9c7; border-radius: 20px; padding: 24px; margin: 24px 0; display: flex; align-items: center; gap: 16px; flex-wrap: wrap;">
        <i class="fas fa-lightbulb" style="font-size: 2.2rem; color: #b45309;"></i>
        <span style="font-weight: 600; font-size: 1.2rem;">Prem's Money Mantra:</span> "Earn, invest, and live below your means — then design a life you love."
      </div>
    </section>

    <!-- Extra: community / newsletter -->
    <div style="text-align: center; margin: 56px 0 32px;">
      <h3 style="font-size: 1.8rem; font-family: 'Montserrat', sans-serif;">Join the Prem Squad</h3>
      <p style="color: #4b5563; max-width: 500px; margin: 12px auto 24px;">Exclusive content, finance tips & early access to merch drops.</p>
      <div style="display: flex; justify-content: center; gap: 12px; flex-wrap: wrap;">
        <input type="email" placeholder="your@email.com" style="padding: 14px 20px; border-radius: 40px; border: 1px solid #d1d5db; width: 260px; font-size: 1rem;">
        <a href="#" class="btn btn-primary" style="padding: 14px 28px;">Subscribe</a>
      </div>
      <div style="margin-top: 24px; color: #6b7280; display: flex; justify-content: center; gap: 28px; font-size: 1.8rem;">
        <i class="fab fa-instagram"></i>
        <i class="fab fa-youtube"></i>
        <i class="fab fa-tiktok"></i>
        <i class="fab fa-twitter"></i>
      </div>
    </div>
  </main>

  <footer>
    <div class="container footer-content">
      <div>
        <div class="logo" style="font-size: 1.8rem; margin-bottom: 8px;">PREM.</div>
        <p>Influencer • Creator • Your daily dose of inspiration.</p>
      </div>
      <div class="footer-links">
        <a href="#">About Prem</a>
        <a href="#">Contact</a>
        <a href="#">Collaborations</a>
        <a href="#">Privacy</a>
      </div>
      <div>
        <p>© 2025 Prem. All rights reserved.</p>
        <p style="font-size:0.9rem;">Made with passion & creativity.</p>
      </div>
    </div>
  </footer>
</body>
</html>
