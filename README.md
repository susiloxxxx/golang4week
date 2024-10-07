# golang4week
fast track learning golang for restfull API on 4 week
Untuk belajar Go dan Go Fiber secara efisien dalam rangka membangun REST API, saya akan membuat silabus step-by-step yang fokus pada hal-hal yang paling penting. Ini mencakup pengenalan dasar Go, serta aspek-aspek utama dalam pengembangan backend REST API. Saya akan membagi langkah-langkah ini menjadi beberapa tahap sehingga kamu bisa mengikuti secara bertahap dan efisien.


## first you need update golang

`git clone https://github.com/udhos/update-golang`
`cd update-golang`
`sudo ./update-golang.sh`


Silabus Belajar Golang dan Fiber untuk REST API
Tahap 1: Pengenalan dan Dasar Golang (2-3 hari)
Instalasi Go:

Instal Go di komputer kamu. (https://golang.org/doc/install)
Pelajari struktur project Go.
Dasar-Dasar Pemrograman Go:

Hello World dan pengenalan tentang package main dan func main().
Variabel, Tipe Data, dan Konstanta: Belajar cara mendeklarasikan variabel, tipe data dasar, dan konstanta di Go.
Kontrol Flow: If-else, for loops, dan switch.
Fungsi: Cara mendefinisikan fungsi, parameter, dan return values.
Struktur Data Dasar:

Array, Slice, dan Map: Pelajari cara menggunakan array, slice, dan map di Go.
Pointer: Pengantar pointer dan bagaimana Go menangani nilai dan referensi.
Error Handling:

Cara mengembalikan dan menangani error di Go dengan baik (error interface).
Goroutines & Concurrency (Pengantar):

Pelajari pengenalan tentang goroutines dan channel untuk concurrency di Go. Walaupun ini lebih lanjut, pemahaman dasar akan membantu nantinya dalam optimasi aplikasi API.
Tahap 2: Go Intermediate (3-4 hari)
Struct dan Interface:

Pelajari cara membuat struct dan mendefinisikan metode untuk struct.
Interface: Cara mendefinisikan dan menggunakan interface untuk menulis kode yang lebih fleksibel dan reusable.
Package dan Modularity:

Pelajari cara memisahkan kode ke dalam package dan menggunakan package pihak ketiga.
Go Modules: Pahami penggunaan go mod untuk manajemen dependensi.
Testing:

Pelajari cara menulis unit test dengan Go's testing package.
Table-Driven Tests: Menulis tes dalam bentuk table-driven untuk berbagai skenario.
Tahap 3: Fiber Framework dan REST API (7-10 hari)
Instalasi Go Fiber dan Pengantar:

Instalasi Go Fiber (https://gofiber.io/).
Pengantar tentang Fiber dan strukturnya, mengapa ini lebih cepat dan ringan.
Membangun REST API Sederhana:

Membuat endpoint sederhana untuk GET, POST, PUT, DELETE.
Pelajari cara parsing JSON request dan mengirim JSON response.
Cara menangani URL parameter dan query parameter di Fiber.
Routing dan Middleware:

Pelajari tentang routing dan bagaimana Fiber mengelola berbagai routes.
Middleware: Pelajari bagaimana menambahkan middleware seperti logging, CORS, dan autentikasi.
Database Integration (PostgreSQL/MySQL):

Instalasi driver database (seperti pgx untuk PostgreSQL atau go-sql-driver/mysql untuk MySQL).
Pelajari cara menghubungkan Go Fiber dengan database, membuat koneksi, dan menjalankan query sederhana (CRUD).
ORM (GORM atau Ent):

Pilih ORM (GORM atau Ent) untuk mempermudah interaksi dengan database.
Implementasikan model dan migration menggunakan ORM yang dipilih.
Error Handling dan Validasi:

Pelajari cara menangani error dengan baik dalam aplikasi REST API.
Gunakan library validasi seperti go-playground/validator untuk memvalidasi input request.
Session dan Autentikasi (JWT):

Implementasi autentikasi dengan JWT (JSON Web Token) di Fiber.
Menyimpan dan mengelola sesi pengguna.
Tahap 4: Deployment dan Optimasi (5-7 hari)
Environment Configuration:

Gunakan package seperti godotenv untuk mengelola environment variables.
Dockerization:

Buat Dockerfile untuk mengemas aplikasi Go Fiber ke dalam container.
Belajar tentang Docker Compose untuk manajemen container database dan aplikasi secara bersamaan.
Logging dan Monitoring:

Implementasi logging dengan package seperti logrus atau zap.
Integrasi alat monitoring seperti Prometheus atau Grafana untuk melacak performa API.
Testing API:

Gunakan alat seperti Postman atau Insomnia untuk menguji API.
Implementasi integration testing untuk API dengan Fiber.
Deployment:

Belajar deployment aplikasi di cloud platform seperti Heroku, DigitalOcean, atau AWS.
Optimalkan aplikasi untuk performa dan scalability.
Catatan Tambahan:
Waktu Total: Sekitar 3-4 minggu dengan asumsi belajar intensif.
Praktik Langsung: Untuk efisiensi, cobalah untuk mempraktikkan setiap langkah segera setelah belajar teori, terutama saat membangun REST API.
Dengan mengikuti langkah-langkah ini secara berurutan, kamu bisa mencapai efisiensi dalam mempelajari Go dan Fiber untuk pengembangan REST API tanpa membuang banyak waktu.
