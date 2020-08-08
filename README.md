# SubmissionMPWA-DicodingAcademy

Kriteria Submission
Berikut kriteria submission yang harus Anda penuhi:

Menampilkan minimal 2 halaman yang mengonsumsi data dari website football-data.org.
Tetap bisa dipakai meskipun status sedang offline (menerapkan cache).
Memiliki fitur penyimpanan data dengan indexed db (bisa menambahkan, menampilkan, dan menghapus tim favorit, jadwal nonton, dsb.) dengan satu halaman khusus untuk menampilkan data yang disimpan.
Dapat menampilkan pesan push dari server (untuk simulasi pesan push dikirim menggunakan Firebase Cloud Messaging). 
Dapat ditambahkan ke homescreen.
Memiliki splash screen.
Kode pada Service Worker harus berbasis Workbox 
Diunggah ke Firebase Hosting atau Github Pages (sertakan link menuju Firebase Hosting dan Github Pages di file hosting.txt)
 

Daftar Endpoint Football Data ORG
Ganti {id_liga} dengan salah satu nomor liga berikut:

Champions League = 2001
Liga Jerman = 2002
Liga Belanda = 2003
Liga Inggris = 2021
Liga Spanyol = 2014
Liga Perancis = 2015
atau dengan menggunakan kode yang terdapat di halaman https://www.football-data.org/docs/v2/index.html#league_codes

Ganti {id_tim} dengan id tim (bisa dilihat dari standing). 

Klasemen Liga: https://api.football-data.org/v2/competitions/{id_liga}/standings
Informasi Tim: https://api.football-data.org/v2/teams/{id_tim}
Jadwal Tanding Tim: https://api.football-data.org/v2/teams/{id_tim}/matches?status=SCHEDULED
Endpoint lainnya: https://www.football-data.org/documentation/quickstart
 

Saran Submission
Submission Anda akan dinilai oleh reviewer dengan penilaian bintang berskala 1-5 berdasarkan dari parameter yang ada.

Anda dapat menerapkan beberapa saran untuk mendapatkan nilai tinggi, berikut sarannya:

Menerapkan saran yang diberikan reviewer pada submission sebelumnya.

Detail penilaian submission:

Bintang 1 : Semua ketentuan terpenuhi, namun terdapat indikasi plagiat yaitu dengan menggunakan proyek orang lain dan hanya mengubah kontennya saja.
Bintang 2 : Semua ketentuan terpenuhi, namun web app yang dikirimkan masih terdapat bug yang mengganggu. Kode yang dituliskan masih perlu banyak yang diimprovisasi.
Bintang 3 : Semua ketentuan terpenuhi, web app berjalan dengan baik, kode yang dituliskan masih banyak yang perlu diimprovisasi.
Bintang 4 : Semua ketentuan terpenuhi, web app berjalan dengan baik, tidak membuat pengguna kebingungan menggunakannya. Kode yang dituliskan rapi, memisahkan kode pada berkas JavaScript yang berbeda sesuai tanggung jawabnya. Memiliki tampilan yang menarik, serta responsif.
Bintang 5 : Semua ketentuan terpenuhi, memiliki semua kriteria point ke 4. Menerapkan modular dalam menuliskan kode, atau menggunakan build tools, module bundler.
Jika submission Anda ditolak maka tidak ada penilaian. Kriteria penilaian bintang di atas hanya berlaku jika submission Anda lulus.



Submission yang Tidak Sesuai Kriteria
Jika submission Anda tidak sesuai dengan kriteria, maka akan ditolak oleh reviewer, berikut poin-poinnya:

Tidak memenuhi kriteria yang ditentukan.
Aplikasi yang dideploy tidak dapat berjalan sesuai kriteria yang ditentukan (pastikan proyek berjalan normal pada local maupun hosting).
Tidak menyertakan link github pages atau firebase hosting dari aplikasi yang dibuat.
Menuliskan event install, activate, dan push secara manual (tidak memanfaatkan API dari Workbox, khusus untuk event push harus tetap dipertahankan).
