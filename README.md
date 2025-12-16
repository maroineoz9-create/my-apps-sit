# my-apps-sit
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="عالم التطبيقات – شرح تطبيقات أندرويد وحلول المشاكل التقنية">
  <title>عالم التطبيقات</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap');

    body {
      font-family: 'Cairo', Arial, sans-serif;
      margin: 0;
      background: #f9f9f9;
      direction: rtl;
      color: #333;
    }

    header {
      background: linear-gradient(90deg, #2196f3, #21cbf3);
      color: white;
      padding: 25px 15px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    header h1 { margin: 0 0 5px; font-size: 2.2em; }
    header p { margin: 0; font-size: 1.1em; opacity: 0.9; }

    nav { background: #333; text-align: center; }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
      padding: 12px 0;
      transition: all 0.3s ease;
    }
    nav a:hover {
      color: #ffeb3b;
      background: rgba(255,255,255,0.1);
      border-radius: 5px;
    }

    .container { max-width: 1000px; margin: 20px auto; padding: 0 15px; }

    .post {
      background: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .post:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    }

    .post img {
      width: 100%;
      border-radius: 10px;
      object-fit: cover;
    }

    .post h2 { margin-top: 0; color: #2196f3; }
    .post p { line-height: 1.6; }

    .post a {
      display: inline-block;
      margin-top: 10px;
      text-decoration: none;
      color: #fff;
      background: #2196f3;
      padding: 8px 15px;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .post a:hover { background: #21cbf3; }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }
    footer .social {
      margin-top: 10px;
    }
    footer .social a {
      color: white;
      margin: 0 8px;
      text-decoration: none;
      font-size: 1.2em;
      transition: color 0.3s;
    }
    footer .social a:hover { color: #ffeb3b; }

    @media (max-width: 600px) {
      nav a { display: block; margin: 5px 0; }
      header h1 { font-size: 1.8em; }
      .post { padding: 15px; }
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>

<body>

<header>
  <h1>عالم التطبيقات</h1>
  <p>شرح تطبيقات أندرويد وحلول المشاكل التقنية</p>
</header>

<nav>
  <a href="#">الرئيسية</a>
  <a href="#">تطبيقات</a>
  <a href="#">مشاكل وحلول</a>
  <a href="#">اتصل بنا</a>
</nav>

<div class="container">

  <!-- مقال التطبيقات المفيدة -->
  <div class="post">
    <img src="https://images.unsplash.com/photo-1581092795361-d3f5a233dc8d?auto=format&fit=crop&w=1000&q=80" alt="أفضل تطبيقات أندرويد">
    <h2>أفضل تطبيقات أندرويد المفيدة</h2>
    <p>في عالم الهواتف الذكية، هناك العديد من التطبيقات التي تسهل حياتك اليومية وتحسن إنتاجيتك. فيما يلي بعض التطبيقات المهمة:</p>
    <ul>
      <li><strong>تطبيقات الإنتاجية:</strong> مثل تطبيقات الملاحظات، تنظيم المهام والتقويم.</li>
      <li><strong>تطبيقات التواصل:</strong> مثل واتساب، تيليجرام، وماسنجر للتواصل السريع.</li>
      <li><strong>تطبيقات الصحة واللياقة:</strong> لمتابعة النشاط البدني والنوم والتغذية.</li>
      <li><strong>تطبيقات الأدوات:</strong> مثل مديري الملفات، الحماية، وأدوات تنظيف الهاتف.</li>
    </ul>
    <p>اختيار التطبيقات الصحيحة يوفر الوقت ويساعدك على تنظيم حياتك الرقمية بكفاءة.</p>
    <a href="#">اقرأ المزيد</a>
  </div>

  <!-- مقال حل مشكلة البطارية -->
  <div class="post">
    <img src="https://images.unsplash.com/photo-1612831455540-bf1b66d33c8b?auto=format&fit=crop&w=1000&q=80" alt="حل مشكلة نفاذ البطارية">
    <h2>حل مشكلة نفاذ البطارية بسرعة</h2>
    <p>يعاني كثير من مستخدمي الهواتف من نفاد البطارية بسرعة، إليك أهم الحلول العملية:</p>
    <ul>
      <li><strong>إغلاق التطبيقات في الخلفية:</strong> لتقليل استهلاك الطاقة.</li>
      <li><strong>تقليل سطوع الشاشة:</strong> الشاشة تستهلك معظم البطارية، ضبط السطوع يساعد كثيرًا.</li>
      <li><strong>تعطيل خدمات الموقع والبلوتوث:</strong> عند عدم الحاجة إليها لتقليل الاستهلاك.</li>
      <li><strong>استخدام وضع توفير الطاقة:</strong> معظم الهواتف تحتوي على هذا الوضع لتقليل الأداء واستهلاك الطاقة.</li>
    </ul>
    <p>بتطبيق هذه النصائح، يمكنك زيادة عمر بطارية هاتفك اليومي بشكل ملحوظ.</p>
    <a href="#">اقرأ المزيد</a>
  </div>

</div>

<footer>
  <p>© 2025 عالم التطبيقات</p>
  <div class="social">
    <a href="#"><i class="fab fa-facebook"></i></a>
    <a href="#"><i class="fab fa-twitter"></i></a>
    <a href="#"><i class="fab fa-whatsapp"></i></a>
    <a href="#"><i class="fab fa-instagram"></i></a>
  </div>
</footer>

</body>
</html>
