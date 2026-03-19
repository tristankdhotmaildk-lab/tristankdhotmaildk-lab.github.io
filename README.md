<html lang="da">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bordplader – komplet overblik</title>
<style>
body {font-family: Arial, sans-serif; margin:0; background:#f4f6f9;}
header {background:#2c3e50; color:white; text-align:center; padding:25px;}
.container {display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:20px; padding:20px;}
.card {background:white; border-radius:12px; padding:20px; box-shadow:0 4px 10px rgba(0,0,0,0.1); cursor:pointer; transition:0.3s;}
.card:hover {transform:scale(1.03);} 
.details {display:none; margin-top:10px; font-size:14px; line-height:1.5;}
.card.active .details {display:block;}
h2 {margin:0 0 10px 0;}
img {width:100%; border-radius:10px; margin-bottom:10px;}
table {width:100%; border-collapse:collapse; margin-top:30px;}
th, td {border:1px solid #ddd; padding:10px; text-align:left;}
th {background:#2c3e50; color:white;}
</style>
</head>
<body>
<header>
<h1>Bordplader – simpelt overblik (HTH)</h1>
<p>Klik på en type for at se alle detaljer</p>
</header>

<div class="container">

<!-- LAMINAT -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Laminat">
<h2>🪵 Laminat</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Laminat er papir lag-på-lag med en slidstærk overflade (melamin), limet på en spånplade.</p>
<p><b>Fordele</b><br>Billig løsning<br>Mange farver og designs<br>Slidstærk til almindeligt brug</p>
<p><b>Ulemper</b><br>Tåler ikke vand i samlinger<br>Tåler ikke høj varme<br>Kan ridses</p>
<p><b>Vedligehold</b><br>Tørres af med fugtig klud<br>Brug skærebræt og bordskåner</p>
<p><b>CO₂</b><br>38,1 kg CO₂/m²</p>
<p>⚠️ OBS: Tal ikke direkte sammenlignelige</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Meget nem<br>Tørres af med fugtig klud<br>Undgå ridser og varme<br>Tør væske op – især ved samlinger</p>
<p>👉 “Meget nem i hverdagen – men kræver omtanke”</p>
</div>
</div>

<!-- FIBERCORE -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Fibercore">
<h2>🧱 FiberCore</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Laminat + stærkere kerne</p>
<p><b>Fordele</b><br>Mere robust<br>Slank<br>Bedre slagstyrke</p>
<p><b>Ulemper</b><br>Følsom for varme/vand<br>Ikke som sten</p>
<p><b>Vedligehold</b><br>Samme som laminat</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Lav<br>Rengøres som laminat<br>Mere robust<br>Stadig følsom for varme</p>
<p>👉 “Stærkere alternativ til laminat”</p>
</div>
</div>

<!-- KOMPAKTLAMINAT -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Kompaktlaminat">
<h2>🧪 Kompaktlaminat</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Massivt laminat</p>
<p><b>Fordele</b><br>Tåler vand<br>Slank<br>Holdbar</p>
<p><b>Ulemper</b><br>Ikke varmefast<br>Kan bevæge sig</p>
<p><b>CO₂</b><br>34,6 kg CO₂/m²</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Meget nem<br>Tåler vand<br>Rengøres med klud<br>Undgå varme</p>
<p>👉 “Som laminat – bare bedre mod vand”</p>
</div>
</div>

<!-- LINOLIUM -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Linoleum">
<h2>🌿 Linoleum</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Naturmateriale</p>
<p><b>Fordele</b><br>Blød<br>Bæredygtig</p>
<p><b>Ulemper</b><br>Tåler ikke vand<br>Ridses<br>Kræver vedligehold</p>
<p><b>Vigtigt</b><br>Skal plejes løbende<br>Ikke til hårdt brug</p>
</div>
</div>

<!-- MASSIVTRÆ -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Massivtræ">
<h2>🌳 Massivtræ</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Ægte træ</p>
<p><b>Fordele</b><br>Flot<br>Kan repareres<br>Lav CO₂</p>
<p><b>CO₂</b><br>7,8 kg CO₂/m²</p>
<p><b>Ulemper</b><br>Kræver olie<br>Tåler ikke vand/varme</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Høj<br>Skal olieres<br>Tør vand op<br>Kan slibes</p>
<p>👉 “Holder længe hvis vedligeholdes”</p>
</div>
</div>

<!-- KOMPOSIT -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Komposit">
<h2>🪨 Komposit</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Knust sten + lim</p>
<p><b>Fordele</b><br>Slidstærk<br>Pletresistent</p>
<p><b>Ulemper</b><br>Ikke varmefast</p>
<p><b>CO₂</b><br>52,4 kg CO₂/m²</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Lav<br>Nem rengøring<br>Tåler det meste<br>Undgå syre</p>
<p>👉 “God til travle køkkener”</p>
</div>
</div>

<!-- KERAMIK -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Keramik">
<h2>🔥 Keramik</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Brændt ler</p>
<p><b>Fordele</b><br>Varmefast<br>Ridsefast</p>
<p><b>Ulemper</b><br>Kan knække</p>
<p><b>CO₂</b><br>58,3 kg CO₂/m²</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Meget lav<br>Tåler alt<br>Næsten ingen vedligehold</p>
<p>👉 “Tåler næsten alt”</p>
</div>
</div>

<!-- GRANIT -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Granit">
<h2>🪨 Granit</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Natursten</p>
<p><b>Fordele</b><br>Slidstærk<br>Vandtæt</p>
<p><b>Ulemper</b><br>Tung</p>
<p><b>Vedligehold</b><br>Imprægneres</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Lav<br>Skal imprægneres<br>Tåler varme</p>
<p>👉 “Stærk natursten”</p>
</div>
</div>

<!-- MARMOR -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Marmor">
<h2>⚪ Marmor / kalksten</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Blød natursten</p>
<p><b>Fordele</b><br>Eksklusivt</p>
<p><b>Ulemper</b><br>Ridses<br>Tåler ikke syre</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Høj<br>Skal forsegles<br>Får patina</p>
<p>👉 “Smukt men sart”</p>
</div>
</div>

<!-- STÅL -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Rustfrit+stål">
<h2>🔩 Rustfrit stål</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Stålbordplade</p>
<p><b>Fordele</b><br>Hygiejnisk</p>
<p><b>Ulemper</b><br>Ridser</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Lav<br>Sæbevand<br>Kan slibes</p>
<p>👉 “Råt look”</p>
</div>
</div>

<!-- CORIAN -->
<div class="card" onclick="toggle(this)">
<img src="https://via.placeholder.com/300x150?text=Corian">
<h2>🧼 Corian</h2>
<div class="details">
<p><b>Hvad er det?</b><br>Mineral + akryl</p>
<p><b>Fordele</b><br>Sømløs</p>
<p><b>Ulemper</b><br>Ikke varmefast</p>
<hr>
<p><b>Vedligehold (udvidet)</b><br>Lav<br>Nem rengøring<br>Kan slibes</p>
<p>👉 “Kan repareres”</p>
</div>
</div>

</div>

<h2 style="padding:20px">KOMPLET PRISOVERSIGT</h2>
<table>
<tr><th>Materiale</th><th>Budget</th><th>Standard</th><th>Premium</th><th>Eksklusiv</th><th>Salgsvinkel</th></tr>
<tr><td>Laminat</td><td>1000-1500</td><td>1500-2000</td><td>2000-2500</td><td>-</td><td>Billigt & praktisk</td></tr>
<tr><td>Kompaktlaminat</td><td>-</td><td>2000-3000</td><td>3000-4000</td><td>-</td><td>Slankt & vandfast</td></tr>
<tr><td>Massivtræ</td><td>-</td><td>2500-4000</td><td>4000-6000</td><td>-</td><td>Varmt & naturligt</td></tr>
<tr><td>Fibercore</td><td>-</td><td>3000-5000</td><td>5000-7000</td><td>-</td><td>Slidstærk & moderne</td></tr>
<tr><td>Komposit</td><td>-</td><td>4000-6000</td><td>6000-9000</td><td>-</td><td>Ensartet & stærk</td></tr>
<tr><td>Keramik</td><td>-</td><td>3000-5000</td><td>5000-8000</td><td>8000+</td><td>Mest robust</td></tr>
<tr><td>Granit</td><td>-</td><td>4000-7000</td><td>7000-10000</td><td>10000+</td><td>Ægte natur</td></tr>
<tr><td>Marmor</td><td>-</td><td>5000-8000</td><td>8000-11000</td><td>11000+</td><td>Smukt men sart</td></tr>
<tr><td>Rustfrit stål</td><td>-</td><td>5000-7000</td><td>7000-9000</td><td>-</td><td>Pro look</td></tr>
</table>

<script>
function toggle(card){card.classList.toggle('active');}
</script>

</body>
</html>
