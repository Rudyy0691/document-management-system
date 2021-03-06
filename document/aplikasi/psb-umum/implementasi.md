---
layout: document
title: Implementasi PSB Umum
description: Implementasi Aplikasi Penerimaan Siswa Baru pada Pemerintah Provinsi Banten.
group: aplikasi
cat: psb-umum
toc: true
---

## Daftar Isi
** Will be replaced with the ToC, excluding the "Contents" header
{:toc}


 ## Implementasi 
Penerimaan Siswa Baru Umum (PSB Umum) adalah suatu aplikasi yang akan dikeluarkan oleh pemerintah Provinsi Banten untuk mendukung terlaksananya sistem penerimaan calon siswa baru yang lebih baik. Didalam aplikasi ini calon siswa dan orang tua dapat mengakses informasi lengkap mengenai pendaftaran sekolah yang terdapat di Banten, seperti melihat sekolah, kuota siswa, info pendaftaran, seleksi dan informasi - informasi terkait pendaftaran siswa baru yang terdapat di Banten.

### Pengujian Program Aplikasi Super Admin
<!-- 1. Untuk memulai akses terhadap aplikasi ****psb****. Buka web browser (IE, Mozila Firefox atau yang lainnya).
  [![tampilan-browser](/document/aplikasi/layanan-kesehatan/images/implementasi/01.tampilan-browser.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/01.tampilan-browser.png)

2. Dengan menulis alamat url http://yankes-01.dev.bantenprov.go.id/admin kemudian tekan ****Enter**** pada tombol keyboard atau klik tombol ****Go**** pada browser. Akan muncul tampilan seperti dibawah ini:
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/14-tampilan-login-admin)](/document/aplikasi/layanan-kesehatan/images/implementasi/14-tampilan-login-admin)

3. Masukan email super admin : admin@site.com dengan password : admin untuk login ****super admin****.
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/15-login-admin)](/document/aplikasi/layanan-kesehatan/images/implementasi/15-login-admin)

4. Menu Admin Rumah sakit, dalam menu admin rumah sakit ****super admin**** bisa bertugas menambahkan list rumah sakit baru dan admin baru di setiap rumah sakit untuk mengelola data rumah sakit tersebut dan menambahkan data dokter dari setiap rumah sakit.
  [![tampilan-superadmin](/document/aplikasi/layanan-kesehatan/images/implementasi/16-admin-rumah-sakit)](/document/aplikasi/layanan-kesehatan/images/implementasi/16-admin-rumah-sakit)

5. New Admin, hanya bisa ditambahkan oleh ****super admin**** untuk menambahkan data admin dari setiap rumah sakit.
  [![tampilan-superadmin](/document/aplikasi/layanan-kesehatan/images/implementasi/17-penambahan-admin)](/document/aplikasi/layanan-kesehatan/images/implementasi/17-penambahan-admin)

contoh penambahan new admin di rumah sakit.
[![tampilan-superadmin](/document/aplikasi/layanan-kesehatan/images/implementasi/18-admin-baru)](/document/aplikasi/layanan-kesehatan/images/implementasi/18-admin-baru) -->

### Pengujian Program Aplikasi Admin
<!-- 1. Untuk memulai akses terhadap aplikasi ****psb****. Buka web browser (IE, Mozila Firefox atau yang lainnya).
  [![tampilan-browser](/document/aplikasi/layanan-kesehatan/images/implementasi/01.tampilan-browser.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/01.tampilan-browser.png)

2. Dengan menulis alamat url http://yankes-01.dev.bantenprov.go.id/admin kemudian tekan ****Enter**** pada tombol keyboard atau klik tombol ****Go**** pada browser. Akan muncul tampilan seperti dibawah ini:
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/14-tampilan-login-admin)](/document/aplikasi/layanan-kesehatan/images/implementasi/14-tampilan-login-admin)

3. Masukan email admin : adminbaru@gmail.com dengan password : admin123 untuk contoh login ****admin****.
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/19-login-admin)](/document/aplikasi/layanan-kesehatan/images/implementasi/19-login-admin)

4. Menu Dokter, dalam menu dokter admin bisa menambahkan list baru untuk dokter dirumah sakit.
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/20-new-dokter)](/document/aplikasi/layanan-kesehatan/images/implementasi/20-new-dokter)

5. Menu dokter jaga, dalam menu dokter jaga admin bisa menambahkan list baru untuk dokter jaga dirumah sakit yang dikelola oleh admin rumah sakit tersebut.
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/21-new-dokter-jaga)](/document/aplikasi/layanan-kesehatan/images/implementasi/21-new-dokter-jaga)

6. Menu Layanan, dalam menu layanan admin bisa menambahkan list baru untuk layanan apa saja yang diberikan oleh rumah sakit yang dikelola oleh admin tersebut.
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/22-new-layanan)](/document/aplikasi/layanan-kesehatan/images/implementasi/22-new-layanan)

