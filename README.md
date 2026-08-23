# Panduan Penggunaan AI untuk Mahasiswa DDP 1

Selamat datang di panduan pemanfaatan *Artificial Intelligence* (Generative AI) dalam perkuliahan pemrograman Anda. Panduan ini dibuat dikarenakan Generative AI, seperti ChatGPT, Gemini, Claude, berkembang sangat cepat belakangan ini dan menjadi bagian dari kehidupan sehari-hari. Bagi Anda sebagai seorang mahasiswa baru mungkin akan bertanya-tanya apakah saya diperbolehkan menggunakannya atau dilarang atau bagaimana dampaknya pada proses pembelajaran bagi saya?

---

## 1. Apa itu *Artificial Intelillegence*?
Definisi mengenai Kecerdasan Buatan (Artificial Intelligence atau AI) sangat beragam dan maknanya terus bergeser tergantung pada konteks pengembangannya. Sejak komputer mulai bermunculan pada dekade 1950-an, para ilmuwan berusaha merancang mesin yang mampu memiliki kecerdasan layaknya manusia. Dari sinilah berbagai algoritma dan bahasa pemrograman mulai dikembangkan agar komputer dapat melakukan tugas-tugas kognitif seperti belajar, beradaptasi, memecahkan masalah (problem solving), hingga mengambil keputusan. 

### Sejarah Perkembangan AI
Jika melihat sejarahnya, perkembangan AI dimulai sekitar tahun 1950-an oleh Alan Turing melalui Turing Test, yang dirancang untuk menguji apakah mesin bisa meniru kecerdasan manusia. Jaringan saraf tiruan (neural networks) pertama juga mulai digunakan pada era ini untuk membantu pengenalan pola dan pemodelan prediktif. Pada tahun 1960-an, chatbot ELIZA diciptakan di MIT sebagai program Natural Language Processing pertama. Sayangnya, penelitian AI sempat terhenti di antara tahun 1960-an hingga 1970-an karena kurangnya dana penelitian, fase yang dikenal sebagai AI Winter. 

Pendaran riset kembali bangkit pada tahun 1990-an melalui dukungan komputasi dari IBM serta perkembangan komputer dan internet. Meningkatnya adopsi internet, kapasitas komputasi yang lebih besar, dan melimpahnya data manusia mendorong kemajuan teknologi AI secara stabil. Hingga akhirnya sejak tahun 2021 ke atas, peluncuran ChatGPT pada tahun 2022 memulai era AI boom dengan kemampuan AI yang jauh lebih akurat dan bertenaga.

### Definisi AI
Secara sederhana, **Artificial Intelligence (AI)** adalah sistem komputasi yang dirancang untuk menjalankan berbagai tugas dengan cara menerima *input* dan menghasilkan *output*. *Input* yang dimasukkan bisa sangat beragam—mulai dari teks, gambar, suara, hingga video. *Input* tersebut kemudian diproses oleh mesin untuk menghasilkan *output* berupa prediksi, pembuatan konten baru, rekomendasi, hingga keputusan yang dipakai oleh kita.

Secara matematis, konsep kerja AI dapat diringkas melalui persamaan fungsi matematika sbb:

$$f(x) = y$$

* **$x$** merepresentasikan **Input** (data atau perintah yang Anda berikan).
* **$y$** merepresentasikan **Output** (hasil, prediksi, atau respons dari AI).
* **$f(x)$** merepresentasikan **Model AI** itu sendiri.

### Perbedaan AI dengan Pemrograman Konvensional

Hal yang membedakan AI dengan pemrograman biasa terletak pada bagaimana fungsi $f(x)$ tersebut dibuat:

1. **Pemrograman Konvensional (*Hard-coded*):** Pemrogram (*programmer*) menulis aturan dan logika secara eksplisit di dalam kode untuk mengubah $x$ menjadi $y$.
2. **Artificial Intelligence (*Data-driven*):** Pemrogram tidak menulis kodenya secara manual, melainkan melatih (*training*) fungsi $f(x)$ menggunakan kumpulan data yang sangat besar. 

Model AI mempelajari pola-pola dari data tersebut untuk memetakan setiap kemungkinan *input* ke *output* berdasarkan **probabilitas**. Oleh karena itu, kualitas dan karakter *output* ($y$) yang Anda dapatkan akan sangat bergantung pada bagaimana fungsi $f(x)$ dibentuk, yang mana sangat dipengaruhi oleh data yang digunakan saat proses pelatihan.

