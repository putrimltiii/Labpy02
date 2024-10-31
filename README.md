# Labpy02

![ss baspem1](https://github.com/user-attachments/assets/5654fc6a-597e-4282-854e-ee0b6938eb36)

Langkah-langah:

# Input Data:

Pengguna diminta untuk memasukkan nama dan nilai UTS, UAS, serta nilai tugas. Dalam hal ini, nama yang dimasukkan adalah "Putri Melati Ramadhaniati"

# Output Data:

Setelah menerima input, program kemudian menampilkan kembali informasi yang telah dimasukkan, termasuk nama dan nilai masing-masing.

Perhitungan Nilai Akhir:

Nilai akhir dihitung berdasarkan nilai UTS, UAS, dan tugas.

Dalam konteks ini, nilai akhir dihitung dengan rumus yang umum digunakan:

# Rumus:

Nilai Akhir= (UTS×0.3)+(UAS×0.4)+(Tugas×0.3) Nilai Akhir= (UTS×0.3)+(UAS×0.4)+(Tugas×0.3)

Dengan menggantikan nilai:

Nilai Akhir =(80×0.3)+(85×0.4)+(90×0.3)1= 84.0 Nilai Akhir= (80×0.3)+(85×0.4)+(90×0.3) =84.0 Konversi Nilai Akhir ke Nilai Huruf: Nilai akhir 84.0 dikonversi menjadi nilai huruf. Berdasarkan sistem penilaian umum, nilai huruf untuk 84.0 adalah "C". Keterangan Kelulusan:

Program memberikan keterangan "LULUS" karena nilai akhir berada di atas ambang batas kelulusan yang biasanya ditetapkan (misalnya, 60 atau 75, tergantung kebijakan). Dengan demikian, hasil dari codingan ini memberikan gambaran lengkap mengenai input, perhitungan, dan status kelulusan dari siswa bernama Putri Melati Ramadhaniati.

![ss baspem2](https://github.com/user-attachments/assets/350fe03c-4b34-4c15-adde-1eef9368382d)

# Input Data:

python Copy code gaji = int(input("Masukkan gaji: ")) berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T) ") == "Y"] punya_rumah = (False, True)[input("Punya rumah? (Y/T) ") == "Y"] Kode ini meminta pengguna untuk memasukkan gaji, status keluarga, dan kepemilikan rumah. Variabel gaji menyimpan nilai gaji sebagai integer. Variabel berkeluarga akan bernilai True jika pengguna memasukkan "Y" (sudah berkeluarga) dan False jika "T". Variabel punya_rumah akan bernilai True jika pengguna memasukkan "Y" (punya rumah) dan False jika "T". Pengecekan Gaji:

python Copy code if gaji > 3000000: print("Gaji sudah di atas UMR") Jika gaji lebih dari 3.000.000, maka program akan mencetak "Gaji sudah di atas UMR". Jika tidak, program akan langsung mencetak "Gaji belum UMR" pada bagian else.

# Pengecekan Status Keluarga:

python Copy code if berkeluarga: print("Wajib ikutan asuransi dan menabung untuk pensiun") else: print("Tidak perlu ikutan asuransi") Jika berkeluarga bernilai True, program akan menampilkan "Wajib ikutan asuransi dan menabung untuk pensiun". Jika berkeluarga bernilai False, program akan menampilkan "Tidak perlu ikutan asuransi". Pengecekan Kepemilikan Rumah:

python Copy code if punya_rumah: print("Wajib bayar pajak rumah") else: print("Tidak wajib bayar pajak rumah") Jika punya_rumah bernilai True, program akan menampilkan "Wajib bayar pajak rumah". Jika punya_rumah bernilai False, program akan menampilkan "Tidak wajib bayar pajak rumah". Gaji di Bawah UMR:

python Copy code else: print("Gaji belum UMR") Jika gaji tidak lebih dari 3.000.000, program akan langsung menampilkan "Gaji belum UMR" tanpa melakukan pengecekan tambahan.

Hasil Program: Pada contoh output di sisi kanan gambar, jika gaji 5.000.000, status berkeluarga "Y", dan punya rumah "Y":

Program menampilkan bahwa gaji di atas UMR. Menampilkan bahwa pengguna wajib ikut asuransi dan menabung untuk pensiun. Menampilkan bahwa pengguna wajib membayar pajak rumah.

![ss baspem3](https://github.com/user-attachments/assets/62f35a0e-1c93-4f72-ab37-20e5f5825bf8)

# Langkah-langkah

python Copy code a = int(input("Masukkan bilangan A: ")) b = int(input("Masukkan bilangan B: ")) c = int(input("Masukkan bilangan C: ")) Kode ini meminta pengguna untuk memasukkan tiga bilangan: a, b, dan c. Input dari pengguna dikonversi ke tipe int agar dapat digunakan dalam operasi aritmatika. Pengecekan Kondisi:

python Copy code if a + b == c or b + c == a or c + a == b: print("BENAR") else: print("SALAH") Kode ini memeriksa apakah salah satu dari kondisi berikut terpenuhi: a + b == c b + c == a c + a == b Jika salah satu kondisi di atas benar, program akan mencetak "BENAR". Jika tidak ada kondisi yang terpenuhi, program akan mencetak "SALAH". Penjelasan Logika:

Kode ini mengecek apakah salah satu dari tiga bilangan (a, b, atau c) dapat merupakan hasil penjumlahan dari dua bilangan lainnya. Pada contoh output di sebelah kanan gambar: Jika a = 100, b = 50, dan c = 200, maka tidak ada kondisi yang terpenuhi, sehingga hasilnya adalah "SALAH".

Kode Python di atas adalah program untuk menghitung total harga tiket bioskop. Program ini meminta input dari user untuk tipe tiket (reguler atau VIP) dan status member (memiliki kartu member atau tidak).







