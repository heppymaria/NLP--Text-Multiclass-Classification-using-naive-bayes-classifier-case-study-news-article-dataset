## Classification-of-TV-Commercial-from-3-Local-and-2-International-News-Channels-Using-the-K-Nearest-Neighbor

Dataset yang dieksplorasi adalah Channel Commercial Detection Dataset yang dapat diakses pada data.world. Tim melakukan exploratory data analysis (EDA) untuk menemukan pola dan karakteristik data. 

Dataset memiliki binary-class classification yaitu 1/-1 atau commercial atau non-commercial dimana setiap baris data di-assign hanya kesatu label kelas saja. Dataset yang digunakan sebanyak 5 buah yang masing-masing dataset terdiri atas 205 atribut bertipe data numerik dan jumlah rows sebagai berikut: 

BBC_Cleaned 17,721 
CNN_Cleaned 22,546 
CNNIBN_Cleaned 
33,118 NDTV_Cleaned 
17,052 TIMESNOW_Cleaned 
39,253

Berikut keterangan feature pada setiap dataset. 
1 Shot Length 
2-3 Motion Distribution( Mean and Variance) 
4-5 Frame Difference Distribution ( Mean and Variance)
6-7 Short time energy ( Mean and Variance) 
8-9 ZCR( Mean and Variance) 
10-11 Spectral Centroid ( Mean and Variance) 
12-13 Spectral Roll off ( Mean and Variance) 
14-15 Spectral Flux ( Mean and Variance) 
16-17 Fundamental Frequency ( Mean and Variance) 18-58 Motion Distribution ( 40 bins) 
59-91 Frame Difference Distribution ( 32 bins) 
92-122 Text area distribution ( 15 bins Mean and 15 bins for variance ) 
123-4123 Bag of Audio Words ( 4000 bins) 4124-4125 Bag of Audio Words ( 4000 bins) 
Label +1/-1 ( Commercials/Non Commercials)

Data yang sudah di-clean dapat diakses pada link berikut:
https://drive.google.com/file/d/1avsqbDnDoWN4Tbwzc46zrjfGtKJelarh/view?usp=sharing


