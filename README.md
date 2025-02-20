## Laporan Praktikum

|  | Pemrograman Berbasis Framework 2024 |
|--|--|
| NIM |  244107027013|
| Nama |  Muhammad Hafidz Setyawan |
| Kelas | TI - 4K RPL |


### Jawaban Soal 1

1. Git adalah sistem kontrol versi yang digunakan untuk melacak perubahan pada kode sumber dalam pengembangan perangkat lunak. Kegunaannya antara lain: Mengelola Versi Kode – Memungkinkan developer menyimpan riwayat perubahan kode dan kembali ke versi sebelumnya jika terjadi kesalahan. Kolaborasi – Memudahkan kerja tim dalam pengembangan perangkat lunak melalui platform seperti GitHub, GitLab, dan Bitbucket.
Branching & Merging – Dapat membuat cabang (branch) untuk mengembangkan fitur baru tanpa mengganggu kode utama, lalu menggabungkannya kembali (merge) setelah selesai.

VS Code adalah editor kode yang ringan namun memiliki banyak fitur yang membantu dalam pengembangan perangkat lunak. Kegunaannya antara lain:
Menulis dan Mengedit Kode – Mendukung berbagai bahasa pemrograman seperti JavaScript, Python, PHP, dan lainnya.
Fitur IntelliSense – Menyediakan saran kode dan debugging untuk meningkatkan efisiensi coding.
Terminal Terintegrasi – Memungkinkan penggunaan perintah Git dan Node.js langsung di dalam VS Code.
Ekstensi & Kustomisasi – Memiliki banyak ekstensi untuk meningkatkan fungsionalitas, seperti integrasi dengan GitHub, linting, dan debugging.

Node.js adalah runtime JavaScript yang berjalan di sisi server. Kegunaannya antara lain:
Menjalankan JavaScript di Server – Memungkinkan pengembangan backend menggunakan JavaScript.
Membangun API & Aplikasi Web – Banyak digunakan dalam pengembangan aplikasi berbasis web, terutama dengan framework seperti Express.js.
Mengelola Paket dengan npm – npm (Node Package Manager) memungkinkan instalasi dan manajemen dependensi untuk proyek JavaScript.
Non-blocking I/O – Cocok untuk aplikasi real-time seperti chat, streaming, dan API berbasis event-driven.

2. ![alt text](<Screenshot (53).png>)
   ![alt text](<Screenshot (54).png>)

### Jawaban Soal 2

1. TypeScript adalah superset dari JavaScript yang dikembangkan oleh Microsoft, menambahkan tipe statis untuk meningkatkan keamanan dan kejelasan kode. Dengan TypeScript, pengembang dapat mendeteksi kesalahan lebih awal melalui pemeriksaan tipe, sehingga lebih aman dan efisien dalam proyek skala besar. ESLint adalah alat linter yang digunakan untuk memeriksa dan memperbaiki kode JavaScript dan TypeScript, membantu menjaga konsistensi serta mencegah potensi bug dengan aturan yang bisa disesuaikan. Tailwind CSS adalah framework CSS berbasis utility-first yang memungkinkan pengembang membangun antarmuka pengguna dengan cepat menggunakan class siap pakai, mengurangi kebutuhan penulisan CSS kustom.
Sementara itu, App Router dalam Next.js adalah sistem routing terbaru yang berbasis React Server Components, memungkinkan rendering yang lebih efisien dengan dukungan layout global dan pemisahan kode antara sisi server dan client. Untuk mempermudah manajemen kode, Import Alias digunakan agar pengembang dapat mengimpor modul dengan path yang lebih pendek dan mudah dibaca, menghindari kesalahan saat perubahan struktur folder. Terakhir, Turbopack adalah bundler modern yang dikembangkan oleh Vercel sebagai penerus Webpack, ditulis dalam Rust untuk performa yang jauh lebih cepat, terutama dalam pengembangan aplikasi berbasis Next.js dengan peningkatan hot module replacement (HMR).

2. Dalam struktur proyek React pada tahap percobaan ke-3, terdapat beberapa folder dan file dengan kegunaan masing-masing. Folder **`node_modules/`** berisi semua dependensi atau paket yang diinstal melalui npm atau yarn dan dibuat secara otomatis setelah menjalankan `npm install`. Folder **`public/`** digunakan untuk menyimpan aset statis seperti `index.html`, yang merupakan template HTML utama untuk merender aplikasi, serta `favicon.ico`, ikon kecil yang muncul di tab browser. Folder **`src/`** adalah tempat utama kode sumber React, berisi file seperti `App.js` atau `App.tsx`, yang menjadi komponen utama aplikasi, serta `index.js` atau `index.tsx`, yang berfungsi sebagai entry point untuk merender aplikasi ke dalam `index.html`.  
Selain itu, dalam **`src/`** biasanya terdapat folder **`components/`** yang menyimpan berbagai komponen React, **`pages/`** yang digunakan untuk mengelola halaman aplikasi jika menggunakan React Router, serta **`styles/`** atau **`assets/`** untuk menyimpan file CSS, gambar, dan aset lainnya. File **`.gitignore`** berfungsi untuk mengabaikan file atau folder tertentu agar tidak dimasukkan ke dalam sistem kontrol versi Git, seperti `node_modules/`. **`package.json`** berisi informasi proyek, daftar dependensi, serta skrip yang digunakan dalam pengembangan aplikasi, sedangkan **`package-lock.json`** mengunci versi dependensi untuk memastikan aplikasi tetap konsisten di berbagai lingkungan pengembangan. Terakhir, **`README.md`** biasanya digunakan sebagai dokumentasi proyek yang berisi petunjuk penggunaan dan informasi penting lainnya.

3. ![alt text](<Screenshot (55).png>)

### Jawaban Soal 3

1. ![alt text](<Screenshot (56)-2.png>)

### Jawaban Soal 4

1. Sintaks **`user.imageUrl`** digunakan untuk mengakses properti **`imageUrl`** dari objek **`user`**, yang biasanya berisi URL gambar profil pengguna. Dalam JavaScript atau React, ini sering digunakan untuk menampilkan gambar dalam elemen **`<img>`**, seperti pada kode `<img src={user.imageUrl} alt="User Profile" />`, sehingga gambar pengguna dapat muncul di halaman web. Jika objek **`user`** tidak memiliki properti **`imageUrl`**, penggunaan **optional chaining (`user?.imageUrl`)** dapat mencegah error akibat nilai yang tidak terdefinisi. Dengan demikian, sintaks ini mempermudah pengelolaan dan penggunaan data pengguna dalam berbagai skenario, terutama dalam pengembangan antarmuka aplikasi berbasis web.

2. ![alt text](<Screenshot (57).png>)
