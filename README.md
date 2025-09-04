<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>کارت ویزیت علی</title>
  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Vazirmatn', sans-serif;
      /* پشت زمینه جدید با گرادیانت و الگو */
      background: radial-gradient(circle at top left, #f0f4f8, #d9e2ec);
      background-image: repeating-radial-gradient(circle, rgba(200, 220, 240, 0.1) 0px, rgba(200, 220, 240, 0.1) 20px, transparent 20px, transparent 40px);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 12px 30px rgba(0,0,0,0.2);
      text-align: center;
      width: 360px;
      animation: fadeIn 1s ease-in-out;
    }
    .msg1 {
      font-weight: bold;
      margin-bottom: 16px;
      font-size: 18px;
    }
    .msg2 {
      font-size: 14px;
      color: green;
      margin-bottom: 15px;
    }
    .msg3 {
      font-size: 14px;
      margin-bottom: 15px;
    }
    .msg4 {
      font-size: 12px;
      color: red;
      margin-bottom: 20px;
    }
    .links-container {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 10px;
    }
    .link-box {
      flex: 1 1 calc(50% - 10px);
      margin: 5px 0;
      padding: 12px;
      border-radius: 20px;
      background: #3498db;
      color: white;
      text-decoration: none;
      font-size: 16px;
      transition: 0.3s;
      box-shadow: 0 4px 8px rgba(0,0,0,0.15);
      text-align: center;
    }
    .link-box:hover {
      transform: translateY(-3px);
      background: #2ecc71;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="msg1">دفتر پیشخوان دولتی و بخش عمومی</div>
    <div class="msg2">از حسن توجه شما بسیار سپاسگذاریم</div>
    <div class="msg3">تمامی ثبت نام های اینترنتی، ثبت نام کنکور، تعویض پلاک و ...</div>
    <div class="msg4">روستایی _ شماره مجوز 1125-7311-(ICT)</div>

    <div class="links-container">
      <a class="link-box" href="https://sapp.ir/ashrafi_c_net" target="_blank">سروش</a>
      <a class="link-box" href="https://wa.me/989148172072" target="_blank">واتساپ</a>
      <a class="link-box" href="tel:+984432551422">تماس تلفنی</a>
    </div>
  </div>
</body>
</html>
