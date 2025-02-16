function kiraTotal() {
let hargaPakaian = parseFloat(document.getElementById("pakaian").value);
let qty = parseInt(document.getElementById("qty").value);
let tambahSampin = document.getElementById("sampin").checked;

let hargaTotal = hargaPakaian \* qty;

if (tambahSampin) {
hargaTotal += 79;
}
document.getElementById("hasil").innerText = "Jumlah Harga: RM" + hargaTotal.toFixed(2);
}