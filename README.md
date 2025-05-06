# MUH.RIFKI

<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Contoh 100 tag HTML">
    <title>100 Tag HTML</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>

    <header>
        <h1>Header Halaman</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
        </ul>
    </nav>

    <section>
        <h2>Section Title</h2>
        <p>Section Content</p>
    </section>

    <article>
        <h3>Artikel Title</h3>
        <p>Artikel Content</p>
    </article>

    <aside>
        <p>Informasi terkait lainnya.</p>
    </aside>

    <div class="container">
        <p>Konten di dalam div.</p>
    </div>

    <span style="color: red;">Text berwarna merah</span>

    <h1>Judul Utama</h1>
    <h2>Sub Judul</h2>
    <h3>Sub-Sub Judul</h3>

    <p>Ini adalah paragraf pertama.</p>
    <p>Paragraf pertama<br>Paragraf kedua setelah break.</p>
    
    <hr>

    <b>Text Tebal</b>
    <i>Text Miring</i>
    <u>Text Garis Bawah</u>
    <strong>Text yang penting</strong>
    <em>Text yang ditekankan</em>
    <del>Text yang dihapus</del>
    <ins>Text yang ditambahkan</ins>

    <a href="https://www.example.com">Link menuju Example</a>

    <img src="image.jpg" alt="Deskripsi gambar">

    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Browser Anda tidak mendukung elemen audio.
    </audio>

    <video controls>
        <source src="video.mp4" type="video/mp4">
        Browser Anda tidak mendukung elemen video.
    </video>

    <iframe src="https://www.example.com" width="600" height="400"></iframe>

    <form action="/submit">
        <label for="name">Nama:</label>
        <input type="text" id="name" name="name">
        <input type="submit" value="Kirim">
    </form>

    <input type="text" name="username" placeholder="Username">
    <textarea name="message" rows="4" cols="50" placeholder="Tulis pesan..."></textarea>
    <button>Submit</button>

    <select name="country">
        <option value="id">Indonesia</option>
        <option value="us">United States</option>
    </select>

    <label for="name">Nama:</label>

    <fieldset>
        <legend>Informasi Kontak</legend>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
    </fieldset>

    <legend>Formulir Pendaftaran</legend>

    <table>
        <tr>
            <th>Nama</th>
            <th>Usia</th>
        </tr>
        <tr>
            <td>Ani</td>
            <td>25</td>
        </tr>
    </table>

    <tr>
        <td>Ani</td>
        <td>25</td>
    </tr>

    <th>Nama</th>

    <caption>Daftar Nama</caption>

    <thead>
        <tr>
            <th>Nama</th>
            <th>Usia</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Ani</td>
            <td>25</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td>Total</td>
            <td>1</td>
        </tr>
    </tfoot>

    <blockquote cite="https://www.example.com">
        "Ini adalah kutipan."
    </blockquote>

    <q>Ini adalah <q>kutipan langsung</q> dari seseorang.</q>

    <cite>Nama Penulis</cite>

    <code>let x = 10;</code>

    <pre>
        function test() {
            console.log('Hello World');
        }
    </pre>

    <kbd>Ctrl</kbd> + <kbd>C</kbd> untuk menyalin.

    <samp>Program selesai dengan hasil sukses.</samp>

    <var>x</var> adalah variabel yang digunakan dalam persamaan.

    <bdo dir="rtl">Teks dalam arah kanan ke kiri</bdo>

    <address>
        Email: contact@example.com
    </address>

    <mark>Highlight Teks</mark>

    <small>Text kecil di bagian bawah</small>
    <big>Text lebih besar</big>

    <abbr title="Hypertext Markup Language">HTML</abbr>

    <dfn>CSS</dfn> adalah bahasa untuk mendesain halaman web.

    <time datetime="2025-05-06">6 Mei 2025</time>

    <bdi>Text terisolasi</bdi>

    <wbr>Jika kata ini terlalu panjang, gunakan <wbr> untuk memecahnya.

    <ruby>
        漢 <rt>kanji</rt>
    </ruby>

    <rt>kanji</rt>

    <rp>(</rp><ruby>漢<rt>kanji</rt></ruby><rp>)</rp>

    <data value="10">10</data>

    <output name="result">0</output>

    <progress value="22" max="100"></progress>

    <meter value="0.7">70%</meter>

    <details>
        <summary>Informasi Detail</summary>
        <p>Konten lebih lanjut...</p>
    </details>

    <summary>Summary informasi</summary>

    <menu>
        <li>Item 1</li>
        <li>Item 2</li>
    </menu>

    <menuitem label="Edit" icon="edit-icon.png" onclick="edit()">Edit</menuitem>

    <template id="myTemplate">
        <p>This is a template.</p>
    </template>

    <script>
        console.log('Hello, World!');
    </script>

    <noscript>Javascript tidak didukung oleh browser Anda.</noscript>

    <style>
        body {
            background-color: lightgray;
        }
    </style>

    <link rel="icon" href="favicon.ico">

    <meta http-equiv="refresh" content="30">

    <object data="movie.mp4" type="video/mp4" width="400" height="300"></object>

    <param name="autoplay" value="true">

    <embed src="image.jpg" width="500" height="500">

    <area shape="rect" coords="34,44,270,350" alt="Laptop" href="laptop.html">
    <map name="map">
        <area shape="rect" coords="34,44,270,350" alt="Laptop" href="laptop.html">
    </map>

    <canvas id="myCanvas" width="200" height="200"></canvas>

    <svg width="100" height="100">
        <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
    </svg>

    <svg width="100" height="100">
        <path d="M10 10 H 90 V 90 H 10 L 10 10" stroke="black" fill="transparent" />
    </svg>

    <svg width="100" height="100">
        <polygon points="50,5 100,50 50,95 0,50" fill="lime" stroke="purple" stroke-width="1" />
    </svg>

    <svg height="100" width="100">
        <line x1="0" y1="0" x2="100" y2="100" stroke="black" stroke-width="2" />
    </svg>

    <svg height="100" width="100">
        <rect width="90" height="90" stroke="green" stroke-width="3" fill="yellow" />
    </svg>

    <svg height="100" width="100">
        <text x="10" y="50" font-family="Verdana" font-size="35" fill="black">Hello</text>
    </svg>

    <svg width="100" height="100">
        <use href="#circle" />
    </svg>

    <svg width="200" height="200">
        <foreignObject width="200" height="200">
            <div xmlns="http://www.w3.org/1999/xhtml">
                <p>Text inside foreignObject</p>
            </div>
        </foreignObject>
    </svg>

    <svg>
        <defs>
            <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
                <stop offset="0%" style="stop-color:rgb(255,255,0);stop-opacity:1" />
                <stop offset="100%" style="stop-color:rgb(255,0,0);stop-opacity:1" />
            </linearGradient>
        </defs>
    </svg>

    <svg width="100" height="100">
        <filter id="f1" x="0" y="0" width="150%" height="150%">
            <feGaussianBlur in="SourceGraphic" stdDeviation="15" />
        </filter>
        <rect width="90" height="90" stroke="green" stroke-width="3" fill="yellow" filter="url(#f1)" />
    </svg>

    <svg height="100" width="100">
        <symbol id="triangle" viewBox="0 0 100 100">
            <polygon points="50,5 100,95 0,95" fill="lime" />
        </symbol>
        <use href="#triangle" x="10" y="10" />
    </svg>

</body>

</html>
