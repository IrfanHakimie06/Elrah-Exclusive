\<!DOCTYPE html>
\<html lang="ms">
\<head>
\<meta charset="UTF-8">
\<meta name="viewport" content="width=device-width, initial-scale=1.0">
\<title>Elrah Exclusive Order\</title>
\<link rel="stylesheet" href="styles.css">
\</head>
\<body>
\<div class="container">
\<h2>Elrah Exclusive - Pilih Item\</h2>
\<label for="pakaian">Pilih Pakaian:\</label>
\<select id="pakaian">
\<option value="199">Baju Melayu (RM199)\</option>
\<option value="199">Baju Melayu Teluk Belanga (RM199)\</option>
\<option value="119">Kurta (RM119)\</option>
\</select>
\<label for="warna">Pilih Warna:\</label>
\<select id="warna">
\<option>BLACK\</option>
\<option>OFFWHITE\</option>
\<option>DARK GREY\</option>
\<option>GREY\</option>
\<option>ASH GREY\</option>
\</select>
\<label for="saiz">Pilih Saiz:\</label>
\<select id="saiz">
\<option>XXS\</option>
\<option>XS\</option>
\<option>S\</option>
\<option>M\</option>
\<option>L\</option>
\<option>XL\</option>
\<option>XXL\</option>
\</select>
\<label for="qty">Kuantiti:\</label>
\<input type="number" id="qty" min="1" value="1">
\<label for="sampin">Tambah Sampin Premium (RM79)?\</label>
\<input type="checkbox" id="sampin">
\<button onclick="kiraTotal()">Kira Jumlah\</button>
\<h3 id="hasil">\</h3>
\</div>
\<script src="script.js">\</script>
\</body>
\</html>