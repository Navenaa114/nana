<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Priya Sharma - Portfolio</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
  <!-- External CSS -->
  <link rel="stylesheet" href="style.css" />
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
        <article class="portfolio-item"><img src="https://via.placeholder.com/300x200" alt="Project 1" />
          <h3>Project 1</h3>
        </article>
        <article class="portfolio-item"><img src="https://via.placeholder.com/300x200" alt="Project 2" />
          <h3>Project 2</h3>
        </article>
        <article class="portfolio-item"><img src="https://via.placeholder.com/300x200" alt="Project 3" />
          <h3>Project 3</h3>
        </article>
        <article class="portfolio-item"><img src="https://via.placeholder.com/300x200" alt="Project 4" />
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