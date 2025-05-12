index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Blog</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="blog.html">Blog</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>Welcome to My Blog</h1>
  </header>

  <main>
    <section>
      <h2>Latest Posts</h2>
      <article>
        <h3>Post Title 1</h3>
        <p>This is a preview of the blog post...</p>
        <button onclick="readMore()">Read More</button>
      </article>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Blog</p>
  </footer>

  <script src="js/script.js"></script>
</body>
</html>
styles.css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

nav {
  background-color: #333;
  padding: 10px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
}

header, footer {
  text-align: center;
  padding: 20px;
  background-color: #f4f4f4;
}

@media (max-width: 600px) {
  nav ul {
    flex-direction: column;
  }
}
script.js
function readMore() {
  alert("Redirecting to full blog post...");
  // You can also redirect using: window.location.href = 'blog.html';
}
