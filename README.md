# labpy03

## Latihan 1

### Menampilkan N Bilangan acak lebih kecil dari 0.5

#### A. Algoritma :
  1.	Mulai
  2.	Tentukan nilai perulangan
  3.	Lakukan perulangan sebanyak jumlah yang ditentukan 
  4.	Lakukan proses pengulangan bilangan selama i <0.5
  5.	Cetak perulangan sebanyak jumlah yang ditentukan
  6.	Cetak bilangan < 0.5 sampai sesuai dengan jumlah yang ditentukan
  7.	Selesai

#### B. Flowchart  :
      
<img width="322" alt="t1" src="https://user-images.githubusercontent.com/47028610/53194615-5b5ddf00-3646-11e9-85af-767620b7b033.png">

#### C. Program  :

Ketik seperti berikut :

              jumlah =int(input("Masukkan jumlah N :"))
              import random
              for i in range (jumlah):
                  print("Data ke", i+1,"=",(random.uniform(0.1,0.5)))
              print("selesai")
              
 <img width="960" alt="tugas1" src="https://user-images.githubusercontent.com/47028610/53194661-7892ad80-3646-11e9-8560-0cc51cdf2138.png">

1. Ketikan Program print ("Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5")

      =>print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5') Untuk Menampilkan atau Mencetak kalimat *Tampilkan N Bilangan Acak   yang Lebih Kecil Dari 0.5

2. Ketikan Program jumlah=int(input("Masukan Jumlah N : "))

      =>jumlah=int(input("Masukan Jumlah N : ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe            data bilangan bulat

3. Ketikan Program import random

      =>import random Untuk pengulangan secara acak

4. Ketikan Program for i in range ( jumlah ) :

      =>for i in range ( jumlah ) : Untuk Pengulangan dengan range jumlah

5. Ketikan Program print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5)))

      =>print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5))) Untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan            hasil di bawah 0.5
      
 #### D. Hasil :
 
 <img width="957" alt="hasil 1" src="https://user-images.githubusercontent.com/47028610/53194684-8cd6aa80-3646-11e9-9311-d2efdf77fd35.png">
      
      
 ## Latihan 2
 
 ### Program menampilkan bilangan terbesar dari N buah data yang diinputkan
 ### Masukan angka 0 untuk menghentikan program
 
 #### A. Algoritma :
 
   1.	Mulai 
   2.	Input bilangan N
   3.	Jika max < a maka akan lanjut pengulangan
   4.	Jika a==0 maka akan berhenti proses pengulangan
   5.	Dan mencetak hasil nilai maxium dari N yang di isikan
   6.	Selesai
   
#### B. Flowchart :

 <img width="187" alt="t2" src="https://user-images.githubusercontent.com/47028610/53194696-9e1fb700-3646-11e9-921b-194d443fb1b3.png">

#### C. Program  :

Ketik seperti berikut :

                  max = 0
                  while True:
                      a=int(input("Masukkan bilangan :"))
                      if max < a:
                          max = a
                      if a ==0:
                           break
                  print("\n Bilangan terbesar adalah :", max)
                  
<img width="960" alt="tugas2" src="https://user-images.githubusercontent.com/47028610/53194713-ad066980-3646-11e9-8585-05c771822368.png">
                  
1. Ketikan Program print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan')

      =>print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan') Untuk menampilkan kalimat Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan

2. Ketikan Program max= 0

      =>max= 0 kode max disini untuk menentukan nilai max nya dalah 0

3. Ketikan Program while true:

      =>while true: Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya

4. Ketikan Program a=int(input("Masukan Bilangan :"))

      =>a=int(input("Masukan Bilangan :")) a untuk menginput tipe data interger ( bilangan bulat )

5. Ketikan Program if max < a

6. Ketikan Program max=a

      =>if max < a max=a jika max kurang dari a maka max = a

7. Ketikan Program if a==0:

