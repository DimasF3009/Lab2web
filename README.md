# Lab2web

## Membuat Dokumen HTML
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>
    <div class="navbar">
        <ul>
            <li><a href="https://www.w3schools.com/css/">CSS DASAR</a></li>
            <li><a href="https://www.w3schools.com/css/">CSS EKSTERNAL</a></li>
            <li><a href="https://www.w3schools.com/html/">HTML DASAR </a></li>
        </ul>
    </div>
    <div id="main">
        <div class="paragraf">
            <p><b>HELLO WORLD</b></p>
            <br>
            <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
                Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
                adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
                dan CSS.</p>
            <br>
            <button><a href="https://www.w3schools.com/css/">INFORMASI SELENGKAPNYA </a></button>
        </div>
    </div>
    
</body>
</html>
```
<img width="954" alt="#1" src="https://github.com/DimasF3009/Lab2web/assets/115356128/6f7a1fcf-6497-4685-aaf3-5162114d6f74">

## Deklarasi Internal
```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      body{
        background-color: aqua;
        font-family:'Open Sans', sans-serif;
      }
    </style>
</head>
```
<img width="959" alt="#2" src="https://github.com/DimasF3009/Lab2web/assets/115356128/46a66833-eb83-4cb7-b340-eb60edce309b">

## Menambahkan Inline CSS
```
    <header style="border: 1px solid; background-color: rgb(216, 18, 234);">
        <h1 style="text-align: center; color: rgb(54, 241, 66);">CSS Internal dan <i>Inline CSS</i></h1>
    </header>
```
<img width="960" alt="#3" src="https://github.com/DimasF3009/Lab2web/assets/115356128/60df2b3d-e39f-4811-912e-0ee83e36e7a5">


## Membuat CSS Eksternal
```
*{
    margin: 0px;
    padding: 0px;
}

body{
    font-family: 'Ubuntu', sans-serif;
}
header{
    align-items: center;
    text-align: center;
    font-size: 20px;
    color: #1f2ce5db;
    padding: 20px 10px;
    display: flex;
    justify-content: space-around;
    background-color: rgb(0, 255, 255);
}

header h1 i {
    color: red;
}

.navbar {
    background-color: rgba(30, 212, 30, 0.884);
    padding: 10px;
    margin: 10px;
    margin-bottom: 0;
}
.navbar ul{
    width: 40%;
    display: flex;
    justify-content: space-around;
    list-style: none;
    color: rgb(248, 241, 241);
}

ul li a{
    text-decoration: none;
    color: white;
}

.paragraf{
    background-color: rgba(71, 71, 228, 0.858);
    padding: 50px;
    margin: 10px;
    margin-top: 0px;
    margin-bottom: 0;
    color: white;
}
.paragraf button{
    width: 300px;
    height: 50px;
    background-color: red;
}
```
<img width="960" alt="#4" src="https://github.com/DimasF3009/Lab2web/assets/115356128/91edee6a-e0ed-4f6a-97cc-318f254a96e2">

```
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
    dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
    penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
   elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
   penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
   terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
   Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )
```
