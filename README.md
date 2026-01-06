<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Recorded Lectures</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#0f172a;
    color:#fff;
}
header{
    background:#1e293b;
    padding:15px;
    text-align:center;
    font-size:20px;
    font-weight:bold;
}
.container{
    padding:15px;
}
.card{
    background:#1e293b;
    border:1px solid #334155;
    border-radius:10px;
    padding:12px;
    margin-bottom:10px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}
.title{
    font-size:14px;
}
button{
    background:#6366f1;
    border:none;
    color:white;
    padding:6px 12px;
    border-radius:6px;
    cursor:pointer;
}
button:hover{
    background:#4f46e5;
}
</style>
</head>

<body>

<header>📚 Recorded Foundation Batch</header>

<div class="container">

<div class="card">
    <div class="title">Lecture 1 – Basic Electrical</div>
    <button onclick="play('https://media-cdn.classplusapp.com/793763/lc/t7o19-3321172/master.m3u8')">▶ Play</button>
</div>

<div class="card">
    <div class="title">Lecture 2 – Microprocessor</div>
    <button onclick="play('https://media-cdn.classplusapp.com/793763/lc/6bwtk-5421209n/master.m3u8')">▶ Play</button>
</div>

<div class="card">
    <div class="title">Lecture 3 – Basic Electronics</div>
    <button onclick="play('https://media-cdn.classplusapp.com/793763/lc/qcnxa-3469099/master.m3u8')">▶ Play</button>
</div>

</div>

<script>
function play(url){
    window.location.href =
    "https://itsgolu-v1player.vercel.app/?url=" + encodeURIComponent(url);
}
</script>

</body>
</html>
