<div align="center">
  
# Membuat Karakter Anime menggunakan Deep Convolutional Generative Adversarial Networks (DCGAN) dan Keras

Proyek ini menggunakan Deep Convolutional Generative Adversarial Networks (DCGANs) untuk menciptakan avatar anime yang berbeda bagi para pemain video game. Proyek ini mencakup pelatihan model DCGAN dengan memanfaatkan dataset Anime Face yang diperoleh dari Kaggle. Model ini memiliki dua komponen utama: Generator, yang menciptakan wajah anime baru, dan Discriminator, yang membedakan antara wajah asli dan yang dihasilkan. Generator diterapkan sebagai jaringan saraf dasar dengan Keras, sedangkan Discriminator diterapkan sebagai fungsi regresi logistik. Proses pelatihan memanfaatkan optimizer Adam, dan fungsi loss ditetapkan untuk menilai kinerja kedua jaringan.

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">
<img src="https://img.shields.io/badge/Kaggle-%2300B7D6.svg?style=for-the-badge&logo=kaggle&logoColor=white">
<img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=keras&logoColor=white">

</div>
============================================================================================

## Daftar Isi
- [1. Deskripsi](#deskripsi)
- [2. Dataset](#dataset)
- [3. Dependensi](#dependensi)
- [4. Cara Menjalankan](#cara-menjalankan)
- [5. Hasil](#hasil)
- [6. Catatan](#catatan)

============================================================================================

## Deskripsi

Proyek ini dibagi menjadi dua bagian:

1. **Dasar Generative Adversarial Networks (GAN)**: Bagian ini memperkenalkan prinsip-prinsip teoritis di balik GAN menggunakan contoh mainan. Ini mencakup Generator, Diskriminator, Fungsi Loss, dan proses pelatihan.
2. **Deep Convolutional Generative Adversarial Networks (DCGAN)**: Bagian ini berfokus pada penerapan DCGAN untuk menghasilkan karakter anime. Ini mencakup pemuatan dataset, pembuatan generator data, membangun Generator dan Diskriminator, mendefinisikan fungsi loss dan pengoptimal, membuat fungsi langkah pelatihan, dan melatih DCGAN. Selain itu, ia mengeksplorasi bagaimana mengubah input ruang laten DCGAN memengaruhi gambar yang dihasilkan.

============================================================================================

## Dataset

<p align="justify">
Proyek ini menggunakan dataset Anime Face dari Kaggle. Dataset asli memiliki 63.632 wajah anime "berkualitas tinggi", tetapi untuk membuat model berlatih lebih cepat, dataset yang lebih kecil yang disebut `cartoon_20000` digunakan. Dataset ini berisi 20.000 gambar yang dipilih secara acak dari dataset asli.
</p>
============================================================================================

## Dependensi

* tensorflow>=2.9.0
* keras
* pandas
* numpy
* scikit-learn
* seaborn
* matplotlib
* tqdm
* skillsnetwork

============================================================================================

## Cara Menjalankan

1. Kloning repositori ini.
2. Buka notebook Google Colab.
3. Jalankan sel kode di notebook.

============================================================================================

## Hasil

Setelah pelatihan, DCGAN akan menghasilkan gambar karakter anime baru. Gambar-gambar ini akan disimpan di folder `images` dalam direktori kerja saat ini.

============================================================================================

## Catatan

* Proyek ini membutuhkan waktu yang lama untuk dilatih.
* Hasilnya dapat bervariasi tergantung pada data pelatihan dan parameter model.

============================================================================================
