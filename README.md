Dataset ini berasal dari penyedia sistem deteksi intrusi, yang berfungsi mencatat dan memantau kejadian-kejadian terkait keamanan siber dalam jaringan. Data ini sangat berguna untuk mengidentifikasi ancaman potensial, menganalisis teknik serangan, serta merespons aktivitas mencurigakan yang terdeteksi dalam sistem. Informasi yang terkandung dalam dataset ini digunakan dalam analisis ancaman keamanan siber, pemantauan jaringan, dan mitigasi risiko. Setiap alert yang tercatat menandakan potensi serangan atau aktivitas berbahaya yang memerlukan tindakan responsif.

Dataset ini memiliki total 575 baris dan 5 kolom atau variabel, dengan deskripsi sebagai berikut:

1. Timestamp: Menunjukkan waktu spesifik kapan sebuah alert keamanan terdeteksi oleh sistem.
2. LevelAsset: Mengindikasikan tingkat keparahan dan kategori aset yang terpengaruh oleh ancaman, seperti Critical atau Medium.
3. IPCategory: Mengidentifikasi kategori alamat IP yang terlibat dalam insiden, termasuk kategori Internal, External, atau Unknown.
4. Mitre: Menunjukkan kesesuaian teknik serangan yang diidentifikasi dengan framework **MITRE ATT&CK**, yang digunakan untuk menggambarkan taktik dan teknik ancaman.
5. Alert: Memberikan hasil deteksi keamanan, menunjukkan apakah ancaman tersebut valid (*Positif) atau tidak (Negatif). Kolom ini juga berfungsi sebagai label atau untuk tujuan supervisi.
