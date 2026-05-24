<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kickvurse Sneakers</title>

<style>
body{
    margin:0;
    font-family:Arial;
    background:#111;
    color:white;
}

header{
    background:black;
    padding:20px;
    text-align:center;
    border-bottom:2px solid red;
}

header h1{
    color:red;
    margin:0;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    padding:20px;
}

.card{
    background:#1e1e1e;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 0 10px rgba(0,0,0,0.5);
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card h2{
    padding:10px;
    margin:0;
}

.price{
    color:#00ff99;
    padding:0 10px;
    font-size:20px;
}

.btns{
    display:flex;
    gap:10px;
    padding:10px;
}

.btn{
    flex:1;
    text-align:center;
    padding:12px;
    border:none;
    border-radius:10px;
    text-decoration:none;
    color:white;
    font-weight:bold;
}

.order{
    background:red;
}

.whatsapp{
    background:green;
}

footer{
    text-align:center;
    padding:20px;
    background:black;
    margin-top:20px;
}
</style>
</head>

<body>

<header>
<h1>KICKVURSE 👟</h1>
<p>Premium Sneakers Collection</p>
</header>

<section class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff" alt="">
<h2>Jordan Retro</h2>
<p class="price">₹4999</p>

<div class="btns">

<a class="btn order"
href="https://wa.me/919242923216">
Order
</a>

<a class="btn whatsapp"
href="https://wa.me/917865800753">
WhatsApp
</a>

</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519" alt="">
<h2>Nike Air Max</h2>
<p class="price">₹3999</p>

<div class="btns">

<a class="btn order"
href="https://wa.me/919242923216">
Order
</a>

<a class="btn whatsapp"
href="https://wa.me/917865800753">
WhatsApp
</a>

</div>
</div>

</section>

<footer>
<p>Cash On Delivery Available 🚚</p>
<p>Contact us on WhatsApp for orders</p>
</footer>

</body>
</html>
