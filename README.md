# Dokumentasi Workshop: Building with AI, Managing Change with GitHub

Nama : Khalid Ahmad Fadillah

## Deskripsi Singkat mengenai Repository

Repository adalah dokumentasi kegiatan workshop yang memuat rangkuman materi (workshop Git/GitHub dan materi pengenalan akademik Program Studi D4 Teknik Informatika, MBKM/MSIB, serta Roadmap Jurusan TIK), poin penting, catatan pembelajaran, serta pendapat pribadi selama mengikuti workshop.

## Tujuan Repository

Repository dibuat untuk mengumpulkan dokumentasi kegiatan workshop, seperti materi yang disampaikan dan catatan pembelajaran selama workshop berlangsung. Melalui repository ini, diharapkan GitHub dapat dimanfaatkan sebagai media penyimpanan, pengelolaan, dan publikasi dokumentasi proyek secara daring.

## Rangkuman 

**Taktik menulis prompt yang efektif:**

- Gunakan kata kerja aksi untuk menentukan tindakan yang diinginkan.
- Tentukan panjang dan format keluaran.
- Sebutkan target audiens.
- Sertakan fakta dan data yang relevan.
- Rujuk sumber atau dokumen tertentu.
- Definisikan istilah dan konsep kunci.

**Keuntungan prompt engineering:**

- Meningkatkan performa model AI.
- Mengurangi bias dan respons yang ofensif.
- Meningkatkan kontrol dan prediktabilitas.
- Memberikan pengalaman pengguna yang lebih baik.

### 2. Git dan GitHub

Git adalah sistem version control terdistribusi (DVCS) yang melacak siapa, kapan, dan apa saja yang diubah dalam suatu file. Git diciptakan oleh Linus Torvalds pada tahun 2005.

GitHub adalah platform berbasis web untuk menyimpan repository Git secara daring dan mendukung kolaborasi.


### 3. Perintah Git Penting

```bash
git init                          # memulai repository baru
git add .                         # memindahkan file ke staging area
git commit -m "pesan"             # menyimpan perubahan ke repository
git remote add origin <url>       # menghubungkan ke repository GitHub
git push origin main              # mengirim perubahan ke GitHub
git pull origin main              # mengambil dan menggabungkan perubahan dari GitHub
git clone "url"                   # menyalin repository dari GitHub
```

### 6. Praktik: Student Task Planner

Alur praktik yang dibahas dalam workshop:

1. Install platform AI (Claude, Antigravity, ChatGPT).
2. Tulis prompt untuk membuat web/aplikasi.
3. Tambahkan ke Git dengan `git init`.
4. Commit dan push ke GitHub.
5. Lakukan perubahan.
6. Commit dan push kembali ke GitHub.

## Materi Pengenalan Akademik

Selain materi Git dan GitHub, terdapat tiga materi pengenalan akademik yang turut didokumentasikan di repository ini.

### A. Kurikulum OBE 2026 Program Studi D4 Teknik Informatika

Dipaparkan oleh **Bambang Warsuta, S.Kom., M.T.I.** (Kepala Program Studi Teknik Informatika D4 TI, Politeknik Negeri Jakarta).

| 8 | 49 | 145 |
| --- | --- | --- |
| semester | mata kuliah | SKS |

**Alur penyusunan kurikulum (disusun mundur):** Profil lulusan → Profesi → CPL (Capaian Pembelajaran Lulusan) → Mata kuliah. Pendekatan yang digunakan adalah *Outcome-Based Education* (OBE); lulusan bergelar **S.Tr.Kom** dengan kualifikasi **KKNI level 6**.

#### Empat Profil Lulusan

| Kode | Profil | Deskripsi | Contoh profesi |
| --- | --- | --- | --- |
| PL01 | Analis solusi | Menganalisis masalah nyata dan merumuskan solusi komputasi | System Analyst, Business Analyst IT, IT Consultant Junior, Solution Analyst |
| PL02 | Pengembang aplikasi | Merancang, membangun, menguji, dan mengevaluasi aplikasi | Software Developer, Web Developer, Mobile Application Developer, Software Quality Assurance, UI/UX Developer |
| PL03 | Penerap teknologi | Menerapkan data, AI, jaringan, cloud, dan keamanan siber | Data Analyst Junior, AI/ML Engineer Junior, Cloud Engineer Junior, Network Administrator, Cybersecurity Analyst Junior |
| PL04 | Profesional kolaboratif | Bekerja etis, komunikatif, kolaboratif, dan adaptif | IT Project Officer, IT Support Specialist, Technical Writer, Scrum Team Member, Technopreneur |

