# praktikum9

Pengertian Array

Array merupakan tipe data terstruktur yang berguna untuk menyimpan sejumlah data yang bertipe sama.
Bagian yang menyusun array disebut elemen array(isi), yang masing-masing elemen dapat diakses tersendiri melalui indeks array.

> Antara satu Variabel dengan variabel lain di dalam array dibedakan berdasarkan Subscript
> Sebuah subscript berupa bilangan di dalam Kurung siku […]
> Melalui subscript inilah masing-masing elemen array dapat diakses.

Sebagai contoh, misalkan terdapat array A yang memiliki 10 buah elemen nilai yang bertipe integer,
maka kita dapat mereprentasikannya dengan gambar berikut.

![contoh-array](https://user-images.githubusercontent.com/44091204/49911619-a24a8e00-feb9-11e8-9267-009f99245f1a.jpg)

latihan1
```
1.mulai program 
2.int proses(int n,int max,int min,int jumlah);
3.if(n==0){
   cout<<endl;
   cout<<" NILAI MAKSIMUM       : "<<max<<endl;
   cout<<" NILAI MINIMUM        : "<<min<<endl;
   cout<<" JUMLAH SELURUH DERET : "<<jumlah<<endl<<endl;
   return 0;
  }

4.else{
   cout<<" Masukkan Bilangan : ";cin>>x;
      jumlah+=x;

   if(x<min)
   {
      min=x;
   }

   if(x>max)
   {
      max=x;
   }
5.return proses(n-1,max,min,jumlah);
6.selesai.

```
hasil sreenshot

![untitled](https://user-images.githubusercontent.com/44091204/49913065-c197ea00-febe-11e8-8035-feec82d2894a.jpg)


FLOWCHART LATIHAN1

![flowchart1](https://user-images.githubusercontent.com/44091204/49915009-230f8700-fec6-11e8-8849-ec68500d0314.jpg)
![flowchart2](https://user-images.githubusercontent.com/44091204/49915014-299dfe80-fec6-11e8-801a-afa25260a31d.jpg)
![flowchart3](https://user-images.githubusercontent.com/44091204/49915017-2c98ef00-fec6-11e8-8f7b-7cb254390158.jpg)


latihan2
```
1.mulai program 
2.mencari modus dari data 1 sampai 10
3.masukan jumlah data = 10
4.masukan nilai-1
5.masukan nilai-2
6.masukan nilai-3
7.masukan nilai-4
8.masukan nilai-5
9.masukan nilai-6
10.masukan nilai-7
11.masukan nilai-8
12.masukan nilai-9
13.masukan nilai-10
14.setiap data di hitung frekuensi kemunculan nya
15.dari frekuensi tersebut dapat di tentukan modus dari data tersebut
16.selesai

```
hasil sreenshot

![sslatihan2](https://user-images.githubusercontent.com/44091204/49913415-17b95d00-fec0-11e8-90f9-71d90913d895.jpg)

latihan3

mengalikan dua buah matriks dengan jumlah baris dan kolom yang sama

Hasil sreenshot 

![untitled](https://user-images.githubusercontent.com/44091204/49914871-8947da00-fec5-11e8-9dee-0028d866d534.jpg)

latihan4

```
Matriks transpose yaitu matriks yang diperoleh dari memindahkan elemen-elemen baris menjadi elemen pada kolom atau sebaliknya.
Transpose matriks A dilambangkan dengan AT Contoh: A3×2 =, maka AT =, perhatikan bahwa ordo dari AT adalah 2 x 3.
Algoritma Transpose Matrik

1.Masukkan ordo matrik(n)
2.Input matrik di dalam array [0][0] sampai dengan array[n][n]
3.ditampilkan matrik tersebut
4.menukar matrik[i][j] menjadi matrik[j][i]
5.ditampilkan hasil matrik tranpose
Deklarasi : a[10][10] : int m,n,i,j : int Deskripsi : Baca (m) Baca (n) for(i=0;i<m;i++) { for(j=0;j<n;j++) { Tulis a[i][j] Transpose : for(i=0;i<m;i++) { for(j=0;j<n;j++) { Transpose a[j][i] }

```
hasil sreenshot

![untitled](https://user-images.githubusercontent.com/44091204/49914958-efccf800-fec5-11e8-922b-91383893700e.jpg)


