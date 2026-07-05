<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Article — The Writer's Portfolio</title>
<link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>W</text></svg>">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Manrope:wght@600;700;800&family=Poppins:wght@500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/styles.css">
</head>
<body>

<a href="#main" class="skip-link">Skip to content</a>

<header class="nav" id="nav">
  <div class="container nav-inner">
    <a href="index.html" class="logo">The Writer's <span>Portfolio</span></a>
    <nav class="nav-links" id="navLinks" aria-label="Primary">
      <a href="category.html?cat=lifestyle">Lifestyle</a>
      <a href="category.html?cat=tech">Tech</a>
      <a href="category.html?cat=news">News</a>
      <a href="category.html?cat=career">Career</a>
      <a href="category.html?cat=health">Health</a>
      <a href="category.html?cat=kids-sports">Kids Sports</a>
      <a href="portfolio.html">Portfolio</a>
    </nav>
    <div class="nav-actions">
      <button class="icon-btn" id="searchOpen" aria-label="Search articles">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="7"/><path d="M21 21l-4.3-4.3"/></svg>
      </button>
      <button class="icon-btn nav-toggle" id="navToggle" aria-label="Toggle menu">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 6h18M3 12h18M3 18h18"/></svg>
      </button>
    </div>
  </div>
</header>

<div class="search-overlay" id="searchOverlay">
  <div class="search-panel">
    <div class="search-input-row">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="7"/><path d="M21 21l-4.3-4.3"/></svg>
      <input type="text" id="searchInput" placeholder="Search articles, topics, categories…" autocomplete="off">
      <button class="search-close" id="searchClose" aria-label="Close search">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6L6 18M6 6l12 12"/></svg>
      </button>
    </div>
    <div class="search-results" id="searchResults"></div>
  </div>
</div>

<main id="main">
  <div id="articleRoot"></div>
</main>

<footer class="footer">
  <div class="container">
    <div class="footer-grid">
      <div class="footer-bio">
        <a href="index.html" class="logo">The Writer's <span>Portfolio</span></a>
        <p>A digital publication and writing portfolio covering technology, culture, career, health, and family life.</p>
      </div>
      <div class="footer-social">
        <a href="https://instagram.com" target="_blank" rel="noopener" aria-label="Instagram"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1"/></svg></a>
        <a href="https://linkedin.com" target="_blank" rel="noopener" aria-label="LinkedIn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/><path d="M10 9v12M10 13a4 4 0 018 0v8"/></svg></a>
        <a href="https://x.com" target="_blank" rel="noopener" aria-label="X"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4l16 16M20 4L4 20"/></svg></a>
        <a href="mailto:manalamja@gmail.com" aria-label="Email"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="M2 7l10 6 10-6"/></svg></a>
      </div>
    </div>
    <div class="footer-bottom">
      <span>&copy; <span id="year"></span> The Writer's Portfolio. All rights reserved.</span>
      <span>Built with GitHub.</span>
    </div>
  </div>
</footer>

<script src="js/site.js" defer></script>
<script src="js/article.js" defer></script>
</body>
</html>