Profil dirumuskan dari *tracer study* lulusan 2021-2024, FGD dan diskusi dengan industri (*advisory board*), SKKNI, kajian kurikulum pembanding (*benchmark*), perkembangan IPTEKS, dan Permendiktisaintek Nomor 39 Tahun 2025.

**Profesi paling fundamental menurut mitra industri:** Data Engineer (PL03), AI Engineer (PL03), Sales Engineer (peran baru dari masukan mitra industri), dan Consultant (PL01).

#### Sebelas CPL

| CPL | Capaian |
| --- | --- |
| 01 | Bertakwa, taat hukum, disiplin, dan bertanggung jawab |
| **02** | **Sikap profesional dan etis, termasuk keamanan informasi** |
| 03 | Memahami sistem komputer; menerapkan algoritma dan metode komputasi |
| **04** | **Menganalisis persoalan komputasi kompleks dan merancang solusi TI** |
| 05 | Merancang dan mensimulasikan aplikasi *multi-platform* |
| **06** | **Berkomunikasi dan presentasi efektif, bekerja sama, dan memimpin dalam tim multidisiplin** (paling dibutuhkan di dunia kerja) |
| 07 | Menyusun laporan dan artikel ilmiah |
| **08** | **Mengimplementasikan kebutuhan komputasi dengan metode yang sesuai** |
| 09 | Merancang dan mengevaluasi antarmuka dan UX |
| 10 | Menerapkan metode analitis secara sistematis dan terukur |
| **11** | **Mengembangkan dan mengevaluasi solusi komputasi *multi-platform*** |

CPL 2, 4, 6, 8, dan 11 disorot berdasarkan hasil diskusi dengan *advisory board* sebagai indikator capaian CPL. Bukan berarti CPL lainnya tidak penting, karena tetap menjadi penopang.

**CPL prioritas per profil lulusan:**

PL01 Analis solusi | CPL 4, 8, 11 
PL02 Pengembang aplikasi | CPL 4, 8, 11 
Penerap teknologi | CPL 2, 8, 11 
Profesional kolaboratif | CPL 2, 4, 6 

#### Struktur Mata Kuliah per Semester

| Semester | SKS | Fokus |
| --- | --- | --- |
| 1 | 17 | Dasar: algoritma, struktur data, basis data, matematika |
| 2 | 18 | Dasar: algoritma, struktur data, basis data, matematika |
| 3 | 23 | Inti: PBO, rekayasa perangkat lunak, kecerdasan buatan, jaringan, keamanan siber |
| 4 | 23 | Inti: PBO, rekayasa perangkat lunak, kecerdasan buatan, jaringan, keamanan siber |
| 5 | 13 | Pendalaman: data besar, pembelajaran mesin, proyek, *stream* pilihan |
| 6 | 19 | Pendalaman: data besar, pembelajaran mesin, proyek, *stream* pilihan |
| 7 | 20 | Magang dan tugas akhir |
| 8 | 12 | Magang dan tugas akhir |

Pengelompokan: semester 1-2 = 35 SKS, semester 3-4 = 46 SKS, semester 5-6 = 32 SKS, semester 7-8 = 32 SKS. Semester 3 dan 4 adalah yang paling padat.


**Semester 1 (17 SKS):** Agama (2), Pancasila (2), Organisasi dan Arsitektur Komputer (2), Matematika Diskrit (3), Algoritma & Pemrograman (3), Sistem Operasi (3), Bahasa Inggris for IT (2).

**Semester 2 (18 SKS):** Kewarganegaraan (2), Hukum dan Kebijakan Teknologi Informasi (2), Etika Profesional (2), Struktur Data (3), Sistem Basis Data Dasar (3), Front End Programming (HTML, CSS, Framework) (3), Aljabar Linier (3).

