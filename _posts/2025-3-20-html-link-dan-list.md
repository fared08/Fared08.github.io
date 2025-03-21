---
layout: post
title: "Html link dan list"
---



Penjelasan tentang link dan list pada HTML.
<br>


# Penjelasan lengkap tentang link dan list pada html

> Dalam HTML, link dan list adalah dua elemen penting yang digunakan untuk membuat navigasi dan menyusun informasi dalam bentuk daftar. Berikut adalah penjelasan lebih lanjut mengenai keduanya.


## Sintaks Dasar Ordered List (`<ol>`)

```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```


## B. Unordered List (<ul>)
>Unordered List digunakan untuk membuat daftar tidak terurut (menggunakan simbol seperti lingkaran, kotak, atau titik).      

```
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

```

#### Atribut pada <ul>


- type – Menentukan simbol untuk setiap item dalam daftar.
- "disc" → Lingkaran hitam (default)
- "circle" → Lingkaran kosong
- "square" → Kotak hitam

> contoh atribut 
<br>

```

<ul type="circle">
    <li>Apel</li>
    <li>Pisang</li>
</ul>

```




### 1. Link (<a>) dalam HTML
> Link digunakan untuk membuat tautan ke halaman lain, file, atau bagian tertentu dalam halaman yang sama.


`a href="https://example.com">Teks Link</a>`



- href → Menentukan tujuan link (URL, file, atau ID dalam halaman).
- `Teks dalam <a>...</a> → Yang akan muncul dan dapat diklik.`



### 2. List (<ul>, <ol>, <li>) dalam HTML
>Jika link tetap berada di tengah karena CSS bawaan, coba tambahkan gaya berikut dalam file .css kamu:
`a {
    display: block;
    text-align: left;
    margin-top: 10px;
}
`

### Cara 2: Menggunakan <div>

`<div style="margin-top: 10px;">
  <a href="https://fared08.github.io/FaredCV.github.io/">CV Farid Haiqal</a>
</div>
`

<br>
<br>
<br>


>Jika kamu masih mengalami masalah, bisa jadi ada properti CSS di tema blog kamu yang mengatur tata letak dengan flexbox atau text-align: center. Coba periksa dengan Inspect Element di browser untuk melihat CSS yang mempengaruhi posisi link.


> Bersabarlah dengan cobaan yang menimpa dirimu, dan bersabarlah
<br>
![Html link dan List](/assets/images/Group.png)
<br>
<br>
[CV Farid Haiqal](https://fared08.github.io/FaredCV.github.io/)

    