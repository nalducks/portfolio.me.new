
# Portfolio Website
Portfolio Website ini merupakan situs web personal yang menampilkan berbagai bagian seperti Home, About, Experience, Education, Projects, dan Contact. Situs ini dibangun menggunakan HTML, CSS, dan JavaScript dengan fitur responsif untuk mendukung tampilan di berbagai perangkat.

# Fitur
Loader: Tampilan animasi loading saat halaman dimuat.
Navbar & Sidebar: Navigasi dengan menu dropdown dan sidebar yang muncul dari bawah navbar.
Responsive Design: Tampilan yang disesuaikan untuk layar besar (desktop) hingga layar kecil (mobile).
Lazy Loading: Penggunaan Intersection Observer untuk memuat gambar secara dinamis saat dibutuhkan.
Visitor Counter: Melacak jumlah pengunjung menggunakan Local Storage.
Theme & Favicon Update: Pengaturan tema dan pembaruan favicon secara otomatis.

# Struktur Proyek
graphql
Salin
Edit
portfolio/
├── index.html           # Halaman utama portfolio
├── css/
│   └── style.css        # File CSS utama untuk styling portfolio
├── js/
│   └── main.js          # File JavaScript untuk interaksi, loader, lazy loading, dsb.
├── images/              # Folder gambar (misal: favicon, gambar profil, project images, dsb.)
└── README.md            # File ini

# Cara Menjalankan
Clone atau Download Repository

bash
Salin
Edit
git clone https://github.com/username/portfolio.git
Buka File HTML

Buka file index.html di browser Anda secara langsung atau gunakan Live Server (misalnya melalui VS Code) untuk melihat tampilan dan interaksi.
Teknologi yang Digunakan
HTML5: Untuk struktur halaman.
CSS3: Untuk styling dan responsive design (menggunakan media queries).
JavaScript (ES6): Untuk interaksi, animasi loader, lazy loading, visitor tracking, dan navigasi.
Local Storage: Untuk menyimpan data tema dan jumlah pengunjung.

# Cara Menyesuaikan
Styling: Edit file css/style.css untuk mengubah tampilan atau menyesuaikan layout sesuai kebutuhan.
JavaScript: Modifikasi file js/main.js untuk menambah atau mengubah interaksi (misal: penambahan kelas active pada sidebar atau menu).

# Penggunaan
Navigasi: Gunakan navbar di bagian atas untuk berpindah antar section. Sidebar dapat diaktifkan melalui tombol menu (btnBar) untuk tampilan mobile.
Lazy Loading: Gambar dengan atribut data-src akan termuat secara otomatis ketika berada di area viewport.
Visitor Counter: Jumlah pengunjung ditampilkan di elemen dengan ID visitorCount (pastikan elemen tersebut ada di HTML).
# License
Project ini bersifat open-source dan dapat digunakan serta dikembangkan sesuai kebutuhan.

# Author
# Dhany Catur Prasetya #
