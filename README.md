# FresCis

WebApp untuk mendeteksi kesegaran ikan melalui gambar mata | Senior Project

- View github page : https://lutfiandri.github.io/frescis/

## Kelompok FresCis

- Ketua Kelompok: Adhyaksa Zhalifunnas - 20/463586/TK/51578
- Anggota 1: Lutfi Andriyanto - 20/456370/TK/50500
- Anggota 2: Ardianto Ramadhan - 20/463594/TK/51586

> **Senior Project TI**
>
> Departemen Teknik Elektro dan Teknologi Informasi, Fakultas Teknik, Universitas Gadjah Mada

<details markdown="1">
<summary><h2>Modul 1</h2></summary>

## Nama Produk

FresCis

## Jenis Produk

Software

## Latar Belakang

Kesegaran ikan merupakan hal yang penting diperhatikan bila ingin mengkonsumsinya.namun, tidak semua pembeli ikan di pasar mengetahui kesegaran ikan yang akan dibeli. Seringkali ikan yang dibeli tidak segar sehingga mempengaruhi rasa dari olahan ikan tersebut.

Perbedaan antara ikan segar dan tidak segar sebenarnya dapat diketahuidengan melihat beberapa bagian ikan, salah satunya adalah bagian mata. Mata ikan segarcenderung memiliki tampan yang jernih dan cerah, serta lebih menonjol. Sebaliknya,ikan yang tidak segar memiliki mata yang cenderung keruh, berwarna merah, dan cekungke dalam.

## Rumusan Permasalahan

Apa perbedaan mata ikan segar dan tidak segar?

## Ide Solusi

Sebuah aplikasi berbasis website yang berfungsi untuk mendeteksi kesegaran ikanmelalui gambar matanya.

| Fitur                  | Keterangan                                                                               |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| Deteksi kesegaran ikan | Memprediksi kesegaran ikan menggunakan kamera berdasarkan mata ikan                      |
| Riwayat hasil deteksi  | Menyimpan hasil deteksi kesegaran ikan dan bisa dikelompokkan untuk memudahkan pencarian |
| Fishpedia              | Pengetahuan umum mengenai ikan-ikan yang dapat dikonsumsi                                |

## Analisis Kompetitor

### Kompetitor 1

| \*               | \*                                        |
| ---------------- | ----------------------------------------- |
| Nama             | Fishku                                    |
| Jenis kompetitor | Direct competitor                         |
| Jenis produk     | Aplikasi mobile                           |
| Target customer  | Pembeli dan penjual                       |
| Unique value     | Merupakan Top 16 Bangkit Capstone Project |

**Kelebihan**

- Memiliki Consumer App dan Seller App
- Memiliki fitur Freshness Detection

**Kelemahan**

- Berbasis mobile (perlu instalasi)

### Kompetitor 2

| \*               | \*                                |
| ---------------- | --------------------------------- |
| Nama             | SILLY FISH INDONESIA              |
| Jenis kompetitor | Indirect competitor               |
| Jenis produk     | Frozen seafood                    |
| Target customer  | Home cook dan Restoran (high-end) |
| Unique value     | Fully fledged company             |

**Kelebihan**

- Terdapat store untuk membeli ikan
- Recipe list
- Customer Service

**Kelemahan**

- Kepastian kesegaran ikan hanya daripihak Silly Fish
- Produk yang ada merupakan ikan beku

### Kompetitor 3

| \*               | \*                                                                                                                                 |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Nama             | eFresh (dari eFishery)                                                                                                             |
| Jenis kompetitor | Tertiary competitor                                                                                                                |
| Jenis produk     | Aplikasi online shop                                                                                                               |
| Target customer  | Pembeli                                                                                                                            |
| Unique value     | Merupakan startup yang berfokus pada bidang udang dan ikan konsumsi, jadi produkeFresh ini seharusnya bisa dipastikan kesegarannya |

**Kelebihan**

- Bisa membeli ikan yang segar secara daring melalui aplikasi

**Kelemahan**

- Kepastian kesegaran ikan hanya daripihak eFishery

</details>

<details markdown="1">
<summary><h2>Modul 2</h2></summary>

## Metodologi SDLC

Metode SDLC Waterfall

### Alasan SDLC

Karena metode waterfall memiliki proses pengerjaan yang terurut, sehingga proses pengerjaan dapat terjadwal dengan baik. Selain itu metode waterfall sangat cocok untuk sistem dengan kompleksitas yang rendah

## Tujuan Produk

Untuk membantu para konsumen untuk memilih antara ikan segar dan tidak segar yang nantinya akan dibeli

## Pengguna Potensial

Para pembeli dan konsumen ikan, terutama para pembeli yang kurang bisa membedakan antara ikan yang segar dan tidak segar

## Use-case Diagram

![Use Case Diagram 1](/images/usecase-1.png)

![Use Case Diagram 2](/images/usecase-2.png)

## Functional Requirements

| FR                       | Deskripsi                                                                                                                                         |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Login                    | Pengguna bisa melakukan login menggunakan akun google                                                                                             |
| Register                 | Pengguna bisa melakukan register menggunakan akun google.                                                                                         |
| Logout                   | Pengguna bisa melakukan logout                                                                                                                    |
| Prediksi kesegaran ikan  | Pengguna bisa melakukan prediksi kesegaran ikan dengan mengambil gambar mata ikan melalui website (website akan dioptimasi untuk tampilan mobile) |
| Melihat history prediksi | Pengguna yang telah login bisa melihat daftar prediksi yang pernah ia lakukan. Akan ada filtering dan grouping berdasar hari di fitur ini         |
| Melihat informasi ikan   | Pengguna bisa melihat informasi-informasi ikan secara umum (untuk bacaan saja)                                                                    |

## Entity Relationship Diagram

![ERD 1](/images/erd-1.png)

**Catatan:**

- Meskipun kami menggunakan ERD. Namun, untuk implementasinya, bisa saja kami akan menggunakan non-relational database karena belum ada pertimbangan database yang digunakan untuk saat ini

## Low-Fidelity Wireframe

![LoFi 1](/images/lofi-1.png)
![LoFi 2](/images/lofi-2.png)

## Gantt-Chart

![Gantt Chart 1](/images/ganttchart-1.png)

</details>