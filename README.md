<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>B&M HARDWARE LTD</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f8f9fa; }
    header { background: #004080; color: white; padding: 20px; text-align: center; position: relative; }
    header .logo {
      position: absolute;
      right: 20px;
      top: 10px;
      background-color: yellow;
      clip-path: polygon(50% 0%, 100% 100%, 0% 100%);
      padding: 25px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    header .logo h2 {
      color: #004080;
      margin: 0;
      font-size: 32px;
      font-weight: bold;
    }
    header .logo span {
      color: #004080;
      font-size: 12px;
      margin-top: 5px;
      font-weight: bold;
    }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    #hero { background: #e6f0ff; text-align: center; }
    .btn { display: inline-block; margin-top: 20px; padding: 10px 20px; background: #004080; color: white; border-radius: 5px; text-decoration: none; }
    #services ul { list-style-type: square; }
    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .gallery img { width: 100%; height: auto; border-radius: 10px; }
    form input, form textarea { width: 100%; padding: 10px; margin-bottom: 10px; border-radius: 5px; border: 1px solid #ccc; }
    form button { background: #004080; color: white; border: none; padding: 10px 15px; border-radius: 5px; }
    .whatsapp-button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background-color: #25D366;
      color: white;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
    footer { background: #004080; color: white; text-align: center; padding: 20px; }
  </style>
</head>
<body>
  <header>
    <h1>B&M HARDWARE LTD</h1>
    <div class="logo">
      <h2>B&amp;M</h2>
      <span>HARDWARE</span>
    </div>
    <nav>
      <a href="#hero">Home</a>
      <a href="#services">Services</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="hero">
    <h2>Welcome to B&M HARDWARE LTD</h2>
    <p>Your trusted supplier of hardware accessories, building materials, welding, and quincaillerie.</p>
    <img src="https://i.imgur.com/zY3aQx2.jpg" alt="Thinner Basco" style="max-width:100%; height:auto; border-radius: 10px; margin: 20px auto;">
    <img src="https://i.imgur.com/k9DpmMa.jpg" alt="Body Filler P38" style="max-width:100%; height:auto; border-radius: 10px; margin: 20px auto;">
    <img src="/mnt/data/ANTIRUST.jpg" alt="Gloss Enamel" style="max-width:100%; height:auto; border-radius: 10px; margin: 20px auto;">
    <img src="/mnt/data/DISC RHODIUS.jpg" alt="Cutting Disc Rhodius" style="max-width:100%; height:auto; border-radius: 10px; margin: 20px auto;">
    <img src="/mnt/data/VIS SELF.jpg" alt="Self Drilling Screw" style="max-width:100%; height:auto; border-radius: 10px; margin: 20px auto;">
    <a class="btn" href="#contact">Contact Us</a>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Hardware Accessories</li>
      <li>Building Materials</li>
      <li>Welding Services</li>
      <li>Quincaillerie Supplies</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Product Showcase</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Welding+Rod" alt="Welding Rod">
      <img src="https://i.imgur.com/k9DpmMa.jpg" alt="Body Filler P38">
      <img src="/mnt/data/VIS SELF.jpg" alt="Self Drilling Screw">
      <img src="https://i.imgur.com/zY3aQx2.jpg" alt="Thinner Basco">
      <img src="/mnt/data/DISC RHODIUS.jpg" alt="Cutting Disc Rhodius">
      <img src="/mnt/data/ANTIRUST.jpg" alt="Gloss Enamel">
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Email:</strong> benjaminmukiza123@gmail.com</p>
    <p><strong>Phone:</strong> +250787793741 / +250789049741</p>
    <p><strong>Address:</strong> GAKINJIRO COPCOM</p>
    <p><strong>WhatsApp:</strong> +250787793741</p>
    <p><strong>Instagram:</strong> BEN MUKIZA</p>

    <form action="https://formsubmit.co/benjaminmukiza123@gmail.com" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>

    <a href="https://wa.me/250787793741" class="whatsapp-button" target="_blank">Message Us on WhatsApp</a>
  </section>

  <footer>
    <p>&copy; 2025 B&M HARDWARE LTD. All rights reserved.</p>
  </footer>
</body>
</html>
