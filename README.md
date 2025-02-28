let jumlah_nilai = 0;

for (let i = 1; i <= 3; i++) {
let nilai = parseFloat(prompt("
Masukkan nilai siswa " + i + ": "));
jumlah_nilai += nilai;
}

let rata_rata = jumlah_nilai / 3;
console.log("Rata -rata nilai siswa adalah:
" + rata_rata);