7. Menu rawat inap, dalam menu rawat inap admin bisa menambahkan list baru untuk kelas ruangan, ruangan rawat inap, dan tempat tidur pasien yang diberikan oleh rumah sakit yang dikelola oleh admin tersebut.
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/23-kelas-ruangan)](/document/aplikasi/layanan-kesehatan/images/implementasi/23-kelas-ruangan)
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/24-ruangan-rawat-inap)](/document/aplikasi/layanan-kesehatan/images/implementasi/24-ruangan-rawat-inap)
  [![tampilan-login](/document/aplikasi/layanan-kesehatan/images/implementasi/25-tempat-tidur-pasien)](/document/aplikasi/layanan-kesehatan/images/implementasi/25-tempat-tidur-pasien) -->

### Pengujian Program Aplikasi User
<!-- 1. Untuk memulai akses terhadap aplikasi ****layanan kesehatan****. Buka web browser (IE, Mozila Firefox atau yang lainnya).
  [![tampilan-browser](/document/aplikasi/layanan-kesehatan/images/implementasi/01.tampilan-browser.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/01.tampilan-browser.png)  -->

## 1. Implementasi 

Penerimaan Siswa Baru Umum (PSB Umum) adalah suatu aplikasi yang akan dikeluarkan oleh pemerintah Provinsi Banten untuk mendukung terlaksananya sistem penerimaan calon siswa baru yang lebih baik. Didalam aplikasi ini calon siswa dan orang tua dapat mengakses informasi lengkap mengenai pendaftaran sekolah yang terdapat di Banten, seperti melihat sekolah, kuota siswa, info pendaftaran, seleksi dan informasi - informasi terkait pendaftaran siswa baru yang terdapat di Banten.

Implementasi aplikasi Penerimaan Siswa Baru merupakan hasil perancangan dan desain dari aplikasi Penerimaan Siswa Baru yang telah dibuat. Didalam implementasi aplikasi ini nantinya akan dijelaskan langkah-langkah penggunaan dari tiap-tiap menu yang ada pada aplikasi Penerimaan Siswa Baru yang sudah terintegrasi tersebut.

## 2. Menu dan Cara Penggunaan Super Admin

### 2. 1 Tampilan Super Admin
<!-- Untuk memulai akses terhadap aplikasi ****Layanan Kesehatan****. Buka web browser (IE, Mozila Firefox atau yang lainnya) dengan menulis alamat url http://yankes-01.dev.bantenprov.go.id/login kemudian tekan ****Enter**** pada tombol keyboard atau klik tombol ****Go**** pada browser. Akan muncul tampilan halaman login aplikasi yankes seperti gambar dibawah ini. -->

### 2.2 Tampilan Login Super Admin
<!-- [![Login Super Admin](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_login-ars-dan-sa.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_login-ars-dan-sa.png)
Disaat membuka aplikasi YANKES untuk admin maka akan timbul **page login**. Disini terdapat 2 **field** yang harus diisi oleh super admin agar super admin dapat masuk kedalam halaman utama super admin. -->

### 2.3 Dashboard Super Admin
<!-- [![Dashboard Super Admin](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-halaman-depan.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-halaman-depan.png)
Didalam **page** ini terdapat beberapa **list menu** yang dapat diolah oleh super admin yang akan terintegrasi dengan aplikasi YANKES. Didalam aplikasi super admin juga dapat melihat berapa jumlah pengunjung aplikasi YANKES dan berita berita yang diinput kedalam YANKES. -->

### 2.4 Tampilan Konten Admin Sekolah
<!-- [![Konten Admin Rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-lihat-admin-rs.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-lihat-admin-rs.png)
Didalam **page** ini super admin dapat melihat siapa saja admin rumah sakit beserta informasi tentang admin rumah sakit tersebut. Dalam **page** ini super admin juga dapat menambahkan admin rumah sakit dengan cara memilih tombol " **New Admin** (RS) " -->

#### 2.4.1 Tampilan Tambah Admin Sekolah
<!-- [![Tambah Admin RS](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-input-admin-rs.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-input-admin-rs.png)
Didalam **page** ini terdapat **form input** admin RS yang terdapat beberapa **field** yang harus diisi oleh super admin agar dapat menambahkan admin RS, setelah mengisi **field** yang tersedia super admin harus memilih tombiol " **ADD** ". Jika terdapat kesalahan dalam pengisian baik sudah ada admin RS maupun kurang lengkap nya pengisian maka secara otomatis akan kembali kedalam **page form input** dan jika berhasil akan dialihkan kedalam **page** admin rumah sakit. -->

### 2.5 Tampilan Konten Siswa
<!-- [![Tampilan Konten Dokter](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-lihat-dokter.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-lihat-dokter.png)
Didalam **page** ini super admin dapat melihat, mengedit, menambahkan dan menghapus data dokter. -->

#### 2.5.1 Tampilan Tambah Siswa
<!-- [![Tambah Dokter](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-input-dokter.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_sa-input-dokter.png)
Didalam **page** ini terdapat **form input** dokter yang harus diisi oleh super admin untuk bisa menambahkan dokter. Jika data sudah ada atau kurang lengkap maka ketika menekan tombol " **ADD** " akan kembali kedalam page tambah dokter dan jika tidak ada masalah maka akan dialihkan ke **page** dokter. -->

## 3. Menu dan Cara Penggunaan Admin

### 3.1 Tampilan Halaman Utama
[![Halaman Utama](/document/aplikasi/psb-umum/images/implementasi/psb-umum_halaman-utama.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_halaman-utama.png)
Disaat membuka aplikasi PSB untuk admin maka akan muncul dua tombol, yaitu tombol **dashboard** dan tombol **daftar**. Disebelah kanan atas terdapat tombol **prinsip utama** dan **login** yang dapat digunakan jika sudah memiliki akun. Tombol prinsip utama akan mengarahkan ke layer asas PPDB dan juga informasi singkat mengenai PPDB.

Berikut ini adalah tampilan layer mengenai informasi singkat dan asas PPDB pada halaman utama:
[![AInformasi Singkat PPDB](/document/aplikasi/psb-umum/images/implementasi/psb-umum_informasi-singkat-ppdb.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_informasi-singkat-ppdb.png)

[![Asas PPDB](/document/aplikasi/psb-umum/images/implementasi/psb-umum_asas-ppdb.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_asas-ppdb.png)

### 3.2 Tampilan Registrasi Admin
[![Registrasi Admin](/document/aplikasi/psb-umum/images/implementasi/psb-umum_halaman-register-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_halaman-register-admin.png)
Disaat menekan tombol **daftar** pada halaman utama, maka akan muncul menu registrasi. Disini terdapat 4 **field** yang harus diisi oleh admin agar mendapatkan akun. Filed yang harus diisi yaitu: Username, E-mail, Password, dan Konfirmasi Password. Jika sudah diisi tekan tombol register dan buka alamat E-mail untuk melakukan proses aktivasi akun.

### 3.3 Tampilan Login admin
[![Login Admin Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_halaman-login-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_halaman-login-admin.png)
Di halaman ini akan muncul menu login. Disini hanya terdapat 2 **field** yng harus diisi, yaitu : Username yang sudah di aktivasi melalui E-mail dan juga password yang telah dibuat ketika register. Jika admin belum melakukan registrasi maka admin dapat menekan tombol **register** untuk melakukan registrasi atau **back to home** yang akan mengarahkan ke halaman utama.

### 3.4 Tampilan Dashboard Admin
[![Dashboard Admin](/document/aplikasi/psb-umum/images/implementasi/psb-umum_halaman-dashboard-utama.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_halaman-dashboard-utama.png)
Didalam page ini terdapat beberapa list menu yang dapat diolah oleh admin yang akan terintegrasi dengan aplikasi PPDB. Didalam aplikasi admin juga dapat melihat berapa jumlah user yang terdaftar pada aplikasi PPDB dan beberapa data utama dalam bentuk chart grafik dan pie.

#### 3.4.1 Tampilan Menu Pendaftaran 
[![Menu Pendaftaran](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-pendaftaran-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-pendaftaran-admin.png)
Didalam **menu** ini terdapat modul pendaftaran, yang didalamnya terdapat data pendaftaran yang telah diinput oleh siswa. Pada menu ini admin dapat mengolah data yang telah ada seperti menambahkan, melihat, mengedit, dan juga menghapus data pendaftaran yang telah ada.

Berikut ini merupakan tampilan **Add** Pendaftaran:
[![Add Pendaftaran](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-pendaftaran-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-pendaftaran-admin.png)

Berikut ini merupakan tampilan **Show** Pendaftaran:
[![Show Pendaftaran](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-pendaftaran-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-pendaftaran-admin.png)

Berikut ini merupakan tampilan **Edit** Pendaftaran:
[![Edit Pendaftaran](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-pendaftaran-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-pendaftaran-admin.png)


#### 3.4.2 Tampilan Menu Seleksi 
[![Menu Seleksi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-seleksi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-seleksi-admin.png)
Didalam **menu** ini terdapat modul seleksi. Pada menu ini terdapat data hasil seleksi siswa yang telah melakukan pendaftaran. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data seleksi yang telah ada.

Berikut ini merupakan tampilan **Add** Seleksi:
[![Add Seleksi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-seleksi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-seleksi-admin.png)

Berikut ini merupakan tampilan **Show** Seleksi:
[![Show Seleksi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-seleksi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-seleksi-admin.png)

Berikut ini merupakan tampilan **Edit** Seleksi:
[![Edit Seleksi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-seleksi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-seleksi-admin.png)

#### 3.4.3 Tampilan Menu Siswa 
[![Menu Siswa](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-siswa-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-siswa-admin.png)
Didalam **menu** ini terdapat data identitas siswa yang telah melakukan pendaftaran. Pada menu ini admin dapat melihat data identitas lengkap dari siswa tersebut. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data siswa yang telah ada.

Berikut ini merupakan tampilan **Add** Siswa:
[![Add Siswa](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-siswa-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-siswa-admin.png)

Berikut ini merupakan tampilan **Show** Siswa:
[![Show Siswa](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-siswa-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-siswa-admin.png)

Berikut ini merupakan tampilan **Edit** Siswa:
[![Edit Siswa](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-siswa-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-siswa-admin.png)

#### 3.4.4 Tampilan Menu Sekolah 
[![Menu Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-sekolah-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-sekolah-admin.png)
Didalam **menu** ini terdapat data sekolah SMA dan SMK negri yang terdapat di seluruh wilayah Provinsi Banten. Pada menu ini admin dapat melihat data sekolah SMA dan SMK negri yang terdapat di Banten. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data sekolah yang telah ada.

Berikut ini merupakan tampilan **Add** Sekolah:
[![Add Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-sekolah-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-sekolah-admin.png)

Berikut ini merupakan tampilan **Show** Sekolah:
[![Show Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-sekolah-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-sekolah-admin.png)

Berikut ini merupakan tampilan **Edit** Sekolah:
[![Edit Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-sekolah-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-sekolah-admin.png)

#### 3.4.5 Tampilan Menu Prodi Sekolah 
[![Menu prodi Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-prodi-sekolah-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-prodi-sekolah-admin.png)
Didalam **menu** ini terdapat data prodi sekolah SMA dan SMK negri yang terdapat di seluruh wilayah Provinsi Banten. Pada menu ini admin dapat melihat data prodi sekolah, program keahlian dan juga kuota siswa pada setiap sekolah SMA dan SMK negri yang terdapat di Banten. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data prodi sekolah yang telah ada.

Berikut ini merupakan tampilan **Add** Prodi Sekolah:
[![Add Prodi Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-prodi-sekolah-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-prodi-sekolah-admin.png)

Berikut ini merupakan tampilan **Show** Prodi Sekolah:
[![Show Prodi Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-prodi-sekolah-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-prodi-sekolah-admin.png)

Berikut ini merupakan tampilan **Edit** Prodi Sekolah:
**APLIKASI MASIH EROR**
[![Edit Prodi Sekolah](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-sekolah-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-sekolah-admin.png)

#### 3.4.6 Tampilan Menu Program keahlian 
[![Menu Program Keahlian](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-program-keahlian-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-program-keahlian-admin.png)
Didalam **menu** ini terdapat data program keahlian yang ditawarkan oleh sekolah SMA dan SMK negri yang terdapat di seluruh wilayah Provinsi Banten. Pada menu ini admin dapat melihat data program keahlian yang terdapat di sekolah SMA dan SMK negri yang terdapat di Banten. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data sekolah yang telah ada.

Berikut ini merupakan tampilan **Add** Program Keahlian:
[![Add Program Keahlian](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-program-keahlian-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-program-keahlian-admin.png)

Berikut ini merupakan tampilan **Show** Program Keahlian:
[![Show Program Keahlian](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-program-keahlian-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-program-keahlian-admin.png)

Berikut ini merupakan tampilan **Edit** Program Keahlian:
[![Edit Program Keahlian](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-program-keahlian-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-program-keahlian-admin.png)

#### 3.4.7 Tampilan Menu Kegiatan 
[![Menu Kegiatan](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-kegiatan-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-kegiatan-admin.png)
Didalam **menu** ini terdapat data kegiatan mengenai proses pendaftaran dan seleksi calon siswa baru yang akan mendaftar ke sekolah SMA dan SMK negri yang terdapat di seluruh wilayah Provinsi Banten. Pada menu ini admin dapat melihat data pendaftaran maupun tanggal dilaksanakannya proses kegiatan dan seleksi penerimaan peserta didik baru. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data kegiatan yang telah ada.

Berikut ini merupakan tampilan **Add** Kegiatan:
[![Add Kegiatan](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-kegiatan-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-kegiatan-admin.png)

Berikut ini merupakan tampilan **Show** Kegiatan:
[![Show Kegiatan](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-kegiatan-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-kegiatan-admin.png)

Berikut ini merupakan tampilan **Edit** Kegiatan:
[![Edit Kegiatan](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-kegiatan-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-kegiatan-admin.png)

#### 3.4.8 Tampilan Menu Orang Tua 
[![Menu Orang Tua](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-orang-tua-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-orang-tua-admin.png)
Didalam **menu** ini terdapat data orang tua dari siswa yang telah melakukan registrasi. Pada menu ini admin dapat melihat data lengkap orang tua siswa yang telah melakukan registrasi. Didalam menu ini admin dapat melihat data orang tua baik alamatnya, pekerjaan, pendidikan, dan data penunjang lainnya. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data orang tua yang telah ada.

Berikut ini merupakan tampilan **Add** Orang Tua:
[![Add Orang Tua](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-orang-tua-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-orang-tua-admin.png)

Berikut ini merupakan tampilan **Show** Orang Tua:
[![Show Orang Tua](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-orang-tua-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-orang-tua-admin.png)

Berikut ini merupakan tampilan **Edit** Orang Tua:
[![Edit Orang Tua](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-orang-tua-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-orang-tua-admin.png)

#### 3.4.9 Tampilan Menu Prestasi 
[![Menu Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-prestasi-admin.png)
Didalam **menu** ini terdapat data prestasi siswa dari lomba yang telah diikutinya. Setiap lomba memiliki nilai yang berbeda-beda dan akan di kalkulasikan ke dalam menu **nilai**. Pada menu ini admin dapat melihat daftar siswa yang memiliki prestasi dan lomba yang diikutinya beserta tingkat dan juaranya. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data prestasi siswa yang telah ada.

Berikut ini merupakan tampilan **Add** Prestasi:
[![Add Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-prestasi-admin.png)

Berikut ini merupakan tampilan **Show** Prestasi:
[![Show Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-prestasi-admin.png)

Berikut ini merupakan tampilan **Edit** Prestasi:
[![Edit Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-prestasi-admin.png)

#### 3.4.10 Tampilan Menu Master Prestasi 
[![Menu Master Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-master-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-master-prestasi-admin.png)
Didalam **menu** ini terdapat data mengenai prestasi, juara, tingkat, dan jumlah nilai yang didapatkan dari prestasi tersebut. Pada menu ini admin dapat melihat daftar data juara dari mulai tingkat kabupaten sampai tingkat internasional. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data prestasi yang telah ada.

Berikut ini merupakan tampilan **Add** Master Prestasi:
[![Add Master Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-master-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-master-prestasi-admin.png)

Berikut ini merupakan tampilan **Show** Master Prestasi:
[![Show Master Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-master-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-master-prestasi-admin.png)

Berikut ini merupakan tampilan **Edit** Master Prestasi:
[![Edit Master Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-master-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-master-prestasi-admin.png)

#### 3.4.11 Tampilan Menu Jenis Prestasi 
[![Menu Jenis Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-jenis-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-jenis-prestasi-admin.png)
Didalam **menu** ini terdapat daftar data jenis prestasi. Pada menu ini admin dapat melihat daftar jenis prestasi yang tersedia, mulai dari kejuaaraan yang diselenggarakan oleh Kemendikbud sampai kejuaraan yang diselenggarakan oleh Kemenag. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data jeni prestasi yang telah ada.

Berikut ini merupakan tampilan **Add** Jenis Prestasi:
[![Add Jenis Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-jenis-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-jenis-prestasi-admin.png)

Berikut ini merupakan tampilan **Show** Jenis Prestasi:
[![Show Jenis Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-jenis-prestasi.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-jenis-prestasi.png)

Berikut ini merupakan tampilan **Edit** Jenis Prestasi:
[![Edit Jenis Prestasi](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-jenis-prestasi-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-jenis-prestasi-admin.png)

#### 3.4.12 Tampilan Menu SKTM 
[![Menu SKTM](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-sktm-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-sktm-admin.png)
Didalam **menu** ini terdapat data mengenai siswa yang memiliki surat keterangan tidak mampu **SKTM**. Siswa yang memiliki SKTM akan mendapatkan nomor SKTM dan juga nilai yang nantinya akan dikalkulasikan ke menu **nilai**. Pada menu ini admin dapat melihat daftar siswa yang memiliki SKTM beserta jenisnya. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data siswa pemegang SKTM yang telah ada.

Berikut ini merupakan tampilan **Add** SKTM:
[![Add SKTM](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-sktm-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-sktm-admin.png)

Berikut ini merupakan tampilan **Show** SKTM:
[![Show SKTM](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-sktm-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-sktm-admin.png)

Berikut ini merupakan tampilan **Edit** SKTM:
[![Edit SKTM](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-sktm-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-sktm-admin.png)

#### 3.4.13 Tampilan Menu Master SKTM 
[![Menu Master SKTM](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-master-sktm-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-master-sktm-admin.png)
Didalam **menu** ini terdapat daftar data SKTM yang ada. Di menu ini terdapat data jenis SKTM yang tersedia yang dapat dipilih oleh siswa. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data Master SKTM yang telah ada

Berikut ini merupakan tampilan **Add** Master SKTM:
[![Add Master SKTM](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-master-sktm-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-master-sktm-admin.png)

Berikut ini merupakan tampilan **Show** Master SKTM:
[![Show Master SKTM](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-master-sktm-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-master-sktm-admin.png)

Berikut ini merupakan tampilan **Edit** Master SKTM:
[![Edit Master SKTM](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-master-sktm-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-master-sktm-admin.png)

#### 3.4.14 Tampilan Menu Nilai 
[![Menu Nilai](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-nilai-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-nilai-admin.png)
Didalam **menu** ini terdapat daftar data nilai siswa yang ada. Di menu ini nilai siswa di dapatkan dari kalkulasi beberapa data yang ada seperti: akademik, SKTM, Prestasi, dan juga zona. Di menu ini admin dapat mengetahui berapa total nilai dan bobot yang didapatkan oleh siswa. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data nilai siswa yang telah ada.

Berikut ini merupakan tampilan **Add** Nilai:
[![Add Nilai](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-nilai-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-nilai-admin.png)

Berikut ini merupakan tampilan **Show** Nilai:
[![Show Nilai](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-nilai-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-nilai-admin.png)

Berikut ini merupakan tampilan **Edit** Nilai:
[![Edit Nilai](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-nilai-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-nilai-admin.png)

#### 3.4.15 Tampilan Menu Akademik 
[![Menu Akademik](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-akademik-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-akademik-admin.png)
Didalam **menu** ini terdapat daftar data nilai siswa yang diperoleh dari hasil UN. Di menu ini nilai Un siswa akan dikalkulasikan ke menu **nilai**, yang nantinya akan akan diolah dengan hasil nilai lainnya  yang di dapatkan dari kalkulasi beberapa data yang ada seperti: SKTM, Prestasi, dan juga zona. Di menu ini admin dapat mengetahui berapa nilai UN yang didapat oleh siswa sperti nilai : Bhs. Indonesia, Bhs. Inggris, Matematika, dan juga IPA. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data nilai UN siswa yang telah ada.

Berikut ini merupakan tampilan **Add** Akademik:
[![Add Akademik](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-akademik-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-akademik-admin.png)

Berikut ini merupakan tampilan **Show** Akademik:
[![Show Akademik](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-akademik-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-akademik-admin.png)

Berikut ini merupakan tampilan **Edit** Akademik:
[![Edit Akademik](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-akademik-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-akademik-admin.png)

#### 3.4.16 Tampilan Menu Zona 
[![Menu Zona](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-zona-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-zona-admin.png)
Didalam **menu** ini terdapat data zona siswa dan zona sekolah yang dipilih oleh siswa ketika melakukan pendaftaran. Pada menu ini zona siswa dan sekolah bisa dilihat, sehingga lokasi siswa dan sekolah bisa diketahui. Didalam menu ini zona siswa dan juga sekolah mempengaruhi nilai zona tersebut, yang nantinya akan dikalkulasikan ke dalam menu nilai. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data zona siswa yang telah ada.

Berikut ini merupakan tampilan **Add** Zona:
[![Add Zona](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-zona-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-zona-admin.png)

Berikut ini merupakan tampilan **Show** Zona:
[![Show Zona](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-zona-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-zona-admin.png)

Berikut ini merupakan tampilan **Edit** Zona:
[![Edit Zona](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-zona-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-zona-admin.png)

#### 3.4.17 Tampilan Menu Master Zona 
[![Menu Master Zona](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-master-zona-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-master-zona-admin.png)
Didalam **menu** ini terdapat data zona dari setiap wilayah yang ada di seluruh Provinsi Banten. Pada menu ini admin dapat melihat kode zona dari setiap kabupaten dan kota yang ada di Banten. Pada menu ini admin dapat menambahkan, melihat, mengedit, dan juga menghapus data master zona yang telah ada.

Berikut ini merupakan tampilan **Add** Master Zona:
[![Add Master Zona](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-master-zona-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-add-master-zona-admin.png)

Berikut ini merupakan tampilan **Show** Master Zona:
[![Show Master Zona](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-master-zona-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-show-master-zona-admin.png)

Berikut ini merupakan tampilan **Edit** Master Zona:
[![Edit Master Zona](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-master-zona-admin.png)](/document/aplikasi/psb-umum/images/implementasi/psb-umum_menu-edit-master-zona-admin.png)

### 3.4 Tampilan Konten Dokter Jaga
[![Tampilan Konten Dokter Jaga](/document/aplikasi/psb-umum/images/implementasi/20171123_ars-lihat-dokter-jaga.png)](/document/aplikasi/psb-umum/images/implementasi/20171123_ars-lihat-dokter-jaga.png)
Didalam **page** ini admin rumah sakit dapat melihat, mengedit dan menghapus data dokter jaga dari aplikasi serta dapat menambahkan dokter jaga dengan memilih tombol " **Add Dokter jaga** ".

#### 3.4.1 Tampilan Tambah Dokter Jaga
[![Tambah Dokter Jaga](/document/aplikasi/psb-umum/images/implementasi/20171123_ars-input-dokter-jaga.png)](/document/aplikasi/psb-umum/images/implementasi/20171123_ars-input-dokter-jaga.png)
Didalam **page** ini terdapat **form input** dokter jaga yang harus diisi oleh admin rs untuk menambahkan dokter jaga. Jika data dokter jaga sudah ada atau tidak lengkap maka memilih tombol "**ADD** " akan kembali kedalam **page** tambah dokter jaga sedangkan jika berhasil akan pindah ke **page** dokter jaga.

### 3.5 Tampilan Konten Layanan
[![Tampilan Konten Dokter Jaga](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-layanan.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-layanan.png)
Didalam **page** ini admin rumah sakit dapat melihat, mengedit dan menghapus data layanan pada aplikasi YANKES serta dapat menambahkan layanan dengan memilih tombol " **Add Layanan** ".

#### 3.5.1 Tampilan Tambah Layanan
[![Tambah Layanan](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-input-layanan.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-input-layanan.png)
Didalam **page** ini terdapat **form input** layanan yang harus diisi oleh admin rs untuk menambahkan layanan. Jika data layanan sudah ada atau tidak lengkap maka memilih tombol "**ADD** " akan kembali kedalam **page** tambah layanan sedangkan jika berhasil akan pindah ke **page** layanan.

### 3.6 Tampilan Konten Kelas Ruangan
[![Lihat kleas Ruangan](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-kelas-ruangan.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-kelas-ruangan.png)
didalam **page** ini admin RS dapat melihat jenis-jenis kelas ruangan. Didalam **page** ini admin RS dapat mengedit dan menghapus data jenis ruangan dengan memilih tombol "**Edit** atau **Delete** ", serta menambahkan data jenis ruangan dengan memilih tombol " **Add** Kelas Ruangan** ".

#### 3.6.1 Tampilan Tambah Kelas Ruangan
[![Tambah Kelas Ruangan](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-input-kelas-ruangan.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-input-kelas-ruangan.png)
Didalam **page** ini terdapat **form input** kelas ruangan yang harus diisi oleh admin RS untuk menambahkan data kelas ruangan.

### 3.7 Tampilan Konten Ruang Rawat
[![Konten Ruang Rawat](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-ruangan-rawat.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-ruangan-rawat.png)
didalam **page** ini admin RS dapat melihat jenis-jenis ruangan rawat. Didalam **page** ini admin RS dapat mengedit dan menghapus data jenis ruang rawat dengan memilih tombol "**Edit** atau **Delete** ", serta menambahkan data jenis ruang rawat dengan memilih tombol " **Add** Ruang Rawat** ".

#### 3.7.1 Tambah Ruang Rawat
[![Input Ruang Rawat](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-input-ruangan-rawat.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-input-ruangan-rawat.png)
Didalam **page** ini terdapat **form input** ruang rawat yang harus diisi oleh admin RS untuk menambahkan data ruang rawat.

### 3.8 Tampilan Konten Tempat Tidur Pasien
[![Lihat tempat Tidur Pasien](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-tempat-tidur-pasien.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-tempat-tidur-pasien.png)
Didalam **page** ini admin RS dapat melihat tempat tidur pasien yang sudah terisi atau masih kosong. Didalam **page** ini admin RS dapat mengganti status tempat tidur pasien di tombol " **Edit** " ataupun menghapus data tempat tidur pasien dengan memilih tombol " **delelte** ". Admin Rs juga dapat menambahkan data tempat idur pasien dengan memilih tombol " **Add** Tempat Tidur ".

#### 3.8.1 Tampilan Tambah tempat Tidur
[![input tempat tidur pasien](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-input-tempat-tidur-pasien.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-input-tempat-tidur-pasien.png)
Didalam **page** ini terdapat **form input** tempat tidur pasien yang harus diisi oleh admin RS untuk menambahkan data tempat tidur pasien.

### 3.9 Tampilan Konten Rumah Sakit
[![Lihat Rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-rs.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-lihat-rs.png)
Didalam **page** ini admin RS dapat melihat informasi tentang rumah sakit dan dapat mengedit informasi rumah sakit dengan memilih **icon** pensil diujung kiri bawah **page**.

#### 3.9.1 Tampilan Edit Rumah Sakit
[![Edit Rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-edit-rs.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-edit-rs.png)
[![Edit Rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-edit-rs2.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-edit-rs2.png)
[![Edit Rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-edit-rs3.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_ars-edit-rs3.png)
Didalam **page** ini terdapat **form input** untuk mengedit rumah sakit didalam **form** ini terdapat juga **field** untuk menambahkan foto dan lokasi map rumah sakit.

## 4. Menu dan Cara Penggunaan **User** (Pengguna Aplikasi)

### 4.1 Halaman Depan Aplikasi

[![Halaman Depan Aplikasi](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes.png)
[![Halaman Depan Aplikasi2](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes2.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes2.png)
[![Halaman Depan Aplikasi3](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes3.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes3.png)
[![Halaman Depan Aplikasi4](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes4.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes4.png)
[![Halaman Depan Aplikasi5](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes5.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_hal-depan-yankes5.png)
Didalam **page** ini berisi tentang informasi dan menu-menu pada bagian atas aplikasi.

### 4.2 Tampilan **Page** Registrasi
[![Page Registrasi](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_registrasi-dokter-dan-pasien.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_registrasi-dokter-dan-pasien.png)
Untuk masuk kedalam **page** ini **user** sebelumnya harus memilih menu "DAFTAR" di menu-menu aplikasi pada halaman depan aplikasi lalu memilih menu "SIGN UP" pada menu "DAFTAR". Didalam **page** ini tedapat beberapa **field** untuk melakukan registrasi jika sudah terisi semua **user** dapat menekan tombol "SIGN UP" pada bagian bawah **form registrasi**.

### 4.3 Tampilan **page** Login
[![Tampilan Login](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_login-dokter-dan-pasien.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171123_login-dokter-dan-pasien.png)
Untuk masuk kedalam **page** ini **user** sebelumnya harus memilih menu "DAFTAR" di menu-menu aplikasi pada halaman depan aplikasi lalu memilih menu "SIGN IN" pada menu "DAFTAR". Didalam **page** ini tedapat beberapa **field** untuk melakukan **log in** jika sudah terisi semua **user** dapat menekan tombol "LOG IN" pada bagian bawah **form log in**.

### 4.4 Tampilan Konten Rumah Sakit
[![Lihat Rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-rumah-sakit.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-rumah-sakit.png)
Didalam **page** ini **user** dapat melihat informasi tentang rumah sakit.Untuk melihat lebih **detail** tentang informasi rumah sakit **user** dapat memilih tombol "LIHAT" dibawah gambar rumah sakit.

### 4.5 Tampilan Profile Rumah Sakit
[![Lihat Profile Rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_profile-rumah-sakit.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_profile-rumah-sakit.png)
Didalam **page** ini **user** dapat melihat informasi rumah sakit beserta dengan layanan yang tersedia dirumah sakit.

### 4.6 Tampilan Dokter Jaga Rumah Sakit
[![Lihat List Dokter Jaga Rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-dokter-jaga-rs.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-dokter-jaga-rs.png)
Tampilan ini berada didalam **page** profile rumah sakit yang tergabung dalam konten layanan rumah sakit. Disini **user** dapat melihat list dokter jaga rumah sakit beserta info spesialis dokter, hari jaga dan jam jaga.

### 4.7 Tampilan Layanan Rumah Sakit
[![Lihat Layanan rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-layanan-rs.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-layanan-rs.png)
Tampilan ini berada didalam **page** profile rumah sakit yang tergabung dalam konten layanan rumah sakit. Disini **user** dapat melihat layanan apa saja yang disediakan oleh rumah sakit baik layanan umum maupun layanan oleh dokter.

### 4.8 Tampilan Tempat Tidur Rawat Inap Rumah Sakit
[![Lihat Tempat Inap rumah Sakit](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-tempat-tidur-rs.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-tempat-tidur-rs.png)
Tampilan ini berada didalam **page** profile rumah sakit yang tergabung dalam konten layanan rumah sakit. Disini **user** dapat melihat ruang kamar inap yang kosongdan jenis kamar nya.

### 4.9 Tampilan Data Dokter
[![Lihat List dokter](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-dokter.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-dokter.png)
Ditampilan ini **user** bisa melihat informasi tentang dokter yang terdaftar diaplikasi YANKES dan untuk melihat informasi lebih lengkap **user** dapat memilih tombol "PROFILE" dibawah informasi dokter.

### 4.10 Tampilan Profile Dokter
[![lihat profile dokter](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_profile-dokter.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_profile-dokter.png)
[![lihat profile dokter](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_jadwal-praktek.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_jadwal-praktek.png)
Ditampilan ini **user** dapat melihat informasi dokter serta jadwal jaga dokter dan terdapat menu konsultasi didalam tampilan ini.

### 4.11 Tampilan Jadwal Praktek Dokter
[![lihat jadwal praktek dokter](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_jadwal-praktek.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_jadwal-praktek.png)
Tampilan ini berada didalam tampilan profile dokter, ditampilan ini **user** dapat melihat jadwal jaga dokter yang ingin dilihat.

### 4.12 Tampilan Konsultasi Dokter
[![Lihat Konsultasi](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-konsultasi.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-konsultasi.png)
Tampilan ini berada didalam tampilan profile dokter, ditampilan ini pasien dapat melakukan konsultasi dengan dokter.

### 4.13 Tampilan Kamar Inap
[![Lihat Kamar Inap](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-kamar-inap.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-kamar-inap.png)
[![Lihat Kamar Inap](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-kamar-inap2.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-kamar-inap2.png)
Didalam tampilan ini **user** dapat melihat list rumah sakit dan kamar rawat inap yang tersedia dirumah sakit tersebut.

### 4.14 Tampilan News
[![Lihat News](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-news.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-news.png)
[![Lihat News](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-news2.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-news2.png)
Ditampilan ini **user** dapat melihat berita berita terkait yang berada di Provinsi Banten, untuk melihat lebih **detail** tentang berita **user** dapat memilih tombol " READ MORE".

#### 4.14.1 Tampilan Detail News
[![lihat detail berita](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_lihat-detail-berita.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_lihat-detail-berita.png)
Ditampilam ini **user** dapat melihat detail berita dari tampilan "NEWS".

### 4.15 Tampilan Blog (Artikel)
[![Tampilan artikel](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-blog.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-blog.png)
[![Tampilan artikel](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-blog2.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-blog2.png)
Didalam tampilan ini **user** dapat melihat artikel-artikel terkait kesehatan yang berada di Provinsi Banten, untuk melihat detail blog **user** dapat memilih tombol "READ MORE".

#### 4.15.1 Tampilan Detail Blog (Artikel)
[![lihat detail blog](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_lihat-detail-blog.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_lihat-detail-blog.png)
Didalam tampilan ini **user** dapat melihat detail dari blog (artikel).

### 4.16 Tampilan Contact
[![Tampilan Contact](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-contact-us.png)](/document/aplikasi/layanan-kesehatan/images/implementasi/20171124_konten-contact-us.png)
Didalam tampilan ini **user** dapat melihat informasi tentang pengembang aplikasi YANKES serta dapat menghubungi pengembang. -->
