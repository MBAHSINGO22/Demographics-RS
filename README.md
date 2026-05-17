<h1 align="center">Sistem Rekomendasi Game Berdasarkan Umur dan Gender</h1>

<p align="center">
  Project sistem rekomendasi game menggunakan algoritma demographics dengan Python
</p>

<hr>

<h2>📌 Deskripsi</h2>

<p>
Project ini merupakan sistem rekomendasi game sederhana yang dibuat menggunakan bahasa Python.
Sistem akan merekomendasikan game berdasarkan data umur dan gender pengguna menggunakan pendekatan demographic filtering.
</p>

<p>
Metode demographic filtering bekerja dengan memberikan rekomendasi berdasarkan karakteristik pengguna seperti usia dan jenis kelamin.
</p>

<hr>

<h2>🛠 Teknologi yang Digunakan</h2>

<ul>
  <li>Python</li>
  <li>Jupyter Notebook</li>
</ul>

<hr>

<h2>✨ Fitur</h2>

<ul>
  <li>Input nama pengguna</li>
  <li>Input usia pengguna</li>
  <li>Input jenis kelamin pengguna</li>
  <li>Rekomendasi game berdasarkan umur</li>
  <li>Rekomendasi game berdasarkan gender</li>
  <li>Menampilkan Top 3 rekomendasi game</li>
</ul>

<hr>

<h2>⚙️ Cara Kerja Program</h2>

<ol>
  <li>Program menyimpan data game beserta genre, batas umur, dan gender populer</li>
  <li>Pengguna memasukkan nama, usia, dan gender</li>
  <li>Program melakukan filtering berdasarkan usia minimum game</li>
  <li>Program mencocokkan gender pengguna dengan data game</li>
  <li>Program menampilkan daftar rekomendasi game</li>
</ol>

<hr>

<h2>📂 Struktur Project</h2>

<pre>
project-folder/
│
├── DEMORS.ipynb
└── README.md
</pre>

<hr>

<h2>🚀 Instalasi</h2>

<p>Clone repository:</p>

<pre>
git clone https://github.com/username/nama-repository.git
</pre>

<p>Masuk ke folder project:</p>

<pre>
cd nama-repository
</pre>

<hr>

<h2>▶️ Cara Menjalankan</h2>

<ol>
  <li>Buka file <b>DEMORS.ipynb</b> menggunakan Jupyter Notebook atau Google Colab</li>
  <li>Jalankan seluruh cell program</li>
  <li>Masukkan nama, usia, dan gender</li>
  <li>Lihat hasil rekomendasi game</li>
</ol>

<hr>

<h2>💻 Contoh Kode</h2>

<pre>
def recommend_games(age, gender):
    recommendations = []

    for game in games:
        if age >= game["age_rating"]:
            if game["popular_gender"].lower() == gender.lower() or game["popular_gender"].lower() == "all":
                recommendations.append(game["title"])

    return recommendations
</pre>

<hr>

<h2>🎮 Contoh Output</h2>

<pre>
Masukkan Nama Anda : Eugenius
Masukkan Usia Anda : 20
Jenis Kelamin (Male/Female): Male

Game yang cocok untuk Eugenius adalah:
1. Fortnite
2. Minecraft
3. Call of Duty: Modern Warfare
</pre>

<hr>

<h2>📈 Pengembangan Selanjutnya</h2>

<ul>
  <li>Menambahkan database game yang lebih banyak</li>
  <li>Menambahkan genre favorit pengguna</li>
  <li>Menggunakan machine learning recommendation system</li>
  <li>Membuat tampilan GUI</li>
  <li>Menghubungkan sistem dengan database</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
Eugenius Kriswinar Adi Cahya
</p>

<hr>

<h2>📄 License</h2>

<p>
Project ini dibuat untuk kebutuhan pembelajaran dan penelitian.
</p>