**Semester 3 (23 SKS):** Desain UI dan UX (3), Pemrograman Berorientasi Objek (3), Fisika (2), Native Programming (3), Probabilitas & Statistika (3), Kecerdasan Buatan (3), Rekayasa Perangkat Lunak (2), Sistem Berbasis Pengetahuan (2), Manajemen Proyek TIK (2).

**Semester 4 (23 SKS):** Jaringan Komputer (3), Sistem Informasi Manajemen (2), Analisis dan Desain Sistem Informasi (3), Pemrograman Berbasis Framework (3), Basis Data Lanjut (3), Pengolahan Citra Digital (3), Keamanan Sistem Informasi & Siber (2), Penjaminan Mutu Perangkat Lunak (2), Bahasa Inggris Profesional (2).

**Semester 5 (13 SKS):** Big Data & Business Intelligence (3), Proyek Kekhususan 1 (3), Pembelajaran Mesin (3), Metode Penelitian 1 (2), IT Preneurship (2).

**Semester 6 (19 SKS, dihitung dengan satu stream pilihan):** Bahasa Indonesia (2), Pemrograman Mobile (3), Proyek Kekhususan 2 (3), Bahasa Inggris Komunikasi (2), serta pilih satu stream (9 SKS):
- *Stream KA:* Data Mining (3), Natural Language Processing (3), Computer Vision (3).
- *Stream RPL:* Sistem Informasi Geografis (3), Sistem Informasi Kesehatan / e-health (3), Emerging Technology (3).

**Semester 7 (20 SKS):** Magang (12), Tata Tulis Laporan Kerja (4), Metode Penelitian 2 (4).

**Semester 8 (12 SKS):** Tugas Akhir (8), Tata Tulis Laporan Ilmiah (4).

#### Strategi Belajar: *Make It Stick*

Pemaparan ditutup dengan ajakan merefleksikan cara belajar: *"Apakah cara belajarmu selama ini membuat kemampuan itu bertahan sampai kamu bekerja?"*

**Empat mitos belajar yang masih banyak dipercaya:**

| Mitos | Fakta |
| --- | --- |
| Membaca ulang berkali-kali adalah cara belajar terbaik | Membaca ulang terasa akrab, tetapi belum tentu dikuasai. Menguji diri lebih efektif |
| Belajar kebut semalam sebelum ujian sudah cukup | Materi cepat lupa. Sesi yang berjarak membuat ingatan bertahan lebih lama |
| Belajar yang baik harus mulus dan bebas salah | Kesulitan yang wajar dan kesalahan justru memperkuat ingatan jangka panjang |
| Setiap orang punya satu gaya belajar tetap (visual, auditori, dst.) | Bukti ilmiah tidak mendukung pencocokan gaya belajar. Strategi yang kuat berlaku untuk semua orang |


**Enam kebiasaan belajar:**

1. **Uji diri sendiri** (*retrieval practice*): tutup catatan, lalu tulis ulang apa yang diingat.
2. **Beri jeda** (*spaced practice*): ulangi materi dalam beberapa sesi berjarak, bukan sekali semalam.
3. **Campur topik** (*interleaving*): latih beberapa topik sekaligus agar terbiasa memilih cara yang tepat.
4. **Jelaskan dengan kata sendiri** (*elaboration*): kaitkan materi baru dengan yang sudah dikuasai, lalu jelaskan ke teman.
5. **Coba dulu, baru dibahas** (*generation*): mencoba soal sebelum diajari membuat pembahasan lebih melekat.
6. **Ukur diri secara jujur** (*calibration*): rasa paham setelah membaca sering keliru, gunakan kuis untuk menilai.

### B. Kurikulum Merdeka, MBKM, dan MSIB

Materi berjudul *"Kurikulum Merdeka di Perguruan Tinggi: Merdeka Belajar - Kampus Merdeka"*.

**Merdeka Belajar - Kampus Merdeka (MBKM)** adalah kebijakan Kemendikbudristek sejak 2020 yang memberi mahasiswa kesempatan mengasah kemampuan sesuai bakat dan minat, termasuk terjun langsung ke dunia kerja. Tujuan utamanya:

- Lulusan siap kerja dan relevan dengan kebutuhan industri.
- Pembelajaran fleksibel, tidak hanya di dalam kelas.
- Kegiatan di luar kampus diakui dan dikonversi menjadi SKS.

