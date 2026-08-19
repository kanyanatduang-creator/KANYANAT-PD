<html lang="th"><head></head><body>```html



<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MINI BRACELET</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f8f8f8;
    color:#333;
}

header{
    background:white;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    box-shadow:0 2px 10px rgba(0,0,0,.05);
}

.logo{
    font-size:28px;
    font-weight:bold;
    letter-spacing:3px;
}

nav a{
    text-decoration:none;
    color:#333;
    margin-left:25px;
}

.hero{
    height:85vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    background:linear-gradient(to bottom,#ffffff,#efefef);
}

.hero h1{
    font-size:60px;
    margin-bottom:15px;
}

.hero p{
    font-size:18px;
    color:#666;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:14px 35px;
    background:black;
    color:white;
    text-decoration:none;
    border-radius:30px;
}

section{
    padding:70px 8%;
}

.title{
    text-align:center;
    font-size:34px;
    margin-bottom:50px;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
}

.card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card img{
    width:100%;
    height:260px;
    object-fit:cover;
}

.card-content{
    padding:20px;
    text-align:center;
}

.price{
    margin:12px 0;
    font-size:22px;
    font-weight:bold;
}

button{
    background:black;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:25px;
    cursor:pointer;
}

.about{
    background:white;
    text-align:center;
    line-height:1.8;
}

footer{
    background:black;
    color:white;
    text-align:center;
    padding:25px;
}

@media(max-width:768px){

.hero h1{
font-size:42px;
}

}
</style>




<header>

<div class="logo">KANYANAT PD</div>

<nav>
<a href="#">หน้าแรก</a>
<a href="#">สินค้า</a>
<a href="#">เกี่ยวกับ</a>
<a href="#">ติดต่อ</a>
</nav>

</header>

<section class="hero">

<div>

<h1>Minimal Bracelet</h1>

<p>กำไลข้อมือเรียบง่าย ใส่ได้ทุกวัน</p>

<a href="#product" class="btn">เลือกซื้อสินค้า</a>

</div>

</section>

<section id="product">

<h2 class="title">สินค้าแนะนำ</h2>

<div class="products">

<div class="card">

<img src="images/2d3c898a0077bc10561a6a0732acfc2f.jfif" alt="">

<div class="card-content">

<h3>NOVA</h3>

<p class="price">฿1,300</p>

<button>สั่งซื้อ</button>

</div>

</div>

<div class="card">

<img src="images/dew].avif" alt="">

<div class="card-content">

<h3>MIRA</h3>

<p class="price">฿1,400</p>

<button>สั่งซื้อ</button>

</div>

</div>

<div class="card">

<img src="images/105B0396-01.jpg" alt="">

<div class="card-content">

<h3>LUNE</h3>

<p class="price">฿1,200</p>

<button>สั่งซื้อ</button>

</div>

</div>

</div>

</section>

<section class="about">

<h2 class="title">เกี่ยวกับร้าน</h2>

<p>

เราคัดสรรกำไลข้อมือดีไซน์มินิมอลที่สวมใส่ได้ในทุกโอกาส
เน้นความเรียบหรู คุณภาพดี และเหมาะกับทุกสไตล์การแต่งตัว

</p>

</section>

<footer>

<p>KANYANAT PD</p>

</footer>



```
</body></html>
