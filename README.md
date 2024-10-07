# Lab2Web
<b>Pemrograman Web Tugas 2</b>

1. Membuat Dokumen HTML<br>
   Buatlah seperti berikut
   ![1](https://github.com/user-attachments/assets/fb99494d-1713-4c70-b674-38a55d549c5e)

   hasil:
   ![hasil1](https://github.com/user-attachments/assets/42c1b395-b6cb-4e43-9a3e-0a6822311db6)

2. Cara Deklarasi CSS Internal <br>
   Deklarasikan CSS pada Head HTML
   ![2](https://github.com/user-attachments/assets/3e8b517f-5761-4471-87a6-1a6441d143d9)

   hasil:
   ![hasil2](https://github.com/user-attachments/assets/78e5d1fd-56dd-4028-8ffb-f03e9b312d75)

3. Cara menambahkan Inline CSS <br>
   Tambahkan Deklarasi Inline CSS pada tag yang ingin ditambahkan, misal tag p
   ![3](https://github.com/user-attachments/assets/c0d90e15-86cf-491f-a751-f930a94e6e67)

   hasil:
   ![hasil3](https://github.com/user-attachments/assets/2f28d7fe-936a-415e-b245-476516d0138e)

4. Cara Membuat CSS Eksternal <br>
   buat file baru yang berekstensi css misal (nama file).css, misal style_eksternal. css, lalu tambahkan link:css(shortcut) pada head, lalu panggil ekstensi pada href
   ![4](https://github.com/user-attachments/assets/71df3cd7-c757-49ea-9eb7-4b083dd4bf04)

5. Tambahkan CSS Selector <br>
   pada file css, tambahkan kode berikut
   ![5](https://github.com/user-attachments/assets/61ce7159-bbfb-48da-8579-b3c92abb76f3)

   hasil:
   ![hasil5](https://github.com/user-attachments/assets/e2bfaa58-1ae9-40b6-8d3a-474dfa1e5b81)



   -------------------
   1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
   dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini. <br>

   hasil:
   ![soalno1](https://github.com/user-attachments/assets/03f8e221-d65a-432f-9aab-0d0d09685d2e)


   2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
   penjelasannya!<br>
   Jawab: <br>
   Jika yang dideklarasikan hanyalah h1 saja, maka yang terubah adalah seluruh elemen yang memiliki tag h1.<br>
   dan, jika kita mendeklarasikan #intro h1, maka yang terubah adalah h1 pada id/wrap #intro saja.
   
   3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
   elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
   penjelasan dan contohnya! <br>
   Jawab: <br>
   Karena didefinisikan secara langsung pada elemen HTML, CSS inline memiliki prioritas yang lebih tinggi daripada CSS eksternal karena berada di halaman yang sama, yang terakhir adalah eksternal css. namun jika ketiganya dideklarasikan, tetap akan berjalan.
   

   4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
   terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
   Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )<br>
   Jawab:<br>
   Jika elemen HTML memiliki baik ID maupun class, CSS dengan selector ID lebih penting daripada CSS dengan selector class. Selector ID (#) memiliki prioritas lebih tinggi daripada selector class (.), karena gaya selector ID dianggap unik dalam dokumen HTML. Jika elemen memiliki deklarasi CSS yang bertentangan dengan kedua class dan ID, gaya selector ID akan digunakan.


   

