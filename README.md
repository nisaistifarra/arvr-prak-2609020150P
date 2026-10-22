# Praktikum AR/VR - Pertemuan 1
- Nama : Nisa Istifarra
- NIM  : 2609020150P
- Link demo : https://nisaistifarra.github.io/arvr-prak-2609020150P/
Project ini berisi scene WebXR pertama menggunakan A-Frame 1.7.1.

1.  Mengapa posisi objek yang terlihat pertama kali oleh pengguna memakai nilai z negatif?
    Karena dalam A-Frame, kamera secara default menghadap ke arah sumbu Z negatif. Jadi, objek yang memiliki nilai Z negatif akan berada di depan kamera dan dapat terlihat oleh pengguna saat scene dibuka.

2.  Mengapa WebXR hanya aktif pada HTTPS atau localhost?
    Karena WebXR membutuhkan koneksi yang aman untuk mengakses fitur perangkat, seperti kamera, sensor gerak, dan headset VR. HTTPS menyediakan koneksi yang aman, sedangkan localhost dianggap aman untuk keperluan pengembangan dan pengujian di komputer sendiri.
    
3.  Jelaskan perbedaan peran WebXR Device API, three.js, dan A-Frame dengan bahasa Anda sendiri.
    - WebXR Device API adalah API browser yang menghubungkan aplikasi web dengan perangkat VR atau AR, seperti headset dan controller.
    - three.js adalah library JavaScript yang membantu membuat dan menampilkan objek serta lingkungan 3D di browser.
    - A-Frame adalah framework untuk membuat pengalaman 3D dan VR menggunakan elemen HTML, sehingga lebih mudah digunakan tanpa harus menulis  banyak kode JavaScript.