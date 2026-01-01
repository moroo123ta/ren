<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>معرض المنتجات</title>
  <style>
:root{
  --main:#e91e63;
  --dark:#111;
  --light:#fff;
  --bg:#faf6f8;
}
*{box-sizing:border-box}
body{font-family:'Tahoma',Arial;margin:0;background:var(--bg);color:#333}
header{
  background:linear-gradient(135deg,#e91e63,#ff8a80);
  color:#fff;padding:70px 20px;text-align:center
}
header h1{margin:0;font-size:40px;letter-spacing:2px}
header p{margin-top:15px;font-size:20px}
section{padding:50px 20px;max-width:1200px;margin:auto}
h2{font-size:28px;margin-bottom:30px;color:var(--main);text-align:center}
.products{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:25px
}
.card{
  background:#fff;
  border-radius:18px;
  box-shadow:0 10px 25px rgba(0,0,0,.12);
  padding:18px;
  text-align:center;
  transition:.3s ease
}
.card:hover{transform:translateY(-8px)}
.card img{
  width:100%;
  border-radius:15px;
  height:260px;
  object-fit:cover
}
.card h3{margin:18px 0 10px;font-size:20px}
.card p{font-size:14px;color:#666}
.price{font-weight:bold;margin:12px 0;color:var(--main)}
.btn{
  display:inline-block;
  margin-top:12px;
  padding:12px 26px;
  background:#25D366;
  color:#fff;
  text-decoration:none;
  border-radius:30px;
  font-size:15px
}
.about,.contact{
  background:#fff;
  border-radius:20px;
  box-shadow:0 10px 25px rgba(0,0,0,.1);
  padding:35px;
  margin-top:40px
}
.about p,.contact p{font-size:16px;line-height:1.9;text-align:center}
footer{text-align:center;padding:25px;background:#111;color:#fff;margin-top:60px}
</style>
</head>
<body>

<header>
  <h1>رين</h1>
  <p>مواد تجميل نسائية مختارة بعناية لإبراز جمالك</p>
</header>

<section>
  <h2>الأكثر طلبًا ⭐</h2>
  <div class="products">
    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="منتج مميز">
      <h3>منتج مميز</h3>
      <p>من أكثر منتجات رين طلبًا من الزبونات.</p>
      <div class="price">حسب الطلب</div>
      <a class="btn" href="https://wa.me/212672058905">اطلبي عبر واتساب</a>
    </div>
  </div>
</section>

<section>
  <h2>منتوجاتنا</h2>
  <div class="products">
    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="منتج 1">
      <h3>اسم المنتج</h3>
      <p>وصف مختصر وجذاب للمنتج.</p>
      <div class="price">حسب الطلب</div>
      <a class="btn" href="https://wa.me/212672058905">اطلب عبر واتساب</a>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="منتج 2">
      <h3>اسم المنتج</h3>
      <p>وصف مختصر وجذاب للمنتج.</p>
      <div class="price">حسب الطلب</div>
      <a class="btn" href="https://wa.me/212672058905">اطلب عبر واتساب</a>
    </div>
  </div>
</section>

<section class="about">
  <h2>من نحن</h2>
  <p>
    مشروع رين متخصص في مواد التجميل النسائية، نحرص على اختيار منتجات ذات جودة عالية وبأسعار مناسبة، مع اهتمام كبير برضا الزبونات والثقة المتبادلة.
  </p>
</section>

<section class="contact">
  <h2>تواصل معنا</h2>
  <p>📞 الهاتف / واتساب: 0672058905</p>
  <p>📍 المغرب</p>
</section>

<footer>
  <p>© 2026 جميع الحقوق محفوظة</p>
</footer>

</body>
</html>
