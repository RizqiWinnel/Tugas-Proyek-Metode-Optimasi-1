# Tugas-Proyek-Metode-Optimasi-1
Judul: Optimasi Sistem Penjadwalan Antrian Teller Bank Berbasis Algoritma Genetika

Algoritma genetika (GA) merupakan algoritma yang berbasis populasi yang memungkinkan digunakan pada masalah optimasi dengan ruang pencarian (search space) yang sangat luas dan kompleks. Properti ini juga memungkinkan GA untuk melompat keluar dari daerah optimum lokal.

GA terdiri dari tahapan utama:
1. Representasi solusi/kromosom (encoding)
2. Pembangkitan populasi
3. Perhitungan nilai fitness
4. Seleksi
5. Crossover
6. Mutasi

Kasus:
Di sebuah bank yang beroperasi setiap hari kerja mulai pukul 08.00 hingga pukul 16.00, dengan total jam operasional selama 8 jam. Dalam operasionalnya, bank menyediakan maksimal 5 teller yang dapat diaktifkan sesuai kebutuhan. Berdasarkan hasil observasi, setiap teller mampu melayani rata-rata 5 nasabah per jam. Namun, jumlah kedatangan nasabah setiap jam tidak selalu sama dan cenderung meningkat tajam pada jam-jam tertentu. Ketidakseimbangan antara jumlah teller yang diaktifkan dan banyaknya nasabah yang datang berpotensi menimbulkan waktu tunggu yang panjang di sisi nasabah atau bahkan waktu menganggur pada pihak teller. Oleh karena itu, permasalahan yang timbul adalah bagaimana menentukan jumlah teller yang optimal pada setiap jam operasional bank agar sistem antrian dapat berjalan secara efisien, dengan waktu tunggu nasabah yang minimum dan pemanfaatan teller yang maksimal.
