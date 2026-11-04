<img src="images/barcode.png" alt="لوگوی کالا خانه بارکد" width="150">
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>گالری بارکد | فروشگاه لوازم خانگی</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;
 font-family:Tahoma,sans-serif;
 background:#f5f5f5;
 color:#222;
}
header{
 background:#111;
 color:white;
 text-align:center;
 padding:25px 15px;
 border-bottom:6px solid #ffd400;
}
.barcode{
 display:flex;
 justify-content:center;
 gap:3px;
 height:75px;
 margin:0 auto 15px;
 max-width:310px;
 align-items:stretch;
 background:#ffd400;
 padding:9px;
 border-radius:8px;
}
.barcode span{background:#111;height:100%}
header h1{color:#ffd400;margin:10px 0}
header p{color:#fff;margin:8px}
nav{
 background:#ffd400;
 padding:12px;
 text-align:center;
}
nav a{
 color:#111;
 text-decoration:none;
 font-weight:bold;
 margin:8px;
}
.container{padding:20px;max-width:1100px;margin:auto}
.hero{
 background:linear-gradient(120deg,#111,#333);
 color:white;
 text-align:center;
 padding:35px 15px;
 border-radius:15px;
}
.hero h2{color:#ffd400}
.btn{
 display:inline-block;
 background:#ffd400;
 color:#111;
 padding:12px 22px;
 margin:8px;
 border-radius:8px;
 text-decoration:none;
 font-weight:bold;
}
.section-title{
 border-right:6px solid #ffd400;
 padding-right:12px;
 margin-top:30px;
}
#categoryList{
 display:none;
 grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
 gap:15px;
 margin-top:20px;
}
.category{
 background:white;
 border:2px solid #ffd400;
 border-radius:12px;
 padding:20px;
 text-align:center;
 box-shadow:0 3px 10px #0001;
}
.category .emoji{font-size:42px}
.category h3{margin:10px 0}
.category p{font-size:13px;color:#666}
button{
 border:0;
 cursor:pointer;
 font-family:inherit;
}
.toggle{
 background:#111;
 color:#ffd400;
 padding:14px 25px;
 border-radius:9px;
 font-weight:bold;
 font-size:16px;
}
.contact{
 background:#111;
 color:white;
 text-align:center;
 padding:25px;
 margin-top:30px;
 border-top:5px solid #ffd400;
 border-radius:12px;
}
.contact a{color:#ffd400;text-decoration:none}
footer{
 background:#111;
 color:#bbb;
 text-align:center;
 padding:18px;
 margin-top:20px;
 font-size:13px;
}
</style>
</head>
<body>

<header>
 <div class="barcode" aria-label="طرح تزئینی بارکد">
  <span style="width:3px"></span>
  <span style="width:8px"></span>
  <span style="width:2px"></span>
  <span style="width:5px"></span>
  <span style="width:10px"></span>
  <span style="width:3px"></span>
  <span style="width:7px"></span>
  <span style="width:2px"></span>
  <span style="width:9px"></span>
  <span style="width:4px"></span>
  <span style="width:6px"></span>
  <span style="width:2px"></span>
  <span style="width:8px"></span>
  <span style="width:3px"></span>
  <span style="width:11px"></span>
  <span style="width:4px"></span>
  <span style="width:2px"></span>
  <span style="width:7px"></span>
 </div>
 <h1>گالری بارکد</h1>
 <p>زیبایی و کیفیت در انتخاب شما</p>
</header>

<nav>
 <a href="#home">صفحه اصلی</a>
 <a href="#categories">دسته‌بندی محصولات</a>
 <a href="#contact">تماس با ما</a>
</nav>

<div class="container" id="home">
 <section class="hero">
  <h2>به گالری بارکد خوش آمدید</h2>
  <p>دنیایی از لوازم خانگی و محصولات متنوع</p>
  <a class="btn" href="#categories">مشاهده محصولات</a>
 </section>

 <section id="categories">
  <h2 class="section-title">دسته‌بندی محصولات</h2>
  <button class="toggle" onclick="toggleCategories()">
   ☰ نمایش دسته‌بندی‌ها
  </button>

  <div id="categoryList">
   <div class="category">
    <div class="emoji">🍳</div>
    <h3>لوازم آشپزخانه</h3>
    <p>انواع وسایل آشپزخانه</p>
   </div>
   <div class="category">
    <div class="emoji">📺</div>
    <h3>تلویزیون و صوتی</h3>
    <p>محصولات صوتی و تصویری</p>
   </div>
   <div class="category">
    <div class="emoji">🧺</div>
    <h3>ماشین لباسشویی</h3>
    <p>انواع لوازم شست‌وشو</p>
   </div>
   <div class="category">
    <div class="emoji">🛏️</div>
    <h3>پتو و تشک</h3>
    <p>محصولات خواب و استراحت</p>
   </div>
   <div class="category">
    <div class="emoji">🧹</div>
    <h3>نظافت منزل</h3>
    <p>وسایل نظافت و خانه‌داری</p>
   </div>
   <div class="category">
    <div class="emoji">💡</div>
    <h3>لوازم برقی</h3>
    <p>انواع وسایل برقی</p>
   </div>
  </div>
 </section>

 <section class="contact" id="contact">
  <h2>ارتباط با گالری بارکد</h2>
  <p>📍 خوزستان، صیدون، فلکه شهدا</p>
  <p>مدیریت: داورپناه</p>
  <p>📞 <a href="tel:09011889181">09011889181</a></p>
  <a class="btn" href="https://wa.me/989011889181">واتساپ</a>
  <a class="btn" href="https://instagram.com/gallery_barkod">اینستاگرام</a>
  <p>آیدی اینستاگرام: gallery_barkod</p>
 </section>
</div>

<footer>
 © گالری بارکد - تمامی حقوق محفوظ است
</footer>

<script>
function toggleCategories(){
 const list=document.getElementById("categoryList");
 const button=document.querySelector(".toggle");
 const visible=list.style.display==="grid";
 list.style.display=visible?"none":"grid";
 button.textContent=visible?
 "☰ نمایش دسته‌بندی‌ها":"✕ بستن دسته‌بندی‌ها";
}
</script>
</body>
</html>




