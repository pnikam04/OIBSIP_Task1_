# OIBSIP_Task1_LandingPage
I Developed this Landing Page using HTML &amp; CSS , JAVA SCRIPT
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>VPN</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: "Montserrat", sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f9f9f9;
        color: #333;
      }
      header {
        background: linear-gradient(135deg, #6e8efb, #a777e3);
        color: #fff;
        text-align: center;
        padding: 100px 20px;
        position: relative;
        border-bottom: 10px solid #fff;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      }
      header h1 {
        font-size: 3rem;
        margin-bottom: 10px;
      }
      header p {
        font-size: 1.2rem;
        margin-bottom: 20px;
      }
      .cta-button {
        background-color: #28a745;
        color: #fff;
        padding: 15px 30px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 1rem;
        transition: background-color 0.3s ease;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      }
      .cta-button:hover {
        background-color: #218838;
      }
      .section {
        padding: 60px 20px;
        text-align: center;
        border-bottom: 1px solid #ddd;
      }
      .section h2 {
        font-size: 2rem;
        margin-bottom: 20px;
        position: relative;
      }
      .section h2::after {
        content: "";
        width: 50px;
        height: 4px;
        background-color: #6e8efb;
        position: absolute;
        bottom: -10px;
        left: 50%;
        transform: translateX(-50%);
      }
      .section p {
        font-size: 1.1rem;
        margin-bottom: 20px;
        color: #555;
      }
      .features {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        gap: 20px;
      }
      .feature {
        background: #fff;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        width: 300px;
        text-align: left;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        border: 1px solid #ddd;
      }
      .feature:hover {
        transform: translateY(-10px);
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
      }
      .feature img {
        max-width: 100%;
        height: auto;
        margin-bottom: 20px;
        border-radius: 10px;
      }
      .feature h3 {
        font-size: 1.5rem;
        margin-bottom: 10px;
        color: #6e8efb;
      }
      .feature p {
        font-size: 1rem;
        color: #666;
      }
      .map-section {
        background: #f0f0f0;
        padding: 60px 20px;
        text-align: center;
      }
      .map-section h2 {
        font-size: 2rem;
        margin-bottom: 20px;
      }
      .map-section .map {
        width: 100%;
        height: auto;
        max-width: 600px;
        margin: 0 auto;
        border: 5px solid #ddd;
        border-radius: 10px;
      }
      .map-section .stats {
        display: flex;
        justify-content: center;
        gap: 30px;
        margin-top: 20px;
      }
      .stats div {
        font-size: 1.2rem;
        background: #fff;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        border: 1px solid #ddd;
      }
      .footer {
        background: #333;
        color: #fff;
        text-align: center;
        padding: 20px;
        border-top: 10px solid #fff;
        box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.1);
      }
    </style>
  </head>
  <body>
    <header>
      <h1>The VPN that just works</h1>
      <p>Go further with the #1 trusted leader in VPN</p>
      <button class="cta-button">Get ExpressVPN</button>
    </header>
    <section class="section">
      <h2>Secure access, worldwide</h2>
      <p>
        Connect reliably from anywhere, to anywhere. Our network of high-speed
        servers across 94 countries puts you in control.
      </p>
      <button class="cta-button">Get ExpressVPN</button>
    </section>
    <section class="section features">
      <div class="feature">
        <img src="https://via.placeholder.com/300" alt="Secure Access" />
        <h3>Secure access</h3>
        <p>Details about secure access.</p>
      </div>
      <div class="feature">
        <img src="https://via.placeholder.com/300" alt="Easy to Use" />
        <h3>One click to a safer internet</h3>
        <p>Details about one-click safety.</p>
      </div>
      <div class="feature">
        <img src="https://via.placeholder.com/300" alt="Every Device" />
        <h3>Use on every device</h3>
        <p>Details about device compatibility.</p>
      </div>
    </section>
    <section class="section map-section">
      <h2>Ultra-fast servers around the globe</h2>
      <img
        class="map"
        src="https://via.placeholder.com/600x300"
        alt="Global Coverage"
      />
      <div class="stats">
        <div><strong>160</strong><br />locations</div>
        <div><strong>94</strong><br />countries</div>
        <div><strong>∞</strong><br />unlimited bandwidth</div>
      </div>
    </section>
    <footer class="footer">
      <p>&copy; 2024 My Landing Page. All rights reserved.</p>
    </footer>
  </body>
</html>
