<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sakib Gaming</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #111;
      color: #fff;
    }
    header {
      background: #222;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
    }
    section {
      padding: 20px;
    }
    .review {
      background: #333;
      margin: 10px 0;
      padding: 15px;
      border-radius: 8px;
    }
    form {
      background: #333;
      padding: 20px;
      border-radius: 8px;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: none;
      border-radius: 5px;
    }
    button {
      padding: 10px 20px;
      background: #00bfff;
      border: none;
      border-radius: 5px;
      color: #fff;
      cursor: pointer;
      margin-top: 10px;
    }
    footer {
      background: #222;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Sakib Gaming</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#reviews">Game Reviews</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home">
    <h2>About Us</h2>
    <p>Sakib Gaming is your go-to hub for the latest game reviews, news, and tips.</p>
  </section>

  <section id="reviews">
    <h2>Latest Game Reviews</h2>
    <div class="review">
      <h3>Game Title 1</h3>
      <p>This game is packed with action and adventure. Highly recommended!</p>
    </div>
    <div class="review">
      <h3>Game Title 2</h3>
      <p>A great mix of strategy and storytelling. Worth playing!</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Sakib Gaming. All rights reserved.</p>
  </footer>
</body>

