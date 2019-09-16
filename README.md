# Tugas-1-Pemograman-Jaringan
Yola Adipratama - 1301144156

Jawaban 
# 1. TCP 
Diagram diatas adalah TCP FInite State Machine yang merupakan three way handshake pada saat ingin membuat TCP.
Hal pertama yang perlu diperhatikan dalam diagram ini adalah bahwa bagian dari transisi state tipikal. clien normal dengan panah solid hijau, dan transisi server normal dengan panah putus-putus merah. Transisi lain valid, tetapi biasanya tidak diharapkan.
Dua transisi yang mengarah ke keadaan CONNECTION ESTABLISHED berhubungan dengan pembukaan koneksi, dan dua transisi yang mengarah dari state CONNECTION ESTABLISHED adalah untuk penghentian koneksi. Kondisi CONNECTION ESTABLISHED adalah tempat transfer data dapat terjadi di antara kedua ujung di kedua arah.
kotak putus-putus dan memberi labelnya TUTUP aktif. Dua kotak lain (CLOSE_WAIT dan LAST_ACK) dikumpulkan dalam kotak putus-putus dengan label pasif TUTUP.
Ketika OPEN pasif dikeluarkan oleh titik akhir, itu masuk ke negara LISTEN. Ini terjadi setiap kali server memulai proses daemon yang diharapkan untuk menunggu permintaan TCP yang masuk. Ketika TCP menerima flag SYN dalam status ini, ia akan memasuki proses jabat tangan 3-arah untuk pindah ke keadaan CONNECTION ESTABLISHED.
OPEN aktif biasanya dikeluarkan oleh klien untuk memulai transaksi TCP dengan server yang diberikan. Mengikuti jalur hijau, seseorang dapat dengan jelas melihat jabat tangan 3 arah yang mengarah ke kondisi CONNECTION ESTABLISHED.

# 2. For 
 Kode Program
git add for.go

For adalah proses mengulang-ulang eksekusi blok kode tanpa henti, selama kondisi yang dijadikan acuan terpenuhi. Biasanya disiapkan variabel untuk iterasi atau variabel penanda kapan perulangan akan diberhentikan

