# Open Kode

Selamat datang di Repositori Open Kode! Open Kode adalah event untuk memasyaraktkan open source yang digagas oleh komunitas [Ngodingo](https://github.com/ngodingo) dan Synkode. Open Kode diselenggarakan sepanjang September hingga Oktober 2023 dalam dua tahap utama, yaitu preparation dan contribution. 

- Preparation dilaksanakan selama bulan September, dimana pada tahap ini peserta Open Kode mendapatkan pembekalan materi oleh Synkode untuk dapat melakukan kontribusi.
- Contribution dilaksanakan selama bulan Oktober bersamaan dengan [Hacktoberfest]( https://www.petanikode.com/hacktoberfest/), dimana pada tahap ini peserta Open Kode dapat melakukan kontribusi pada proyek open source apapun atau pada proyek yang telah dipersiapkan oleh Ngodingo.

# Panduan Kontribusi Proyek Open Source

Dalam panduan ini, akan dijelaskan bagaimana langkah-langkah untuk berkontribusi ke proyek open source di GitHub.

## Langkah 1: Fork Repositori

Langkah pertama adalah melakukan fork repositori dari proyek open source ke akun GitHub pribadi Anda. Langkah ini bertujuan untuk membuat salinan repositori tersebut di akun GitHub pribadi Anda, yang dapat Anda ubah dan kontribusikan tanpa memengaruhi repositori utama.

1. Buka halaman repositori proyek di GitHub

2. Klik tombol "Fork" di sudut kanan atas halaman untuk melakukan fork proyek ke akun Anda.

Jika sudah melakukan langkah di atas, maka seharusnya salinan dari repositori proyek tersebut sudah tersedia pada akun pribadi Anda.

## Langkah 2: Clone Repositori

Setelah Anda telah melakukan fork repositori proyek open source, Anda perlu membuat clone salinan repositori tersebut ke komputer lokal Anda agar dapat melakukan perubahan dan kontribusi.

1.  Buka salinan repositori lalu klik pada bagian “Code” dan copy link yang tersedia

2.  Lakukan command git clone pada git local komputer Anda

```
git clone https://github.com/akun-anda/repositori-proyek.git
```
```
git clone git@github.com:ardianta/belajar-git.git
```

## Langkah 3: Buat Branch Baru

Sebelum Anda mulai melakukan perubahan, Anda dapat membuat branch baru untuk fitur khusus yang Anda kerjakan. Ini akan membantu memisahkan pekerjaan Anda dari branch utama repositori dan branch pekerjaan orang lain. Penamaan branch baru seharusnya menggunakan nama yang relevan dengan fitur atau tugas yang Anda kerjakan.

```
git checkout -b fitur-baru
```

## Langkah 4: Lakukan Perubahan

Sekarang, Anda dapat melakukan perubahan pada source code proyek tersebut sesuai dengan kontribusi yang Anda ingin kerjakan. Pastikan untuk melakukan perubahan dengan mengikuti pedoman yang telah ditetapkan oleh proyek tersebut. Hal ini bertujuan agar kontribusi yang kita buat dapat diterima dan dapat dirilis oleh pemilik proyek tersebut.

## Langkah 5: Commit dan Push Perubahan

Setelah Anda selesai melakukan perubahan pada branch fitur anda, Anda harus melakukan commit perubahan pada repositori lokal dan melakukan push ke repositori Anda di GitHub. Dalam membuat commit baiknya memberikan pesan yang singkat dan jelas mengenai perubahan apa yang telah dibuat. 

```bash
git status
git add .
git commit -m "Deskripsi singkat perubahan"
```
```
git push origin
```

Jika langkah diatas sudah berhasil, seharusnya saat ini perubahan kode yang Anda buat di lokal sudah tersedia di repositori salinan pada akun github pribadi Anda.

## Langkah 6: Buat Pull Request (PR)

Jika push sudah berhasil, Anda dapat melihat pesan bahwa Anda baru saja melakukan push ke branch pada akun github pribadi Anda. Klik tombol “New Pull Request” untuk membuat permintaan penggabungan dari repositori salinan di akun github Anda ke repositori asli proyek tersebut. 

Jika perubahan kode yang anda buat sudah memungkinkan merge dengan repositori asli maka Anda dapat membuat pull request dengan klik tombol “Create Pull Request” dan tuliskan pesan pull request yang jelas dan informatif.

## Langkah 7: Review dan Diskusi

Pemilik proyek akan mereview Pull Request yang Anda buat dan ada kemungkinan untuk diskusi atau perbaikan sebelum perubahan Anda diterima dan dirilis di repositori asli proyek tersebut. Pastikan Anda siap untuk berkolaborasi dan melakukan perubahan sesuai dengan feedback yang diberikan.

## Langkah 8: Perubahan Diterima

Setelah perubahan Anda disetujui, pemilik proyek akan menggabungkannya dengan repositori utama. Dengan itu, maka Anda telah berhasil menjadi kontributor pada proyek open source. Dan jika Anda ingin melakukan kontribusi lagi pastikan agar repositori lokal anda sudah terupdate sesuai dengan kondisi repositori asli proyek open source tersebut.
