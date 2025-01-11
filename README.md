# html-landing-page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="TimeMaster - A time management tool to help you boost productivity">
  <title>TimeMaster - Boost Your Productivity</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      color: #333;
      margin: 0;
    }

    /* Header */
    header {
      background-color: #333;
      padding: 20px;
      text-align: center;
      color: #fff;
    }

    header .logo img {
      width: 150px;
    }

    /* Hero Section */
    #hero {
      background: url('https://via.placeholder.com/1600x600') no-repeat center center/cover;
      color: #fff;
      text-align: center;
      padding: 100px 20px;
    }

    #hero h1 {
      font-size: 48px;
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
    }

    /* Features Section */
    #features {
      background-color: #f9f9f9;
      padding: 60px 20px;
    }

    #features h2 {
      text-align: center;
      margin-bottom: 40px;
    }

    .features-list {
      display: flex;
      justify-content: space-around;
      text-align: center;
    }

    .feature {
      width: 30%;
    }

    .feature h3 {
      margin-bottom: 10px;
    }

    /* CTA Section */
    #cta {
      background-color: #333;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    #cta h2 {
      margin-bottom: 20px;
    }

    /* Testimonials Section */
    #testimonials {
      padding: 60px 20px;
    }

    .testimonials {
      display: flex;
      justify-content: space-around;
    }

    .testimonial {
      width: 40%;
      font-style: italic;
      text-align: center;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px 0;
    }

    footer .social-links a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }

    footer .social-links a:hover {
      color: #ff6600;
    }

    /* Responsive */
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
      <p>The all-in-one tool that helps you manage time and tasks effectively.</p>
      <a href="#cta" class="cta-button">Get Started</a>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features">
    <h2>Why Choose TimeMaster?</h2>
    <div class="features-list">
      <div class="feature">
        <h3>Easy to Use</h3>
        <p>Simplified task management for busy professionals.</p>
      </div>
      <div class="feature">
        <h3>Advanced Analytics</h3>
        <p>Track your time and see where you can improve.</p>
      </div>
      <div class="feature">
        <h3>Team Collaboration</h3>
        <p>Work seamlessly with your team, no matter where they are.</p>
      </div>
    </div>
  </section>

  <!-- Call-to-Action Section -->
  <section id="cta">
    <h2>Ready to Take Control of Your Time?</h2>
    <p>Sign up now and start boosting your productivity today!</p>
    <a href="#signup" class="cta-button">Sign Up Now</a>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials">
    <h2>What Our Users Say</h2>
    <div class="testimonials">
      <div class="testimonial">
        <p>"TimeMaster helped me manage my tasks and improved my team's productivity!"</p>
        <cite>- Sarah Lee, Project Manager</cite>
      </div>
      <div class="testimonial">
        <p>"I can't imagine my workday without TimeMaster. It's an essential tool for our business."</p>
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
/* Global styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  line-height: 1.6;
  color: #333;
  margin: 0;
}

/* Header */
header {
  background-color: #333;
  padding: 20px;
  text-align: center;
  color: #fff;
}

header .logo img {
  width: 150px;
}

/* Hero Section */
#hero {
  background: url('https://via.placeholder.com/1600x600') no-repeat center center/cover;
  color: #fff;
  text-align: center;
  padding: 100px 20px;
}

#hero h1 {
  font-size: 48px;
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
  background-color: #f9f9f9;
  padding: 60px 20px;
}

#features h2 {
  text-align: center;
  margin-bottom: 40px;
}

.features-list {
  display: flex;
  justify-content: space-around;
  text-align: center;
}

.feature {
  width: 30%;
}

.feature h3 {
  margin-bottom: 10px;
}

.feature p {
  font-size: 16px;
  color: #555;
}

/* Call-to-Action Section */
#cta {
  background-color: #333;
  color: white;
  padding: 60px 20px;
  text-align: center;
}

#cta h2 {
  margin-bottom: 20px;
}

/* Testimonials Section */
#testimonials {
  padding: 60px 20px;
}

.testimonials {
  display: flex;
  justify-content: space-around;
}

.testimonial {
  width: 40%;
  font-style: italic;
  text-align: center;
  margin-bottom: 30px;
}

.testimonial cite {
  display: block;
  margin-top: 10px;
  color: #555;
  font-size: 14px;
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

/* Responsive Styles */
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
