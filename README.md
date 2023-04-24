<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DIGITAL MKT /title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <h1>Digital Marketing Company</h1>
    <p>Boost Your Online Presence & make your company a BRAND with Us</p>
  </header>

  <main>
    <section class="services">
      <h2>Our Services</h2>
      <ul>
        <li>SEO</li>
        <li>Social Media Marketing</li>
        <li>Website Creation</li>
        <li>Email Marketing</li>
        <li>Content Marketing</li>
      </ul>
    </section>

    <section class="about">
      <h2>About Us</h2>
      <p>Currently,I am student who has completed a Digital Marketing Course & can provide a range of services to help you reach your target audience and achieve your goals to help your businesses grow and succeed online.</p>
    </section>

    <section class="contact">
      <h2>Contact Us</h2>
      <form action="submit-form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Digital Marketing Company. All rights reserved.</p>
  </footer>
</body>
</html>