| MBKM | MSIB |
| --- | --- |
| Payung kebijakan | Program unggulan (Magang dan Studi Independen Bersertifikat) |
| Hak belajar hingga 2 semester di luar program studi | Dijalankan bersama mitra industri dan organisasi terbaik |
| 8 bentuk kegiatan pembelajaran di luar kelas | Berlangsung 1 semester dengan pengalaman belajar terstruktur |
| Kegiatan dikonversi menjadi 20 SKS oleh program studi | Peserta memperoleh sertifikat |
| Berlaku untuk seluruh perguruan tinggi, termasuk Politeknik Negeri Jakarta | Salah satu jalur pelaksanaan MBKM |

**Delapan bentuk kegiatan pembelajaran MBKM:** pertukaran pelajar, magang/praktik kerja, asistensi mengajar, penelitian/riset, proyek kemanusiaan, kegiatan wirausaha, proyek independen, dan membangun desa/KKN.

**Skema studi (ilustrasi program D4, 8 semester):** 1 semester di luar program studi namun dalam kampus yang sama, dan 1 semester di luar kampus (misalnya magang di industri). Konversi SKS ditetapkan program studi bersama dosen pembimbing.

**Dua jalur MSIB:**

- **Magang bersertifikat:** belajar sambil bekerja di mitra, mengerjakan tugas dan proyek nyata, serta dibimbing mentor dari industri.
- **Studi independen bersertifikat:** belajar kompetensi spesifik dari pakar berbasis tantangan nyata mitra industri, dalam bentuk *short course*, *bootcamp*, atau MOOC, dilanjutkan proyek atau studi kasus.

Keduanya berdurasi 1 semester, dikonversi menjadi 20 SKS, memperoleh sertifikat, dan membuka peluang rekomendasi ke mitra.

**Metode pembelajaran:**

| Metode | Ciri utama |
| --- | --- |
| Project-Based Learning (PjBL) | Belajar lewat karya nyata; umumnya berkelompok; hasil berupa produk, prototipe, aplikasi, atau laporan yang dipresentasikan |
| Problem-Based Learning (PBL) | Belajar lewat pemecahan masalah nyata tanpa jawaban tunggal; dosen sebagai fasilitator |
| Case-Based Learning (CBL) | Menganalisis kasus yang sudah tersedia melalui lima tahap: pelajari kasus, identifikasi masalah, analisis dan diskusi, rumuskan solusi, presentasi dan refleksi |

Kesamaan ketiganya: mahasiswa aktif, kerja tim, berbasis masalah nyata, dan melatih berpikir kritis.

**Manfaat bagi mahasiswa politeknik:** pengalaman kerja nyata, kompetensi relevan, jejaring profesional, serta sertifikat dan SKS yang diakui secara akademik.

**Alur mengikuti program Kampus Merdeka:**

1. Cek data PDDikti.
2. Buat akun di portal Kampus Merdeka dan aktifkan lewat email.
3. Pilih program magang atau studi independen dari mitra.
4. Daftar dan ikuti seleksi.
5. Jalani program, raih sertifikat, lalu ajukan konversi SKS ke program studi.

**Tips sukses:** kenali minat dan arah karier, konsultasi dengan dosen sejak awal, siapkan CV dan portofolio, rapikan data akademik, serta disiplin mendokumentasikan kegiatan harian. Selalu cek informasi resmi karena ketentuan, kuota, dan mitra dapat berubah tiap periode.

### C. Rencana Strategis Jurusan TIK 2026-2030

Materi berjudul *"Rencana Strategis JTIK: Roadmap 2026-2030, Pengenalan Akademik Jurusan TIK"* (Politeknik Negeri Jakarta), yang memuat arah pengembangan pendidikan vokasi, SDM, kemitraan, infrastruktur, dan inovasi digital.

**Visi:** menjadi jurusan bertaraf internasional untuk mendukung daya saing bangsa dalam bidang informatika dan komputer, dengan tiga kata kunci: **internasional** (standar dan jejaring global), **berdaya saing** (lulusan adaptif dan unggul), dan **berdampak** (inovasi untuk masyarakat).

**Misi:**

