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

## Pemanfaatan AI di Pemrograman
Sebenarnya ada banyak jenis sistem AI tergantung dengan tujuan dan data latihnya. Di satu sisi, Anda mungkin menyadari bahwa Anda sedang memanfaatkan AI seperti pada saat menggunakan Claude, di sisi lain Anda mungkin sedang tidak sadar ketika menggunakan AI, yaitu seperti memprediksi kata berikutnya saat Anda mengetik di HP Anda.

Di sisi pemrograman, AI bukanlah suatu hal yang baru. Sebelum ChatGPT populer, banyak tools yang dipakai programmer sehari-hari sudah menggunakan AI. Misalnya adalah _code completion_, yaitu rekomendasi kode berikutnya dengan pendekatan AI (_machine learning_) klasik seperti _rule based_. Namun, saat ini dengan berkembangnya generative AI, sudah jauh lebih pintar, yaitu kita bisa memintanya untuk memberikan kita kode pemrograman dengan input adalah perintah yang biasa kita sebut dengan _prompt_. Di dunia pengembangan perangkat lunak modern, AI telah menjadi alat bantu utama (*copilot*) bagi para pemrogram. Pemanfaatan AI dapat meningkatkan efisiensi dan membantu kita belajar menulis kode dengan lebih cepat.

Berikut adalah beberapa penerapan utama AI dalam pemrograman yang perlu Anda ketahui:
#### 1. Generasi Kode Otomatis (*Code Generation*)
AI dapat membuat potongan kode (*code snippet*), fungsi, atau bahkan kerangka aplikasi berdasarkan instruksi teks (*prompt*) yang diberikan.
* **Contoh:** Menuliskan instruksi *"Buat fungsi Python untuk mengurutkan array angka secara ascending"*, dan AI akan langsung menghasilkan kodenya.

#### 2. Melengkapi Kode Otomatis (*Code Completion*)
Mirip dengan fitur *autocomplete* pada keyboard HP, AI pada editor kode (seperti VS Code) dapat memprediksi baris kode selanjutnya saat Anda sedang mengetik.
* **Dampak:** Mempercepat proses mengetik kode (*coding*) dan mengurangi kesalahan penulisan (*syntax error*).

#### 3. Penemuan dan Perbaikan Bug (*Bug Detection & Fixing*)
Sistem AI dapat menganalisis kode untuk menemukan potensi kesalahan, kerentanan keamanan, atau variabel yang tidak digunakan sebelum program dijalankan.
* **Dampak:** AI tidak hanya menunjukkan lokasi error, tetapi juga menyarankan solusi perbaikannya.

#### 4. Pembuatan Dokumen Kode Otomatis (*Automated Documentation*)
AI dapat membaca logika kode yang telah ditulis dan secara otomatis membuatkan komentar penjelasan atau dokumentasi teknis.
* **Dampak:** Membantu pemrogram lain (atau Anda sendiri di masa depan) untuk memahami alur fungsi kode dengan lebih cepat.

#### 5. Pengujian Perangkat Lunak (*Automated Testing*)
AI dapat secara otomatis membuat skenario pengujian (*test cases*) dan *unit test* untuk memastikan program berjalan sesuai rencana dalam berbagai kondisi *input*.

#### 6. Refaktor Kode (*Code Refactoring*)
AI dapat menganalisis kode yang sudah ada dan menyarankan struktur baru yang lebih bersih, lebih efisien, serta lebih mudah dirawat tanpa mengubah hasil akhirnya.

---

> **Peringatan untuk Mahasiswa Dasar-Dasar Pemrograman 1:**  
> AI adalah **alat bantu**, bukan **pengganti logika berpikir Anda**. Menggunakan AI untuk memahami sintaks dan mencari *bug* sangat dianjurkan, tetapi mengandalkan AI tanpa memahami logika kodenya sendiri akan menghambat perkembangan Anda sebagai seorang *software engineer*.

### Tips Berinteraksi dengan AI (Prompt Engineering) untuk Pemrograman

#### 1. AI Bukan Manusia: Mereka Membutuhkan Konteks Lengkap
AI tidak memiliki intuisi, perasaan, atau pemahaman tentang latar belakang masalah Anda jika tidak diberi tahu. Berikan detail latar belakang yang jelas agar AI memahami situasi yang sedang Anda hadapi.

#### 2. Prompt LLM Berbeda dengan Mesin Pencari (*Search Engine*)
Saat menggunakan Google, kita terbiasa mengetik kata kunci pendek seperti `"cara sort array python"`. Namun pada Large Language Model (LLM) seperti ChatGPT atau Claude, **prompt yang terlalu singkat tidak akan maksimal**. AI membutuhkan instruksi yang deskriptif dan terstruktur.

#### 3. Jelaskan Masalah dan Tujuan Program Secara Spesifik
Sampaikan secara eksplisit apa gol utama yang ingin dicapai dan batasan teknis yang harus dipatuhi AI.
* **Sebutkan Bahasa & Versi:** Misal: Python 3.10, C++, atau Java.
* **Sebutkan Library/Framework:** Misal: *"Gunakan pustaka NumPy"* atau *"Jangan gunakan pustaka eksternal, gunakan pure C++"*.
* **Sebutkan Batasan (*Constraints*):** Misal: *"Buat kode ini seefisien mungkin tanpa menggunakan perulangan bersarang (nested loop)"*.