---

> **Catatan Akademis:**  
> Konsep probabilitas dan pemetaan statistik ini akan Anda pelajari secara mendalam pada mata kuliah **Statistika dan Probabilitas** dan **KASDD**. Pemahaman mendasar ini akan menjadi fondasi penting ketika Anda mengambil mata kuliah lanjutan di ranah AI, seperti **Machine Learning (ML)** dan **Deep Learning (DL)**.

## Pengaplikasian AI di Pemrograman
Sebenarnya ada banyak jenis sistem AI tergantung dengan tujuan dan data latihnya. Di satu sisi, Anda mungkin menyadari bahwa Anda sedang memanfaatkan AI seperti pada saat menggunakan Claude, di sisi lain Anda mungkin sedang tidak sadar ketika menggunakan AI, yaitu seperti memprediksi kata berikutnya saat Anda mengetik di HP Anda.

Di sisi pemrograman, AI bukanlah suatu hal yang baru. Sebelum ChatGPT populer, banyak tools yang dipakai programmer sehari-hari sudah menggunakan AI. Misalnya adalah _code completion_, yaitu rekomendasi kode berikutnya dengan pendekatan AI (_machine learning_) klasik seperti _rule based_. Namun, saat ini dengan berkembangnya generative AI, sudah jauh lebih pintar, yaitu kita bisa memintanya untuk memberikan kita kode pemrograman dengan input adalah perintah yang biasa kita sebut dengan _prompt_.


## Karakteristik & Keterbatasan AI yang Wajib Dipahami

Sebelum memanfaatkan AI untuk mendukung aktivitas akademik dan pemograman, ada beberapa aspek fundamental mengenai cara kerja dan keterbatasan AI yang perlu Anda pahami:

### 1. AI Sangat Bergantung pada Keputusan Manusia (Bias & Praktik Kerja)
AI dikembangkan berdasarkan bagaimana manusia merancang algoritma, mengumpulkan data, mengelola, serta melakukan *labeling* (anotasi) data. 
* **Asumsi & Bias Manusia:** Keputusan mengenai data apa yang dimasukkan atau dibuang sepenuhnya bergantung pada kriteria tim pengembang.
* **Eksploitasi Tenaga Kerja (*Labour Practices*):** Proses anotasi data sering kali melibatkan tenaga kerja berupah rendah di negara berkembang. Sebagai contoh, OpenAI pernah memanfaatkan pekerja di Kenya untuk menandai konten bahaya/beracun guna melatih model ChatGPT.
* **Representasi Data:** Data yang dikumpulkan sering kali tidak mewakili kondisi global secara adil (*underrepresented*), sehingga model cenderung memihak pada budaya atau populasi dari sumber data terbesar.

### 2. Kualitas Data Internet: Hak Cipta, Informasi Palsu, dan *Synthetic Data*
Sistem AI dilatih menggunakan miliaran data yang beredar di internet—termasuk data yang mungkin pernah Anda unggah. Konsekuensinya:
* **Informasi Tidak Terverifikasi:** Data internet mengandung banyak *hoax*, rumor, atau bias sosial yang dapat ikut dipelajari oleh AI.
* **Isu Hak Cipta & Privasi:** Banyak model AI dilatih menggunakan karya cipta orang lain atau data pribadi (*private data*) tanpa izin yang sah secara etis.
* **Data Sintetis (*Synthetic Data*):** Kini semakin banyak data di internet yang dibuat oleh AI lain untuk melatih AI baru, yang berisiko memperburuk kualitas model di masa depan (*model collapse*).

### 3. AI Belajar dari Interaksi Kita (*User Data*)
Saat Anda berinteraksi dengan sistem AI, platform tersebut sering kali merekam percakapan, perintah (*prompt*), dan kode yang Anda unggah untuk dijadikan bahan pelatihan tambahan. 
> *Pertanyaan untuk Anda: Menurut Anda, apa contoh bahaya nyata jika seorang pemrogram memasukkan kode rahasia atau API Key milik perusahaan ke dalam kolom chat AI?*

