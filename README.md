# HTML-Dasar
Source code mata kuliah Pemrograman Web B materi HTML Dasar membuat profil diri

``
<!DOCTYPE html>
<html>
<head>
    <title>Profil Saya</title>
</head>
<body>
    <!-- Heading -->
    <h1>Profil Mahasiswa</h1>

    <!-- Paragraf -->
    <p>Halo! Nama saya <b>Najma Lail Arazy</b>. Saya seorang mahasiswa semester 3 program studi Teknik Informatika di Institut Teknologi Sepuluh Nopember Surabaya 
    yang tertarik pada pengembangan web dan pemrograman.</p>

    <!-- Gambar -->
    <img src="d:\makalah\pasfoto.jpg" alt="Foto Profil" width="100">

    <!-- List -->
    <h2>Hobi Saya:</h2>
    <ul>
        <li>Traveling</li>
        <li>Olahraga</li>
        <li>Belajar hal baru</li>
    </ul>

    <!-- Tabel -->
    <h2>Pendidikan</h2>
    <table border="1" cellpadding="5">
        <tr>
            <th>Tahun</th>
            <th>Sekolah</th>
        </tr>
         <tr>
            <td>2018 - 2021</td>
            <td>SMP Negeri 1 Semarang</td>
        </tr>
        <tr>
            <td>2021 - 2024</td>
            <td>SMA Negeri 1 Semarang</td>
        </tr>
        <tr>
            <td>2024 - Sekarang</td>
            <td>Institut Teknologi Sepuluh Nopember</td>
        </tr>
    </table>

    <!-- Form -->
    <h2>Kontak Saya</h2>
    <form>
        <label>Nama:</label><br>
        <input type="text" name="nama"><br><br>

        <label>Email:</label><br>
        <input type="email" name="email"><br><br>

        <label>Pesan:</label><br>
        <textarea name="pesan" rows="4" cols="30"></textarea><br><br>

        <input type="submit" value="Kirim">
    </form>

    <!-- Link -->
    <p>Kunjungi <a href="https://www.instagram.com/najmarra/">Instagram</a> untuk melihat aktivitas saya.</p>
    <p>Kunjungi <a href="https://github.com/najmarra/">Github</a> untuk melihat project saya.</p>
</body>
</html>
``
