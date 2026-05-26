<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Payment</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Prompt',sans-serif;
}

body{
min-height:100vh;
display:flex;
justify-content:center;
align-items:center;
padding:30px;
background:
linear-gradient(180deg,#eef9ff,#ffffff);
}

.card{
width:100%;
max-width:430px;
background:#fff;
border-radius:32px;
overflow:hidden;
box-shadow:
0 10px 30px rgba(0,0,0,.08);
}

.top{
background:#163f73;
padding:32px 24px;
text-align:center;
color:#fff;
}

.top h1{
font-size:32px;
font-weight:600;
letter-spacing:1px;
}

.top p{
margin-top:6px;
opacity:.85;
font-size:14px;
}

.content{
padding:30px;
text-align:center;
}

.qr-box{
background:#f7f9fc;
border-radius:24px;
padding:22px;
margin-bottom:24px;
}

.qr-box img{
width:100%;
max-width:260px;
border-radius:18px;
}

.save-btn{
display:inline-block;
margin-top:16px;
padding:12px 22px;
border-radius:14px;
background:#163f73;
color:#fff;
text-decoration:none;
font-size:15px;
transition:.2s;
}

.save-btn:hover{
transform:scale(1.03);
}

.name{
font-size:26px;
font-weight:600;
margin-bottom:24px;
color:#1d1d1d;
}

.info{
background:#f9fbff;
border:1px solid #e5eefb;
border-radius:18px;
padding:18px;
margin-bottom:18px;
text-align:left;
}

.label{
font-size:14px;
color:#7c8aa5;
margin-bottom:6px;
}

.value{
font-size:20px;
font-weight:500;
color:#111;
word-break:break-all;
}

.copy-btn{
width:100%;
margin-top:14px;
padding:12px;
border:none;
border-radius:12px;
background:#4a8cff;
color:#fff;
font-size:15px;
cursor:pointer;
transition:.2s;
}

.copy-btn:hover{
opacity:.9;
}

.footer{
padding:22px;
text-align:center;
font-size:13px;
color:#999;
}

</style>
</head>

<body>

<div class="card">

<div class="top">
<h1>Payment</h1>
<p>Scan QR or Copy Account ♡</p>
</div>

<div class="content">

<div class="qr-box">

<img src="A316889E-0539-4CDF-9A58-B947E90BA361.jpeg" alt="QR">

<br>

<a
class="save-btn"
href="A316889E-0539-4CDF-9A58-B947E90BA361.jpeg"
download
>
♡ Save QR Code
</a>

</div>

<div class="name">
จีรนันท์ ทาทอง
</div>

<div class="info">

<div class="label">
♡• K-PLUS
</div>

<div class="value">
151-3-39255-5
</div>

<button
class="copy-btn"
onclick="copyText('151-3-39255-5')"
>
คัดลอกเลขบัญชี
</button>

</div>

<div class="info">

<div class="label">
♡• WALLET
</div>

<div class="value">
0933857458
</div>

<button
class="copy-btn"
onclick="copyText('0933857458')"
>
คัดลอกเบอร์ Wallet
</button>

</div>

</div>

<div class="footer">
Thank you for your support ♡
</div>

</div>

<script>

function copyText(text){

navigator.clipboard.writeText(text);

alert("คัดลอกเรียบร้อย ♡");

}

</script>

</body>
</html>