### 4. Pembentukan Pola melalui *Reinforcement Learning*
Sistem AI dilatih untuk mengenali preferensi manusia. Saat Anda disajikan dua pilihan jawaban dan diminta memilih mana yang lebih baik, Anda sedang berpartisipasi dalam **RLHF (*Reinforcement Learning from Human Feedback*)**. 
* Melalui mekanisme *trial and error*, sistem menerima umpan balik (*reward*) untuk memprioritaskan gaya respons yang paling disukai pengguna.

---

### Kesimpulan: Mengapa AI Bisa "Halusinasi"?

Dengan memahami seluruh proses di atas, Anda dapat menyimpulkan bahwa **output dari AI tidak pernah 100% akurat**. 

AI bekerja berdasarkan pencocokan pola statistik dan probabilitas, bukan berdasarkan pemahaman fakta yang sebenarnya. Ketika AI memberikan jawaban yang terdengar sangat meyakinkan tetapi secara faktual salah atau mengada-ada, fenomena ini disebut sebagai **Halusinasi AI (*AI Hallucination*)**. 

Sebagai calon _programmer_, tugas Anda bukanlah menelan mentah-mentah output AI, melainkan melakukan *code review*, verifikasi logika, dan validasi fakta secara kritis.

## 2. Penggunaan AI yang Diizinkan (Zona Hijau)
Anda sangat disarankan menggunakan alat AI untuk mempercepat pembelajaran, memperluas pemahaman konsep, dan membantu proses perbaikan kode (*debugging*).

* **Penjelasan Konsep:** Meminta AI menjelaskan algoritma yang rumit, struktur data, atau arti dari sebuah pesan *error*.
* **Review Kode:** Menempelkan *kode yang Anda tulis sendiri* ke AI dan meminta saran perbaikan sintaks atau optimasi performa.
* **Membuat Test Case:** Meminta AI membuat variasi input acak untuk menguji ketahanan program yang Anda buat.

### Contoh Prompt AI yang Benar
> *"Saya menulis algoritma binary search dengan Python ini, tetapi mengalami infinite loop pada array berukuran genap. Bisakah Anda menjelaskan secara konsep mengapa ini terjadi tanpa memberikan perbaikan kodenya secara langsung?"*

## 3. Penggunaan AI yang Dilarang (Zona Merah)
Menggunakan AI dengan cara di bawah ini termasuk dalam pelanggaran akademik dan akan dikenakan sanksi disiplin.

* **Pembuatan Kode Secara Langsung:** Memasukkan soal tugas kuliah ke AI agar AI menuliskan fungsi, skrip, atau seluruh program untuk Anda.
* **Bantuan Ujian dan Kuis:** Menggunakan alat AI apa pun selama kuis, ujian, atau penilaian praktikum yang dibatasi waktu.
* **Kamuflase Kode:** Menggunakan AI untuk menulis ulang (*rewrite/humanize*) kode hasil buatan AI agar lolos dari deteksi plagiarisme otomatis (seperti MOSS).

```python
# 🚫 DILARANG: Jangan copy-paste soal tugas langsung ke AI
def selesaikan_tugas_3_untuk_saya():
    pass
```

## 4. Aturan Atribusi (Sitasi)
Jika alat AI membantu Anda secara signifikan dalam memperbaiki *bug* atau mengoptimalkan bagian dari kode Anda, Anda wajib mendokumentasikannya di bagian komentar kode.

### Format Sitasi
Tuliskan blok komentar di bagian atas file atau tepat di atas fungsi yang dibantu oleh AI:

```javascript
// SITASI AI
// Alat yang Digunakan: Anthropic Claude 3.5 Sonnet
// Prompt: "Bagaimana cara mengoptimalkan nested loop ini menjadi pencarian Hash Map?"
// Adaptasi: Mengubah nama variabel agar sesuai dengan skema proyek dan menambahkan penanganan error.
```

## 5. Aturan "Jelaskan Kodemu"
Dosen dan asisten praktikum berhak memanggil mahasiswa kapan saja untuk sesi *code-review* secara langsung. Jika Anda tidak bisa menjelaskan logika, kompleksitas waktu (*time complexity*), dan sintaks dari kode yang Anda kumpulkan, **Anda akan mendapat nilai nol untuk tugas tersebut**, terlepas dari apakah software plagiarisme mendeteksinya atau tidak.
