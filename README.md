# Lab2Web

## 1.Membuat Dokumen HTML
<img width="960" alt="Gambar1" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/0044140a-3ea8-47f6-9806-2c3ce463d79d">

<img width="960" alt="Gambar2" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/3c91eea7-974c-4667-8829-250bd864f39e">

## 2.Mendeklarasikan CSS Internal
<img width="960" alt="Gambar3" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/06b1234d-c74e-481a-8f52-318469bdf4e5">

<img width="960" alt="Gambar4" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/0abda247-4e58-458e-8de5-c9ddc7196aab">

## 3. Menambahkan Inline CSS
<img width="960" alt="Gambar5" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/9d182b4b-274d-43e0-a2db-e2f1d42879df">

<img width="960" alt="Gambar6" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/eb1f33c5-1c9d-4a3a-bbcc-603903ad71d4">

## 4. Membuat CSS Eksternal
<img width="960" alt="Gambar7" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/bcd92396-a980-49c9-afb4-4b15640f339e">

<img width="960" alt="Gambar8" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/9a5fc933-f227-4725-a8b1-996f7dcf18aa">

## 5.Menambahkan CSS Selector
<img width="960" alt="Gambar9" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/9e119a1a-b89c-4e88-8ea3-b6b6e7953022">

<img width="960" alt="Gambar10" src="https://github.com/Akramfarrasanto/Lab2Web/assets/115552876/f211d635-69ff-4eed-ad69-0cb8f9f65293">

# Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.


2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
  - Kalau h1 menggunakan internal dan inline pada penggunaan style nya sedangkan intro menggunakan eksternal css style nya

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

  - Ketika ada deklarasi CSS secara internal, CSS eksternal, dan inline CSS pada elemen yang sama, maka urutan keutamaan (specificity) akan menentukan deklarasi mana yang akan ditampilkan pada browser. Urutan prioritas biasanya adalah sebagai berikut, dari yang paling tinggi hingga yang paling rendah:

  - a. Inline CSS memiliki prioritas tertinggi.
  
  - b. Kemudian, deklarasi CSS yang ada dalam elemen `<style>` secara internal (internal CSS) akan digunakan jika ada konflik antara inline dan internal CSS.
  
  - c. Terakhir, deklarasi dari file CSS eksternal akan digunakan jika ada konflik dengan inline dan internal CSS.

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`
   

  - Ketika sebuah elemen HTML memiliki ID dan class, dan keduanya memiliki deklarasi CSS, maka deklarasi yang akan digunakan akan bergantung pada spesifikitas (specificity) dari selector tersebut. Secara umum, ID selector memiliki spesifikitas yang lebih tinggi daripada class selector. Oleh karena itu, jika ada konflik antara deklarasi CSS ID dan class, deklarasi dari ID akan digunakan.
