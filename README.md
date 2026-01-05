<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PinkMove Club</title>
<style>
body { font-family: Arial, sans-serif; background-color: #ffe0f0; color: #333; margin:0; padding:0;}
header { background-color: #ff99cc; padding: 20px; text-align:center; color:white;}
h1 { margin:0; }
.container { padding:20px; display:flex; flex-wrap: wrap; justify-content: center;}
.plan { background-color: #fff0f5; border:2px solid #ff99cc; border-radius:10px; margin:10px; padding:15px; width:220px; box-sizing:border-box; text-align:center;}
.plan h2 { margin-top:0; color:#ff3399; }
.buy-btn { display:inline-block; margin-top:10px; padding:10px 15px; background-color:#ff66b3; color:white; text-decoration:none; border-radius:5px; }
.buy-btn:hover { background-color:#ff3399;}
</style>
</head>
<body>
<header>
<h1>PinkMove Club</h1>
<p>20 wyjątkowych planów treningowych dla kobiet</p>
</header>

<div class="container" id="plans-container"></div>

<script>
const plans = [
{ name: "Pink Start", desc: "Lekkie ćwiczenia dla początkujących", price: "79 zł", link: "https://buy.stripe.com/3cI8wRgJqcB16uO8yPfrW0l" },
{ name: "Soft Shape", desc: "Modelowanie sylwetki w domu", price: "89 zł", link: "https://buy.stripe.com/6oU14p50I0Sj3iCdT9frW0k" },
{ name: "Core Glow", desc: "Trening na mięśnie brzucha", price: "99 zł", link: "https://buy.stripe.com/28E9AV1Ow1WnbP86qHfrW0j" },
{ name: "Leg Power", desc: "Ćwiczenia na nogi i pośladki", price: "89 zł", link: "https://buy.stripe.com/6oUbJ32SA58zdXgdT9frW0i" },
{ name: "Arm Tone", desc: "Wz
