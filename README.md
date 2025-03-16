<!DOCTYPE html>
<html lang="he">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>נטייל בלי דאגות – כלבך תמיד שמח!</title>
  <style>
    /* Reset some default styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f0f8f0;
      color: #333;
      direction: rtl; /* Right-to-left for Hebrew */
    }
    header {
      background: url('https://via.placeholder.com/1200x600?text=Hero+Image') center/cover no-repeat;
      height: 80vh;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    header::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.4);
    }
    header h1 {
      position: relative;
      color: #fff;
      font-size: 3em;
      padding: 0 20px;
    }
    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #444;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      margin-bottom: 40px;
    }
    .service {
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      margin: 10px;
      flex: 1 1 220px;
      padding: 20px;
      text-align: center;
    }
    .service h3 {
      margin-bottom: 10px;
      color: #2a7a2a;
    }
    form {
      max-width: 600px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
    }
    form input, form textarea {
      margin-bottom: 15px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1em;
    }
    form button {
      padding: 12px;
      background: #2a7a2a;
      color: #fff;
      border: none;
      border-radius: 4px;
      font-size: 1em;
      cursor: pointer;
    }
    form button:hover {
      background: #246c24;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header>
    <h1>נטייל בלי דאגות – כלבך תמיד שמח!</h1>
  </header>

  <!-- Services Section -->
  <section id="services">
    <h2>השירותים שלנו</h2>
    <div class="services">
      <div class="service">
        <h3>טיולי כלבים</h3>
        <p>סיורים קבועים להבטחת פעילות וכיף לכלבך.</p>
      </div>
      <div class="service">
        <h3>ביקורי ביניים</h3>
        <p>ביקורים קצרים לשמירה על מצב רוח טוב ובריאות.</p>
      </div>
      <div class="service">
        <h3>מפגשי גורים</h3>
        <p>פעילויות חברתיות לגורים להנאה ולחינוך.</p>
      </div>
      <div class="service">
        <h3>מחירים מיוחדים</h3>
        <p>הנחות למספר כלבים וחבילות לטווח ארוך.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>צור קשר</h2>
    <p style="text-align: center;">טלפון: <strong>(555) 123-4567</strong> | אתר: <strong>www.dogwalks.com</strong></p>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="שמך" required>
      <input type="email" name="email" placeholder="האימייל שלך" required>
      <textarea name="message" rows="5" placeholder="הודעה" required></textarea>
      <button type="submit">שלח הודעה</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 נטייל בלי דאגות. כל הזכויות שמורות.</p>
  </footer>

</body>
</html>