#### 4. Gunakan Pendekatan Bertahap (*Iterative Prompting*)
Sangat jarang AI bisa memberikan jawaban 100% sempurna hanya dalam **satu kali perintah**. Mengembangkan kode bersama AI adalah proses dialog bertahap:
1. Berikan perintah awal untuk membuat kerangka dasar.
2. Uji coba (*run*) kode tersebut di komputer Anda.
3. Jika ada *error* atau kekurangan, salin pesan *error* tersebut dan minta AI untuk memperbaikinya (*debugging* bertahap).

### Perbandingan Contoh Instruksi (*Prompt*)

* **Contoh Singkat / Kurang Baik (Gaya Search Engine):**
  > *"Buat kode bikin grafik di python."*
  
* **Contoh Spesifik & Berkonteks (Gaya LLM):**
  > *"Saya mahasiswa semester 1 sedang belajar menganalisis data. Tolong buatkan fungsi Python menggunakan library **Matplotlib** untuk membuat **line chart** dari data penjualan bulanan. Berikan komentar penjelasan pada setiap baris kode agar saya mudah memahaminya."*

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


### Dampak dan Risiko AI dalam Pemembangan Perangkat Lunak

Meskipun AI memberikan keuntungan yang sangat besar dalam pengembangan perangkat lunak, teknologi ini juga membawa potensi risiko yang harus dikelola secara proaktif.

#### 1. Bias pada Model AI (*Bias in AI Models*)
Model AI dapat menghasilkan kode atau keputusan yang memihak atau diskriminatif jika data pelatihannya memiliki bias.
* **Solusi:** Melakukan audit secara berkala terhadap output AI untuk memastikan keadilan, serta mengintegrasikan alat pendeteksi bias (*bias detection tools*) untuk menghasilkan luaran yang lebih setara dan adil.

#### 2. Ketergantungan Berlebihan pada AI (*Overreliance on AI*)
Pengembang (*developer*) dapat menjadi terlalu bergantung pada alat AI untuk menulis kode, melakukan *debugging*, atau pengujian. Hal ini berisiko menurunkan keterampilan dasar pemrograman (*fundamental programming skills*) mereka.
* **Solusi:** Pengembang harus menjadikan AI sebagai **alat bantu** sembari terus menjaga, melatih, dan mengasah keahlian teknis mereka sendiri.

#### 3. Kerentanan Keamanan (*Security Vulnerabilities*)
Kode yang dihasilkan oleh AI dapat membawa celah atau kerentanan keamanan jika tidak diperiksa dengan benar.
* **Solusi:** Pengawasan manual oleh manusia (*human oversight*) harus tetap menjadi komponen krusial dalam proses peninjauan kode (*code review*).

#### 4. Kurangnya Transparansi (*Lack of Transparency*)
Banyak model AI, khususnya dalam *Machine Learning*, bekerja seperti "kotak hitam" (*black box*) yang proses pengambilan keputusannya tidak sepenuhnya transparan atau tidak dapat dijelaskan kepada pengguna.
* **Solusi:** Jika memungkinkan, pengembang sebaiknya memilih dan menggunakan model-model yang lebih mudah diinterpretasikan (*interpretable models*).
* 

### Penggunaan AI secara Bertanggung Jawab (Responsible AI Use)

Menggunakan AI secara bertanggung jawab membutuhkan lebih dari sekadar tahu alat apa yang harus dipakai. Anda dituntut untuk memiliki kemampuan **berpikir kritis** terhadap informasi yang dihasilkan AI, memahami asal-usulnya, menyadari keterbatasannya, serta mengambil keputusan akhir berdasarkan pertimbangan logika dan pertimbangan manusia (*human judgement*).

Untuk mengevaluasi kode maupun informasi yang dihasilkan AI, Anda dapat menggunakan kerangka kerja evaluasi kritis berikut:

---

#### Kerangka Evaluasi Kritis Output AI

1. **Otoritas (*Authority*)**
   * **Pertanyaan Evaluasi:** Apakah AI memberikan referensi asal informasinya? Apakah kutipan, tautan, atau fungsi pustaka (*library*) yang disarankan benar-benar ada?
   * **Tindakan Anda:** Jangan langsung percaya pada nama fungsi atau sintaks baru. Cek kembali ke **dokumentasi resmi** (*official documentation*) bahasa pemrograman atau pustaka yang digunakan untuk memastikan referensinya bukan hasil halusinasi.

2. **Bias (*Bias*)**
   * **Pertanyaan Evaluasi:** Dari sudut pandang mana AI merespons masalah tersebut? Apakah AI hanya menyarankan satu solusi tertentu dan mengabaikan alternatif lainnya?
   * **Tindakan Anda:** Sadari bahwa AI cenderung merekomendasikan metode populer di internet. Pertimbangkan apakah metode tersebut benar-benar paling efisien untuk studi kasus Anda atau hanya sekadar yang paling sering ditulis orang lain.

