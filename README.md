<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tech2Future Picks</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Tech2Future Picks</h1>
    <p>Curated tools for smarter living — powered by Leon Bland</p>
  </header>

  <section class="products">
    <div class="product-card">
      <img src="images/ai-tool.jpg" alt="AI Productivity Tool" />
      <h2>AI Productivity Suite</h2>
      <p>Boost your workflow with this intuitive AI assistant.</p>
      <a href="https://affiliate-link.com/ai-tool" target="_blank">Explore Now</a>
    </div>

    <div class="product-card">
      <img src="images/solar-kit.jpg" alt="Solar Starter Kit" />
      <h2>Solar Starter Kit</h2>
      <p>Clean energy at your fingertips — perfect for beginners.</p>
      <a href="https://affiliate-link.com/solar-kit" target="_blank">Shop Solar</a>
    </div>

    <!-- Add more product cards here -->
  </section>

  <footer>
    <p>© 2025 Tech2Future Solutions, LLC</p>
  </footer>
</body>
</html>

body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  background-color: #f4f8fc;
  color: #333;
}

header {
  background-color: #004080;
  color: white;
  padding: 2rem;
  text-align: center;
}

.products {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 2rem;
}

.product-card {
  background: white;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  margin: 1rem;
  padding: 1rem;
  width: 300px;
  text-align: center;
}

.product-card img {
  max-width: 100%;
  border-radius: 4px;
}

.product-card a {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.5rem 1rem;
  background-color: #0077cc;
  color: white;
  text-decoration: none;
  border-radius: 4px;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #e0e0e0;
}
// Future enhancement: Load products dynamically
fetch('products.json')
  .then(res => res.json())
  .then(data => {
    // Render product cards dynamically
  });