1. **Pendidikan vokasi:** menyelenggarakan pendidikan vokasi berbasis ilmu pengetahuan, teknologi, rekayasa, dan seni yang menghasilkan lulusan berkarakter dan bertakwa kepada Tuhan Yang Maha Esa.
2. **Riset dan inovasi:** mengembangkan penelitian serta produk inovasi berkualitas di bidang informatika dan komputer untuk meningkatkan daya saing bangsa.
3. **Tata kelola digital:** mengembangkan jurusan yang efisien, efektif, dan akuntabel berbasis teknologi informasi dan komunikasi.

**Lima agenda pengembangan:**

| No | Agenda | Cakupan |
| --- | --- | --- |
| 01 | Penguatan internal TIK | Tata kelola, proses kerja, dokumentasi, dan layanan |
| 02 | Kerja sama institusi dan industri | Kemitraan strategis dan kolaborasi berkelanjutan |
| 03 | Pengembangan SDM TIK | Pemetaan profil, peningkatan kompetensi, dan distribusi kegiatan |
| 04 | Sarana, prasarana, dan infrastruktur | Pengelolaan fasilitas pembelajaran dan laboratorium |
| 05 | Inkubator bisnis TIK | Pengembangan produk, *technopreneurship*, dan hilirisasi |

**Kerangka implementasi:** enam bidang kerja (pendidikan vokasi; riset dan pengabdian masyarakat; SDM dan kompetensi; sarpras dan infrastruktur; inkubator bisnis; mahasiswa dan kemitraan) yang ditopang oleh dokumentasi, data profil SDM, monitoring, dan evaluasi.

**Mitra yang tercantum:** CCIT, MSU, Dinkes Depok, Pemkot Depok, Agate, Cisco, Huawei, Oracle, LZPU/Hopu, QCU, dan PT. Argios.

## Poin Penting

- **Prompt yang spesifik menghasilkan output yang lebih baik.** Gunakan struktur Role, Task, Context, dan Format, serta minta AI memverifikasi hasilnya sebelum menyatakan berhasil.
- **Git dan GitHub berbeda.** Git bekerja secara lokal untuk melacak perubahan, sedangkan GitHub menyimpan repository secara daring dan memudahkan kolaborasi.
- **Alur dasar version control:** working directory → staging area → repository (commit) → GitHub (push).
- **Commit yang rutin dan pesan yang jelas** membuat riwayat perubahan mudah ditelusuri.
- **SSH key** membuat autentikasi ke GitHub lebih aman dan praktis.
- **AI mempercepat pembuatan, Git mengelola perubahan.** Keduanya saling melengkapi dalam proses membangun produk.
- **Kurikulum OBE 2026 disusun mundur** dari profil lulusan ke CPL, lalu ke 49 mata kuliah (145 SKS, 8 semester).
- **CPL 6 (komunikasi dan kerja tim)** adalah yang paling dibutuhkan dunia kerja, sehingga kemampuan teknis perlu diimbangi soft skill.
- **Semester 7 dan 8 dikhususkan untuk magang dan tugas akhir**, sehingga pengalaman industri menjadi bagian inti studi.
- **MBKM dan MSIB** memungkinkan kegiatan di luar kelas dikonversi menjadi 20 SKS dan disertai sertifikat.
- **Belajar yang bertahan lama** membutuhkan usaha: uji diri, beri jeda, campur topik, dan jelaskan dengan kata sendiri, bukan sekadar membaca ulang.
- **Roadmap JTIK 2026-2030** berfokus pada pendidikan vokasi, riset dan inovasi, serta tata kelola digital menuju jurusan bertaraf internasional.

## Pendapat tentang Workshop

Workshop ini menurut saya sangat bermanfaat karena menggabungkan dua keterampilan yang relevan: memanfaatkan AI untuk membangun sesuatu dan mengelola hasilnya dengan Git dan GitHub. Penjelasan bahwa konteks menentukan kualitas hasil AI membuat saya sadar bahwa menulis prompt perlu direncanakan, bukan asal mengetik. Dari sisi Git, pemisahan antara working directory, staging area, dan repository membantu saya memahami alur version control dengan lebih jelas. Praktik membuat Student Task Planner juga membantu menghubungkan teori dengan hasil nyata.
Ke depan, saya berharap dapat menerapkan alur ini pada proyek-proyek lain, mulai dari membuat prototipe dengan bantuan AI hingga mendokumentasikan dan mempublikasikannya melalui GitHub.