3. **Kredibilitas (*Credibility*)**
   * **Pertanyaan Evaluasi:** Apakah ada klaim teknis, algoritma, atau penjelasan kode yang tidak didukung oleh bukti atau praktik terbaik (*best practices*)?
   * **Tindakan Anda:** Uji coba kode tersebut dalam lingkungan pengembangan Anda (*local environment*). Jangan mengasumsikan kode itu benar hanya karena penjelasan AI terdengar meyakinkan.

4. **Keterkinian Data (*Currency*)**
   * **Pertanyaan Evaluasi:** Seberapa baru data yang digunakan untuk melatih AI tersebut?
   * **Tindakan Anda:** Selalu periksa batas waktu data pelatihan (*knowledge cutoff*) dari AI yang Anda gunakan. Mengingat perkembangan teknologi terus berjalan pesat, AI dengan data pelatihan lama bisa saja menyarankan metode, sintaks, atau fungsi yang sudah tidak berlaku (*deprecated*) pada versi terbaru saat ini.

5. **Relevansi (*Relevance*)**
   * **Pertanyaan Evaluasi:** Apakah output yang dihasilkan benar-benar menyelesaikan masalah spesifik Anda?
   * **Tindakan Anda:** Jika jawaban AI terlalu umum atau melenceng, jangan ragu untuk mengedit dan menyempurnakan kembali instruksi (*prompt*) Anda dengan memberikan detail kasus yang lebih spesifik.

---

> **Ingat:** AI adalah asisten, tetapi Anda adalah pengemudinya (*pilot*). Tanggung jawab atas kebenaran, keamanan, dan kualitas kode sepenuhnya ada di tangan Anda sebagai pemrogram.


### Lembar Refleksi Penggunaan AI dalam Pemrograman

Gunakan pertanyaan-pertanyaan refleksi berikut untuk mengevaluasi proses kerja dan kolaborasi Anda bersama AI saat menyelesaikan tugas pemrograman:

1. **Identifikasi Model AI**
   * **Pertanyaan:** Model AI apa yang Anda gunakan? (Contoh: ChatGPT-4o, Claude 3.5 Sonnet, GitHub Copilot, Gemini, dll.)

2. **Perancangan Instruksi Awal (*Initial Prompt*)**
   * **Pertanyaan:** Bagaimana perintah (*prompt*) awal yang Anda berikan, dan bagaimana respons pertama yang diberikan oleh model AI tersebut?

3. **Integrasi dan Eksekusi Kode**
   * **Pertanyaan:** Apakah kode yang dihasilkan AI dapat langsung diintegrasikan ke dalam program Anda dan berhasil dijalankan (*compile/run*) tanpa error?

4. **Proses Debugging & Pemecahan Masalah**
   * **Pertanyaan:** Jika terdapat *bug* atau error pada kode dari AI, bagaimana proses Anda memperbaikinya? Apa hal yang paling mudah dan paling sulit dari proses tersebut? Apakah Anda sekadar menyalin balik pesan error ke AI, atau mencoba mendiagnosis dan memperbaikinya sendiri secara manual?

5. **Evaluasi Efektivitas Prompt**
   * **Pertanyaan:** Menurut Anda, perintah (*prompt*) mana yang berhasil menghasilkan jawaban paling berguna? Detail atau informasi spesifik apa yang Anda masukkan ke dalam *prompt* tersebut sehingga AI dapat memberikan respons yang berkualitas tinggi?

---

> **Tujuan Refleksi:**  
> Melatih kesadaran metakognitif (*metacognition*) Anda agar tidak sekadar menjadi "tukang salin" (*copy-paster*), melainkan mampu menganalisis efektivitas *prompt* dan mengasah kemampuan *debugging* secara mandiri.


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

## 5. Aturan "Jelaskan Kodemu"
Dosen dan asisten praktikum berhak memanggil mahasiswa kapan saja untuk sesi *code-review* secara langsung. Jika Anda tidak bisa menjelaskan logika, kompleksitas waktu (*time complexity*), dan sintaks dari kode yang Anda kumpulkan, **Anda akan mendapat nilai nol untuk tugas tersebut**, terlepas dari apakah software plagiarisme mendeteksinya atau tidak.

## Referensi

## Acknowledgement
Halaman ini berasal dari berbagai sumber tentang literasi AI dan panduan penggunaan AI pada pemrograman. Hasil rangkuman tersebut kemudian menjadi slide presentasi untuk mata kuliah PBP dan kemudian diubah menjadi halaman panduan ini. Tim penulis juga meminta bantuan AI (Gemini) untuk memperbaiki isi tulisan dan kemudian direview dan diperbaiki lagi oleh tim penulis.

## Tim Penulis
- Iis Afriyanti
- Daya Adianto
Jika Anda ingin berkontribusi untuk memperbaiki halaman ini, silakan kontak iisafriyanti@cs.ui.ac.id
