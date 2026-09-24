<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>فهمني | مساعدك التعليمي</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f5f7fb;
            color: #222;
        }

        header {
            background: #ffffff;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.08);
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
            color: #2563eb;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin-right: 20px;
        }

        .hero {
            text-align: center;
            padding: 90px 20px;
            background: linear-gradient(135deg, #2563eb, #7c3aed);
            color: white;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        .button {
            display: inline-block;
            background: white;
            color: #2563eb;
            padding: 14px 30px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: bold;
        }

        .section {
            padding: 60px 8%;
            text-align: center;
        }

        .section h2 {
            font-size: 32px;
            margin-bottom: 40px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }

        .card h3 {
            color: #2563eb;
            margin-bottom: 15px;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #111827;
            color: white;
        }
    </style>
</head>

<body>

<header>
    <div class="logo">فهمني</div>

    <nav>
        <a href="#">الرئيسية</a>
        <a href="#subjects">المواد</a>
        <a href="#about">عن فهمني</a>
    </nav>
</header>

<section class="hero">
    <h1>فهمني 📚</h1>

    <p>
        منصة تعليمية تساعدك تفهم دروسك بطريقة سهلة وبسيطة
    </p>

    <a href="#subjects" class="button">
        ابدأ التعلم
    </a>
</section>

<section class="section" id="subjects">

    <h2>اختر المادة</h2>

    <div class="cards">

        <div class="card">
            <h3>📐 الرياضيات</h3>
            <p>شرح المسائل والقوانين بطريقة بسيطة.</p>
        </div>

        <div class="card">
            <h3>🔬 العلوم</h3>
            <p>فهم الدروس والمعلومات العلمية بسهولة.</p>
        </div>

        <div class="card">
            <h3>📖 اللغة العربية</h3>
            <p>شرح النحو والقراءة والبلاغة.</p>
        </div>

        <div class="card">
            <h3>🌍 الدراسات</h3>
            <p>مساعدة الطلاب على فهم التاريخ والجغرافيا.</p>
        </div>

    </div>
</section>

<section class="section" id="about">

    <h2>عن فهمني</h2>

    <p>
        فهمني هو موقع تعليمي هدفه مساعدة الطلاب على الوصول
        إلى المعلومة وفهم الدروس بطريقة سهلة وسريعة.
    </p>

</section>

<footer>
    © 2026 فهمني - جميع الحقوق محفوظة
</footer>

</body>
</html>
