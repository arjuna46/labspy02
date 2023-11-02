## Installation environmet virtual(venv) & Deactivate di visual studio code
- python - m venv praktikum3
- for activate praktikum3/Scripts/activate
- deactivate
## Operating System Used
* [WINDOWS 10](https://www.microsoft.com/software-download/windows10) -You can use this page to download a disc image (ISO file) that can be used to install or reinstall Windows 10.
## command 
 - git add dapat digunakan secara spesifik untuk file tertentu atau direktori, memberikan Anda fleksibilitas untuk memilih perubahan mana yang akan dimasukkan dalam staging 
  area.
 - git commit -m “hi” Untuk menyimpan perubahan yang ada kedalam database repository local
 - git remote add origin https://github.com/arjuna46/labspy02.git Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada 
   local repository, sehingga dapat diakses oleh banyak user.
 - git push -u origin master/main Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
 - git clone [url] Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working 
   directory).
## labspy02
## Pertama 
- program meminta pengguna untuk memasukkan tiga bilangan menggunakan input(), dan hasilnya disimpan dalam variabel bilangan1, bilangan2, dan bilangan3.
  Kemudian, program memeriksa tiga kondisi menggunakan if:
## pertama
- memeriksa apakah bilangan1 lebih besar dari bilangan2 dan bilangan3. Jika benar, maka bilangan1 adalah yang terbesar.
## kedua
- jika kondisi pertama salah, maka memeriksa apakah bilangan2 lebih besar dari bilangan1 dan bilangan3. Jika benar, maka bilangan2 adalah yang terbesar.
  Jika kedua kondisi sebelumnya salah, maka bilangan3 adalah yang terbesar.Hasil bilangan terbesar ditampilkan menggunakan pernyataan print.
## output
![Screenshot (38)](https://github.com/arjuna46/labspy02/assets/147571007/358c8217-a040-424c-bdb5-e523aeed5491)

Dengan demikian, program akan menentukan bilangan terbesar di antara ketiga bilangan yang dimasukkan oleh pengguna dan mencetaknya ke layar.
## labspy03
- LATIHAN1 
- import random: Ini adalah pernyataan untuk mengimpor modul random, yang digunakan untuk menghasilkan bilangan acak.
- n = int(input("Masukkan nilai n: ")): Program ini meminta pengguna untuk memasukkan sebuah nilai n melalui keyboard. Nilai tersebut kemudian dikonversi menjadi integer 
  (bilangan bulat) dan disimpan dalam variabel n.
- count = 0: Variabel count diinisialisasi dengan nilai 0. Variabel ini akan digunakan sebagai penghitung untuk melacak berapa kali bilangan acak telah dihasilkan.
- while count < n:: Ini adalah awal dari loop while. Kode dalam loop ini akan dieksekusi selama nilai count kurang dari n.
- random_number = random.random(): Ini adalah pernyataan yang menghasilkan sebuah bilangan acak antara 0 dan 1 dengan menggunakan fungsi random.random() dari modul random. 
  Hasilnya disimpan dalam variabel random_number.
- if random_number < 0.5:: Program memeriksa apakah random_number kurang dari 0.5. Jika benar, maka bilangan tersebut akan dicetak.
- print(random_number): Jika bilangan acak memenuhi kondisi sebelumnya (kurang dari 0.5), maka bilangan tersebut akan dicetak ke layar.
## OUTPUT
![Screenshot (46)](https://github.com/arjuna46/labspy02/assets/147571007/a2cb0310-42b1-474a-b4d7-c3fec5415098)
