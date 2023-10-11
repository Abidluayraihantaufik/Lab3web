# Lab3web
## Pertanyaan
Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
```<!DOCTYPE html>
<html>
<head>
    <title>Contoh Form dengan Dropdown dan Listbox</title>
</head>
<body>
    <h2>Pilih Fakultas Anda:</h2>
    <form action="proses_form.php" method="post">
        <label for="Prodi">Pilih Prodi:</label>
        <select id="Prodi" name="Prodi">
            <option value="Teknik Informatika">Teknik Informatika</option>
            <option value="Teknik Industri">Teknik Industri</option>
            <option value="Teknik Sipil">Teknik Sipil</option>
        </select>

        <h2>Pilih Matakuliah Anda:</h2>
        <label for="Matakuliah">Pilih Matakuliah :</label>
        <select id="Matakuliah" name="Matakuliah[]" multiple="multiple">
            <option value="Agama">Agama</option>
            <option value="Pemrograman web">Pemrograman web</option>
            <option value="Pemrograman mobile">Pemrograman mobile</option>
            <option value="Statistika">Statistika</option>
            <option value="Jaringan komputer">Jaringan komputer</option>
        </select>

        <input type="submit" value="Submit">
```
![img](gambar/8.PNG)
