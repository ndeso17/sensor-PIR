# Sensor PIR (Passive InfraRed)

Kode program ini dijalankan menggunakan Wemos D1 R2, selain dijalankan pada Wemos kode program ini juga bisa dijalankan pada keluarga Arduino dan ESP. Sesuaikan pin I/O pada board yang akan dipakai.

Program ini akan menampilkan informasi jika ada object yang melewati module sensor PIR. Berikut beberapa trigger dari sensor PIR :

1. Gerakan:
   - Sensor PIR membutuhkan perubahan posisi sumber IR untuk mendeteksi. Jika seseorang diam, sensor tidak akan memicu.
2. Kontras Suhu:
   - Deteksi lebih efektif jika suhu tubuh manusia (atau hewan) memiliki kontras yang tinggi terhadap suhu lingkungan. Contohnya: Orang di ruangan dingin (20°C) lebih mudah terdeteksi dibandingkan di ruangan panas (35°C).
3. Kecepatan Gerakan:
   - Gerakan lambat dapat membuat sensor kesulitan mendeteksi, karena perubahan pola IR terjadi perlahan.
4. Benda Non-Manusia:
   - Objek panas seperti api, atau benda yang memancarkan IR (misalnya lampu IR), juga dapat memicu sensor jika ada perubahan intensitas radiasi.

Wemos D1 R2 [Pinout](https://hobbycomponents.com/images/forum/wemos/Wemos_D1_HCWEMO0001_Pinout.png "Pinout") :

![pinout Wemos D1 R2](https://hobbycomponents.com/images/forum/wemos/Wemos_D1_HCWEMO0001_Pinout.png "Pinout")

Thanks To :
[hobbycomponents](https://hobbycomponents.com)
