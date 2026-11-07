# Day-1-FarCry_5_Khalid_Ahmad_Fadillah
Repository ini berisi dokumentasi kegiatan workshop From AI to GitHub: Building with AI, Managing Change with GitHub

## Identitas
Nama lengkap: Khalid Ahmad Fadillah

## Deskripsi Singkat
Repository ini adalah dokumentasi kegiatan workshop yang memuat rangkuman materi, poin penting, catatan pembelajaran, serta pendapat pribadi selama mengikuti workshop.

## Tujuan Repository
Repository ini dibuat untuk mengumpulkan dokumentasi kegiatan workshop, seperti materi yang disampaikan dan catatan pembelajaran selama workshop berlangsung. Melalui repository ini, diharapkan GitHub dapat dimanfaatkan sebagai media penyimpanan, pengelolaan, dan publikasi dokumentasi proyek secara daring.

## Informasi Kegiatan Workshop
| Judul | From AI to GitHub: Building with AI, Managing Change with GitHub |
| Pemateri | Nugi Farhan (Senior Product Designer, 6 tahun pengalaman) |
| Topik 1 | Membuat dan mengembangkan sesuatu dengan AI (Prompt Engineering) |
| Topik 2 | Manajemen perubahan dan kolaborasi dengan Git dan GitHub |
| Proyek praktik | Student Task Planner (aplikasi web sederhana) |

### Capaian Pembelajaran
- Dapat menjelaskan bagaimana prompt AI yang lebih spesifik menghasilkan hasil yang lebih baik.
- Dapat membedakan Git dan GitHub.
- Dapat mengidentifikasi repository, commit, branch, dan pull request.
- Dapat melakukan version controlling.

## Rangkuman Materi

### 1. Prompt Engineering
Prompt adalah instruksi atau masukan yang diberikan kepada model AI untuk mendapatkan hasil tertentu. Bentuknya beragam: pertanyaan sederhana, kata kunci, instruksi rumit, hingga potongan kode. Prompt engineering adalah cara merancang instruksi agar AI memberikan jawaban yang tepat, relevan, dan layak digunakan. Prompt singkat seperti "Create student task planner" menghasilkan keluaran yang kurang terarah, sedangkan prompt dengan konteks yang jelas menghasilkan hasil yang jauh lebih sesuai kebutuhan.

Taktik menulis prompt yang efektif:
- Gunakan kata kerja aksi untuk menentukan tindakan yang diinginkan.
- Tentukan panjang dan format keluaran.
- Sebutkan target audiens.
- Sertakan fakta dan data yang relevan.
- Rujuk sumber atau dokumen tertentu.
- Definisikan istilah dan konsep kunci.

Keuntungan prompt engineering:
- Meningkatkan performa model AI.
- Mengurangi bias dan respons yang ofensif.
- Meningkatkan kontrol dan prediktabilitas.
- Memberikan pengalaman pengguna yang lebih baik.

### 2. Git dan GitHub
Git adalah sistem version control terdistribusi (DVCS) yang melacak siapa, kapan, dan apa saja yang diubah dalam suatu file. Git diciptakan oleh Linus Torvalds pada tahun 2005.
GitHub adalah platform berbasis web untuk menyimpan repository Git secara daring dan mendukung kolaborasi.
Alur kerjanya: Working Directory → (stage) → Staging Area → (commit) → Repository

### 3. Perintah Git Penting
git init                          # memulai repository baru
git add .                         # memindahkan file ke staging area
git commit -m "pesan"             # menyimpan perubahan ke repository
git remote add origin <url>       # menghubungkan ke repository GitHub
git push origin main              # mengirim perubahan ke GitHub
git pull origin main              # mengambil dan menggabungkan perubahan dari GitHub
git clone "url"                   # menyalin repository dari GitHub

## Poin Penting
- Prompt yang spesifik menghasilkan output yang lebih baik. Gunakan struktur Role, Task, Context, dan Format, serta minta AI memverifikasi hasilnya sebelum menyatakan berhasil.
- Git dan GitHub berbeda. Git bekerja secara lokal untuk melacak perubahan, sedangkan GitHub menyimpan repository secara daring dan memudahkan kolaborasi.
- Alur dasar version control: working directory → staging area → repository (commit) → GitHub (push).
- Commit yang rutin dan pesan yang jelas membuat riwayat perubahan mudah ditelusuri.
- SSH key membuat autentikasi ke GitHub lebih aman dan praktis.
- AI mempercepat pembuatan, Git mengelola perubahan. Keduanya saling melengkapi dalam proses membangun produk.

## Pendapat tentang Workshop
Workshop ini menurut saya sangat bermanfaat karena menggabungkan dua keterampilan yang relevan: memanfaatkan AI untuk membangun sesuatu dan mengelola hasilnya dengan Git dan GitHub. Penjelasan bahwa konteks menentukan kualitas hasil AI membuat saya sadar bahwa menulis prompt perlu direncanakan, bukan asal mengetik. Dari sisi Git, pemisahan antara working directory, staging area, dan repository membantu saya memahami alur version control dengan lebih jelas. Praktik membuat Student Task Planner juga membantu menghubungkan teori dengan hasil nyata. Ke depan, saya berharap dapat menerapkan alur ini pada proyek-proyek lain, mulai dari membuat prototipe dengan bantuan AI hingga mendokumentasikan dan mempublikasikannya melalui GitHub.

## Sumber
- Materi workshop *"From AI to GitHub: Building with AI, Managing Change with GitHub"* oleh Nugi Farhan.
- Referensi prompt engineering: https://cloud.google.com/discover/what-is-prompt-engineering
