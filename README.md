<!DOCTYPE html>
<html lang="he">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>אייל פרץ | המרכז לנכסים</title>
  <style>
    body {
      background: #181818;
      color: #fff;
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      direction: rtl;
    }
    .bsd {
      position: absolute;
      right: 18px;
      top: 12px;
      font-size: 0.94em;
      color: #ff8000;
      font-weight: bold;
      letter-spacing: 2px;
      opacity: 0.88;
      z-index: 2;
      background: rgba(24,24,24,0.7);
      padding: 2px 10px 2px 4px;
      border-radius: 8px;
      font-family: 'Segoe UI', Arial, sans-serif;
      box-shadow: 0 1px 6px rgba(0,0,0,0.12);
    }
    .profile-photo {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 36px;
      margin-bottom: 12px;
    }
    .profile-photo img {
      width: 136px;
      height: 136px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #ff8000;
      box-shadow: 0 2px 12px rgba(0,0,0,0.17);
      background: #fff;
    }
    .logo-bar {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 8px;
      margin-bottom: 18px;
    }
    .logo-bar img {
      max-width: 260px;
      max-height: 84px;
      width: auto;
      height: auto;
      border-radius: 12px;
      background: #fff;
      box-shadow: 0 1px 8px rgba(0,0,0,0.10);
      padding: 4px 12px;
    }
    .header {
      background: #181818;
      padding: 0 0 0 0;
      text-align: center;
      border-bottom: 6px solid #ff8000;
    }
    .header h1 {
      margin: 0;
      font-size: 2.1em;
      font-weight: bold;
      letter-spacing: 1px;
    }
    .header .subtitle {
      color: #ccc;
      font-size: 1.13em;
      margin-bottom: 8px;
    }
    .profile {
      text-align: center;
      margin: 22px 0 10px 0;
    }
    .profile h2 {
      margin: 0 0 8px;
      font-size: 1.45em;
    }
    .profile .license {
      color: #fff;
      background: #ff8000;
      display: inline-block;
      padding: 4px 12px;
      border-radius: 12px;
      font-weight: bold;
      margin-bottom: 10px;
      font-size: 1em;
    }
    .profile p {
      margin: 0 0 6px;
      color: #ff8000;
      font-size: 1.09em;
    }
    .contact {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
      margin-bottom: 25px;
      margin-top: 12px;
    }
    .contact a {
      background: #ff8000;
      color: #fff;
      padding: 12px 24px;
      border-radius: 22px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.09em;
      transition: background 0.2s;
      margin: 3px 0;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
    }
    .contact a:hover { background: #ffa94d; }
    .wa-channel {
      text-align: center;
      margin: 18px 0 0 0;
    }
    .wa-channel a {
      background: #25D366;
      color: #fff;
      padding: 10px 22px;
      border-radius: 22px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.07em;
      transition: background 0.2s;
      display: inline-block;
      margin-top: 7px;
    }
    .wa-channel a:hover {
      background: #1ebc59;
    }
    .info {
      background: #222;
      margin: 0 auto 24px auto;
      padding: 18px 18px 12px 18px;
      border-radius: 16px;
      max-width: 350px;
      box-shadow: 0 2px 12px rgba(0,0,0,0.16);
      text-align: right;
    }
    .info p { margin: 5px 0; direction: rtl; }
    .slogan {
      text-align: center;
      background: #ff8000;
      color: #fff;
      font-weight: bold;
      font-size: 1.12em;
      padding: 10px 0;
      margin-top: 18px;
      letter-spacing: 1px;
    }
    @media (max-width: 600px) {
      .info { max-width: 98vw; }
      .header h1 { font-size: 1.2em; }
      .profile h2 { font-size: 1em; }
      .contact a, .wa-channel a { font-size: 1em; padding: 10px 10px; }
      .profile-photo img { width: 92px; height: 92px; }
      .logo-bar img { max-width: 180px; max-height: 60px;}
      .bsd { right: 8px; top: 6px; font-size: 0.89em;}
    }
  </style>
</head>
<body>
  <div class="bsd">בס"ד</div>
  <div class="profile-photo">
    <img src="profile.jpg" alt="תמונה אישית">
  </div>
  <div class="logo-bar">
    <img src="logo.png" alt="לוגו המרכז לנכסים">
  </div>
  <div class="header">
    <h1>המרכז לנכסים</h1>
    <div class="subtitle">יזמות ושיווק נדל"ן</div>
  </div>
  <div class="profile">
    <h2>אייל פרץ</h2>
    <div class="license">רישיון תיווך: 3984852</div>
    <p>יועץ נדל"ן ומגשר מוסמך</p>
  </div>
  <div class="contact">
    <a href="tel:0525421411">התקשר עכשיו</a>
    <a href="https://wa.me/972525421411" target="_blank">שלח הודעת וואטסאפ</a>
    <a href="mailto:perezcenter@gmail.com">שלח דוא"ל</a>
  </div>
  <div class="wa-channel">
    <span>לערוץ יעוץ נדל"ן בוואטסאפ:</span><br>
    <a href="https://whatsapp.com/channel/0029Vb5hjuT5Ejxrcy6fkB2X" target="_blank">כניסה לערוץ</a>
  </div>
  <div class="info">
    <p><strong>טלפון נוסף:</strong> 08-9453649</p>
    <p><strong>כתובת:</strong> אחד העם 2, רחובות</p>
    <p><strong>אימייל:</strong> perezcenter@gmail.com</p>
  </div>
  <div class="slogan">
    הופך חלום למציאות
  </div>
</body>
</html>
