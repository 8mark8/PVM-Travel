<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f0f4f8;
    color: #333;
    margin: 0;
    padding: 0;
  }
  #villas {
    padding: 40px 20px;
    background-color: #e0ecf4;
    text-align: center;
  }
  #villas h2 {
    font-size: 2.5rem;
    margin-bottom: 30px;
    color: #2c3e50;
  }
  .villas {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    max-width: 1200px;
    margin: 0 auto;
  }
  .villa {
    background-color: #ffffff;
    border-radius: 12px;
    padding: 20px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s;
  }
  .villa:hover {
    transform: translateY(-5px);
  }
  .villa img {
    max-width: 100%;
    border-radius: 8px;
    margin-bottom: 15px;
  }
  .villa h3 {
    color: #34495e;
    margin: 10px 0;
    font-size: 1.3rem;
  }
  .villa p {
    color: #555;
    font-size: 1rem;
    margin-bottom: 10px;
  }
  .villa a {
    display: inline-block;
    padding: 10px 20px;
    background-color: #3498db;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    transition: background-color 0.3s;
  }
  .villa a:hover {
    background-color: #2c80b4;
  }
</style>

<section id="villas">
  <h2>Featured Villas</h2>
  <div class="villas">
    <!-- Property cards (unchanged, already in document) -->
    ...
  </div>
</section>

    <p>&copy; 2025 PVM Travel. All rights reserved.</p>
  </footer>
</body>
</html>
