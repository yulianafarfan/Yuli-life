<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yuli's Blog</title>
  <style>
    :root {
      --bg: #f9f8f6;
      --text: #333;
      --accent: #d4cfc9;
      --link: #6e6e6e;
    }

    body {
      margin: 0;
      font-family: "Helvetica Neue", sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 10;
      background-color: var(--bg);
      padding: 1.5rem 1rem 1rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      text-align: center;
    }

    header h1 {
      font-size: 2.2rem;
      margin: 0.3rem 0;
    }

    header p {
      font-size: 1rem;
      color: var(--link);
      margin: 0.2rem 0 0.8rem;
    }

    nav {
      margin-top: 0.5rem;
    }

    nav a {
      margin: 0 12px;
      text-decoration: none;
      color: var(--link);
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      max-width: 700px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    article {
      background-color: white;
      padding: 1.5rem;
      margin-bottom: 2rem;
      border-left: 4px solid var(--accent);
      box-shadow: 0 1px 4px rgba(0,0,0,0.05);
    }

    article h2 {
      margin-top: 0;
    }

    footer {
      text-align: center;
      font-size: 0.9rem;
      color: var(--link);
      margin: 4rem 1rem 1rem;
    }

    .socials a {
      margin: 0 0.5rem;
      text-decoration: none;
      color: var(--link);
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }

      nav a {
        display: inline-block;
        margin: 0.3rem 6px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Yuli's Blog</h1>
    <p>Life as a MILSO & Stay-at-Home Mom</p>
    <nav>
      <a href="#posts">Blog</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="posts">
      <article>
        <h2>Welcome to My Blog</h2>
        <p>Hi! I'm Yuli — a military SO, stay-at-home mama, and lover of cozy mornings and quiet strength. This is my space to share pieces of my everyday: motherhood moments, the ups and downs of military life, and small joys that make life beautiful.</p>
      </article>

      <article>
        <h2>How I Balance SAHM Life with Military Life</h2>
        <p><em>Posted July 27, 2025</em></p>
        <p>Being a stay-at-home mom while supporting a partner in the military can feel like juggling invisible weights. But routines, support systems, and grace make all the difference. Here's how I make space for myself, even in the chaos.</p>
      </article>
    </section>

    <section id="about">
      <article>
        <h2>About Me</h2>
        <p>I'm Yuli — currently based in Germany, raising my little one while holding down the homefront. I write to connect, reflect, and breathe life into the everyday. Whether you're a fellow MILSO, a tired mama, or someone just passing by, I'm glad you're here.</p>
      </article>
    </section>

    <section id="contact">
      <article>
        <h2>Contact</h2>
        <p>I'd love to connect! You can reach out or follow along here:</p>
        <div class="socials">
          <a href="mailto:youremail@example.com">Email</a>
          <a href="https://instagram.com/yourhandle" target="_blank">Instagram</a>
          <a href="https://www.pinterest.com/yourhandle" target="_blank">Pinterest</a>
        </div>
      </article>
    </section>
  </main>

  <footer>
    &copy; 2025 Yuli's Blog — All rights reserved
  </footer>
</body>
</html>