<script>

</script>

<main class="container">
  <header class="hero">
    <h1>Developer Hub</h1>
    <p class="subtitle">Your gateway to building exceptional applications</p>
  </header>

  <section class="features">
    <div class="feature-card">
      <h2>Documentation</h2>
      <p>Comprehensive guides and API references to help you build better applications.</p>
    </div>

    <div class="feature-card">
      <h2>Resources</h2>
      <p>Access tools, libraries, and best practices to accelerate your development.</p>
    </div>

    <div class="feature-card">
      <h2>Community</h2>
      <p>Join our developer community to share knowledge and get support.</p>
    </div>
  </section>
</main>

<style>
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
  }

  .hero {
    text-align: center;
    padding: 4rem 0;
  }

  h1 {
    font-size: 3rem;
    color: #2c3e50;
    margin-bottom: 1rem;
  }

  .subtitle {
    font-size: 1.5rem;
    color: #666;
    margin-bottom: 2rem;
  }

  .features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
  }

  .feature-card {
    background: white;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease;
  }

  .feature-card:hover {
    transform: translateY(-5px);
  }

  .feature-card h2 {
    color: #2c3e50;
    margin-bottom: 1rem;
  }

  .feature-card p {
    color: #666;
    margin-bottom: 1.5rem;
    line-height: 1.6;
  }

  .button {
    display: inline-block;
    padding: 0.8rem 1.5rem;
    background-color: #3498db;
    color: white;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.2s ease;
  }

  .button:hover {
    background-color: #2980b9;
  }

  @media (max-width: 768px) {
    .container {
      padding: 1rem;
    }

    h1 {
      font-size: 2.5rem;
    }

    .subtitle {
      font-size: 1.2rem;
    }
  }
</style>
