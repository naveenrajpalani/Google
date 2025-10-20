<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Google Search (Mini)</title>
  <link rel="stylesheet" href="styles.css">
  <script defer src="script.js"></script>
</head>
<body>
  <header class="toplinks">
    <nav>
      <a href="images.html">Images</a>
      <a href="advanced.html">Advanced Search</a>
    </nav>
  </header>

  <main class="home">
    <!-- Optional logo area (you can replace with an <img> if you like) -->
    <div class="logo-placeholder" aria-hidden="true"></div>

    <!-- Main search form: action to google search; name="q" is the required parameter -->
    <form id="searchForm" class="search-form" action="https://www.google.com/search" method="get" target="_self">
      <input type="text" name="q" id="q" class="search-input" placeholder="Search Google or type a URL" required autocomplete="off">

      <div class="buttons">
        <button type="submit" class="btn primary">Google Search</button>
        <!-- I'm Feeling Lucky — name="btnI" triggers Google's immediate-first-result behavior -->
        <button type="submit" name="btnI" value="I" class="btn lucky">I'm Feeling Lucky</button>
      </div>
    </form>

    <p class="helper">This is a minimal Google-style page for demonstration.</p>
  </main>

  <footer class="footer">
    <small>Mini Google — demo page</small>
  </footer>
</body>
</html>
