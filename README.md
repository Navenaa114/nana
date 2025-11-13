<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Priya Sharma - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
  
  <style>
    /* Global Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #fafafa;
    }

    header {
      background: #222;
      color: #fff;
      padding: 1rem 0;
    }

    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1100px;
      margin: auto;
      padding: 0 1rem;
    }

    .logo {
      font-size: 1.5rem;
      font-weight: 700;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 1rem;
    }

    .nav-links a {
      text-decoration: none;
      color: #fff;
      transition: color 0.3s ease;
    }

    .nav-links a:hover {
      color: #ff9800;
    }

    /* Main Sections */
    section {
      max-width: 1100px;
      margin: 2rem auto;
      padding: 1rem;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    section h2 {
      text-align: center;
      margin-bottom: 1rem;
      color: #333;
    }

    #services p {
      text-align: center;
    }

    /* Skills */
    .skills-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      list-style: none;
      gap: 1rem;
      margin-top: 1rem;
    }

    .skills-list li {
      background: #ff9800;
      color: #fff;
      padding: 0.5rem 1rem;
      border-radius: 20px;
      font-weight: bold;
    }

    /* Portfolio */
    .portfolio-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      margin-top: 1rem;
    }

    .portfolio-item {
      background: #f0f0f0;
      border-radius: 10px;
      text-align: center;
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .portfolio-item:hover {
      transform: scale(1.03);
    }

    .portfolio-item img {
      width: 100%;
      height: auto;
    }

    .portfolio-item h3 {
      padding: 0.5rem;
      background: #fff;
      margin-top: -5px;
    }

    /* Testimonial */
    #testimonial {
      background: #ff9800;
      color: #fff;
      text-align: center;
      padding: 2rem 1rem;
      border-radius: 10px;
      max-width: 1100px;
      margin: 2rem auto;
    }

    #testimonial blockquote {
      font-style: italic;
      margin-bottom: 1rem;
    }

    #testimonial cite {
      font-weight: bold;
    }

    /* Contact Form */
    .contact-form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 600px;
      margin: auto;
    }

    .contact-form label {
      font-weight: bold;
    }

    .contact-form input,
    .contact-form textarea {
      padding: 0.8rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
      width: 100%;
    }

    .contact-form button {
      background: #222;
      color: #fff;
      padding: 0.8rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s ease;
      font-weight: bold;
    }

    .contact-form button:hover {
      background: #ff9800;
    }

    /* Footer */
    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
      margin-top: 2rem;
    }

    /* Responsive Navbar */
    @media (max-width: 768px) {
      .nav-links {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <nav class="navbar">
      <div class="logo">Priya Sharma</div>
      <ul class="nav-links">
        <li><a href="#services" class="nav-link">Services</a></li>
        <li><a href="#skills" class="nav-link">Skills</a></li>
        <li><a href="#portfolio" class="nav-link">Portfolio</a></li>
        <li><a href="#contact" class="nav-link">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="services">
      <h2>Services</h2>
      <p>Professional web design and development services, including responsive design, UI/UX improvements, and branding.</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul class="skills-list">
        <li>HTML5 & CSS3</li>
        <li>JavaScript & jQuery</li>
        <li>React & Vue.js</li>
        <li>Responsive & Mobile Design</li>
        <li>SEO Best Practices</li>
      </ul>
    </section>

    <section id="portfolio">
      <h2>Portfolio</h2>
      <div class="portfolio-gallery">
        <article class="portfolio-item">
          <img src="https://via.placeholder.com/300x200" alt="Project 1" />
          <h3>Project 1</h3>
        </article>
        <article class="portfolio-item">
          <img src="https://via.placeholder.com/300x200" alt="Project 2" />
          <h3>Project 2</h3>
        </article>
        <article class="portfolio-item">
          <img src="https://via.placeholder.com/300x200" alt="Project 3" />
          <h3>Project 3</h3>
        </article>
        <article class="portfolio-item">
          <img src="https://via.placeholder.com/300x200" alt="Project 4" />
          <h3>Project 4</h3>
        </article>
      </div>
    </section>

    <aside id="testimonial">
      <h2>Testimonial</h2>
      <blockquote>"Priya transformed our website with her exceptional design and attention to detail. Highly recommended!"</blockquote>
      <cite>- Client Name</cite>
    </aside>

    <section id="contact">
      <h2>Contact</h2>
      <form class="contact-form" action="#" method="post">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" placeholder="Your name" required />

        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="Your email" required />

        <label for="message">Message</label>
        <textarea id="message" name="message" placeholder="Your message" rows="5" required></textarea>

        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Priya Sharma. All rights reserved.</p>
  </footer>
</body>
</html>
