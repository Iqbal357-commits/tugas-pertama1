# Proyek Pertama
<!DOCTYPE html>
<html>
<head>
    <title>Website Table Layout</title>
</head>
<body>

<!-- Section 1: Menu -->
<table border="1" width="100%">
    <tr align="center">
        <td>Header</td>
        <td>Biodata</td>
        <td>Portofolio</td>
    </tr>
</table>
<br>

<!-- Section 2: Judul di kiri dan Gambar di kanan -->
<table border="1" width="100%">
    <tr>
        <td width="50%">
            <h2>Selamat Datang di Website Saya</h2>
            <p>Ini adalah contoh header dengan 2 kolom, kolom kiri berisi teks seperti ini.</p>
            <button>Pelajari lebih lanjut</button>
        </td>
        <td width="50%" align="center">
            <img src="https://via.placeholder.com/250" alt="Gambar" width="250">
        </td>
    </tr>
</table>
<br>

<!-- Section 3: Biodata dengan 6 box -->
<table border="1" width="100%" id="Section">
    <tr>
        <td colspan="3" align="center"><h2>Abaut me</h2>
        <p>A brief introduction abaut myself</p></td>
    </tr>
    <tr align="center">
        <td>full Name</td>
        <td>Education</td>
        <td>Pekerjaan</td>
    </tr>
    <tr align="center">
        <td>Contact</td>
        <td>Hobi</td>
        <td>Alamat</td>
    </tr>
</table>
<br>

<!-- Section 4: Portofolio -->
<table border="1" width="100%">
    <tr>
        <td align="center" colspan="3"><h2>Portofolio</h2></td>
    </tr>
    <tr align="center" valign="top">
        <td><img src="https://via.placeholder.com/200" alt="Portofolio 1">
        <h3>Proyek 1</h3>
    <p>Deskripsi Proyek</p></td>
        <td><img src="https://via.placeholder.com/150" alt="Portofolio 2">
        <h3>Proyek 1</h3>
    <p>Deskripsi Proyek</p></td>
        <td><img src="https://via.placeholder.com/150" alt="Portofolio 3">
        <h3>Proyek 1</h3>
    <p>Deskripsi Proyek</p></td>
    </tr>
</table>

</body>
</html>
