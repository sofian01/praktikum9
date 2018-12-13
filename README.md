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

hasil sreenshot

![untitled](https://user-images.githubusercontent.com/44091204/49913065-c197ea00-febe-11e8-8035-feec82d2894a.jpg)


latihan2

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

hasil sreenshot

![sslatihan2](https://user-images.githubusercontent.com/44091204/49913415-17b95d00-fec0-11e8-90f9-71d90913d895.jpg)

