<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Book Services</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #232124;
      color: #e2e2e2;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #5d3764;
      padding: 20px;
      text-align: center;
      color: #fcac31;
    }

    header h1 {
      margin: 0;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      padding: 20px;
      justify-content: center;
    }

    .card {
      background-color: #b9832c;
      color: #232124;
      width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
      overflow: hidden;
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 10px rgba(0, 0, 0, 0.4);
    }

    .card-header {
      background-color: #844890;
      padding: 10px;
      color: #e2e2e2;
      font-size: 18px;
      font-weight: bold;
    }

    .card-body {
      padding: 15px;
    }

    .card-body p {
      margin: 10px 0;
      font-size: 14px;
    }

    .card-footer {
      background-color: #5d3764;
      color: #fcac31;
      padding: 10px;
      font-size: 14px;
      font-weight: bold;
    }

    button {
      background-color: #fcac31;
      color: #232124;
      border: none;
      padding: 10px 20px;
      margin-top: 10px;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s, transform 0.2s;
    }

    button:hover {
      background-color: #b9832c;
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <header>
    <h1>AI Book Services</h1>
  </header>
  <div class="container">
    <div class="card">
      <div class="card-header">تلخيص الكتب</div>
      <div class="card-body">
        <p>أدخل كتابًا للحصول على ملخص دقيق وسريع حسب السياق (أكاديمي أو عام).</p>
        <button>ابدأ الآن</button>
      </div>
      <div class="card-footer">استخدام GPT-4</div>
    </div>
    <div class="card">
      <div class="card-header">قراءة الكتب بالصوت</div>
      <div class="card-body">
        <p>حوّل النصوص إلى مقاطع صوتية بجودة عالية مع خيارات نبرة وسرعة متعددة.</p>
        <button>ابدأ الآن</button>
      </div>
      <div class="card-footer">تقنية Text-to-Speech</div>
    </div>
    <div class="card">
      <div class="card-header">الترجمة الاحترافية</div>
      <div class="card-body">
        <p>ترجم الكتب بدقة واحترافية مع خيارات التدقيق اللغوي.</p>
        <button>ابدأ الآن</button>
      </div>
      <div class="card-footer">DeepL & Google Translate</div>
    </div>
  </div>
</body>
</html>
