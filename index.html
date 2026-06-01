<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>The Best Farm</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:tahoma,sans-serif;
}

body{
background:#f5f5f5;
color:#333;
}

header{
background:#2E7D32;
color:white;
padding:20px;
}

.container{
width:90%;
max-width:1200px;
margin:auto;
}

nav{
margin-top:15px;
display:flex;
gap:15px;
flex-wrap:wrap;
}

nav a{
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
background:white;
padding:80px 20px;
text-align:center;
}

.hero h1{
font-size:48px;
}

.section{
padding:50px 20px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
border-radius:12px;
overflow:hidden;
box-shadow:0 2px 10px rgba(0,0,0,.1);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card-content{
padding:15px;
}

.btn{
background:#2E7D32;
color:white;
border:none;
padding:10px 15px;
border-radius:8px;
cursor:pointer;
}

footer{
background:#222;
color:white;
text-align:center;
padding:20px;
}

#adminBtn{
position:fixed;
right:20px;
bottom:20px;
width:60px;
height:60px;
border-radius:50%;
border:none;
background:#2E7D32;
color:white;
font-size:24px;
cursor:pointer;
}

.modal{
display:none;
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,.5);
}

.modal-content{
background:white;
width:350px;
padding:20px;
border-radius:10px;
margin:100px auto;
}

.admin-panel{
display:none;
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:white;
overflow:auto;
padding:20px;
z-index:9999;
}

input,textarea{
width:100%;
padding:10px;
margin:5px 0;
}

</style>
</head>

<body>

<header>
<div class="container">

<h1>🐔 The Best Farm</h1>
<p>เดอะเบสท์ฟาร์ม</p>

<nav>
<a href="#breeds">สายพันธุ์ไก่</a>
<a href="#products">สินค้า</a>
<a href="#gallery">แกลเลอรี</a>
<a href="#contact">ติดต่อ</a>
</nav>

</div>
</header>

<section class="hero">
<h1>Premium Poultry Farm</h1>
<p>ฟาร์มไก่คุณภาพ</p>
</section>

<section id="breeds" class="section container">
<h2>สายพันธุ์ไก่</h2>
<br>
<div class="grid" id="breedList"></div>
</section>

<section id="products" class="section container">
<h2>สินค้า</h2>
<br>
<div class="grid" id="productList"></div>
</section>

<section id="gallery" class="section container">
<h2>แกลเลอรี</h2>
<br>
<div class="grid" id="galleryList"></div>
</section>

<section id="contact" class="section container">

<div class="card">

<div class="card-content">

<h2>ติดต่อฟาร์ม</h2>

<p>📞 082-193-1056</p>
<p>💬 Line : best25511</p>
<p>📘 Facebook : The Best Farm</p>

</div>

</div>

</section>

<footer>
© 2026 The Best Farm
</footer>

<button id="adminBtn">⚙</button>

<div class="modal" id="loginModal">

<div class="modal-content">

<h2>Admin Login</h2>

<input id="username" placeholder="Username">

<input
type="password"
id="password"
placeholder="Password">

<br><br>

<button
class="btn"
onclick="login()">

เข้าสู่ระบบ

</button>

</div>

</div>

<div class="admin-panel" id="adminPanel">

<h1>THE BEST FARM CMS</h1>

<br>

<button
class="btn"
onclick="showBreedForm()">

เพิ่มสายพันธุ์

</button>

<button
class="btn"
onclick="showProductForm()">

เพิ่มสินค้า

</button>

<button
class="btn"
onclick="closeAdmin()">

ปิด

</button>

<hr><br>

<div id="adminContent"></div>

</div>

<script>

const ADMIN_USER="bestfarm";
const ADMIN_PASS="BestFarm@2026";

let breeds=
JSON.parse(localStorage.getItem("breeds"))||[];

let products=
JSON.parse(localStorage.getItem("products"))||[];

let gallery=
JSON.parse(localStorage.getItem("gallery"))||[];

function saveData(){

localStorage.setItem(
"breeds",
JSON.stringify(breeds)
);

localStorage.setItem(
"products",
JSON.stringify(products)
);

localStorage.setItem(
"gallery",
JSON.stringify(gallery)
);

render();

}

document.getElementById(
"adminBtn"
).onclick=function(){

document.getElementById(
"loginModal"
).style.display="block";

};

function login(){

const user=
document.getElementById(
"username"
).value;

const pass=
document.getElementById(
"password"
).value;

if(
user===ADMIN_USER &&
pass===ADMIN_PASS
){

document.getElementById(
"loginModal"
).style.display="none";

document.getElementById(
"adminPanel"
).style.display="block";

}
else{

alert("เข้าสู่ระบบไม่สำเร็จ");

}

}

function closeAdmin(){

document.getElementById(
"adminPanel"
).style.display="none";

}

function showBreedForm(){

document.getElementById(
"adminContent"
).innerHTML=`

<h2>เพิ่มสายพันธุ์</h2>

<input id="breedName" placeholder="ชื่อ">

<input id="breedImage" placeholder="URL รูป">

<textarea id="breedDesc"
placeholder="รายละเอียด"></textarea>

<button
class="btn"
onclick="saveBreed()">

บันทึก

</button>

`;

}

function saveBreed(){

breeds.push({

name:
document.getElementById(
"breedName"
).value,

image:
document.getElementById(
"breedImage"
).value,

desc:
document.getElementById(
"breedDesc"
).value

});

saveData();

alert("บันทึกแล้ว");

}

function showProductForm(){

document.getElementById(
"adminContent"
).innerHTML=`

<h2>เพิ่มสินค้า</h2>

<input id="productName" placeholder="ชื่อสินค้า">

<input id="productImage" placeholder="URL รูป">

<input id="productPrice" placeholder="ราคา">

<button
class="btn"
onclick="saveProduct()">

บันทึก

</button>

`;

}

function saveProduct(){

products.push({

name:
document.getElementById(
"productName"
).value,

image:
document.getElementById(
"productImage"
).value,

price:
document.getElementById(
"productPrice"
).value

});

saveData();

alert("บันทึกแล้ว");

}

function render(){

renderBreeds();
renderProducts();
renderGallery();

}

function renderBreeds(){

const list=
document.getElementById(
"breedList"
);

list.innerHTML="";

breeds.forEach(item=>{

list.innerHTML+=`

<div class="card">

<img src="${item.image}">

<div class="card-content">

<h3>${item.name}</h3>

<p>${item.desc}</p>

</div>

</div>

`;

});

}

function renderProducts(){

const list=
document.getElementById(
"productList"
);

list.innerHTML="";

products.forEach(item=>{

list.innerHTML+=`

<div class="card">

<img src="${item.image}">

<div class="card-content">

<h3>${item.name}</h3>

<p>${item.price} บาท</p>

</div>

</div>

`;

});

}

function renderGallery(){

const list=
document.getElementById(
"galleryList"
);

list.innerHTML="";

gallery.forEach(item=>{

list.innerHTML+=`

<div class="card">

<img src="${item.image}">

</div>

`;

});

}

render();

</script>

</body>
</html>
