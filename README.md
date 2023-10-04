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

## Membuat CSS Eksternal
