# deploy-ML-model-with-flask

## Dataset 
Dataset yang digunakan dalam training adalah gambar berupa suit batu gunting kertas, pada model yang di deploy bisa menggunakan gambar pose suit tersebut

## Model
menggunakan Model ResNet, melakukan imagegenerator dengan melakukan 10 epcoh

## Resnet
ResNet (Residual Network) adalah jenis arsitektur neural network yang mendalam yang memperkenalkan konsep blok residual. Arsitektur ini dikembangkan oleh Microsoft Research pada tahun 2015 dan memenangkan kompetisi ImageNet pada saat itu. Ide utama di balik ResNet adalah mengatasi masalah pelatihan yang lebih dalam dengan menggunakan blok-blok residual.

Pada dasarnya, ResNet menggunakan blok-blok yang memiliki shortcut connections (jalan pintas) yang memungkinkan informasi untuk melompati beberapa lapisan sekaligus. Hal ini membantu mencegah masalah pelatihan yang dikenal sebagai vanishing gradient, di mana gradient dari lapisan-lapisan awal menjadi sangat kecil sehingga sulit untuk melakukan pelatihan yang efektif pada jaringan yang dalam.

Dengan adanya jalan pintas atau shortcut connections, ResNet memungkinkan aliran informasi yang lancar dan membantu dalam pembelajaran representasi yang lebih baik. Arsitektur ResNet telah terbukti sangat efektif dalam tugas-tugas pengenalan gambar dan telah menjadi dasar bagi banyak pengembangan arsitektur jaringan saraf konvolusional (CNN) yang mendalam.


## Evaluasi Model
evaluasi untuk model yang digunakan adalah menggunakan probabilitas prediksi dan waktu prediksi. Hal ini digunakan untuk melihat berapa kemungkinan prediksi kelas yang dilakukan oleh model pada gambar yang diprediksi
