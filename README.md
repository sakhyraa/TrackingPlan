# Our Journey — Wedding & First Home Planner

Website perencanaan pernikahan dan rumah pertama dengan HTML, CSS, dan JavaScript. Tidak membutuhkan database, Firebase, PHP, atau Node.js.

## Cara menjalankan
1. Ekstrak ZIP ini.
2. Buka folder `our-journey` di Visual Studio Code.
3. Jalankan `index.html` menggunakan ekstensi **Live Server**, atau buka `index.html` langsung di browser modern.
4. Semua menu di sidebar bisa diklik untuk berpindah halaman.

## Fitur
- Dashboard dan milestone rumah, akad, resepsi.
- Tabungan dengan target terpisah, setoran/penarikan, dan riwayat transaksi.
- Pemasukan dan pengeluaran harian, sumber dana, kategori, serta penanggung jawab.
- Wedding planner, seserahan dan mahar.
- Daftar vendor dengan kontak, harga, pembayaran, dan status.
- Daftar rumah dengan harga, estimasi DP/cicilan, kontak, dan jadwal survei.
- Timeline tugas dengan penanggung jawab, deadline, prioritas, dan checklist.
- Ekspor seluruh data ke JSON, impor backup JSON, dan ekspor transaksi ke CSV.

## Penyimpanan dan backup
Data disimpan otomatis di `localStorage` browser yang sedang digunakan. Data tidak otomatis tersinkron ke perangkat lain. Untuk berbagi dengan pasangan, buka menu **Pengaturan & Backup**, ekspor JSON, lalu bagikan file tersebut. Di perangkat pasangan, buka website yang sama dan impor file JSON. Sepakati satu file backup terbaru agar perubahan tidak saling menimpa.

**Penting:** menghapus data browser atau menggunakan browser/perangkat berbeda bisa membuat data lokal tidak tersedia. Simpan backup JSON secara rutin.
