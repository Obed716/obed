<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>عبيد - مبرمج مواقع</title>
  <style>
    /* الأساسيات */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.8;
      background-color: #f8f9fa;
      color: #333;
    }
    h1, h2 {
      margin-bottom: 20px;
    }
    p {
      margin: 0 0 15px;
    }
    section {
      padding: 50px 20px;
    }
    /* شريط التنقل */
    header {
      background-color: #004aad;
      padding: 15px 0;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    header a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    header a:hover {
      color: #ffd700;
    }
    /* الفواصل */
    .divider {
      height: 5px;
      background: linear-gradient(to right, #004aad, #ffd700);
      margin: 0 auto 20px;
      width: 80px;
      border-radius: 5px;
    }
    /* الأقسام */
    #about {
      background-color: #f4f4f4;
      text-align: center;
    }
    #skills {
      background-color: #eafaff;
      text-align: center;
    }
    #services {
      background-color: #fdf5d8;
      text-align: center;
    }
    #contact {
      background-color: #ffffff;
      text-align: center;
    }
    /* الصناديق */
    .service-box {
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      width: 250px;
      margin: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .service-box:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
    }
    .services-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    /* نموذج التواصل */
    input, textarea, button {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #004aad;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #003080;
    }
  </style>
</head>
<body>
  <!-- شريط التنقل -->
  <header>
    <nav>
      <a href="#about">من أنا</a>
      <a href="#skills">مهاراتي</a>
      <a href="#services">خدماتي</a>
      <a href="#contact">تواصل معي</a>
    </nav>
  </header>

  <!-- قسم من أنا -->
  <section id="about">
    <h1>مرحبًا! أنا عبيد</h1>
    <div class="divider"></div>
    <p>
      عمري 23 عامًا، وأنا مبرمج مواقع متخصص في تصميم وتطوير مواقع إلكترونية حديثة ومتجاوبة. أمتلك خبرة في إنشاء واجهات مستخدم جذّابة وتجربة مستخدم سلسة، بالإضافة إلى برمجة النظم الخلفية باستخدام أحدث التقنيات.
    </p>
  </section>

  <!-- قسم مهاراتي -->
  <section id="skills">
    <h2>مهاراتي</h2>
    <div class="divider"></div>
    <ul style="list-style: none; padding: 0;">
      <li><strong>تصميم واجهات المستخدم (UI):</strong> تصميم مبتكر لتجارب مميزة.</li>
      <li><strong>تطوير الواجهات الأمامية (Front-End):</strong> باستخدام HTML، CSS، JavaScript مع React وBootstrap.</li>
      <li><strong>تطوير الواجهات الخلفية (Back-End):</strong> برمجة الخوادم بـ PHP وقواعد البيانات MySQL.</li>
      <li><strong>تحسين الأداء (Optimization):</strong> تحسين سرعة وأداء المواقع.</li>
    </ul>
  </section>

  <!-- قسم خدماتي -->
  <section id="services">
    <h2>خدماتي</h2>
    <div class="divider"></div>
    <div class="services-container">
      <div class="service-box">
        <h3>تصميم المواقع</h3>
        <p>أُصمّم مواقع جذابة تسهّل على المستخدم التنقل.</p>
      </div>
      <div class="service-box">
        <h3>تطوير المواقع</h3>
        <p>برمجة حلول ويب حديثة تلبي احتياجات العملاء.</p>
      </div>
      <div class="service-box">
        <h3>تحسين الأداء</h3>
        <p>تحسين سرعة الموقع وأدائه ليعمل بكفاءة عالية.</p>
      </div>
    </div>
  </section>

  <!-- قسم تواصل معي -->
  <section id="contact">
    <h2>تواصل معي</h2>
    <div class="divider"></div>
    <p>يمكنك التواصل معي عبر النموذج التالي:</p>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="اسمك" required>
      <input type="email" name="email" placeholder="بريدك الإلكتروني" required>
      <textarea name="message" rows="4" placeholder="رسالتك" required></textarea>
      <button type="submit">إرسال</button>
    </form>
  </section>
</body>
</html>
