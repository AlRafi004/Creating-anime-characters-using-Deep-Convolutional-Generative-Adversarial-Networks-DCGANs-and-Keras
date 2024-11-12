# Membuat Karakter Anime menggunakan Deep Convolutional Generative Adversarial Networks (DCGAN) dan Keras

Proyek ini menunjukkan cara membuat karakter anime menggunakan Deep Convolutional Generative Adversarial Networks (DCGAN) dan Keras.

## Deskripsi

Proyek ini dibagi menjadi dua bagian:

1. **Dasar: Generative Adversarial Networks (GAN)**: Bagian ini memperkenalkan prinsip-prinsip teoritis di balik GAN menggunakan contoh mainan. Ini mencakup Generator, Diskriminator, Fungsi Loss, dan proses pelatihan.
2. **Deep Convolutional Generative Adversarial Networks (DCGAN)**: Bagian ini berfokus pada penerapan DCGAN untuk menghasilkan karakter anime. Ini mencakup pemuatan dataset, pembuatan generator data, membangun Generator dan Diskriminator, mendefinisikan fungsi loss dan pengoptimal, membuat fungsi langkah pelatihan, dan melatih DCGAN. Selain itu, ia mengeksplorasi bagaimana mengubah input ruang laten DCGAN memengaruhi gambar yang dihasilkan.

## Dataset

Proyek ini menggunakan dataset Anime Face dari Kaggle. Dataset asli memiliki 63.632 wajah anime "berkualitas tinggi", tetapi untuk membuat model berlatih lebih cepat, dataset yang lebih kecil yang disebut `cartoon_20000` digunakan. Dataset ini berisi 20.000 gambar yang dipilih secara acak dari dataset asli.

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

## Cara Menjalankan

1. Kloning repositori ini.
2. Buka notebook Google Colab.
3. Jalankan sel kode di notebook.

## Hasil

Setelah pelatihan, DCGAN akan menghasilkan gambar karakter anime baru. Gambar-gambar ini akan disimpan di folder `images` dalam direktori kerja saat ini.

## Catatan

* Proyek ini membutuhkan waktu yang lama untuk dilatih.
* Hasilnya dapat bervariasi tergantung pada data pelatihan dan parameter model.

## Referensi

* [1] Goodfellow, I. J., Pouget-Abadie, J., Mirza, M., Xu, B., Warde-Farley, D., Ozair, S., ... & Bengio, Y. (2014). Generative adversarial networks. *Advances in neural information processing systems*, *27*.
* [2] Radford, A., Metz, L., & Chintala, S. (2015). Unsupervised representation learning with deep convolutional generative adversarial networks. *arXiv preprint arXiv:1511.06434*.
* [3] How to Develop a Deep Convolutional GAN (DCGAN) From Scratch. *LearnOpenCV*.