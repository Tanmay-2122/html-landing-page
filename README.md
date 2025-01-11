#first landing page html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="TimeMaster - A time management tool to help you boost productivity">
  <meta name="author" content="Your Company">
  <title>TimeMaster - Boost Your Productivity</title>
  <style>
    /* Global Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Body & Font */
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f4f4f4;
    }

    h1, h2, h3, p {
      margin-bottom: 20px;
    }

    /* Header */
    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header .logo img {
      width: 150px;
    }

    /* Hero Section */
    #hero {
      background: url('https://via.placeholder.com/1600x800') no-repeat center center/cover;
      color: #fff;
      text-align: center;
      padding: 120px 20px;
    }

    #hero h1 {
      font-size: 48px;
      font-weight: 700;
      margin-bottom: 20px;
    }

    #hero p {
      font-size: 20px;
      margin-bottom: 40px;
    }

    .cta-button {
      background-color: #ff6600;
      color: white;
      padding: 15px 30px;
      font-size: 20px;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .cta-button:hover {
      background-color: #e55b00;
    }

    /* Features Section */
    #features {
      padding: 60px 20px;
      text-align: center;
      background-color: #fff;
    }

    #features h2 {
      font-size: 36px;
      margin-bottom: 40px;
    }

    .features-list {
      display: flex;
      justify-content: space-around;
      text-align: center;
    }

    .feature {
      width: 30%;
      padding: 20px;
    }

    .feature h3 {
      font-size: 24px;
      margin-bottom: 10px;
    }

    .feature p {
      font-size: 16px;
      color: #555;
    }

    /* Call to Action Section */
    #cta {
      background-color: #333;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    #cta h2 {
      margin-bottom: 20px;
      font-size: 32px;
    }

    /* Testimonials Section */
    #testimonials {
      padding: 60px 20px;
      background-color: #f9f9f9;
    }

    .testimonials {
      display: flex;
      justify-content: space-around;
      text-align: center;
    }

    .testimonial {
      width: 40%;
      font-style: italic;
      margin-bottom: 30px;
    }

    .testimonial cite {
      display: block;
      margin-top: 10px;
      color: #555;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px 0;
    }

    footer p {
      margin-bottom: 10px;
    }

    footer .social-links a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }

    footer .social-links a:hover {
      color: #ff6600;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .features-list {
        flex-direction: column;
        align-items: center;
      }

      .feature {
        width: 80%;
        margin-bottom: 20px;
      }

      .testimonials {
        flex-direction: column;
        align-items: center;
      }

      .testimonial {
        width: 80%;
        margin-bottom: 20px;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">
      <img src="https://via.placeholder.com/150x50" alt="TimeMaster Logo">
    </div>
  </header>

  <!-- Hero Section -->
  <section id="hero">
    <div>
      <h1>Boost Your Productivity with TimeMaster</h1>
      <p>Manage your time better, increase your focus, and get more done with TimeMaster.</p>
      <a href="#cta" class="cta-button">Get Started</a>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features">
    <h2>Why Choose TimeMaster?</h2>
    <div class="features-list">
      <div class="feature">
        <h3>Easy to Use</h3>
        <p>Our intuitive interface makes it easy for anyone to get started right away.</p>
      </div>
      <div class="feature">
        <h3>Powerful Insights</h3>
        <p>Get real-time analytics on how you're spending your time to improve productivity.</p>
      </div>
      <div class="feature">
        <h3>Seamless Collaboration</h3>
        <p>Work together with your team, no matter where they are, and stay aligned.</p>
      </div>
    </div>
  </section>

  <!-- Call-to-Action Section -->
  <section id="cta">
    <h2>Ready to Take Control of Your Time?</h2>
    <p>Sign up today to start optimizing your workflow and boost your productivity!</p>
    <a href="#signup" class="cta-button">Sign Up Now</a>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials">
    <h2>What Our Users Say</h2>
    <div class="testimonials">
      <div class="testimonial">
        <p>"TimeMaster is a game-changer! It has transformed the way my team works."</p>
        <cite>- Sarah Lee, Project Manager</cite>
      </div>
      <div class="testimonial">
        <p>"I’ve never been this productive! TimeMaster keeps me on track and focused."</p>
        <cite>- John Smith, CEO of TechWorks</cite>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 TimeMaster. All rights reserved.</p>
    <div class="social-links">
      <a href="https://facebook.com" target="_blank">Facebook</a>
      <a href="https://twitter.com" target="_blank">Twitter</a>
      <a href="https://linkedin.com" target="_blank">LinkedIn</a>
    </div>
  </footer>

</body>
</html>