8. Ketikan Program break

      =>if a==0: break jika a= 0 maka akan berhenti dengan syarat break yang terpenuhi

9. Ketikan Program print("Bilangan Tebesar Adalah :", max)

      =>print("Bilangan Tebesar Adalah :", max) Menampilkan *Bilangan Tebesar Adalah : Nilai maxiumnya
      
  #### D. Hasil  :
  
<img width="958" alt="hasil 2" src="https://user-images.githubusercontent.com/47028610/53194734-bc85b280-3646-11e9-9b4c-6502d41a38ba.png">
        
  
  ## Program 1
  
  ### Program mencari total laba dengan presentase keuntungan tertentu setiap bulannya
  
  #### A. Algoritma :
          1.	Mulai
          2.	Input modal x = 100.000.000 
          3.	Input presentase untung A=0*x, b=0*x, c=0.01*x, d=0.01*x, e=0.05*x, f=0.05*x, g=0.05*x, h=0.03*x 
          4.	For i in range (len (y))  pengulangan
          5.	Print (“laba bulan ke-“,i+1,”sebesar:” ,y[i])
          6.	Menghitung jumlah laba keseluruhan Z= (a+b+c+d+e+f+g+h)
          7.	Print (“jumlah laba selama 8 bulan adalah:”)
          8.	selesai
          
  #### B. Flowchart :
  
 <img width="280" alt="t3" src="https://user-images.githubusercontent.com/47028610/53194777-d1fadc80-3646-11e9-9d50-c827ef0ea05e.png">
  
  #### C. Program :
  
                      x=100000000
                      print ("Investasi modal awal :",x)
                      a=0*x
                      b=0*x
                      c=0.01*x
                      d=0.01*x
                      e=0.05*x
                      f=0.05*x
                      g=0.05*x
                      h=0.03*x
                      y=[a,b,c,d,e,f,g,h]

                      for i in range (len(y)):
                          print ("Laba bulan ke",i+1  ,"Sebesar :",y[i])

                      z= (a+b+c+d+e+f+g+h)
                      print ("\nJumlah Laba selama 8 bulan adalah :",z)
                      
<img width="960" alt="tugas3" src="https://user-images.githubusercontent.com/47028610/53194819-e0e18f00-3646-11e9-82de-15ce882207c2.png">

1. Ketikan Program print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan')

      =>print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan') Untuk Menampilkan kalimat *Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

2. Ketikan Program

      =>x=100000000

3. Ketikan Program print (" Modal Awal:",x)

      =>print (" Modal Awal:",x) Menampilkan kalimat *Modal Awal : dan data yang berisi di x yaitu 100000000

4. Ketikan Program a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x

      =>a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 100000000

5. Ketikan Program y=[a,b,c,d,e,f,g,h]

      =>y=[a,b,c,d,e,f,g,h] untuk menentukan syarat y= yang berisi a,b,c,d,e,f,g,h
      
6. Ketikan Program For i in range (len (y))

7. Ketikan Program Print (“laba bulan ke-“,i+1,”sebesar:” ,y[i])

      =>For i in range (len (y)) Print (“laba bulan ke-“,i+1,”sebesar:” ,y[i]) untuk perulangan data dengan isi data yaitu Ydengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data Y

8. Ketikan Program

      =>Z= (a+b+c+d+e+f+g+h)

9. Ketikan Program Print (“jumlah laba selama 8 bulan adalah:”)

      =>Z= (a+b+c+d+e+f+g+h) Print (“jumlah laba selama 8 bulan adalah:”) Z berisi data penjumlahan data angka yang ada didalam kode a,b,c,d,e,f,g,h yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan
      
 ### D. Hasil :
 
<img width="957" alt="hasil 3" src="https://user-images.githubusercontent.com/47028610/53194845-f0f96e80-3646-11e9-9b7a-372439eaf65c.png">

 
 
     #### Nama    :Bagus Dwi Saputro
     #### NIM     :311810029
     #### Kelas   :18 TI B1
