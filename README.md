
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>کالا خانه بارکد</title>
<style>
*{box-sizing:border-box}
body{margin:0;font-family:Tahoma;background:#f2f6fa;color:#142f46}
header{background:#12344f;color:white;text-align:center;padding:25px}
header h1{margin:5px}
.qr{background:white;width:170px;margin:15px auto;padding:12px;border-radius:12px;color:#12344f}
.qr img{width:145px;height:145px;display:block;margin:auto}
nav{text-align:center;background:white;padding:15px}
nav a{margin:7px;color:#12344f;text-decoration:none}
.hero{text-align:center;background:#17618a;color:white;padding:40px 15px;line-height:2}
button{background:#ffc044;border:0;padding:12px;border-radius:8px}
h2{text-align:center}
.products{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;padding:15px}
.card{background:white;border-radius:12px;text-align:center;overflow:hidden;text-decoration:none;color:#12344f;padding-bottom:12px}
.card img{width:100%;height:130px;object-fit:cover}
.info{background:white;margin:15px;padding:20px;text-align:center;line-height:2.3;border-radius:12px}
footer{background:#12344f;color:white;text-align:center;padding:20px}
@media(min-width:700px){.products{grid-template-columns:repeat(4,1fr)}}
</style>
</head>
<body>

<header>
<h1>کالا خانه بارکد</h1>
<p>فروشگاه لوازم خانگی و برقی</p>
<div class="qr">
<img id="siteQR" alt="QR Code کالا خانه بارکد">
<p>برای ورود به سایت اسکن کنید</p>
</div>
</header>

<nav>
<a href="#home">صفحه اصلی</a>
<a href="#categories">محصولات</a>
<a href="#about">درباره ما</a>
<a href="#contact">تماس با ما</a>
</nav>

<section class="hero" id="home">
<h2>به کالا خانه بارکد خوش آمدید</h2>
<p>معرفی محصولات خانگی و برقی</p>
<a href="#categories"><button>مشاهده محصولات</button></a>
</section>

<h2 id="categories">دسته‌بندی محصولات</h2>
<div class="products">
<a class="card" href="#kitchen">
<img src="https://images.unsplash.com/photo-1556911220-e15b29be8c8f?w=600" alt="لوازم آشپزخانه">
<h3>لوازم آشپزخانه</h3>
</a>
<a class="card" href="#washing">
<img src="https://images.unsplash.com/photo-1626806787461-102c1bfaaea1?w=600" alt="ماشین لباسشویی">
<h3>ماشین لباسشویی</h3>
</a>
<a class="card" href="#tv">
<img src="https://images.unsplash.com/photo-1593359677879-a4bb92f829d1?w=600" alt="تلویزیون">
<h3>تلویزیون و صوتی</h3>
</a>
<a class="card" href="#bedding">
<img src="https://images.unsplash.com/photo-1631049307264-da0ec9d70304?w=600" alt="پتو و تشک">
<h3>پتو و تشک</h3>
</a>
</div>

<section class="info" id="kitchen"><h2>لوازم آشپزخانه</h2><p>برای اطلاع از محصولات تماس بگیرید.</p></section>
<section class="info" id="washing"><h2>ماشین لباسشویی</h2><p>برای اطلاع از مدل‌ها تماس بگیرید.</p></section>
<section class="info" id="tv"><h2>تلویزیون و صوتی</h2><p>برای اطلاع از محصولات تماس بگیرید.</p></section>
<section class="info" id="bedding"><h2>پتو و تشک</h2><p>برای اطلاع از محصولات تماس بگیرید.</p></section>

<section class="info" id="about">
<h2>درباره فروشگاه</h2>
<p>هدف ما معرفی محصولات و ارائه خدمات مناسب به مشتریان عزیز است.</p>
<p>مدیریت: داورپناه</p>
</section>

<section class="info" id="contact">
<h2>تماس با فروشگاه</h2>
<p>📍 خوزستان، صیدون، فلکه شهدا</p>
<p>📞 09011889181</p>
<p>مدیریت: داورپناه</p>
<p><a href="https://www.instagram.com/gallery_barkod/">اینستاگرام: gallery_barkod</a></p>
<p><a href="https://wa.me/989011889181">🟢 ارتباط در واتساپ</a></p>
</section>

<footer>
<p>کالا خانه بارکد</p>
<p>طراحی و مدیریت: داورپناه</p>
<p>تمام حقوق محفوظ است.</p>
</footer>

<script>
const address="https://abolfazl1427.github.io/kala-khane-barkod1/";
document.getElementById("siteQR").src=
"https://quickchart.io/qr?size=200&text="+encodeURIComponent(address);
</script>

</body>
</html>
<!-- گالری لوازم آشپزخانه -->
<section class="info" id="kitchen-gallery">
<h2>گالری لوازم آشپزخانه</h2>
<div class="gallery">
<img src="images/kitchen1.jpg" alt="محصول آشپزخانه">
<img src="images/kitchen2.jpg" alt="محصول آشپزخانه">
<img src="images/kitchen3.jpg" alt="محصول آشپزخانه">
</div>
</section>

<!-- گالری ماشین لباسشویی -->
<section class="info" id="washing-gallery">
<h2>گالری ماشین لباسشویی</h2>
<div class="gallery">
<img src="images/washing1.jpg" alt="ماشین لباسشویی">
<img src="images/washing2.jpg" alt="ماشین لباسشویی">
<img src="images/washing3.jpg" alt="ماشین لباسشویی">
</div>
</section>

<!-- گالری تلویزیون -->
<section class="info" id="tv-gallery">
<h2>گالری تلویزیون و صوتی</h2>
<div class="gallery">
<img src="images/tv1.jpg" alt="تلویزیون">
<img src="images/tv2.jpg" alt="تلویزیون">
<img src="images/tv3.jpg" alt="تلویزیون">
</div>
</section>

<!-- گالری پتو و تشک -->
<section class="info" id="bedding-gallery">
<h2>گالری پتو و تشک</h2>
<div class="gallery">
<img src="images/bedding1.jpg" alt="پتو و تشک">
<img src="images/bedding2.jpg" alt="پتو و تشک">
<img src="images/bedding3.jpg" alt="پتو و تشک">
</div>
</section>



