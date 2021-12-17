# Workshop Extensive Data Mining Tanpa Coding di R ft. Exsight

1. Install R
2. Install RStudio (opsional)
3. Install package RGtk2
```
install.packages("RGtk2")
```
4. Install package rattle dan pendukungnya
```
install.packages("rattle")
```
Jika Anda ingin install semua package yang digunakan oleh Rattle, Anda dapat jalankan perintah berikut ini. NNamun Anda perlu pertimbangkan bahwa perintah tersebut akan menginstall **BANYAK SEKALI PACKAGE TAMBAHAN** yang mendukung Rattle dan mungkin butuh waktu lama. 
```
install.packages("rattle", dependencies = "Suggests")
```
5. Jalankan Rattle
```
library(rattle)
rattle()
```
