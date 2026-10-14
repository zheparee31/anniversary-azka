# Website First Anniversary untuk Azka

Website statis satu halaman, tanpa proses build atau dependensi tambahan. Buka `index.html` untuk melihat pratinjau.

## Menambahkan foto yang tampil untuk semua pengunjung

Kedua foto yang Anda kirim sudah ditambahkan di bagian atas halaman, tepat setelah pemutar lagu. File-nya ada di folder `media`; foto yang disertakan di folder ini akan ikut terlihat oleh semua pengunjung setelah situs diterbitkan. Untuk menggantinya, ubah atribut `src` pada elemen `<img>` di bagian `id="couplePhotosTitle"`.

1. Buat folder `media` di samping `index.html`.
2. Simpan foto yang ingin dibagikan ke folder tersebut, misalnya `media/foto-1.jpg`.
3. Di `index.html`, cari bagian foto pasangan dan ubah `src` foto ke file yang ingin ditampilkan:

   ```html
   <img src="media/foto-1.jpg" alt="Kenangan kita" width="768" height="1024">
   ```

4. Ulangi untuk foto lainnya. Karena situs ini publik, foto yang dimasukkan ke halaman akan bisa dilihat siapa saja.

## Lagu

Pemutar Spotify untuk **Magnolia — Magnolia Celebration** tampil di bagian atas halaman. Embed Spotify menyediakan cuplikan lagu; untuk pemutaran penuh, pengunjung dapat membuka tautan Spotify di bawah pemutar. Ketersediaan mengikuti akun dan ketentuan Spotify. File lagu tidak disertakan di situs.

## Situs publik

Situs ini telah diterbitkan melalui GitHub Pages dan dapat dibuka di:

**https://zheparee31.github.io/anniversary-azka/**

Repository publiknya: <https://github.com/zheparee31/anniversary-azka>. File situs dan semua foto di repository dapat dilihat siapa saja. Perubahan pada file lokal perlu diunggah ke repository agar tampil pada versi publik.
