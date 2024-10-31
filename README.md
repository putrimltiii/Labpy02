# Labpy02

![ss baspem1](https://github.com/user-attachments/assets/5654fc6a-597e-4282-854e-ee0b6938eb36)
Pasti! Mari kita lihat kode langkah demi langkah:

#!/usr/bin/python3: Ini adalah baris shebang, yang menentukan interpreter yang akan digunakan untuk skrip ini. Dalam hal ini, ini menggunakan interpreter Python 3 yang terletak di /usr/bin/python3.
nama = input("Masukkan nama: "): Baris ini meminta pengguna untuk memasukkan nama mereka dan menyimpan input dalam variabel nama.
uts = input("Masukkan nilai UTS: "): Baris ini meminta pengguna untuk memasukkan skor UTS (Ujian Tengah Semester) mereka dan menyimpan input dalam variabel uts.
uas = input("Masukkan nilai UAS: "): Baris ini meminta pengguna untuk memasukkan skor UAS (Ujian Akhir) mereka dan menyimpan input dalam variabel UAS.
tugas = input("Masukkan nilai Tugas: "): Baris ini meminta pengguna untuk memasukkan skor Tugas (Tugas) mereka dan menyimpan input dalam variabel tugas.
Akhir = (int(tugas) * 0.2) + (int(uts) * 0.4) + (int(uas) * 0.4): Garis ini menghitung nilai akhir (Nilai Akhir) berdasarkan rumus tertimbang. Rumusnya mengambil skor Tugas dengan bobot 20%,
