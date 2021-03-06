## Mohammad Sofiyan 
## 312010225
## TI.20.A2
## Pemrograman web

## 1.membuat orderlist
![orderlist](img/Order_list.png)

orderlist adalah list yang tersusun dan terurut
```html
<section id="order-list">
        <h2>Ordered List</h2>
        <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
        </ol>
        </section>
```

## 2. membuat unorderlist 
![unorderlist](img/unorder_list.png)

unorderlist adalah list yang acak atau tidak terurut dan tersusun 
```html
<section id="unorder-list">
            <h2>Unordered List</h2>
            <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
            </ul>
            </section>
```
## 3. membuat deskripsilist
![deskripsilist](img/deskripsi_list.png)

deskripsilist adalah diskripsi yang di dalamnya terdapat dt untuk konten sebuah istilah sementara dd adalah penjelasannya.
```html
<section id="unorder-list">
                <h2>Description List</h2>
                <dl>
                <dt>Fakultas Teknik</dt>
                <dd>Teknik Industri</dd>
                <dd>Teknik Informatika</dd>
                <dd>Teknik Lingkungan</dd>
                <dt>Fakultas Ekonomi dan Bisnis</dt>
                <dd>Akuntansi</dd>
                <dd>Manajemen</dd>
                <dd>Bisnis Digital</dd>
                </dl>
                </section>
```
## 4. membuat table 
![table](img/table.png)

dalam membuat tabel mengunakan tag table yang kemudian disusul thead dan juga tr untuk table row untuk th adalah table head.
```html
<table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td>Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
```
## 5. menambahkan pading & margin 
![pading](img/menambahkan_pading.png)
sebelumnya saya cellpading saya adalah 4 lalu sayah ubah menjadi 10 
```html
<table border="1" cellpadding="10" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td>Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
```
## 6. mengabungkan sel data 
![menggabungkansel_data](img/menggabungkansel_data.png)
rowspan adalah untuk menggabungkan data secara vertikal 
```html 
 <table border="1" cellpadding="10" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
```
## 7. membuat form 
![form](img/form.png)
dalam membuat form diperlukan tag form kemudian input sesuai kebutuhan client 
```html
<header>
        <h1>Membuat Form</h1>
    </header>
    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Pelanggan</legend>
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama">
            </p>
            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
            </p>
            <p>
                <label>Jenis Kelamin</label>
                <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="P" /><label 
                for="jk_p">Perempuan</label>
            </p>
            <p><input type="submit" value="Login"></p>
            </fieldset>
            </form>
```
## 8. menambahkan css 
![from_css](img/form_css.png)
menambahkan internal css pada html form 
```css
<style>
        form p>label {
            display: inline-block;
            width: 100px;
        }

        form input[type="text"],
        form textarea {
            border: 1px solid #197a43;
        }

        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
        }
    </style>
```