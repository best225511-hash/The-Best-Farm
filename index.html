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
font-family:Tahoma,sans-serif;
}

body{
background:#f5f5f5;
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

.logo-box{
display:flex;
align-items:center;
gap:15px;
}

.logo{
width:80px;
height:80px;
border-radius:12px;
background:white;
object-fit:cover;
}

nav{
margin-top:15px;
display:flex;
flex-wrap:wrap;
gap:15px;
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
font-size:50px;
}

.btn{
display:inline-block;
padding:12px 25px;
background:#2E7D32;
color:white;
text-decoration:none;
border:none;
border-radius:10px;
cursor:pointer;
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
border:none;
border-radius:50%;
background:#2E7D32;
color:white;
font-size:22px;
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
width:400px;
padding:20px;
margin:80px auto;
border-radius:12px;
}

input,textarea{
width:100%;
padding:10px;
margin-top:10px;
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
padding:30px;
z-index:9999;
}

</style>
</head>

<body>

<header>

<div class="container">

<div class="logo-box">

<img
id="logo"
class="logo"
src="https://via.placeholder.com/100">

<div>

<h1>The Best Farm</h1>

<p>เดอะเบสซ์ฟาร์ม</p>

</div>

</div>

<nav>

<a href="#">หน้าแรก</a>
<a href="#breeds">สายพันธุ์ไก่</a>
<a href="#products">สินค้า</a>
<a href="#news">ข่าวสาร</a>
<a href="#blog">บทความ</a>
<a href="#contact">ติดต่อ</a>

</nav>

</div>

</header>

<section class="hero">

<h1>🐔 The Best Farm</h1>

<p>ฟาร์มไก่คุณภาพ Premium Poultry Farm</p>

<br>

<a href="#contact" class="btn">
ติดต่อฟาร์ม
</a>

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

<section id="news" class="section container">

<h2>ข่าวสาร</h2>

<br>

<div id="newsList"></div>

</section>

<section id="blog" class="section container">

<h2>บทความความรู้</h2>

<br>

<div id="blogList"></div>

</section>

<section id="contact" class="section container">

<div class="card">

<div class="card-content">

<h2>ติดต่อเรา</h2>

<p>โทร : 082-193-1056</p>

<p>Line : best25511</p>

<p>Facebook : เดอะเบสซ์ฟาร์ม</p>

</div>

</div>

</section>

<footer>

© 2026 The Best Farm

</footer>

<button
id="adminBtn"
onclick="showLogin()">
⚙
</button>

<div id="loginModal" class="modal">

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

<div
id="adminPanel"
class="admin-panel">

<h1>Dashboard</h1>

<hr><br>

<button class="btn" onclick="addBreed()">
เพิ่มสายพันธุ์
</button>

<button class="btn" onclick="addProduct()">
เพิ่มสินค้า
</button>

<button class="btn" onclick="addNews()">
เพิ่มข่าว
</button>

<button class="btn" onclick="addBlog()">
เพิ่มบทความ
</button>

<button class="btn" onclick="closeAdmin()">
ปิด
</button>

<br><br>

<div id="adminContent"></div>

</div>

<script>

let breeds=
JSON.parse(
localStorage.getItem("breeds")
)||[];

let products=
JSON.parse(
localStorage.getItem("products")
)||[];

function save(){

localStorage.setItem(
"breeds",
JSON.stringify(breeds)
);

localStorage.setItem(
"products",
JSON.stringify(products)
);

render();

}

function render(){

document.getElementById(
"breedList"
).innerHTML="";

breeds.forEach(item=>{

document.getElementById(
"breedList"
).innerHTML+=`

<div class="card">

<img src="${item.image}">

<div class="card-content">

<h3>${item.name}</h3>

<p>${item.desc}</p>

</div>

</div>

`;

});

document.getElementById(
"productList"
).innerHTML="";

products.forEach(item=>{

document.getElementById(
"productList"
).innerHTML+=`

<div class="card">

<img src="${item.image}">

<div class="card-content">

<h3>${item.name}</h3>

<p>${item.price}</p>

</div>

</div>

`;

});

}

render();

function showLogin(){

document.getElementById(
"loginModal"
).style.display="block";

}

function login(){

if(
document.getElementById("username").value=="admin"
&&
document.getElementById("password").value=="123456"
){

document.getElementById(
"adminPanel"
).style.display="block";

document.getElementById(
"loginModal"
).style.display="none";

}
else{

alert("Login Failed");

}

}

function closeAdmin(){

document.getElementById(
"adminPanel"
).style.display="none";

}

function addBreed(){

document.getElementById(
"adminContent"
).innerHTML=`

<h2>เพิ่มสายพันธุ์</h2>

<input id="bname" placeholder="ชื่อ">

<input id="bimage" placeholder="URL รูป">

<textarea id="bdesc"></textarea>

<button class="btn"
onclick="saveBreed()">
บันทึก
</button>

`;

}

function saveBreed(){

breeds.push({

name:
document.getElementById("bname").value,

image:
document.getElementById("bimage").value,

desc:
document.getElementById("bdesc").value

});

save();

}

function addProduct(){

document.getElementById(
"adminContent"
).innerHTML=`

<h2>เพิ่มสินค้า</h2>

<input id="pname">

<input id="pimage">

<input id="pprice">

<button class="btn"
onclick="saveProduct()">
บันทึก
</button>

`;

}

function saveProduct(){

products.push({

name:
document.getElementById("pname").value,

image:
document.getElementById("pimage").value,

price:
document.getElementById("pprice").value

});

save();

}

function addNews(){

alert("ระบบข่าวสารจะเพิ่มในส่วนถัดไป");

}

function addBlog(){

alert("ระบบบทความจะเพิ่มในส่วนถัดไป");

}

</script>

</body>
</html>
function addNews(){

alert("ระบบข่าวสารจะเพิ่มในส่วนถัดไป");

}
function addNews(){

document.getElementById(
"adminContent"
).innerHTML=`

<h2>เพิ่มข่าวสาร</h2>

<input
id="newsTitle"
placeholder="หัวข้อข่าว">

<textarea
id="newsContent"
placeholder="รายละเอียด"></textarea>

<button
class="btn"
onclick="saveNews()">

บันทึก

</button>

`;

}
function saveNews(){

news.push({

title:
document.getElementById(
"newsTitle"
).value,

content:
document.getElementById(
"newsContent"
).value

});

save();

}
document.getElementById(
"newsList"
).innerHTML="";

news.forEach(item=>{

document.getElementById(
"newsList"
).innerHTML+=`

<div class="card">

<div class="card-content">

<h3>${item.title}</h3>

<p>${item.content}</p>

</div>

</div>

`;

});
function addBlog(){

alert("ระบบบทความจะเพิ่มในส่วนถัดไป");

}
function addBlog(){

document.getElementById(
"adminContent"
).innerHTML=`

<h2>เพิ่มบทความ</h2>

<input
id="blogTitle"
placeholder="หัวข้อ">

<textarea
id="blogContent"
placeholder="เนื้อหา"></textarea>

<button
class="btn"
onclick="saveBlog()">

บันทึก

</button>

`;

}
function saveBlog(){

blogs.push({

title:
document.getElementById(
"blogTitle"
).value,

content:
document.getElementById(
"blogContent"
).value

});

save();

}
document.getElementById(
"blogList"
).innerHTML="";

blogs.forEach(item=>{

document.getElementById(
"blogList"
).innerHTML+=`

<div class="card">

<div class="card-content">

<h3>${item.title}</h3>

<p>${item.content}</p>

</div>

</div>

`;

});
<h2>โลโก้ฟาร์ม</h2>

<input
type="file"
id="logoUpload"
accept="image/*">

<br><br>

<img
id="previewLogo"
style="
width:150px;
border-radius:10px;
">
<h2>โลโก้ฟาร์ม</h2>

<input
type="file"
id="logoUpload"
accept="image/*">

<br><br>

<img
id="previewLogo"
style="
width:150px;
border-radius:10px;
">
const savedLogo =
localStorage.getItem("farmLogo");

if(savedLogo){

document
.getElementById("logo")
.src = savedLogo;

}
document
.addEventListener(
"change",
function(e){

if(
e.target.id==="logoUpload"
){

const file =
e.target.files[0];

const reader =
new FileReader();

reader.onload =
function(event){

localStorage.setItem(
"farmLogo",
event.target.result
);

document
.getElementById("logo")
.src =
event.target.result;

};

reader.readAsDataURL(
file
);

}

});
<button
class="btn"
onclick="backupData()">

สำรองข้อมูล

</button>
function backupData(){

const data = {

breeds,
products,
news,
blogs

};

const blob =
new Blob(
[
JSON.stringify(
data,
null,
2
)
],
{
type:"application/json"
}
);

const a =
document.createElement("a");

a.href =
URL.createObjectURL(blob);

a.download =
"thebestfarm-backup.json";

a.click();

}
<input
type="file"
id="restoreFile"
accept=".json">
document
.addEventListener(
"change",
function(e){

if(
e.target.id==="restoreFile"
){

const file =
e.target.files[0];

const reader =
new FileReader();

reader.onload =
function(event){

const data =
JSON.parse(
event.target.result
);

breeds =
data.breeds || [];

products =
data.products || [];

news =
data.news || [];

blogs =
data.blogs || [];

save();

};

reader.readAsText(
file
);

}

});
<button
onclick="deleteBreed(${index})">

ลบ

</button>
breeds.forEach(item=>{
breeds.forEach((item,index)=>{
function deleteBreed(index){

if(
confirm(
"ลบข้อมูลนี้ ?"
)
){

breeds.splice(
index,
1
);

save();

}

}
function deleteProduct(index){

products.splice(
index,
1
);

save();

}admin
123456
localStorage.setItem(
"adminPassword",
"123456"
);
const password =
localStorage.getItem(
"adminPassword"
)
||
"123456";
